Интегральное уравнение  
\[
y(x) - \lambda \int_0^\infty \sin(xt) y(t) \, dt = f(x),
\]  
где \(\lambda \neq \pm \sqrt{\frac{2}{\pi}}\), решается с использованием свойства двойного синус-преобразования:  
\[
\int_0^\infty \sin(xt) \left( \int_0^\infty \sin(tu) y(u) \, du \right) dt = \frac{\pi}{2} y(x).
\]  

Решение имеет вид:  
\[
\boxed{y(x) = \frac{1}{1 - \frac{\pi}{2} \lambda^2} \left[ f(x) + \lambda \int_0^\infty \sin(xt) f(t) \, dt \right]}.
\]  
Условие \(\lambda \neq \pm \sqrt{\frac{2}{\pi}}\) обеспечивает невырожденность знаменателя и единственность решения.