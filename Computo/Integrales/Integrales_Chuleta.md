# Inmediatas

$u = f(x)$
$a =$ Cualquier constante

## Funciones Base

| Funciones simples                   | Funciones compuestas                   |
| ----------------------------------- | -------------------------------------- |
| $\int a dx = ax$                    |                                        |
| $\int x^a dx = \frac{x^{a-1}}{a-1}$ | $\int u' u^a dx = \frac{u^{a-1}}{a-1}$ |
| $\int a^x dx = \frac{a^x}{ln(a)}$   | $\int u' a^u dx = \frac{a^u}{ln(a)}$   |
| $\int \frac{1}{x} dx = ln(x)$       | $\int \frac{u'}{u} dx= ln(u)$          |

## Trigonométricas

| Funciones simples                            | Funciones compuestas                          |
| -------------------------------------------- | --------------------------------------------- |
| $\int sen(x) dx = -cos(x)$                   | $\int u' sen(u) dx = -cos(u)$                 |
| $\int cos(x) dx = sen(x)$                    | $\int u' cos(u) dx = sin(u)$                  |
| $\int \frac{1}{cos^2(x)} dx = tg(x)$         | $\int \frac{u'}{cos^2(u)} dx = tg(u)$         |
| $\int \frac{1}{sen^2(x)} dx = -cotg(x)$      | $\int \frac{u'}{sen^2(u)} dx = -cotg(u)$      |
| $\int \frac{1}{\sqrt{1-x^2}} dx = arcsen(x)$ | $\int \frac{u'}{\sqrt{1-u^2}} dx = arcsen(u)$ |
| $\int \frac{1}{1+x^2} dx = arctg(x)$         | $\int \frac{u'}{1+u^2} dx = arctg(u)$         |

# Por partes
> Nemónico: 
> Solo Un Dia Vi Un Valiente Soldadito Vestido De Uniforme

$$
\int udv = uv - \int vdu
$$
O lo que es lo mismo
$$
\int uv' = uv - \int vu'
$$

# Cambio de Variable
Pasos ilustrados con ejemplo ([fuente](https://matesfacil.com/resueltos-integracion-por-sustitucion.htm))
$$\int \frac{ln(x)+1}{x \cdot ln(x)} dx$$
1. Se elige el termino a sustituir $z = ln(x)$ 
2. Se calcula dx y en caso necesario x. 
	- $x = e^z$
	- $dx = (e^z)' = e^z dz$
3. Se sustituye y simplifica
$$
\int \frac{z+1}{ e^z \cdot z} e^z dz \newline
$$$$
\int \frac{z+1}{ z} dz
$$
$$
\int 1 + \frac  {1}{ z} dz
$$

$$
\int 1 dz + \int \frac  {1}{ z} dz
$$
$$
z + ln(z) + C
$$

4. Deshacemos la sustitución
$$ln(x) + ln(ln(x)) + k$$