## 1. Obliczanie pochodnych funkcji

### (a) $y(x) = -3x + 3$

Funkcja jest liniowa. Pochodna $-3x$ wynosi $-3$, a pochodna $3$ to $0$ (pochodna stałej wynosi $0$).  
Zatem:
$$y'(x) = -3$$

---

### (b) $y(x) = \pi x + \sin(1)$

Pochodna $\pi x$ wynosi $\pi$, ponieważ $\pi$ jest stałą. Pochodna $\sin(1)$ wynosi $0$, ponieważ $\sin(1)$ jest stałą.  
Zatem:
$$y'(x) = \pi$$

---

### (c) $y(x) = 4 + \sin(2)$

Oba składniki ($4$ i $\sin(2)$) są stałe. Pochodna stałej zawsze wynosi $0$.  
Zatem:
$$y'(x) = 0$$

---

### (d) $y(x) = 2x^3 - 3x^2 + 8x - 9$

Stosujemy regułę pochodnej potęgowej: $\frac{d}{dx}(x^n) = nx^{n-1}$ dla każdego składnika:

- Pochodna $2x^3$: $6x^2$
- Pochodna $-3x^2$: $-6x$
- Pochodna $8x$: $8$
- Pochodna $-9$: $0$

Zatem:
$$y'(x) = 6x^2 - 6x + 8$$

---

### (e) $y(x) = 6x^{1/3}$

Zastosowano regułę pochodnej potęgowej:

- Pochodna $x^{1/3}$ wynosi $\frac{1}{3}x^{-2/3}$
- Mnożymy przez $6$, otrzymujemy:
$$y'(x) = \frac{2}{x^{2/3}}$$

---

### (f) $y(x) = \sqrt{x}$

Przekształcamy $\sqrt{x}$ na $x^{1/2}$. Stosujemy regułę pochodnej potęgowej:

- Pochodna $x^{1/2}$ wynosi $\frac{1}{2}x^{-1/2}$
- Przekształcamy:
$$y'(x) = \frac{1}{2\sqrt{x}}$$

---

### (g) $y(x) = \cos(x) + \sin(x)$

Stosujemy reguły pochodnych funkcji trygonometrycznych:

- Pochodna $\cos(x)$: $-\sin(x)$
- Pochodna $\sin(x)$: $\cos(x)$

Zatem:
$$y'(x) = -\sin(x) + \cos(x)$$

---

### (h) $y(x) = 2\sin(x)\cos(x)$

Stosujemy tożsamość trygonometryczną: $2\sin(x)\cos(x) = \sin(2x)$.  
Następnie obliczamy pochodną $\sin(2x)$:

- Pochodna $\sin(2x)$: $2\cos(2x)$

Zatem:
$$y'(x) = 2\cos(2x)$$

---

### (i) $y(x) = x\sin(x)$

Stosujemy regułę iloczynu: $\frac{d}{dx}(uv) = u'v + uv'$.

- $u = x$, $u' = 1$
- $v = \sin(x)$, $v' = \cos(x)$

Zatem:
$$y'(x) = 1 \cdot \sin(x) + x \cdot \cos(x) = \sin(x) + x\cos(x)$$

---

### (j) $y(x) = (x + 1)(x + 1)$

Rozwijamy nawiasy: $y(x) = (x + 1)^2$.  
Stosujemy regułę pochodnej potęgowej:

- Pochodna $(x + 1)^2$: $2(x + 1)$

Zatem:
$$y'(x) = 2(x + 1)$$

---

### (k) $y(x) = \frac{x}{x + 1}$

Stosujemy regułę pochodnej ilorazu:  
$$\frac{d}{dx} \left(\frac{u}{v}\right) = \frac{u'v - uv'}{v^2}$$

- $u = x$, $u' = 1$
- $v = x + 1$, $v' = 1$

Zatem:
$$y'(x) = \frac{1 \cdot (x + 1) - x \cdot 1}{(x + 1)^2} = \frac{(x + 1) - x}{(x + 1)^2} = \frac{1}{(x + 1)^2}$$

---

### (l) $y(x) = (x + 1)e^{x}$

Stosujemy regułę iloczynu:

- $u = x + 1$, $u' = 1$
- $v = e^x$, $v' = e^x$

Zatem:
$$y'(x) = 1 \cdot e^x + (x + 1) \cdot e^x = e^x + (x + 1)e^x = (x + 2)e^x$$

---

### (m) $y(x) = \sin(x^2)$

Stosujemy regułę funkcji złożonej:  
$$\frac{d}{dx} \sin(g(x)) = \cos(g(x)) \cdot g'(x)$$

- $g(x) = x^2$, $g'(x) = 2x$

Zatem:
$$y'(x) = \cos(x^2) \cdot 2x = 2x\cos(x^2)$$

---

### (n) $y(x) = e^{-2x}$

Stosujemy regułę funkcji złożonej:

- Pochodna $e^u$: $e^u \cdot u'$
- $u = -2x$, $u' = -2$

Zatem:
$$y'(x) = e^{-2x} \cdot (-2) = -2e^{-2x}$$

---

### (o) $y(x) = \frac{\sin(1)}{\sin(x + 1)}$

$\sin(1)$ jest stałą, stosujemy regułę ilorazu:

- $u = \sin(1)$, $u' = 0$
- $v = \sin(x + 1)$, $v' = \cos(x + 1)$

Zatem:
$$y'(x) = \frac{0 \cdot \sin(x + 1) - \sin(1) \cdot \cos(x + 1)}{\sin^2(x + 1)} = -\frac{\sin(1)\cos(x + 1)}{\sin^2(x + 1)}$$

---

### (p) $y(x) = \sqrt{2x + 1}$

Przekształcamy: $y(x) = (2x + 1)^{1/2}$. Stosujemy regułę pochodnej potęgowej i złożonej:

- Pochodna $(2x + 1)^{1/2}$: $\frac{1}{2}(2x + 1)^{-1/2} \cdot 2$

Zatem:
$$y'(x) = \frac{1}{\sqrt{2x + 1}}$$

