---
tags:
  - PHY105
  - Lecture
aliases:
  - Thermal Physics
  - thermal physics
---

[[Learning Dashboard]] / [[Home]] / [[01 - Thermometry]]

# 01 - Thermometry

## Thermometry
a science that deals with the study, design and calibration of temperature measuring device called thermometers.

- **Degree (°)** - division in a temperature scale.

### Requirements in thermometers:
- **Thermometric property**
	- the property of the material that varies with temperature such as expansion of liquid, resistance of the substance, colors and radiation emitted, etc.
- **Standard Temperature**
	- **Lower Fixed Point**
		- refers to the temperature at which the solid and the liquid phase coexists
	- **Upper Fixed Point**
		- refers to the temperature at which the liquid and the vapor phase coexists.
### Temperature Scales
- Celsius Scale
- Fahrenheit Scale
- Absolute Temperature Scale
	- Kelvin Scale
	- Rankine Scale

Conversion between Temperature Scale:
$$

\begin{align}
t_c \, &= \, \frac{5}{9} \>\cdot \> (t_f - 32) \\ \notag \\
t_f \, &= \, (\frac{9}{5} \>\cdot \> t_c)\>+ \>32 \notag \\ \notag \\
t_k \, &= \,t_c \> + \> 273.15 \notag \\ \notag \\
t_r \, &= \, t_f \> + \> 460 \notag 

\end{align}

$$

## Problems on Temperature Scales:
### SW01 , August 19, 2024
These problems are to practice your temperature conversion skills. Here, we use a math concept called *linear transformation,* where we take advantage of the proportional relationship present between both different temperature scales to convert temperatures from one scale to another. The typical formula that we will use would be:

$$\frac{T_{1}-T_{freeze}}{T_{boil} - T_{freeze}} = \frac{T_{2}-T_{freeze}}{T_{boil} - T_{freeze}}$$

Where $T_{1}  \>\text{and} \> T_2$ are equivalent temperatures however in different temperature scales. Either may be the unknown so long as they are equivalent. The following problems will showcase their relationship and how to utilize the formula.


> [!info] Info
> The numerator is ordered by this:  $T_{greater}- T_{smaller}$ wherein the larger temperature is first before the other number. The numerator may also utilize the boiling point instead of the freezing point: $T_{1}- T_{boil}$


> [!example]
> On the X temperature scale, the freezing point of water is -22°X and the boiling point in 109°X.  The highest heat index forecast today (May 22, 2024) is 43°C. What is its equivalent in the X temperature scale?
> 
> Round off your answer to the nearest whole number. Input only the number.

**ANSWER:  34 °X**
*Soln.*
$$
\begin{align}

    \frac{(109 °X - x)}{(109 °X - (-22 °X))} &= \frac{(100 °C - 43 °C)}{(100 °C -  0 °C)}\notag \\\notag\\
\clap{OR} \notag\\
\frac{(x - (-22 °X))}{(109 °X - (-22 °X))} &= \frac{(43 °C - 0 °C)}{(100 °C -  0 °C)} \notag\\\notag\\
\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x &= 34.33°X \notag\\
&\approx 34°X \notag\\\notag\\\notag\\

\clap{Algebraically:} \notag \\\notag\\ \notag

\frac{(109 °X - x)}{(109 °X - (-22 °X))} &= \frac{(100 °C - 43 °C)}{(100 °C -  0 °C)} \tag{1}\\\notag\\\notag\\
\clap{Simplify:} \notag\\\notag\\
\frac{(109 °X - x)}{(109 °X + 22 °X)} &= \frac{(100 °C - 43 °C)}{(100 °C -  0 °C)} \tag{2}\\\notag\\
\frac{109 °X - x}{131 °X} &= \frac{100 °C - 43 °C}{100 °C} \tag{3}\\\notag\\\notag\\
\clap{Cross multiply:} \notag\\\notag\\
(109°X - x) \times 100 °C &= 131 °X \times 57°C\tag{4}\\
(10900°CX) - 100°C \times x &= 7467°CX\tag{5}\\
10900°CX - 7467°CX &= 100°C \times x \tag{6}\\
3433°CX  &= 100°C \times x \tag{7}\\
x &= \frac{3433\cancel{°C}X}{100\cancel{°C}}\tag{8}\\
x &= 34.33°X \notag\\
&\approx 34°X \notag\\\notag\\
\clap{equivalent to SHIFT+SOLVE value:}\notag\\\notag\\
34°X &= 34°X \quad \text{✔} \notag\\\notag\\
\end{align}

$$

