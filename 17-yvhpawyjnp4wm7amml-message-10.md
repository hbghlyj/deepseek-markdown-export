Уравнение  
\[
\int_0^x y(t) y(x - t) \, dt = a x + b, \quad a > 0, \ b > 0,
\]  
с допущением интегрируемой особенности в нуле решается с помощью преобразования Лапласа. Левая часть — свёртка \(y * y\), поэтому в образах Лапласа  
\[
Y(s)^2 = \frac{a}{s^2} + \frac{b}{s}.
\]  
Отсюда  
\[
Y(s) = \pm \frac{\sqrt{a + b s}}{s}.
\]  
Обратное преобразование Лапласа даёт решение:  
\[
y(x) = \pm \left[ \sqrt{\frac{b}{\pi}} \frac{e^{-(a/b) x}}{\sqrt{x}} + \sqrt{a} \, \operatorname{erf}\left( \sqrt{\frac{a}{b} x} \right) \right].
\]  
Проверка: при \(x \to 0^+\) главный член \( \sim 1/\sqrt{x} \) обеспечивает интегрируемую особенность, а свёртка \(y * y\) равна \(a x + b\) по построению.

\[
\boxed{y(x) = \pm \left[ \sqrt{\frac{b}{\pi}} \frac{e^{-(a/b) x}}{\sqrt{x}} + \sqrt{a} \, \operatorname{erf}\left( \sqrt{\frac{a}{b} x} \right) \right]}
\]