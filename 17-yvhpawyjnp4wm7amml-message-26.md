Интегральное уравнение  
\[
y(x) - \lambda \int_{-\infty}^{\infty} e^{-|x-t|} y(t) \, dt = 0,
\]  
с параметром \(\lambda > 0\) решается с помощью преобразования Фурье. Условие существования нетривиальных решений определяется соотношением \(1 - \frac{2\lambda}{1 + \omega^2} = 0\), что приводит к \(\omega^2 = 2\lambda - 1\).  

- При \(\lambda \le \frac{1}{2}\) уравнение имеет только тривиальное решение \(y(x) = 0\).  
- При \(\lambda > \frac{1}{2}\) общее решение выражается через тригонометрические функции:  
\[
y(x) = C_1 \cos\left(\sqrt{2\lambda - 1} \, x\right) + C_2 \sin\left(\sqrt{2\lambda - 1} \, x\right),
\]  
где \(C_1\) и \(C_2\) — произвольные постоянные.  

\[
\boxed{y(x) = 
\begin{cases}
0, & \lambda \le \dfrac{1}{2}, \\[6pt]
C_1 \cos\left(\sqrt{2\lambda - 1} \, x\right) + C_2 \sin\left(\sqrt{2\lambda - 1} \, x\right), & \lambda > \dfrac{1}{2}.
\end{cases}}
\]