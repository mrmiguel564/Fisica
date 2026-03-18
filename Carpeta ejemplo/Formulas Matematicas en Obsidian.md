# Fórmulas Matemáticas en Obsidian

Obsidian utiliza **MathJax** para renderizar expresiones matemáticas escritas en sintaxis **LaTeX**.

- **Modo en línea** (inline): escribe la fórmula entre signos `$...$`
- **Modo bloque** (display): escribe la fórmula entre `$$...$$` en líneas separadas

---

## 1. Operaciones básicas

| Resultado | Código LaTeX |
|:---|:---|
| $a + b$ | `$a + b$` |
| $a - b$ | `$a - b$` |
| $a \cdot b$ | `$a \cdot b$` |
| $a \times b$ | `$a \times b$` |
| $\frac{a}{b}$ | `$\frac{a}{b}$` |
| $a^2$ | `$a^2$` |
| $a_i$ | `$a_i$` |
| $\sqrt{x}$ | `$\sqrt{x}$` |
| $\sqrt[3]{x}$ | `$\sqrt[3]{x}$` |
| $|x|$ | `$|x|$` |

---

## 2. Fracciones

Fracción simple:

$$\frac{a}{b}$$

Fracción anidada:

$$\frac{1}{1 + \frac{1}{x}}$$

Ejemplo físico (conversión Celsius–Fahrenheit):

$$T_F = \frac{9}{5} \cdot T_C + 32$$

---

## 3. Potencias y subíndices

| Resultado | Código |
|:---|:---|
| $x^2$ | `$x^2$` |
| $x^{10}$ | `$x^{10}$` |
| $x_i$ | `$x_i$` |
| $x_{ij}$ | `$x_{ij}$` |
| $x_0^2$ | `$x_0^2$` |
| $10^{-6}$ | `$10^{-6}$` |
| $e^{i\pi}$ | `$e^{i\pi}$` |

---

## 4. Letras griegas

| Minúscula | Código | Mayúscula | Código |
|:---:|:---|:---:|:---|
| $\alpha$ | `\alpha` | $\Alpha$ | `\Alpha` |
| $\beta$ | `\beta` | $\Beta$ | `\Beta` |
| $\gamma$ | `\gamma` | $\Gamma$ | `\Gamma` |
| $\delta$ | `\delta` | $\Delta$ | `\Delta` |
| $\epsilon$ | `\epsilon` | — | — |
| $\theta$ | `\theta` | $\Theta$ | `\Theta` |
| $\lambda$ | `\lambda` | $\Lambda$ | `\Lambda` |
| $\mu$ | `\mu` | — | — |
| $\pi$ | `\pi` | $\Pi$ | `\Pi` |
| $\rho$ | `\rho` | — | — |
| $\sigma$ | `\sigma` | $\Sigma$ | `\Sigma` |
| $\tau$ | `\tau` | — | — |
| $\phi$ | `\phi` | $\Phi$ | `\Phi` |
| $\omega$ | `\omega` | $\Omega$ | `\Omega` |

---

## 5. Sumatoria

Sumatoria genérica:

$$\sum_{i=1}^{n} a_i = a_1 + a_2 + \cdots + a_n$$

Suma de los primeros $n$ números naturales:

$$\sum_{k=1}^{n} k = \frac{n(n+1)}{2}$$

Suma de cuadrados:

$$\sum_{k=1}^{n} k^2 = \frac{n(n+1)(2n+1)}{6}$$

---

## 6. Productoria

$$\prod_{i=1}^{n} a_i = a_1 \cdot a_2 \cdots a_n$$

Ejemplo — factorial:

$$n! = \prod_{k=1}^{n} k$$

---

## 7. Integrales

| Resultado | Código |
|:---|:---|
| $\int f(x)\, dx$ | `\int f(x)\, dx` |
| $\int_a^b f(x)\, dx$ | `\int_a^b f(x)\, dx` |
| $\iint$ | `\iint` |
| $\oint$ | `\oint` |

