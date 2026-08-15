Интегральное уравнение

\[
y(x) + \lambda \int_0^\infty e^{-|x-t|} y(t) \, dt = f(x), \quad x \ge 0,
\]

где \( \lambda > -\frac{1}{2} \) и \( f(x) \) — произвольная функция, решается с помощью преобразования Лапласа. В результате получается явное выражение для \( y(x) \):

\[
\boxed{
y(x) = f(x) + \frac{2\lambda}{\sqrt{1+2\lambda}} \int_0^x \sinh\left(\sqrt{1+2\lambda} \, (x-t)\right) f(t) \, dt - \frac{2\lambda \, C}{\sqrt{1+2\lambda}+1} \left( \cosh\left(\sqrt{1+2\lambda} \, x\right) + \frac{\sinh\left(\sqrt{1+2\lambda} \, x\right)}{\sqrt{1+2\lambda}} \right)
}
\]

где

\[
C = \int_0^\infty e^{-\sqrt{1+2\lambda} \, t} f(t) \, dt.
\]

Решение существует и единственно при условии \( \lambda > -\frac{1}{2} \). При \( \lambda = 0 \) решение сводится к \( y(x) = f(x) \).