> [!example]
> Betong devises a customized temperature scale that assigns a temperature reading of 14 to the normal melting point of gold (1063°C) and a temperature reading of 222 to its boiling point (2808°C). What temperature on the Betong scale corresponds to absolute zero of temperature? 
> 
> Absolute zero in Celsius scale is -273°C. Round off your answer to the nearest whole number. Input only the number.

**ANSWER:  145 °B** *(Find absolute zero in Betong (°B) Scale)*

$$ 
\begin{align}

\frac{14 °B - x}{222 °B - 14 °B}&= \frac{1063° C - (-273 °C)}{2808 °C - 1063 °C}\notag\\\notag\\
\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x &= -145.25°X \notag\\
&\approx 145°X \notag\\\notag\\\notag\\

\end{align}
$$

> [!example]
> Betong devises a customized temperature scale that assigns a temperature reading of 16 to the normal melting point of gold (1063°C) and a temperature reading of 170 to its boiling point (2808°C). The Betong thermometer shows the temperature inside W312 is -37°B. What would this temperature be on the Celsius scale?
> 
> Round off your answer to the nearest whole number. Input only the number.

**ANSWER:  462 °C** *(Find the equivalent of °B in °C)*

$$ 
\begin{align}

\frac{16 °B - (-37 °B)}{170 °B - 16 °B}&= \frac{1063 °C - x}{2808 °C - 1063 °C} \notag\\\notag\\
\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x &= 462.44°C \notag\\
&\approx 462°C \notag\\\notag\\\notag\\

\end{align}
$$

> [!example]
> Space invaders land on earth. On the invaders' temperature scale, the ice point is at 52°I (I = invader), and the steam point is at 990°I. What temperature on the I scale corresponds to absolute zero of temperature? Absolute zero in Fahrenheit scale is -460°F. 
> 
> Round off your answer to the nearest whole number. Input only the number.

**ANSWER:  -2512 °I** *(Find absolute zero in Invader (°I) Scale)*

$$ 
\begin{align}

\frac{52 °I - x}{990 °I - 52 °I}&= \frac{32 °F - (-460 °F)}{212 °F - 32 °F} \notag\\\notag\\
\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x &= -2511.86 °I \notag\\
&\approx -2512 °I \notag\\\notag\\

\end{align}
$$

> [!info] Info
> **Remember!** Ice point = Freezing Point; Steam Point = Boiling Point

## **Thermal Expansion or Contraction**
A phenomenon where in the dimensions of the body change whenever there is a change in temperature (*driving force*).

The change in dimension of the body depends on the following:
- original dimension, $L, \>A, \> V\>$ (length, area, volume)
- change in temperature, $\Delta \, t$
- coefficient of expansion, $\alpha \> , \gamma \> ,\beta, \> \frac{1}{C}$
    - reflects the rate of change of a material's dimension when there is a temperature change. 

### **Linear Expansion**
the linear expansion or contraction is the change in length due to the change in temperature.
$$
\begin{align}
\Delta L \> &= \> \alpha \, L_o \,\Delta t \notag \\ 
L_f \> &= \> L_o\,(1 \, + \, \alpha \, \Delta t)
\end{align}
$$

### **Area Expansion**
the area expansion or contraction is the change in area due to the change in temperature.
$$
\begin{align}
\Delta A \> &= \> \gamma \, A_o \,\Delta t \notag \\ 
A_f \> &= \> A_o\,(1 \, + \, \gamma \, \Delta t)
\end{align}
$$

### **Volume Expansion**
the volume expansion or contraction is the change in volume due to the change in temperature.
$$
\begin{align}
\Delta V \> &= \> \beta \, V_o \,\Delta t \notag \\ 
V_f \> &= \> V_o\,(1 \, + \, \beta \, \Delta t)
\end{align}
$$
## **Problems:** 


> [!example]
> A temperature control system is operated by the expansion of a zinc rod which is 200mm long at 15°C. If the system is set so that the source of heat supply is cut off when the rod has expanded to 200.20 mm, determine the temperature to which the system is limited. Assume the coefficient of linear expansion of zinc to be $31 \times 10^{-6} \frac{1}{K}.$

**ANSWER:  462 °C** *(Find the temperature)*

$$ 
\begin{align}
L_f &= L_o \,(1 + \alpha \, \Delta t) \notag \\
200.20 \, \text{mm} & = 200 \, \text{m} \cdot \left(1 + \left(31 \times 10^{-6} \frac{1}{\text{K}}\right)(x-15°C)\right) \notag \\ \notag \\
\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x & = 47.26 \, °C \notag
\end{align}

$$

