Подстановка функции  
\[
y(x) = -b \cdot \frac{f(x)}{f(a-x)}, \quad f(x) \neq 0,
\]  
в уравнение \( y(x) \cdot y(a-x) = b^2 \) даёт:

\[
\begin{aligned}
y(a-x) &= -b \cdot \frac{f(a-x)}{f(a - (a-x))} = -b \cdot \frac{f(a-x)}{f(x)}, \\[4pt]
y(x) \cdot y(a-x) &= \left( -b \cdot \frac{f(x)}{f(a-x)} \right) \cdot \left( -b \cdot \frac{f(a-x)}{f(x)} \right) = b^2 \cdot \frac{f(x) f(a-x)}{f(a-x) f(x)} = b^2.
\end{aligned}
\]

Таким образом, функция удовлетворяет уравнению.

**Замечание:**  
При \( b \neq 0 \) общее решение можно записать в виде  
\[
y(x) = b \cdot \frac{f(x)}{f(a-x)},
\]  
так как замена \( f(x) \to -f(x) \) не меняет выражения. Поэтому форма с дополнительным знаком «минус» не даёт новых решений, но подтверждает корректность общего вида.