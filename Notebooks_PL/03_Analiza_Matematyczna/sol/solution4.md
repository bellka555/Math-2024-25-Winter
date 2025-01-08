### Завдання з математичного аналізу

#### 2. Довести:
$$
\frac{d}{dx} (\ln(\sin(x))) = \cot(x)
$$
**Розв'язок:**
1. Використовуємо правило похідної для $\ln(u)$:
$$
\frac{d}{dx} (\ln(\sin(x))) = \frac{1}{\sin(x)} \cdot \frac{d}{dx}(\sin(x)).
$$
**Komentarz (PL):** Używamy reguły pochodnej logarytmu naturalnego.

2. Похідна $\sin(x)$ дорівнює $\cos(x)$:
$$
\frac{1}{\sin(x)} \cdot \cos(x) = \cot(x).
$$
**Komentarz (PL):** Liczymy pochodną sinusa i upraszczamy wyrażenie.

3. Вираз $\frac{\cos(x)}{\sin(x)}$ є означенням $\cot(x)$:
$$
\frac{d}{dx} (\ln(\sin(x))) = \cot(x).
$$
**Komentarz (PL):** Zastosowano definicję cotangensa.

---

#### 3. Для $f(x) = \cos(x)$ довести, що $f'(x) = -f(x)$.
**Розв'язок:**
1. Похідна $\cos(x)$:
$$
\frac{d}{dx}(\cos(x)) = -\sin(x).
$$
**Komentarz (PL):** Liczymy pochodną kosinusa.

2. Відомо, що $f(x) = \cos(x)$, тоді:
$$
f'(x) =
$$

3.
$$

$$
**Komentarz (PL):** Wykazano, że pochodna funkcji spełnia podaną równość.

---

#### 4. Використовуючи правило Лопіталя, знайти межі:

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

#### 5. У фізиці позиція частинки задається рівнянням:
$$
x(t) = 3t^2 - 6t + 1.
$$
**Розв'язок:**
1. Знайдемо швидкість $V(t) = x'(t)$:
$$
x'(t) = \frac{d}{dt}(3t^2 - 6t + 1) = 6t - 6.
$$
**Komentarz (PL):** Liczymy prędkość jako pochodną położenia.

2. Знайдемо прискорення $a(t) = V'(t)$:
$$
V'(t) = \frac{d}{dt}(6t - 6) = 6.
$$
**Komentarz (PL):** Liczymy przyspieszenie jako pochodną prędkości.

3. Підставимо $t = 2$:
   - $V(2) = 6(2) - 6 = 12 - 6 = 6.$
   - $a(2) = 6.$

**Відповідь:**
- $V(2) = 6$,
- $a(2) = 6$.

**Komentarz (PL):** Podstawiono wartość $t = 2$ do wzorów na prędkość i przyspieszenie.
