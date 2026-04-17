# Dilatación Térmica

La **dilatación térmica** es el aumento de las dimensiones de un cuerpo cuando se incrementa su temperatura. Esto ocurre porque al aumentar la temperatura, las moléculas vibran con mayor intensidad, aumentando la distancia entre ellas.

## Dilatación Lineal

Cuando un sólido se calienta, su longitud aumenta proporcionalmente al cambio de temperatura. La expresión que describe este fenómeno es:

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T$$

La longitud final se obtiene como:

$$L_f = L_0 + \Delta L$$

$$L_f = L_0 + \alpha \cdot L_0 \cdot \Delta T$$

$$L_f = L_0 (1 + \alpha \cdot \Delta T)$$

Donde:
- $L_f$: longitud final
- $L_0$: longitud inicial
- $\Delta L$: cambio en la longitud ($L_f - L_0$)
- $\alpha$: coeficiente de expansión lineal del material
- $\Delta T$: cambio de temperatura

## Coeficientes de Expansión Lineal

| Material | $\alpha$ (×10⁻⁶ °C⁻¹) |
|:---|:---:|
| Hielo | 51 |
| Aluminio | 24 |
| Latón | 19 |
| Bronce | 18 |
| Cobre | 17 |
| Fierro (Hierro) | 12 |
| Hormigón | 12 |
| Acero | 11 |
| Vidrio ordinario | 9 |
| Vidrio Pyrex | 3.2 |

> Los valores son aproximados y pueden variar según la composición exacta del material.

## Ejemplo

Una regla de acero mide **50 cm** a una temperatura de **5 °C**. Si se calienta hasta **40 °C**, ¿cuál será su longitud final?

**Datos:**
- $L_0 = 50 \text{ cm}$
- $T_0 = 5 \text{ °C}$
- $T_f = 40 \text{ °C}$
- $\alpha_{\text{acero}} = 11 \times 10^{-6} \text{ °C}^{-1}$

**Desarrollo:**

Calculamos el cambio de temperatura:

$$\Delta T = T_f - T_0 = 40 - 5 = 35 \text{ °C}$$

Calculamos el cambio en la longitud:

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T$$

$$\Delta L = 11 \times 10^{-6} \cdot 50 \cdot 35$$

$$\Delta L = 0.01925 \text{ cm}$$

Calculamos la longitud final:

$$L_f = L_0 + \Delta L = 50 + 0.01925$$

$$\boxed{L_f = 50.01925 \text{ cm}}$$

## Corrección de medida con regla expandida

Si medimos un objeto usando la regla que ya se expandió (a 40 °C), la lectura que obtenemos ($L_{medida}$) no es la longitud real del objeto, porque cada marca de la regla ahora está más separada de lo que debería.

La longitud real del objeto es:

$$L_{real} = L_{medida} \cdot (1 + \alpha \cdot \Delta T)$$

Donde:
- $L_{real}$: longitud real del objeto
- $L_{medida}$: lectura obtenida con la regla expandida
- $\alpha$: coeficiente de expansión lineal de la regla
- $\Delta T$: diferencia de temperatura respecto a la temperatura de calibración

Ignorando el material del objeto y dejando $\Delta T$ expresado, la función queda:

$$f(L_{medida}) = L_{medida} \cdot (1 + \alpha \cdot \Delta T)$$

## Ejemplo 2: Esfera y placa con orificio

Considere una esfera de acero a **0 °C** la cual tiene un diámetro de **8,000 cm**. A su vez, una placa de aluminio con un agujero circular de **7,990 cm** de diámetro a la misma temperatura que la esfera.

Determine la mínima temperatura común para que la esfera pase a través del orificio.

**Datos:**
- $d_{s} = 8{,}000 \text{ cm}$ (diámetro de la esfera de acero)
- $d_{h} = 7{,}990 \text{ cm}$ (diámetro del agujero en aluminio)
- $T_0 = 0 \text{ °C}$
- $\alpha_{\text{acero}} = 1{,}2 \times 10^{-5} \text{ °C}^{-1}$
- $\alpha_{\text{aluminio}} = 2{,}4 \times 10^{-5} \text{ °C}^{-1}$

> **Nota:** El aluminio tiene un coeficiente de expansión mayor que el acero, por lo tanto al calentar ambos, el agujero crece más rápido que la esfera.

**Desarrollo:**

Al calentar, cada diámetro cambia según:

$$d_s(T) = d_{s} \cdot (1 + \alpha_{\text{acero}} \cdot \Delta T)$$

$$d_h(T) = d_{h} \cdot (1 + \alpha_{\text{aluminio}} \cdot \Delta T)$$

En la temperatura mínima, ambos diámetros son iguales: $d_s(T) = d_h(T)$

$$d_{s} \cdot (1 + \alpha_{\text{acero}} \cdot \Delta T) = d_{h} \cdot (1 + \alpha_{\text{aluminio}} \cdot \Delta T)$$

Expandiendo:

$$8{,}000 + 8{,}000 \cdot 1{,}2 \times 10^{-5} \cdot \Delta T = 7{,}990 + 7{,}990 \cdot 2{,}4 \times 10^{-5} \cdot \Delta T$$

$$8{,}000 + 9{,}600 \times 10^{-5} \cdot \Delta T = 7{,}990 + 19{,}176 \times 10^{-5} \cdot \Delta T$$

Agrupando:

$$8{,}000 - 7{,}990 = (19{,}176 - 9{,}600) \times 10^{-5} \cdot \Delta T$$

$$0{,}010 = 9{,}576 \times 10^{-5} \cdot \Delta T$$

> **Cuidado con las cifras significativas:** La diferencia $0{,}010$ tiene **2 cifras significativas**.

