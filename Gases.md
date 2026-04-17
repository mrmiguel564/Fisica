# Teoría Cinética de los Gases

## Acerca de los gases

### Presión

Definimos la **presión** como la magnitud de la componente perpendicular de la fuerza respecto al área de la superficie de contacto:

$$P = \frac{F_\perp}{A}$$

donde $F_\perp$ es la componente de fuerza normal a la superficie y $A$ el área de contacto. La presión es una cantidad **escalar**. En el SI se mide en Pascales $[\text{Pa}]$.

Equivalencias:

$$1 \; [\text{Pa}] = 1 \; \left[\frac{\text{N}}{\text{m}^2}\right] \qquad ; \qquad 1 \; [\text{atm}] = 101{,}325 \; [\text{kPa}] \qquad ; \qquad 1 \; [\text{bar}] = 100 \; [\text{kPa}]$$

---

## Antecedentes históricos — Leyes de los gases

### Ley de Boyle (1662)

Robert Boyle observó que, a **temperatura constante**, la presión de un gas es inversamente proporcional a su volumen. Mariotte (1676) llegó a la misma conclusión en Francia (Ley de Boyle-Mariotte).

$$PV = \text{cte.}$$

### Ley de Charles (1787)

Jacques Charles descubrió experimentalmente que, a **presión constante**, el volumen de un gas aumenta proporcionalmente con la temperatura. Sus resultados fueron difundidos por Gay-Lussac en 1802.

$$\frac{V}{T} = \text{cte.}$$

### Ley de Gay-Lussac (1808)

Joseph-Louis Gay-Lussac formuló que, a **volumen constante**, la presión de un gas es proporcional a la temperatura. Sus experimentos mostraron que las proyecciones de las rectas $P$ vs $T$ para distintos gases convergen a una temperatura común ($T_K = T_C + 273{,}15$).

$$\frac{P}{T} = \text{cte.}$$

### Ley de Avogadro (1811)

Amedeo Avogadro propuso que, bajo las mismas condiciones de presión y temperatura, volúmenes iguales de gases distintos contienen el mismo número de partículas.

$$\frac{V}{N} = \text{cte.}$$

Esta idea fue fundamental para el desarrollo del concepto de **mol** y de la constante de Avogadro:

$$N_A \approx 6{,}022 \times 10^{23} \; \left[\frac{1}{\text{mol}}\right] \qquad ; \qquad n = \frac{N}{N_A} \quad \text{(número de moles)}$$

> Un mol es la unidad con que se mide la cantidad de materia/sustancia, independiente de su composición. Es como contar "docenas" — ¡pero docenas más grandes!

---

## Masa molar

La **masa molar** es la masa de un mol de entidades elementales (átomos, moléculas) de una sustancia. Se expresa en $\left[\frac{\text{g}}{\text{mol}}\right]$ y constituye un vínculo directo entre la escala microscópica ($N_A$) y la escala macroscópica (masa medible en laboratorio).

| Elemento (Molécula estable) | Masa molar (g/mol) |
| :-------------------------: | :----------------: |
|        $\text{H}_2$         |         2          |
|         $\text{He}$         |         4          |
|        $\text{N}_2$         |         28         |
|        $\text{O}_2$         |         32         |
|         $\text{Ar}$         |         40         |
|        $\text{CO}_2$        |         44         |
|        $\text{Cl}_2$        |         71         |

> Para gases diatómicos ($\text{H}_2$, $\text{O}_2$, $\text{N}_2$, $\text{Cl}_2$) se considera su forma molecular estable. Los gases nobles ($\text{He}$, $\text{Ar}$) son monoatómicos.

---

## Ecuación de Estado del Gas Ideal

De las leyes anteriores se sintetiza:

$$PV \propto NT \implies PV = N k_B T$$

### Constante de Boltzmann

$$k_B \approx 1{,}38 \times 10^{-23} \; \left[\frac{\text{J}}{\text{K}}\right]$$

En términos de moles:

$$\boxed{PV = nRT}$$

### Constante universal de los gases

$$R = N_A \cdot k_B \approx 8{,}314 \; \left[\frac{\text{J}}{\text{mol·K}}\right] \approx 0{,}082 \; \left[\frac{\text{atm·L}}{\text{mol·K}}\right]$$

