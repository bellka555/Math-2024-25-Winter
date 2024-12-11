

## 2. Udowodnij, że $$\frac{d}{dx} (\ln(\sin(x))) = \cot(x)$$

### Kroki:

1. Zastosuj wzór na pochodną logarytmu:  
   $$\frac{d}{dx} (\ln(u)) = \frac{u'}{u}$$  
   Tutaj $u = \sin(x)$.

2. Oblicz pochodną $u$:  
   $$u' = \cos(x)$$

3. Podstaw do wzoru:  
   $$\frac{\cos(x)}{\sin(x)} = \cot(x)$$

Dowód zakończony.

---

## 3. Udowodnij, że dla $$f(x) = \cos(x)$$, $$f''(x) = -f(x)$$

1. Pochodna pierwsza:  
   $$f'(x) = -\sin(x)$$

2. Pochodna druga:  
   $$f''(x) = -\cos(x)$$

3. Porównanie:  
   $$f''(x) = -f(x)$$

Dowód zakończony.

---

## 4. Granice z regułą de L’Hospitala

### (a) $$\lim_{x \to 0} \frac{\sin(x)}{x}$$

Stosujemy regułę:  
$$\lim_{x \to 0} \frac{\sin(x)}{x} = \lim_{x \to 0} \frac{\cos(x)}{1} = 1$$

---

### (b) $$\lim_{x \to \infty} \frac{\ln(x)}{x}$$

Stosujemy regułę:  
$$\lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{\frac{1}{x}}{1} = \lim_{x \to \infty} \frac{1}{x} = 0$$

---

### (c) $$\lim_{x \to \infty} e^x$$

Funkcja rośnie nieograniczenie:  
$$\lim_{x \to \infty} e^x = \infty$$

---

## 5. Zadanie z fizyki: pozycja, prędkość i przyspieszenie cząstki

Dla $x(t) = 3t^2 - 6t + 1$:

### (a) Prędkość:  
$$V(t) = x'(t) = 6t - 6$$  
Przy $t = 2$:  
$$V(2) = 6 \cdot 2 - 6 = 6$$

---

### (b) Przyspieszenie:  
$$a(t) = V'(t) = 6$$  
Przy $t = 2$:  
$$a(2) = 6$$
