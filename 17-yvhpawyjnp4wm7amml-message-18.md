Дано интегральное уравнение:

\[
\int_{-\infty}^\infty e^{-\lambda |x-t|} y(t) \, dt = f(x), \quad \lambda > 0,
\]

где \( f(x) \) — произвольная функция с условием \( f(\pm \infty) = 0 \).

Это уравнение свёртки с ядром \( K(x) = e^{-\lambda |x|} \). Применяя преобразование Фурье, получим:

\[
\mathcal{F}[K](\omega) = \frac{2\lambda}{\lambda^2 + \omega^2}.
\]

Пусть \( Y(\omega) \) и \( F(\omega) \) — образы Фурье функций \( y(x) \) и \( f(x) \) соответственно. Тогда в пространстве Фурье уравнение принимает вид:

\[
\frac{2\lambda}{\lambda^2 + \omega^2} Y(\omega) = F(\omega),
\]

откуда

\[
Y(\omega) = \frac{\lambda^2 + \omega^2}{2\lambda} F(\omega).
\]

Переходя к обратному преобразованию Фурье и используя свойство \( \mathcal{F}[f''](\omega) = -\omega^2 F(\omega) \), получим искомое решение:

\[
y(x) = \frac{\lambda}{2} f(x) - \frac{1}{2\lambda} f''(x).
\]

\[
\boxed{y(x)=\frac{\lambda}{2}f(x)-\frac{1}{2\lambda}f''(x)}
\]