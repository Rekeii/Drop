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
## **Problems** 

## Heat
Refers to the transfer of thermal energyfrom a body of high temperature to a body of low temperature.

Units of temperature:

Sensible Heat..

$$Q \> = \> m \, c \, \Delta t \notag$$
## **Problems:**


> [!example]
> A temperature control system is operated by the expansion of a zinc rod which is 200mm long at 15°C. If the system is set so that the source of heat supply is cut off when the rod has expanded to 200.20 mm, determine the temperature to which the system is limited. Assume the coefficient of linear expansion of zinc to be $31 \times 10^{-6} \frac{1}{K}$