> Se usa $R = 8{,}314$ cuando $P$ está en Pa y $V$ en m³. Se usa $R = 0{,}082$ cuando $P$ está en atm y $V$ en L.

### Definiciones relevantes

- **Gas ideal:** Idealización de un gas real donde:
	- Se asume una baja densidad del gas.
	- Las partículas colisionan elásticamente entre sí siguiendo las leyes de Newton.
	- El tiempo de duración de las colisiones es despreciable.
	- En la práctica ¡es un gas diluido!

- **Variables de estado:** Variables macroscópicas que caracterizan un sistema termodinámico:
	- Presión, Volumen, Temperatura, Número de partículas o moles, etc.

- **Ecuación de estado:** Relación matemática entre las variables de estado que describen el sistema macroscópico.

---

## Ejercicios sobre gases

### Ejercicio 1: Masa y densidad de $1 \; [\text{m}^3]$ de aire

Estime la masa de aire contenido en $1 \; [\text{m}^3]$ de aire. ¿Cuál sería su densidad?

**Datos:**
- $V = 1 \; [\text{m}^3]$
- $T = 20\;°\text{C} = 293{,}15 \; [\text{K}]$ (temperatura ambiente típica)
- $P = 1 \; [\text{atm}] = 101\,325 \; [\text{Pa}]$
- Composición del aire:
	- $\text{N}_2$: $\approx 78{,}08\%$
	- $\text{O}_2$: $\approx 20{,}95\%$
	- $\text{Ar}$: $\approx 0{,}93\%$
	- $\text{CO}_2$: $\approx 0{,}035\%$
- Masa molar del aire:

$$\mathcal{M}_{\text{aire}} = 0{,}7808 \times 28 + 0{,}2095 \times 32 + 0{,}0093 \times 40 + 0{,}00035 \times 44$$

$$\mathcal{M}_{\text{aire}} = 21{,}862 + 6{,}704 + 0{,}372 + 0{,}0154 = 28{,}95 \; [\text{g/mol}]$$

**Desarrollo:**

De la ecuación de estado $PV = nRT$, obtenemos el número de moles:

$$n = \frac{PV}{RT} = \frac{101\,325 \times 1}{8{,}314 \times 293{,}15} = \frac{101\,325}{2437{,}4} \approx 41{,}6 \; [\text{mol}]$$

La masa total:

$$m = n \cdot \mathcal{M}_{\text{aire}} = 41{,}6 \times 28{,}95 \times 10^{-3} \approx 1{,}204 \; [\text{kg}]$$

La densidad:

$$\boxed{\rho = \frac{m}{V} \approx 1{,}20 \; \left[\frac{\text{kg}}{\text{m}^3}\right]}$$

---

### Ejercicio 2: Moléculas en una sala de clases

Estime el número de moléculas de Nitrógeno y Oxígeno en una sala de clases tradicional. ¿A cuántos moles equivalen?

**Datos:**
- Sala típica: $10 \times 8 \times 3 = 240 \; [\text{m}^3]$
- $T = 293 \; [\text{K}]$, $P = 101\,325 \; [\text{Pa}]$

**Desarrollo:**

Número total de moles en la sala:

$$n_{\text{total}} = \frac{PV}{RT} = \frac{101\,325 \times 240}{8{,}314 \times 293} = \frac{24\,318\,000}{2436} \approx 9\,982 \; [\text{mol}] \approx 10^{4} \; [\text{mol}]$$

Número total de moléculas:

$$N_{\text{total}} = n_{\text{total}} \times N_A = 9\,982 \times 6{,}022 \times 10^{23} \approx 6{,}01 \times 10^{27} \; \text{moléculas}$$

Distribuyendo por componente:

| Gas          | Fracción |      Moles       |            Moléculas            |
| :----------- | :------: | :--------------: | :-----------------------------: |
| $\text{N}_2$ |  $78\%$  | $\approx 7\,786$ | $\approx 4{,}69 \times 10^{27}$ |
| $\text{O}_2$ |  $21\%$  | $\approx 2\,096$ | $\approx 1{,}26 \times 10^{27}$ |

