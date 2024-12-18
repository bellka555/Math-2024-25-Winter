# Zadania dotyczące granic

## 1. Oblicz granice:
### (a) $\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n}$

Dzielimy licznik i mianownik przez $n^2$ (najwyższy stopień $n$):

$$
\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} = \lim_{n \to \infty} \frac{\frac{n^2}{n^2} + \frac{3n}{n^2}}{\frac{2n^2}{n^2} - \frac{2n}{n^2}} = \lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}}.
$$

Kiedy $n \to \infty$, $\frac{3}{n} \to 0$ i $\frac{2}{n} \to 0$. Zatem:

$$
\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n} = \frac{1 + 0}{2 - 0} = \frac{1}{2}.
$$

**Odpowiedź:** $\frac{1}{2}$.

---

### (b) $\lim_{n \to \infty} \frac{(2n + 3)^3}{n^3 - 1}$

**Odpowiedź:** $8$.

---

## 2. Udowodnij za pomocą twierdzenia o trzech ciągach:
### $\lim_{n \to \infty} \frac{\sin(n)}{n}$

Wiemy, że $\sin(n)$ jest ograniczone w przedziale $[-1, 1]$. W konsekwencji:

$$
-\frac{1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}.
$$

Gdy $n \to \infty$, obie granice $-\frac{1}{n}$ i $\frac{1}{n}$ dążą do $0$. Zatem na podstawie twierdzenia o trzech ciągach:

$$
\lim_{n \to \infty} \frac{\sin(n)}{n} = 0.
$$

**Odpowiedź:** $0$.

---

## 3. Znajdź granicę ciągu:
### $a_n = \left(1 + \frac{1}{n}\right)^n$

1. **Rozwinięcie przybliżenia:** Dla dużych wartości $n$, wyrażenie $\left(1 + \frac{1}{n}\right)^n$ dąży do liczby zwanej **liczbą Eulera ($e$)**, która jest fundamentalną stałą matematyczną i wynosi w przybliżeniu $e \approx 2.718$.

2. **Logarytm naturalny i pochodne:** Aby zrozumieć zachowanie ciągu, weźmy logarytm naturalny:

   $$
   \ln\left(a_n\right) = \ln\left(\left(1 + \frac{1}{n}\right)^n\right) = n \cdot \ln\left(1 + \frac{1}{n}\right).
   $$

3. **Rozwinięcie logarytmu w szereg Taylora:** Dla dużych $n$ rozwijamy logarytm $\ln(1 + x)$ w przybliżeniu dla małych wartości $x = \frac{1}{n}$:

   $$
   \ln\left(1 + \frac{1}{n}\right) \approx \frac{1}{n}.
   $$

   Wstawiamy to z powrotem do równania:

   $$
   \ln\left(a_n\right) \approx n \cdot \frac{1}{n} = 1.
   $$

4. **Ekspotencjowanie:** Ostatecznie, bierzemy eksponent:

   $$
   a_n = e^{\ln(a_n)} = e^1 = e.
   $$

**Odpowiedź:** $e$.