> [!example]
> The brass bar and aluminum bar in the drawing are attached to an immovable wall. At $28°C$ the air gap between the rods is $1.3 \times 10^{-3}m.$ At what temperature will the gap be closed? 
> $\alpha_{ALUMINUM} = 23 \times 10^{-6} \frac{1}{C°} \>$ and $\> \alpha_{BRASS} = 19 \times 10^{-6} \frac{1}{C°}$

![[Screenshot 2024-08-24 123337.png]]
**ANSWER:  49.31 °C** *(Find the temperature)*

$$ 
\begin{align}
\clap{recall:} \notag \\
\Delta L \> &= \> \alpha \, L_o \,\Delta t \notag \\ 
\Delta L_{BRASS}\> + \> \Delta L_{ALUMINUM} &=  1.3 \times 10^{-3}m \notag \\
\alpha \, L_o \,\Delta t \, + \, \alpha \, L_o \,\Delta t &= 1.3 \times 10^{-3}m \notag \\ \notag

\end{align}
$$
$$
\begin{align}
\left[19 \times 10^{-6} \frac{1}{C°} \, \cdot \, 2m \, \cdot \, (x - 28°C) \right] \, + \, \left[3 \times 10^{-6} \frac{1}{C°} \, \cdot \,  1m \, \cdot \, (x - 28°C)\right] &= 1.3 \times 10^{-3}m \notag \\ \notag \\ \notag
\end{align}
$$
$$
\begin{align}
\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x = 49.31 \, °C \notag
\end{align}
$$


> [!example]
> A 10-m length bar with a crack at its center buckles up due to an increase of temperature of 30C°. If the coefficient of linear expansion of the bar is $30 \times 10^{-6} \frac{1}{C°}$, find the vertical displacement of the center.

**ANSWER:  0.2122 m** *(Find the vertical displacement from the center)*

$$
\begin{align}
L_f &= L_o \,(1 + \alpha \, \Delta t) \notag \\
L_{f} &= 5m \, \cdot \,(1 + 30 \times 10^{-6} \frac{1}{C°} \, \cdot \, 30C°) \notag \\
L_{f} &= 5.0045 \,m \\ \notag \\
\clap{Using Pythagorean Theorem:} \notag \\ \notag \\ 
\sqrt{(c^{2} - a^{2})} &= b \notag \\
b &= \sqrt{(5.0045m)^{2} \, - \, (5m)^{2}} \notag\\
b &= 0.2122\,m \notag \\

x &= 0.2122\,m \notag \\
&\approx \, 0.21\,m\notag

\end{align}
$$
## Heat
Refers to the transfer of thermal energy from a body of high temperature to a body of low temperature.

Units of temperature:

| JOULE | CALORIE | BTU (British Thermal Unit) |
| ----- | ------- | -------------------------- |
4.186 J = 1 cal


**Sensible Heat** - when transfer of energy is by virtue of the temperature difference.

$$
\begin{align}
Q \> = \> m \, c \, \Delta t \notag
\end{align}
$$
**Specific Heat Capacity**


$\frac{J}{kg\,-\,C°}$ OR  $\frac{cal}{g\,-\,C°}$


## **Problems:**

> [!example]
> In an effort to stay awake for an all night study session, a student makes a cup of coffee by first placing a 200-W electric immersion heater in 0.320 kg of water. How much time is required to raise its temperature from 20 °C to 80 °C? Assume that all of the heater’s power goes into heating the water.

**ANSWER:  401.86s** *(Find the time required to raise the temp from 20°C to 80°C)*
$$
\begin{aligned}

Q \, &= \, mc\Delta T \notag \\
Q \, &= \, 0.320kg \, \times \, 4186 \frac{J}{kg \, \cdot \, C\degree} \, \times \, (80\degree C \, - \, 20\degree C) \notag \\
Q \, &= \, 80371.25 \, J \notag \\ \notag \\ 
\clap{RECALL:} \notag \\ \notag \\
P &= \frac{Q}{t} \, ; \, t = \frac{Q}{P} \notag \\
t &= \frac{80371.25J}{200W}\notag \\
t &= 401.856 s \notag \\
t &\approx 401.86 s

\end{aligned}
$$


> [!example]
> A temperature control system is operated by the expansion of a zinc rod which is 200 mm long at 15°C. If the system is set so that the source of heat supply is cut off when the rod has expanded to 200.20 mm, determine the temperature to which the system is limited. Assume the coefficient of linear expansion of zinc to be $31 \times 10^{-6} \frac{1}{K}$.

**ANSWER:  47.26°C  *(Find the temperature where system is limited)**
$$

\begin{aligned}

L \, &= \, L_{o}\,(1 \,+ \, \alpha \Delta T) \notag \\
200.20mm \, &= \, 200mm \, \left(1 + \left(31 \times 10^{-6} \frac{1}{K}\right) \, \cdot \, (x - 15\degree C)\right) \notag \\ \notag \\

