# Rozwiązanie zadań

## 1. Obliczyć:
$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}.
$$

### Rozwiązanie:

1. Podzielmy licznik i mianownik przez $x^4$ (największy stopień w mianowniku):
   $$
   \frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{x^3}{x^4} + \frac{2x^2}{x^4}}{\frac{x^4}{x^4} - \frac{3x^3}{x^4}} = \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}.
   $$

2. Dla $x \to \infty$, wszystkie składniki z $\frac{1}{x}$, $\frac{2}{x^2}$, $\frac{3}{x}$ zmierzają do zera:
   $$
   \lim_{x \to \infty} \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}} = \frac{0 + 0}{1 - 0} = 0.
   $$

**Odpowiedź:** $\boxed{0}$.

---

## 2. Obliczyć:
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1}.
$$

### Rozwiązanie:

1. Wiadomo, że $\lim_{x \to 0} \sin(3x) = 3x$ (ponieważ $\sin(kx) \approx kx$ dla $x \to 0$).

2. Stąd:
   $$
   \lim_{x \to 0} \frac{\sin(3x)}{2x + 1} = \frac{\lim_{x \to 0} \sin(3x)}{\lim_{x \to 0} (2x + 1)} = \frac{0}{1} = 0.
   $$

**Odpowiedź:** $\boxed{0}$.

---

## 3. Znaleźć asymptoty funkcji:

### (a) $f(x) = \frac{x^2 - 1}{x^2 + 1}$

- **Asymptoty poziome:**
  Dla $x \to \pm \infty$, podzielmy licznik i mianownik przez $x^2$:
  $$
  f(x) = \frac{\frac{x^2}{x^2} - \frac{1}{x^2}}{\frac{x^2}{x^2} + \frac{1}{x^2}} = \frac{1 - 0}{1 + 0} = 1.
  $$
  Zatem asymptota pozioma: $y = 1$.

- **Asymptoty pionowe:**
  Funkcja $f(x)$ nie ma asymptot pionowych, ponieważ mianownik $x^2 + 1 > 0$ dla wszystkich $x$.

---

### (b) $g(x) = \frac{\sin(x)}{x^2 + 1}$

- **Asymptoty poziome:**
  Dla $x \to \pm \infty$, licznik $\sin(x)$ oscyluje w granicach $[-1, 1]$, a mianownik $x^2 + 1$ zmierza do $\infty$. Stąd:
  $$
  \lim_{x \to \pm \infty} g(x) = 0.
  $$
  Asymptota pozioma: $y = 0$.

- **Asymptoty pionowe:**
  Mianownik $x^2 + 1 > 0$ dla wszystkich $x$, więc asymptot pionowych brak.

---

## Odpowiedzi:

1. $y = 1$ — asymptota pozioma $f(x)$.  
2. $y = 0$ — asymptota pozioma $g(x)$.  
3. Obie funkcje nie mają asymptot pionowych.

