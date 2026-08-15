Для сильно эллиптического уравнения  
\[
u_{xxxx} + a u_{xxyy} + b u_{yyyy} = 0, \quad b > 0, \quad a > -2\sqrt{b},
\]  
фундаментальное решение \(E(x,y)\) (удовлетворяющее \(P(D)E = \delta\)) задаётся формулой:  

\[
E(x,y) = \frac{1}{8\pi^2} \int_0^{2\pi} \frac{K(x\cdot\omega)}{Q(\theta)} \, d\theta,
\]  

где  
- \(\omega = (\cos\theta, \sin\theta)\),  
- \(x\cdot\omega = x\cos\theta + y\sin\theta\),  
- \(Q(\theta) = \cos^4\theta + a \cos^2\theta \sin^2\theta + b \sin^4\theta > 0\),  
- \(K(t) = \dfrac{1}{4\pi} t^2 \ln |t| - \dfrac{1-2\ln 2}{4\pi} t^2\).  

В полярных координатах \(x = r\cos\phi,\; y = r\sin\phi\) это принимает вид:  

\[
E = A(\phi) \, r^2 \ln r + B(\phi) \, r^2,
\]  

где коэффициенты выражаются через интегралы:  

\[
\begin{aligned}
A(\phi) &= \frac{1}{8\pi^2} I_1(\phi), \\
B(\phi) &= \frac{1}{8\pi^2} \bigl( I_2(\phi) - (1-2\ln 2) I_1(\phi) \bigr),
\end{aligned}
\]  

\[
I_1(\phi) = \int_0^{2\pi} \frac{\cos^2(\theta-\phi)}{Q(\theta)} \, d\theta, \quad
I_2(\phi) = \int_0^{2\pi} \frac{\cos^2(\theta-\phi) \ln |\cos(\theta-\phi)|}{Q(\theta)} \, d\theta.
\]  

Эти интегралы в общем случае вычисляются численно и зависят от направления \(\phi\), поскольку оператор не является вращательно-инвариантным (за исключением случая \(a=2,\; b=1\), когда \(Q(\theta)\equiv1\) и \(E = \dfrac{1}{8\pi} r^2 \ln r\)).  

Таким образом, фундаментальное решение существует, имеет логарифмическую сингулярность и представимо в указанном виде.