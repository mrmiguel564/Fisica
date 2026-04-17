+ Radiación: Propagación de energía mediante ondas electromagnéticas. Este mecanismo no requiere de un medio material para llevarse a cabo.
+ Convección: Transporte conjunto de energía y masa debido a diferencia de temperatura. Esta puede manifestarse de dos maneras:
	+ Natural: circulación de aire en radiadores, brisas marinas, etc.
	+ Forzada: ventilador, secador de pelo, bomba de calor, etc.
+ Conducción: Propagación de energía por contacto directo, sin transporte de masa.

---

## Radiación

### Espectro de cuerpo negro

- **Explicación de Rayleigh-Jeans:**

$$I(\lambda) = \frac{2\pi c k_B T}{\lambda^4}$$

- **Explicación de Planck:**

$$I(\lambda) = \frac{2\pi h c^2}{\lambda^5 \left(e^{hc/\lambda k_B T} - 1\right)}$$

- **Ley de desplazamiento de Wien:**

$$\lambda_{\text{máx}} T \approx 2{,}90 \times 10^{-3} \; [\text{m·K}]$$

- **Ley de Stefan-Boltzmann:**

$$I = \varepsilon \sigma_{SB} T^4 \qquad ; \qquad 0 \leq \varepsilon \leq 1$$

$$\sigma_{SB} = \frac{2\pi^5 k_B^4}{15 c^2 h^3} \approx 5{,}67 \times 10^{-8} \; \left[\frac{\text{W}}{\text{m}^2 \text{K}^4}\right]$$

Constantes:
$$k_B \approx 1{,}38 \times 10^{-23} \; \left[\frac{\text{J}}{\text{K}}\right] \qquad ; \qquad h \approx 6{,}626 \times 10^{-34} \; [\text{J·s}]$$

---

## Flujo (concepto genérico)

El **flujo** es la tasa de transporte de una cantidad extensiva (energía, masa, carga, etc.) por unidad de tiempo:

$$J_V = \frac{\text{cantidad}}{\text{tiempo}}$$

La **densidad de flujo** es el flujo por unidad de área:

$$\mathcal{J}_V = \frac{J_V}{A} = \frac{\text{cantidad}}{\text{tiempo} \times \text{área}}$$

---

## Radiación — Ejercicio que todo ingeniero/a debe conocer La intensidad de la radiación solar que llega a las capas superiores de la atmósfera terrestre es de aproximadamente 1,4 $\frac{\text{kW}}{\text{m}^2}$. Este es un valor a recordar para toda la vida. Considere además que la distancia de la Tierra al Sol es de 1,00 UA.


1) Determine la potencia total de la radiación que emite el Sol.

La intensidad $I$ se distribuye uniformemente sobre una esfera de radio $r = 1 \; \text{UA} = 1{,}4 \times 10^{11} \; \text{m}$:

$$P = I \cdot 4\pi r^2 = 1400 \times 4\pi \times (1{,}496 \times 10^{11})^2$$

$$P = 1400 \times 4\pi \times 2{,}238 \times 10^{22} = 1400 \times 2{,}812 \times 10^{23}$$

$$\boxed{P \approx 3{,}94 \times 10^{26} \; \text{W}}$$

2) Determine la temperatura en la superficie del Sol. ¿De qué color debería verse?
3) Calcule la potencia de la radiación solar recibida en la Tierra.
4) Averigüe (lea al respecto) cuánta energía necesita Chile para funcionar (demanda) y, en base a ello, ¿qué superficie se debería cubrir con paneles solares para tales propósitos? Explique por qué esto es inviable.

La demanda eléctrica de Chile es de aproximadamente $80 \; \text{TWh/año}$, lo que equivale a una potencia media:

$$P_{\text{Chile}} = \frac{80 \times 10^{12} \; \text{Wh}}{8760 \; \text{h}} \approx 9{,}13 \times 10^{9} \; \text{W} \approx 9{,}13 \; \text{GW}$$

Considerando la irradiancia solar $I = 1{,}4 \; \frac{\text{kW}}{\text{m}^2}$, una eficiencia de paneles solares $\eta \approx 20\%$ y un factor de capacidad solar $f_c \approx 25\%$ (horas de sol efectivas):

$$A = \frac{P_{\text{Chile}}}{I \cdot \eta \cdot f_c} = \frac{9{,}13 \times 10^{9}}{1400 \times 0{,}20 \times 0{,}25} = \frac{9{,}13 \times 10^{9}}{70} \approx 1{,}3 \times 10^{8} \; \text{m}^2$$

