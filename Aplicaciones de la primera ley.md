# Aplicaciones de la Primera Ley de la Termodinámica

La Primera Ley de la Termodinámica establece la conservación de la energía en sistemas termodinámicos:

$$\Delta U = Q - W$$

Donde:
- $\Delta U$: variación de la energía interna del sistema (J)
- $Q$: calor absorbido por el sistema (J) — positivo si entra calor
- $W$: trabajo realizado **por** el sistema (J) — positivo si el sistema expande

---

## Procesos especiales

### Proceso isotérmico ($\Delta T = 0$)

La temperatura es constante, por lo tanto la energía interna no varía ($\Delta U = 0$):

$$Q = W$$

El trabajo realizado por un gas ideal a temperatura constante es:

$$W = nRT \ln\left(\frac{V_f}{V_i}\right)$$

### Proceso isocórico ($\Delta V = 0$, volumen constante)

No hay trabajo de expansión ($W = 0$):

$$\Delta U = Q$$

### Proceso isobárico ($\Delta P = 0$, presión constante)

El trabajo es $W = P \Delta V$, por lo tanto:

$$\Delta U = Q - P\Delta V$$

### Proceso adiabático ($Q = 0$)

No hay intercambio de calor con el entorno:

$$\Delta U = -W$$

---

## Calor específico

El calor necesario para cambiar la temperatura de una masa $m$ sin cambio de fase es:

$$Q = m \cdot c \cdot \Delta T$$

Donde $c$ es el **calor específico** del material (J/kg·°C).

### Tabla de calores específicos

| Material | $c$ (J/kg·°C) |
|:---|:---:|
| Agua | 4 186 |
| Hielo | 2 090 |
| Vapor de agua | 2 010 |
| Aluminio | 900 |
| Hierro | 450 |
| Cobre | 387 |
| Plomo | 128 |

---

## Ejemplo: mezcla de dos cuerpos

Un bloque de hierro de $m_1 = 0{,}5$ kg a $T_1 = 200$ °C se sumerge en $m_2 = 2$ kg de agua a $T_2 = 20$ °C. ¿Cuál es la temperatura final de equilibrio?

Aplicando conservación de energía ($Q_{\text{cedido}} = Q_{\text{absorbido}}$):

$$m_1 c_{\text{Fe}} (T_1 - T_f) = m_2 c_{\text{agua}} (T_f - T_2)$$

$$T_f = \frac{m_1 c_{\text{Fe}} T_1 + m_2 c_{\text{agua}} T_2}{m_1 c_{\text{Fe}} + m_2 c_{\text{agua}}}$$

$$T_f = \frac{0{,}5 \times 450 \times 200 + 2 \times 4186 \times 20}{0{,}5 \times 450 + 2 \times 4186}$$

$$T_f = \frac{45{,}000 + 167{,}440}{225 + 8{,}372} = \frac{212{,}440}{8{,}597}$$

$$\boxed{T_f \approx 24{,}7 \text{ °C}}$$
