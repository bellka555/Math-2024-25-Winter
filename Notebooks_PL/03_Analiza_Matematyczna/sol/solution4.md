### Завдання з математичного аналізу

#### 2. Udowodnić (Довести):

$$
\frac{d}{dx} (\ln(\sin(x))) = \cot(x)
$$

**Rozwiązanie (Розв'язок):**

1. Znalezienie dziedziny definicji funkcji (Знайдемо область визначення функції:):

   Sinus jest dodatni sin(x)>0 kiedy 𝑥 leży w przedziale

   k jest dowolną liczbą całkowitą

   sinus ma okres 2𝜋 bierzemy pod uwagę wszystkie przedziały, w których jest on dodatni w każdym okresie
   $$
   0 < \sin(x) ≤ 1, x ∊ (2𝞹k; 𝞹(2k + 1)], k ∊ Z.
   $$

2. Użyj reguły pochodnej dla $\ln(u)$ (Використовуємо правило похідної для):
   $$
   \frac{d}{dx} (\ln(\sin(x))) = \frac{1}{\sin(x)} \cdot \frac{d}{dx}(\sin(x)).
   $$

3. Pochodna $\sin(x)$ równa się $\cos(x)$:

   $$
   \frac{1}{\sin(x)} \cdot \cos(x) = \cot(x).
   $$


4. Odpowiedź:
   $$
   \frac{d}{dx} (\ln(\sin(x))) = \cot(x).
   $$

   $$

   x∊(2𝞹k;𝞹(2k+1)],k∊Z.

   $$

---

#### 3. Dla $f(x) = \cos(x)$ udowodnić, że $f''(x) = -f(x)$.

**Rozwiązanie:**

1. Pochodna $\cos(x)$:

   $$
   \frac{d}{dx}(\cos(x)) = -\sin(x).
   $$

2. Wiadomo, że  $f(x) = \cos(x)$, wtedy:

   $$
   f'(x) = -\sin(x)
   $$

3. $f''(x) = (f'(x))' = (-sin(x))' = -cos(x) = -f(x)$



---

#### 4. Korzystając z reguły Lopitala, znajdź granice:

1. $\lim_{x \to 0} \frac{\sin(x)}{x}$:

   - Межа має вигляд $\frac{0}{0}$, тому застосовуємо правило Лопіталя:
     $$
     \lim_{x \to 0} \frac{\sin(x)}{x} = \lim_{x \to 0} \frac{\cos(x)}{1} = \cos(0) = 1.
     $$
     **Komentarz (PL):** Użyto reguły de L'Hôpitala, ponieważ wyrażenie miało postać $\frac{0}{0}$.

2. $\lim_{x \to \infty} \frac{\ln(x)}{x}$:

   - Межа має вигляд $\frac{\infty}{\infty}$, тому застосовуємо правило Лопіталя:
     $$
     \lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{\frac{1}{x}}{1} = \lim_{x \to \infty} \frac{1}{x} = 0.
     $$
     **Komentarz (PL):** Ponownie zastosowano regułę de L'Hôpitala dla wyrażenia $\frac{\infty}{\infty}$.

3. $\lim_{x \to \infty} \frac{\exp(x)}{x}$:
   - Межа має вигляд $\frac{\infty}{\infty}$, тому застосовуємо правило Лопіталя:
     $$
     \lim_{x \to \infty} \frac{\exp(x)}{x} = \lim_{x \to \infty} \frac{\exp(x)}{1} = \exp(x) \to \infty.
     $$
     **Komentarz (PL):** Wyrażenie dąży do nieskończoności, co wykazano po zastosowaniu reguły de L'Hôpitala.

---

#### 5. Znaleźć prędkość i przyspieszenie
$$
x(t) = 3t^2 - 6t + 1.
$$

**Rozwiązanie:**

1. Знайдемо швидкість $V(t) = x'(t)$:

   $$
   V (t)= \frac{d}{dt}(3t^2 - 6t + 1) = 6t - 6.
   $$

   **Komentarz (PL):** Liczymy prędkość.

2. Знайдемо прискорення $a(t) = V'(t)$:

   $$
   a(t) = \frac{d}{dt}(6t - 6) = 6.
   $$

   **Komentarz (PL):** Liczymy przyspieszenie.

3. Zastępujemy $t = 2$:
   - $V(2) = 6(2) - 6 = 12 - 6 = 6.$
   - $a(2) = 6.$

**Odpowiedź:**

- $V(2) = 6$,
- $a(2) = 6$.

**Komentarz (PL):** Podstawiono wartość $t = 2$ do wzorów na prędkość i przyspieszenie.