$$\boxed{A \approx 130 \; \text{km}^2}$$

Esto equivale a un cuadrado de ~11,4 km de lado. Es inviable porque:
- No hay sol las 24 horas ni todos los días (nubes, noche, estaciones).
- Se requeriría almacenamiento masivo de energía (baterías) para cubrir la demanda nocturna.
- La infraestructura de transmisión, mantenimiento, terreno y costo de inversión serían enormes.
- La demanda real incluye también energía térmica e industrial, no solo eléctrica, lo que aumentaría aún más la superficie necesaria.



Ejercicio de Calor
Un termo panel o "ventan de doble vidrio", esta  formando por dos placas de vidrio de 10mm de espesor que encierra la capa de argon Tambien de 10mm Suponga que la cara exterior del panel esta a -5 y la cara interior a 15C Ademas. 

---

## Conducción — Ley de Fourier

Considere una barra de longitud $L$, cuyos extremos están a temperaturas $T_a > T_b$. En **estado estacionario**, el flujo de calor es:

$$J_Q = \frac{dQ}{dt} = -\kappa A \frac{dT}{dx}$$

donde $\kappa$ es la conductividad térmica del material.

Para el caso lineal (barra):

$$J_Q = \kappa A \frac{\Delta T}{L}$$

### Conductividad térmica de materiales

| Material | $\kappa$ $\left[\frac{\text{W}}{\text{m·K}}\right]$ |
|:---|:---:|
| Plata | 406 |
| Cobre | 385 |
| Aluminio | 205 |
| Latón | 109 |
| Acero | 50 |
| Plomo | 35 |
| Hormigón | 0,8 |
| Vidrio | 0,8 |
| Ladrillo (tabiquería) | 0,6 |
| Ladrillo (aislante) | 0,15 |
| Corcho | 0,04 |
| Fieltro | 0,04 |
| Fibra de vidrio | 0,04 |

---

## Ejercicio: Termo-panel (ventana de doble vidrio)

Un termo-panel está formado por dos placas de vidrio de $10 \; [\text{mm}]$ de espesor que encierran una capa de argón también de $10 \; [\text{mm}]$. La cara exterior está a $-5\;°\text{C}$ y la interior a $15\;°\text{C}$. Área transversal de $1 \; [\text{m}^2]$.

Datos: $\kappa_{\text{vidrio}} = 0{,}8 \; \frac{\text{W}}{\text{m·K}}$ ; $\kappa_{\text{Ar}} = 0{,}02 \; \frac{\text{W}}{\text{m·K}}$

a) La diferencia de temperatura a la cual se encuentra sometida la capa de argón.
b) El flujo de energía (calor) a través del termo-panel.
c) El espesor que debería tener un solo vidrio para igualar la resistencia térmica del termo-panel.

### Desarrollo parcial


$K_V(T_1-15) = -K_V(5+T_2)$
$T_1 = (15-5) - T_2$
$T_1 = 10-T_2$

Luego: $H_{ar}(T_2 - 10+T2) = -K_V(5+T_2)$
$2K_{ar} T_2 -10K_{ar} = -5K_v - K_v T_2$

$T_2 = \frac{10K_{ar} -5K_v}{2K_{ar}+K_v} = \frac{10 * 0.02 -5 * 0.9}{2*0.02 + 0.3} = -4.523$




aqui iria el ejercicio de la tuberia.

---

## Ejercicio: Conducción en tubería cilíndrica

Considere una tubería cilíndrica de largo $L$, conductividad térmica $\kappa$, radio interno $R_1$ y externo $R_2$ ($R_2 > R_1$). Por el interior se transporta un fluido a temperatura $T_1$, y el exterior está a $T_2 < T_1$. En estado estacionario:

a) Determine la potencia transferida desde el interior hacia el exterior.
b) Obtenga la temperatura en función del radio, $T(r)$. ¿Varía linealmente?
c) ¿A qué distancia desde $r = R_1$ la temperatura ha disminuido en la mitad de $T_1 - T_2$?
d) Grafique $T(r)$ para $R_1 \leq r \leq R_2$.
e) Analice el límite de tubo delgado: $\frac{R_2 - R_1}{R_1} \ll 1$.

### Solución

