# Calorimetría

## Conceptos fundamentales — No olvidar ni confundir

### Temperatura

Propiedad **intrínseca** de los cuerpos — ¡los cuerpos tienen temperatura! Se mide en:
- **Kelvin** → K
- **Celsius** → °C
- **Fahrenheit** → °F

$$T_F = \frac{9}{5}T_C + 32 \qquad ; \qquad T_K = T_C + 273{,}15 \qquad ; \qquad \Delta T_K = \Delta T_C$$

### Calor

**Energía en tránsito.** Al ser energía, sus unidades de medida son:
- **Joule** → J
- **Caloría** → cal
- **British Thermal Unit** → BTU

$$1 \; [\text{cal}] = 4{,}184 \; [\text{J}] \approx 4{,}2 \; [\text{J}] \qquad ; \qquad 1 \; [\text{BTU}] = 1055{,}06 \; [\text{J}]$$

---

## Definiciones

### Capacidad calorífica

Energía necesaria (calor) para incrementar la temperatura en $1\;°\text{C}$:

$$C = \frac{Q}{\Delta T}$$

Dado que el calor transferido depende de la cantidad de materia involucrada (variable extensiva), lo normalizamos por unidad de sustancia (variable intensiva):

### Calor específico por unidad de masa

$$c = \frac{C}{m} = \frac{Q}{m\Delta T} \implies Q = cm\Delta T$$

### Calor específico molar (útil en gases)

$$c = \frac{C}{n\mathcal{M}} = \frac{Q}{n\mathcal{M}\Delta T} \implies Q = nc_V \Delta T$$

donde $c_V$ representa el calor específico (molar) a volumen constante.

---

## Ejemplo: Temperatura de equilibrio

Considere dos trozos de material distinto, uno con capacidad calorífica $C_A$ y temperatura $T_A$, y el otro con capacidad calorífica $C_B$ y temperatura $T_B$. Ambos se ponen en contacto térmico. Determine una expresión para la temperatura final de equilibrio del sistema. Asuma que **no** se produce cambio de fase en el proceso.

Por conservación de energía, el calor cedido por el cuerpo más caliente es igual al calor absorbido por el más frío:

$$Q_{\text{cedido}} = Q_{\text{absorbido}}$$

$$C_A (T_A - T_f) = C_B (T_f - T_B)$$

Despejando $T_f$:

$$\boxed{T_f = \frac{C_A T_A + C_B T_B}{C_A + C_B}}$$

---

## Algunas definiciones

### Calor latente

El **calor latente** $L$ es la energía necesaria (por unidad de masa) para producir un cambio de fase a temperatura constante:

$$Q = L \cdot m$$

Donde:
- $Q$: calor absorbido o cedido (J)
- $L$: calor latente del material (J/kg)
- $m$: masa de la sustancia (kg)

> Nótese que en los cambios de fase la **temperatura no varía**.

### Calor sensible

El **calor sensible** es el calor que produce un cambio de temperatura **sin** cambio de fase:

$$Q = m \cdot c \cdot \Delta T$$

Donde:
- $m$: masa (kg)
- $c$: calor específico del material (J/kg·°C)
- $\Delta T = T_f - T_i$: cambio de temperatura (°C)

## Ejercicio: Potencia de la juguera

Teniendo 450 g de agua a 15 °C y 600 g de hielo a −15 °C, se mezclan en una juguera durante 120 segundos, dejando la mezcla a 5 °C. ¿Cuál es la potencia de la juguera?

### Datos

| Magnitud                        | Valor                             |
| ------------------------------- | --------------------------------- |
| $m_w = 0{,}450 \; \text{kg}$    | Masa de agua                      |
| $T_{w} = 15 \; °\text{C}$       | Temperatura inicial del agua      |
| $m_h = 0{,}600 \; \text{kg}$    | Masa de hielo                     |
| $T_{h} = -15 \; °\text{C}$      | Temperatura inicial del hielo     |
| $T_f = 5 \; °\text{C}$          | Temperatura final de la mezcla    |
| $t = 120 \; \text{s}$           | Tiempo de funcionamiento          |
| $c_w = 0,5 \; \text{J/(kg·°C)}$ | Calor específico del agua         |
| $c_h = 1 \; \text{J/(kg·°C)}$   | Calor específico del hielo        |
| $L_f = 334\,000 \; \text{J/kg}$ | Calor latente de fusión del hielo |