$$\boxed{N_{\text{total}} \approx 6 \times 10^{27} \; \text{moléculas} \quad ; \quad n_{\text{total}} \approx 10^4 \; \text{mol}}$$

---

### Ejercicio 3: Volumen molar a condiciones normales

¿Qué volumen ocupa $1 \; [\text{mol}]$ de un gas ideal a condiciones normales de presión y temperatura?

**Datos (CNPT):**
- $n = 1 \; [\text{mol}]$
- $T = 0\;°\text{C} = 273{,}15 \; [\text{K}]$
- $P = 1 \; [\text{atm}] = 101\,325 \; [\text{Pa}]$

**Desarrollo:**

$$V = \frac{nRT}{P} = \frac{1 \times 8{,}314 \times 273{,}15}{101\,325} = \frac{2271}{101\,325}$$

$$\boxed{V \approx 0{,}02241 \; [\text{m}^3] = 22{,}4 \; [\text{L}]}$$

> Este es un resultado clásico: **un mol de cualquier gas ideal a CNPT ocupa 22,4 litros**, independiente del tipo de gas.

---

### Ejercicio 4: Densidad de la atmósfera de Marte

La atmósfera de Marte es rica en $\text{CO}_2$. En su superficie la presión atmosférica es de $650 \; [\text{Pa}]$ y la temperatura media es de $-20\;°\text{C}$. Determine la densidad de la atmósfera cerca de la superficie.

**Datos:**
- $P = 650 \; [\text{Pa}]$
- $T = -20\;°\text{C} = 253{,}15 \; [\text{K}]$
- $R = 8{,}314 \; \left[\frac{\text{J}}{\text{mol·K}}\right]$
- $\mathcal{M}_{\text{CO}_2} = \underbrace{12}_{\text{1 Carbono}} + \underbrace{2 \times 16}_{\text{2 Oxígenos}} = 44 \; [\text{g/mol}] = 0{,}044 \; [\text{kg/mol}]$

**Desarrollo:**

De $PV = nRT$ y $n = \frac{m}{\mathcal{M}}$:

$$PV = \frac{m}{\mathcal{M}}RT \implies \frac{m}{V} = \rho = \frac{P\mathcal{M}}{RT}$$

$$\rho = \frac{650 \times 0{,}044}{8{,}314 \times 253{,}15} = \frac{28{,}6}{2104{,}7}$$

$$\boxed{\rho \approx 0{,}0136 \; \left[\frac{\text{kg}}{\text{m}^3}\right] \approx 13{,}6 \; \left[\frac{\text{g}}{\text{m}^3}\right]}$$

> Comparado con la densidad del aire terrestre ($\sim 1{,}2 \; \text{kg/m}^3$), la atmósfera marciana es unas **88 veces menos densa**.

---

### Ejercicio 5: Bulbos interconectados

Dos bulbos de vidrio idénticos están interconectados por un tubo delgado de volumen despreciable. Se llenan con el mismo gas ideal a $0\;°\text{C}$ y $1 \; [\text{atm}]$. Se coloca uno en un baño de agua con hielo, y el otro en un baño de vapor. La presión del gas en el segundo bulbo aumentó en un 50%.

Determine la temperatura de equilibrio del bulbo sumergido en el baño de vapor de agua (en °C).

> **Importante:** No asuma que la temperatura del vapor es $100\;°\text{C}$, pues no hay dos fases coexistiendo.

**Datos:**
- Volumen de cada bulbo: $V$ (idénticos)
- Estado inicial: $T_0 = 273{,}15 \; [\text{K}]$, $P_0 = 1 \; [\text{atm}]$ en ambos
- Bulbo frío: $T_1 = 0\;°\text{C} = 273{,}15 \; [\text{K}]$ (baño de hielo)
- La presión final del sistema: $P_f = 1{,}5 P_0 = 1{,}5 \; [\text{atm}]$
- Bulbo caliente: $T_2 = ?$

**Desarrollo:**

El número total de moles se conserva (sistema cerrado):

$$n_{\text{total}} = n_1^{(i)} + n_2^{(i)} = n_1^{(f)} + n_2^{(f)}$$

Inicialmente, cada bulbo tiene:

$$n_1^{(i)} = n_2^{(i)} = \frac{P_0 V}{R T_0}$$