**a) Potencia:** En estado estacionario el flujo es constante. La geometría cilíndrica da $A = 2\pi r L$:

$$J_Q = -\kappa (2\pi r L) \frac{dT}{dr} \implies J_Q \frac{dr}{r} = -2\pi\kappa L \; dT$$

Integrando entre $R_1$ y $R_2$:

$$\boxed{J_Q = \frac{2\pi\kappa L(T_1 - T_2)}{\ln(R_2/R_1)}}$$

**b) Temperatura en función del radio:** El flujo es constante en todo punto, haciendo $R_2 \to r$ y $T_2 \to T(r)$:

$$\boxed{T(r) = T_1 - (T_1 - T_2)\frac{\ln(r/R_1)}{\ln(R_2/R_1)}}$$

- Si $r \to R_1$: $T(R_1) = T_1$ ✓
- Si $r \to R_2$: $T(R_2) = T_2$ ✓
- La temperatura **no varía linealmente** (varía logarítmicamente).

**c) Punto medio de temperatura:** Evaluando $T(r) = \frac{T_1 + T_2}{2}$:

$$\frac{\ln(r/R_1)}{\ln(R_2/R_1)} = \frac{1}{2} \implies \boxed{r = \sqrt{R_1 R_2}}$$

La distancia desde $R_1$ es: $\sqrt{R_1 R_2} - R_1$.

**e) Límite de tubo delgado:** Usando $\ln(1+\varepsilon) \approx \varepsilon$ para $\varepsilon \ll 1$:

$$T(r) \approx T_1 - (T_1 - T_2)\frac{r - R_1}{R_2 - R_1}$$

> ¡Se recupera la variación lineal del caso plano (como el termo-panel)!



## Ejemplo lago congelado.

Tenemo un lago que se va congelando 
Donde el el aire esta a -30 C y el lago esta a 4 grados (investigar el fenomeno)

El traspaso de calor esta en W trabajo.
Mientras que el hielo que se va congelando va usando Calorias. 

Por ende se debe Derivar el trabajo para determinar el espesor del hielo.

### Enunciado completo

Considere un lago extenso, de área $A$, cuya superficie se encuentra expuesta a una temperatura ambiente constante $T_a < 0\;°\text{C}$. El lago está parcialmente congelado, con una capa de hielo de espesor $H_0$ sobre el agua líquida. Suponga transferencia de calor solo por conducción y temperatura ambiente constante (estado estacionario).

a) Determine una expresión para el flujo de calor (potencia) a través de la capa de hielo.
b) Plantee un modelo para cómo crece la capa de hielo $h(t)$.
c) Determine el tiempo para que la capa duplique su espesor $H_0$.
d) Grafique $h(t)$.

### Modelo

El flujo de calor a través de la capa de hielo ya formada:

$$J = \kappa A \frac{\Delta T}{h}$$

Esta energía proviene de una nueva capa de hielo en formación:

$$J = \frac{dQ}{dt} = \frac{L_f (\rho A \; dh)}{dt}$$

Igualando ambos flujos:

$$\kappa \frac{\Delta T}{h} = \rho L_f \frac{dh}{dt}$$

Separando variables e integrando:

$$h \; dh = \frac{\kappa \Delta T}{\rho L_f} dt$$

$$\int_{H_0}^{h(t)} h' \; dh' = \frac{\kappa \Delta T}{\rho L_f} \int_0^t dt'$$

$$\boxed{h(t) = \sqrt{H_0^2 + \frac{2\kappa \Delta T}{\rho L_f} t}}$$

> Notar que $h(t) \propto \sqrt{t}$: el crecimiento del hielo se ralentiza con el tiempo, porque la capa más gruesa actúa como mejor aislante.

---

## Caso General: Ecuación de difusión térmica

Para el caso general $T \to T(x, t)$ (unidimensional), a partir de la conservación de la energía se obtiene:

$$\frac{\partial T}{\partial t} = D \frac{\partial^2 T}{\partial x^2}$$

La constante de **difusión térmica**:

$$D = \frac{\kappa}{\rho c}$$

caracteriza la rapidez con que un material responde a variaciones de temperatura. Mide la relación entre la capacidad del material para **conducir** calor ($\kappa$) y su capacidad para **almacenarlo** ($\rho c$).

- **$D$ alto:** el material transmite rápidamente los cambios térmicos.
- **$D$ bajo:** respuesta más lenta y amortiguada.