### Resolución

**1) Calor que necesita el hielo** (tres etapas):

Calentar hielo de −15 °C a 0 °C:

$$Q_1 = m_h \cdot c_h \cdot \Delta T = 0{,}6 \times 2090 \times 15 = 18\,810 \; \text{J}$$

Fundir el hielo a 0 °C:

$$Q_2 = m_h \cdot L_f = 0{,}6 \times 334\,000 = 200\,400 \; \text{J}$$

Calentar el agua resultante de 0 °C a 5 °C:

$$Q_3 = m_h \cdot c_w \cdot \Delta T = 0{,}6 \times 4186 \times 5 = 12\,558 \; \text{J}$$

$$Q_{\text{necesario}} = Q_1 + Q_2 + Q_3 = 18\,810 + 200\,400 + 12\,558 = 231\,768 \; \text{J}$$

**2) Calor cedido por el agua** al enfriarse de 15 °C a 5 °C:

$$Q_{\text{cedido}} = m_w \cdot c_w \cdot \Delta T = 0{,}45 \times 4186 \times 10 = 18\,837 \; \text{J}$$

**3) Trabajo de la juguera** (balance de energía):

$$W = Q_{\text{necesario}} - Q_{\text{cedido}} = 231\,768 - 18\,837 = 212\,931 \; \text{J}$$

**4) Potencia:**

$$\boxed{P = \frac{W}{t} = \frac{212\,931}{120} \approx 1\,774 \; \text{W} \approx 1{,}77 \; \text{kW}}$$

---

## Calores específicos y latentes del agua

| Propiedad (agua) | Calor específico $\left[\frac{\text{cal}}{\text{g·K}}\right]$ | Calor latente $\left[\frac{\text{cal}}{\text{g}}\right]$ |
|:---|:---:|:---:|
| Hielo (sólido) | 0,50 | — |
| Agua (líquida) | 1,00 | — |
| Vapor de agua (gas) | 0,47 | — |
| Fusión (hielo ↔ agua) | — | 80 |
| Vaporización (agua ↔ vapor) | — | 540 |

> $1 \; [\text{cal}] = 4{,}184 \; [\text{J}] \approx 4{,}2 \; [\text{J}]$

---

## Ejercicios adicionales

### Ejercicio 1: Hielo en agua

Considere un recipiente de paredes completamente aislantes, capacidad calorífica despreciable, y sellado. Contiene $900 \; [\text{cm}^3]$ de agua a $20\;°\text{C}$. Determine la cantidad de hielo (en gramos) que se debe añadir para que se funda completamente y la temperatura final sea $0\;°\text{C}$. El hielo se encuentra inicialmente a $-20\;°\text{C}$.

### Ejercicio 2: Mezcla de tres líquidos

Considere 3 líquidos diferentes $\ell_A$, $\ell_B$ y $\ell_C$, de masas iguales y temperaturas iniciales $12\;°\text{C}$, $18\;°\text{C}$ y $28\;°\text{C}$ respectivamente. Cuando se mezclan $\ell_A$ con $\ell_B$, la temperatura final es $16\;°\text{C}$. Cuando se mezclan $\ell_B$ con $\ell_C$, la temperatura final es $23\;°\text{C}$. Determine la temperatura final de la mezcla de $\ell_A$ con $\ell_C$.

### Ejercicio 3: Olla de cobre

Considere una olla de cobre de masa $m = 2 \; [\text{kg}]$ (incluida su tapa) a $T = 130\;°\text{C}$. Sobre ella se vierten $30 \; [\text{g}]$ de agua inicialmente a $10\;°\text{C}$ y se tapa herméticamente. Determine el **porcentaje de masa de agua que cambia de fase**.