$$n_{\text{total}} = \frac{2P_0 V}{R T_0}$$

En el estado final, la presión es uniforme ($P_f$) porque los bulbos están conectados:

$$n_1^{(f)} = \frac{P_f V}{R T_1} \qquad ; \qquad n_2^{(f)} = \frac{P_f V}{R T_2}$$

Igualando:

$$\frac{2P_0 V}{R T_0} = \frac{P_f V}{R T_1} + \frac{P_f V}{R T_2}$$

Simplificando $\frac{V}{R}$:

$$\frac{2P_0}{T_0} = P_f \left(\frac{1}{T_1} + \frac{1}{T_2}\right)$$

Sustituyendo $P_f = 1{,}5 P_0$ y $T_1 = T_0$:

$$\frac{2P_0}{T_0} = 1{,}5 P_0 \left(\frac{1}{T_0} + \frac{1}{T_2}\right)$$

$$\frac{2}{T_0} = 1{,}5 \left(\frac{1}{T_0} + \frac{1}{T_2}\right)$$

$$\frac{2}{1{,}5 \cdot T_0} = \frac{1}{T_0} + \frac{1}{T_2}$$

$$\frac{4}{3 T_0} - \frac{1}{T_0} = \frac{1}{T_2}$$

$$\frac{4 - 3}{3 T_0} = \frac{1}{T_2}$$

$$\frac{1}{3 T_0} = \frac{1}{T_2} \implies T_2 = 3T_0$$

$$T_2 = 3 \times 273{,}15 = 819{,}45 \; [\text{K}]$$

$$\boxed{T_2 \approx 546\;°\text{C}}$$

> Efectivamente $T_2 \neq 100\;°\text{C}$: el vapor en el baño está sobrecalentado, no hay dos fases coexistiendo.

---

## Teoría Cinética de los Gases

### Derivación de la presión desde colisiones moleculares

Usamos el hecho de que las partículas colisionan elásticamente entre sí y con las paredes siguiendo las leyes de Newton. Definimos la **concentración** del gas:

$$\frac{N}{V} = \int d^3v \; f(\vec{v})$$

donde $f(\vec{v})$ es la función de distribución de velocidades moleculares.

Para una sola colisión con la pared:

$$\Delta \vec{p}_1 = 2mv_x \;\hat{\imath}$$

El intercambio total de momentum es:

$$\Delta \vec{p}_{\text{total}} = m A \Delta t \int_{v_x > 0} d^3v \; v_x^2 \; f(\vec{v}) \;\hat{\imath}$$

De la segunda ley de Newton obtenemos la presión:

$$P = \frac{F_x}{A} = m \int_{v_x > 0} d^3v \; v_x^2 \; f(\vec{v})$$

Evaluando la integral:

$$\boxed{PV = Nm\overline{v_x^2}}$$

### Equipartición y energía cinética

Por simetría estadística: $\overline{v_x^2} = \overline{v_y^2} = \overline{v_z^2} = \frac{1}{3}\overline{v^2}$, así:

$$PV = \frac{1}{3}Nm\overline{v^2} = \frac{2}{3}N\langle E_k \rangle = \frac{2}{3}U$$

donde $\langle E_k \rangle = \frac{1}{2}m\overline{v^2}$ es la energía cinética promedio por partícula y $U$ la energía interna del gas.

Comparando con $PV = Nk_BT$:

$$\boxed{\langle E_k \rangle = \frac{3}{2}k_BT}$$

> La **temperatura** resulta ser una medida indirecta de la energía cinética promedio de las partículas del gas. La **presión** representa una medida indirecta del golpeteo de las partículas contra las paredes.

---

## Rapidez cuadrática media (RMS)

$$v_{rms} = \sqrt{\overline{v^2}}$$

Para un gas ideal:

- **Por partícula:** $v_{rms} = \sqrt{\dfrac{3k_BT}{m}}$

- **Por mol:** $v_{rms} = \sqrt{\dfrac{3RT}{\mathcal{M}_{\text{molar}}}}$

### Ejercicio 6: Auditorio

Considere un auditorio de volumen $V \approx 10^3 \; [\text{m}^3]$, a $T \approx 300 \; [\text{K}]$ y $P \approx 1 \; [\text{atm}]$. Estime:

**a) Rapidez cuadrática media de las moléculas de nitrógeno.**

**Datos:** $\mathcal{M}_{N_2} = 28 \; [\text{g/mol}] = 0{,}028 \; [\text{kg/mol}]$, $T = 300 \; [\text{K}]$

$$v_{rms} = \sqrt{\frac{3RT}{\mathcal{M}}} = \sqrt{\frac{3 \times 8{,}314 \times 300}{0{,}028}} = \sqrt{\frac{7\,483}{0{,}028}} = \sqrt{267\,250}$$

$$\boxed{v_{rms} \approx 517 \; \left[\frac{\text{m}}{\text{s}}\right]}$$

> ¡Las moléculas de $\text{N}_2$ se mueven a más de $500 \; \text{m/s}$ a temperatura ambiente! (Comparable a la velocidad del sonido en aire, $\sim 343 \; \text{m/s}$.)

**b) Flujo de colisiones moleculares sobre las paredes.**

Primero calculamos la concentración molecular:

$$\frac{N}{V} = \frac{P}{k_B T} = \frac{101\,325}{1{,}38 \times 10^{-23} \times 300} = \frac{101\,325}{4{,}14 \times 10^{-21}} \approx 2{,}45 \times 10^{25} \; \left[\frac{\text{moléculas}}{\text{m}^3}\right]$$

El flujo de colisiones por unidad de área se calcula como:

$$J = \frac{1}{4} \cdot \frac{N}{V} \cdot \langle v \rangle$$

donde $\langle v \rangle = \sqrt{\frac{8k_BT}{\pi m}}$ es la velocidad media. La masa de una molécula de $\text{N}_2$:

$$m = \frac{\mathcal{M}}{N_A} = \frac{0{,}028}{6{,}022 \times 10^{23}} = 4{,}65 \times 10^{-26} \; [\text{kg}]$$

$$\langle v \rangle = \sqrt{\frac{8 \times 1{,}38 \times 10^{-23} \times 300}{\pi \times 4{,}65 \times 10^{-26}}} = \sqrt{\frac{3{,}312 \times 10^{-20}}{1{,}461 \times 10^{-25}}} = \sqrt{2{,}267 \times 10^{5}} \approx 476 \; \left[\frac{\text{m}}{\text{s}}\right]$$

$$J = \frac{1}{4} \times 2{,}45 \times 10^{25} \times 476 = 2{,}92 \times 10^{27} \; \left[\frac{\text{colisiones}}{\text{m}^2 \cdot \text{s}}\right]$$

Convirtiendo a $\text{cm}^2$:

$$\boxed{J \approx 2{,}92 \times 10^{23} \; \left[\frac{\text{colisiones}}{\text{cm}^2 \cdot \text{s}}\right]}$$

**c) Separación promedio entre moléculas.**

Si cada molécula ocupa un volumen cúbico promedio $\ell^3$:

$$\ell = \left(\frac{V}{N}\right)^{1/3} = \left(\frac{1}{N/V}\right)^{1/3} = \left(\frac{1}{2{,}45 \times 10^{25}}\right)^{1/3}$$

$$\ell = (4{,}08 \times 10^{-26})^{1/3} \approx 3{,}44 \times 10^{-9} \; [\text{m}]$$

$$\boxed{\ell \approx 3{,}4 \; [\text{nm}]}$$

> La separación entre moléculas ($\sim 3{,}4 \; \text{nm}$) es mucho mayor que el tamaño de una molécula ($\sim 0{,}3 \; \text{nm}$), lo cual justifica la aproximación de gas ideal.

---

## Distribución de Maxwell-Boltzmann

La distribución de velocidades moleculares viene dada por:

$$f(v) = 4\pi \left(\frac{m}{2\pi k_B T}\right)^{3/2} v^2 \; e^{-mv^2 / 2k_BT}$$

A partir de esta distribución se obtienen tres velocidades características:

| Velocidad | Expresión | Descripción |
|:---|:---:|:---|
| Más probable (moda) | $v_{mp} = \sqrt{\dfrac{2k_BT}{m}}$ | Pico de la distribución |
| Media (promedio) | $\langle v \rangle = \sqrt{\dfrac{8k_BT}{\pi m}}$ | Valor esperado |
| Cuadrática media (RMS) | $v_{rms} = \sqrt{\dfrac{3k_BT}{m}}$ | Raíz del segundo momento |