\clap{Using SHIFT+SOLVE in your calculator:}\notag \\\notag\\
x &= 47.26 \degree C \notag

\end{aligned}

$$

> [!example]
> A 14 grams aluminum beer contains 375 mL of beer. How much ice at 0°C will have to melt in order to cool 24 full cans from 25°C to 2°C? The specific heats of beer and aluminum are 4.0 and $0.88 \frac{kJ}{kg-C°}$, respectively, and the relative density of the beer is 0.985.

**ANSWER:  2.46 kg *(Find the mass of ice)**

$$

\begin{aligned}
\clap{Solving for Aluminum:} \notag \\ \notag \\
24 \, \times \, 0.014kg \, &= \, 0.336 kg \notag \\
Q \, &= \, mc\Delta T \notag \\
Q \, &= \, 0.336kg \, \times \, 0.88 \, \frac{kJ}{kg \, \cdot \, C\degree} \, \times \, 23 \degree C \notag \\ 
Q \, &= \, 6.80064 \, kJ \notag \\ \notag \\

\clap{Solving for the mass of Beer:} \notag \\ \notag \\
375 \, mL \, &= \, 0.375 \, L \notag \\
\left(0.905 \, \frac{kg}{\cancel{L}} \, \times \, 0.375 \, \cancel{L}\right) \, \times \, 24 \, &= \, 8.865 \, kg \notag \\ \notag \\

\clap{Solving for Beer:} \notag \\ \notag \\
 
Q \, &= \, mc\Delta T \notag \\
Q \, &= \, 8.865kg \, \times \, 4 \, \frac{kJ}{kg \, \cdot \, C\degree} \, \times \, 23 \degree C \notag \\ 
Q \, &= \, 815.58 \, kJ \notag \\ \notag \\

\clap{Solving for total kJ:} \notag \\ \notag \\

Q_{total} \, &= \, 815.58 \, kJ \, +  \, 6.80064 \, kJ \notag \\
Q_{total} \, &= \, 822.38064 \, kJ  \notag \\
Q_{total} \, &\approx \, 822.38 \, kJ \notag \\ \notag \\

\clap{Solving for mass of Ice:} \notag \\ \notag \\

Q \, &= \, mL_{f} \notag \\
m \, &= \, \frac{822.38064 \, kJ}{334 \frac{kJ}{kg}} \notag \\
m \, &= \, 2.46 \, kg \notag \\

\end{aligned}

$$

> [!example]
> An aluminum container of capacity 1500 mL is filled with 1490 mL of water at 20°C. The system is then heated slowly so that the water does not evaporate. At what temperature will the container be fully filled with water? αaluminum = $2.38 \times 10^{-5} \frac{1}{C°}$ and αwater = $2.10 \times 10^{-4} \frac{1}{C°}$

$$

$$

> [!example]
> Ice at −10°C and steam at 115°C are brought together in a perfectly insulated container. After thermal equilibrium is reached, the liquid phase at 50°C is present. Ignoring the container, find the ratio of the mass of steam to the mass of ice. The specific heat capacity of steam is $0.48 \frac{cal}/{(g·C°)}$ and the specific heat capacity of ice is $0.5 \frac{cal}{(g·C°)}$

> [!example]
> A substance has the following properties; Boiling Point = 120°C, Freezing Point = -20°C, specific heat as a gas, liquid and solid, $0.8 \frac{cal}{g-C°}$, $3 \frac{cal}{g-C°}$ and $2 cal/g-C°$, respectively. Heat of fusion = $200 \frac{cal}{g}$ and heat of vaporization = $800 \frac{cal}{g}$. How much heat must be added in changing 100g of this substance from -40°C to 180°C?

> [!example]
> A pot with a steel bottom 8.50 mm thick rests on a hot stove. The area of the bottom of the pot is $0.15 m^2$. The water inside the pot is at 100°C and 0.390 kg are evaporated every 3 min. Find the temperature of the lower surface of the pot which is in contact with the stove. Thermal conductivity of steel is $50.2 \, \frac{W}{m-K}$

> [!example]
> Three building materials, plasterboard ($k \, =\, 0.30 \frac{J}{(s-m-C°)}$), brick ($k \, = \,0.60 \frac{J}{(s-m-C°)}$), and wood ($k \, = \, 0.10 \frac{J}{(s-m-C°)}$), are sandwiched together. The temperatures at the inside and outside surfaces are 32°C and 0°C, respectively. Each material has the same thickness and cross-sectional area. Find the temperature (a) at the plaster-board-brick interface and (b) at the brick-wood interface. (b) How much heat is conducted in 8 hours?

