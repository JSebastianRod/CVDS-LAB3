# **CVDS-LAB3**
## Escuela Colombiana de Ingenieria Julio Garavito
### *Ingeniería de sistemas*

### *Integrantes*
Juan Pablo Daza Pinzon / Juan Sebastian Rodriguez Peña

## Ejercicio "Descuento de tarifas":

1. La excepcion: ExcepcionParametrosInvalidos debe ser arrojada cuando la variable "edad" este entre 18 y 65 o cuando esta sea negativa o nula.
Tambien es necesario cuando la variable diasAntelacion es menor a 21, sea negativa o nula.

2. 
| Numero | Clase de equivalencia                          | Resultado Correcto / Incorrecto      | 
| -------| ---------------------------------------------- |--------------------------------------|
|    17  |  Caso valido menor de edad                     | Correcto                             |
|    -2  |  Caso invalido edad negativa                   | Incorrecto                           |
|    35  |  Caso invalido entre las edades de descuento   | Incorrecto                           |
|    88  |  Caso valido perosna de la tercera edad        | Correcto                             |

3. 
**Caso valido menor de edad**:
calculoTarifa(tarifaBase, 

4. 
| Numero | Clase de equivalencia | Resultado Correcto / Incorrecto      | 
| -------| --------------------- |--------------------------------------|
|    17  |  x: x < 18 ^ x > -1   | Correcto                             |
|    -2  |  x: x =< -1           | Incorrecto                           |
|    35  |  x: x < 65 ^ x > 17   | Incorrecto                           |
|    88  |  x: x > 65            | Correcto                             |

5.