Integral definida:

$$\int_a^b f(x)\, dx = F(b) - F(a)$$

Ejemplo — trabajo en termodinámica:

$$W = \int_{V_i}^{V_f} P\, dV$$

---

## 8. Límites y derivadas

Límite:

$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

Derivada:

$$\frac{d}{dx}\left(x^n\right) = n\, x^{n-1}$$

Derivada parcial:

$$\frac{\partial f}{\partial x}$$

Segunda derivada:

$$\frac{d^2 y}{dx^2}$$

---

## 9. Funciones trigonométricas y logarítmicas

| Resultado | Código |
|:---|:---|
| $\sin\theta$ | `\sin\theta` |
| $\cos\theta$ | `\cos\theta` |
| $\tan\theta$ | `\tan\theta` |
| $\arcsin x$ | `\arcsin x` |
| $\ln x$ | `\ln x` |
| $\log_{10} x$ | `\log_{10} x` |
| $\log_b x$ | `\log_b x` |

Identidad de Euler:

$$e^{i\pi} + 1 = 0$$

---

## 10. Vectores y notación matricial

Vector con flecha:

$$\vec{v} = v_x\, \hat{i} + v_y\, \hat{j} + v_z\, \hat{k}$$

Módulo de un vector:

$$|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$$

Producto punto:

$$\vec{A} \cdot \vec{B} = |\vec{A}||\vec{B}|\cos\theta$$

Producto vectorial (magnitud):

$$|\vec{A} \times \vec{B}| = |\vec{A}||\vec{B}|\sin\theta$$

Matriz 2×2:

$$\begin{pmatrix} a & b \\ c & d \end{pmatrix}$$

Sistema de ecuaciones con `cases`:

$$\begin{cases} 2x + y = 5 \\ x - y = 1 \end{cases}$$

---

## 11. Texto dentro de fórmulas

Usar `\text{}` para escribir texto dentro de una expresión matemática:

$$F = m \cdot a \quad \text{(Segunda Ley de Newton)}$$

$$\Delta T = T_f - T_i \quad \text{donde } T_f > T_i$$

---

## 12. Alineación de ecuaciones

Para alinear pasos de un desarrollo, usa `aligned`:

$$\begin{aligned}
\Delta L &= \alpha \cdot L_0 \cdot \Delta T \\
         &= 11 \times 10^{-6} \cdot 50 \cdot 35 \\
         &= 0{,}01925 \text{ cm}
\end{aligned}$$

---

## 13. Cajas para resultados

Resalta el resultado final con `\boxed{}`:

$$\boxed{T_f \approx 104 \text{ °C}}$$

---

## 14. Espaciado en fórmulas

| Resultado | Código | Descripción |
|:---|:---|:---|
| $a\, b$ | `a\, b` | espacio fino |
| $a\; b$ | `a\; b` | espacio medio |
| $a\quad b$ | `a\quad b` | espacio grande |
| $a\qquad b$ | `a\qquad b` | espacio muy grande |

---

## 15. Ejemplos físicos completos

### Energía cinética

$$E_k = \frac{1}{2} m v^2$$

### Ley de gravitación universal

$$F = G \frac{m_1 m_2}{r^2}$$

### Ecuación de onda

$$y(x, t) = A \sin\!\left(kx - \omega t + \phi\right)$$

### Primer Principio de la Termodinámica

$$\Delta U = Q - W$$

### Entropía

$$\Delta S = \int_i^f \frac{\delta Q_{\text{rev}}}{T}$$

### Ley de Fourier (conducción de calor)

$$\frac{dQ}{dt} = -k A \frac{\Delta T}{\Delta x}$$

### Período de un péndulo simple

$$T = 2\pi\sqrt{\frac{L}{g}}$$

### Efecto Doppler

$$f' = f \cdot \frac{v \pm v_o}{v \mp v_s}$$