Despejando $\Delta T$:

$$\Delta T = \frac{0{,}010}{9{,}576 \times 10^{-5}} = \frac{1{,}0 \times 10^{-2}}{9{,}576 \times 10^{-5}}$$

$$\Delta T = 104{,}4 \text{ °C}$$

Como $T_0 = 0$ °C:

$$\boxed{T_{min} \approx 104 \text{ °C}}$$

**Verificación:**

- Esfera: $8{,}000 \times (1 + 1{,}2 \times 10^{-5} \times 104{,}4) = 8{,}000 \times 1{,}0012528 = 8{,}0100 \text{ cm}$
- Agujero: $7{,}990 \times (1 + 2{,}4 \times 10^{-5} \times 104{,}4) = 7{,}990 \times 1{,}0025056 = 8{,}0100 \text{ cm}$

Ambos diámetros coinciden en **8,0100 cm**, confirmando que a **104 °C** la esfera justo pasa por el orificio.

## Ejemplo 3: Cálculo de la subida del nivel del mar

El coeficiente de expansión **volumétrica** del agua de mar es $\beta = 2{,}1 \times 10^{-4} \text{ °C}^{-1}$.

Estima cuánto aumenta el nivel del mar si la columna de agua tiene una profundidad de **2 km** y la temperatura sube **2 °C**.

**Datos:**
- $L_0 = 2 \text{ km} = 2{,}000 \text{ m}$ (profundidad de la columna de agua)
- $\Delta T = 2 \text{ °C}$
- $\beta = 2{,}1 \times 10^{-4} \text{ °C}^{-1}$ (coeficiente volumétrico)

**Estrategia:** Para pasar del coeficiente volumétrico $\beta$ al lineal $\alpha$ se usa la relación:

$$\alpha \approx \frac{\beta}{3} = \frac{2{,}1 \times 10^{-4}}{3} = 0{,}7 \times 10^{-4} \text{ °C}^{-1}$$

**Desarrollo:**

$$\Delta L = \alpha \cdot L_0 \cdot \Delta T = \frac{\beta}{3} \cdot L_0 \cdot \Delta T$$

$$\Delta L = 0{,}7 \times 10^{-4} \cdot 2{,}000 \cdot 2$$

$$\boxed{\Delta L = 0{,}28 \text{ m} = 28 \text{ cm}}$$

> Este resultado ilustra el impacto del calentamiento global: un aumento de 2 °C en la temperatura del océano puede elevar el nivel del mar varios centímetros solo por expansión térmica, sin considerar el deshielo de glaciares.

---

## Dilatación Superficial

Suponga una plancha metálica rectangular de dimensiones $L_0$ y $H_0$, con área inicial $A_0 = L_0 H_0$, a temperatura $T_0$.

Si la temperatura se incrementa en $\Delta T$, el área final es:

$$A = L_0(1 + \alpha \Delta T) \cdot H_0(1 + \alpha \Delta T) = A_0(1 + \alpha \Delta T)^2$$

Despreciando el término $\alpha^2 \Delta T^2$ (muy pequeño):

$$\boxed{A \approx A_0(1 + 2\alpha \Delta T)}$$

> **¿Qué pasa con un agujero?** Si la plancha tiene un agujero circular, al calentarla el agujero **se agranda**. El material se expande uniformemente, incluyendo la frontera del agujero.

---

## Dilatación Volumétrica

Para volúmenes ($V \sim L^3$):

$$V = V_0(1 + \alpha \Delta T)^3 \approx V_0(1 + \beta \Delta T)$$

donde $\beta = 3\alpha$ es el coeficiente de expansión volumétrica.

### Coeficientes de expansión volumétrica de fluidos

| Material | $\beta$ (×10⁻⁴ K⁻¹) |
|:---|:---:|
| Agua | 2,1 |
| Mercurio | 1,8 |
| Bencina | 9,6 |

### Propiedad importante

Nótese que:

$$L = L_0(1 + \alpha \Delta T) \implies \frac{\Delta L}{L_0} = \alpha \Delta T$$

Ante similares condiciones, porcentualmente **todos los materiales se dilatan en la misma proporción**. El caso general (superficies y volúmenes) es similar.

---

## Ejercicio: Impacto del calentamiento global en el nivel del mar

Suponiendo que la profundidad media del océano es de $4 \; [\text{km}]$ y que la temperatura del agua de los océanos aumenta en $2\;°\text{C}$:

a) ¿En qué porcentaje varía el volumen del agua de mar debido a su dilatación?

b) ¿Cuánto sube el nivel medio del mar por este aumento de temperatura?

> Referencia: "Why do we keep talking about 1.5 °C and 2 °C above the pre-industrial era?" (Copernicus Climate Change Service, 2023).

---

## Anomalía del agua

En general, los líquidos disminuyen su volumen mientras se enfrían (en fase líquida). Sin embargo, el agua entre $0\;°\text{C}$ y $4\;°\text{C}$ presenta un **comportamiento anómalo**:

- Entre $4\;°\text{C}$ y $100\;°\text{C}$: el agua se comporta normalmente (se expande al calentar).
- Entre $0\;°\text{C}$ y $4\;°\text{C}$: el agua **se contrae** al calentar (la densidad **aumenta**).
- La **densidad máxima** del agua ocurre a $\approx 4\;°\text{C}$ ($\rho \approx 999{,}97 \; \text{kg/m}^3$).

Este fenómeno tiene consecuencias importantes:
- En invierno, el agua más fría ($< 4\;°\text{C}$) sube a la superficie del lago, donde se congela.
- El agua a $4\;°\text{C}$ (más densa) permanece en el fondo, permitiendo la supervivencia de los organismos acuáticos bajo el hielo.