> Se cumple siempre: $v_{mp} < \langle v \rangle < v_{rms}$

---

## Transformaciones de fase

### Presiones parciales (Ley de Dalton)

En una mezcla de gases ideales, la presión total es la suma de las presiones parciales de cada componente:

$$P_{\text{total}} = \sum P_{\text{parcial}}$$

Para el aire:

$$P_{\text{aire}} = P_{N_2} + P_{O_2} + P_{H_2O} + P_{CO_2} + \ldots$$

### Humedad relativa

La **humedad relativa** es la razón entre la presión de vapor de agua existente en la atmósfera y la presión de saturación en las mismas condiciones:

$$\text{Humedad Relativa} = \frac{\text{Presión del vapor}}{\text{Presión de saturación en curva PT}}$$

### Ejercicio 7 (continuación del auditorio): Humedad

d) Si la presión parcial de agua en la atmósfera de la sala es $0{,}015 \; [\text{atm}]$, determine la masa total de agua disuelta en el aire.

**Datos:** $V = 10^3 \; [\text{m}^3]$, $T = 300 \; [\text{K}]$, $P_{H_2O} = 0{,}015 \; [\text{atm}] = 1\,520 \; [\text{Pa}]$, $\mathcal{M}_{H_2O} = 18 \; [\text{g/mol}]$

**Desarrollo:**

Usando la ecuación de estado con la presión parcial del vapor de agua:

$$n_{H_2O} = \frac{P_{H_2O} \cdot V}{RT} = \frac{1\,520 \times 10^3}{8{,}314 \times 300} = \frac{1{,}52 \times 10^{6}}{2\,494} \approx 609{,}5 \; [\text{mol}]$$

$$m_{H_2O} = n_{H_2O} \times \mathcal{M}_{H_2O} = 609{,}5 \times 18 = 10\,971 \; [\text{g}]$$

$$\boxed{m_{H_2O} \approx 11{,}0 \; [\text{kg}]}$$

> ¡Hay aproximadamente 11 kg de agua disuelta en el aire del auditorio!

---

e) La presión de vapor del agua a $20\;°\text{C}$ es $0{,}023 \; [\text{atm}]$. ¿Cuántos kilos adicionales de agua se pueden disolver en la atmósfera sin que comience a condensar?

**Desarrollo:**

La presión parcial adicional de agua que cabe antes de saturar:

$$\Delta P = P_{\text{sat}} - P_{H_2O} = 0{,}023 - 0{,}015 = 0{,}008 \; [\text{atm}] = 810{,}6 \; [\text{Pa}]$$

$$n_{\text{adicional}} = \frac{\Delta P \cdot V}{RT} = \frac{810{,}6 \times 10^3}{8{,}314 \times 300} = \frac{810\,600}{2\,494} \approx 325 \; [\text{mol}]$$

$$m_{\text{adicional}} = 325 \times 18 = 5\,850 \; [\text{g}]$$

$$\boxed{m_{\text{adicional}} \approx 5{,}9 \; [\text{kg}]}$$

La humedad relativa actual de la sala es:

$$HR = \frac{0{,}015}{0{,}023} \times 100\% \approx 65\%$$

---

## Apéndice: Momentos de una distribución

En la Teoría de Probabilidades, los **momentos** de una distribución se definen como:

$$\mathbb{E}[x^n] = \sum_x x^n f(x) \qquad ; \qquad \mathbb{E}[x^n] = \int_{-\infty}^{+\infty} dx \; x^n f(x)$$

| Momento | Significado | Análogo en física |
|:---:|:---|:---|
| $n=1$ | Media (tendencia central) | Centro de masas |
| $n=2$ | Varianza (dispersión) | Momento de inercia |
| $n=3$ | Asimetría (sesgo) | — |
| $n=4$ | Curtosis (peso de las colas) | — |

Para la distribución de velocidades, el segundo momento da:

$$\overline{v^2} = \frac{\int d^3v \; v^2 f(\vec{v})}{\int d^3v \; f(\vec{v})} = \frac{V}{N} \int d^3v \; v^2 f(\vec{v})$$

