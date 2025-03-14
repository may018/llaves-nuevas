# llaves-nuevas
Generación de Claves en Cifrado Simplificado
Este proyecto implementa un proceso de permutación y generación de claves basado en una clave binaria de 10 bits. El código está inspirado en métodos de cifrado como SDES (Simplified Data Encryption Standard), donde se generan claves derivadas a través de permutaciones y desplazamientos.

Descripción del Código
Definición de la clave inicial (k0)

Se parte de una clave de 10 bits definida en k0.
Permutación inicial (kp0)

Se reorganizan los bits de la clave original según un orden específico.
Generación de subconjuntos (LS1, LS2, LS3)

Se extraen y reorganizan partes de kp0 para futuras transformaciones.
Generación de claves (k1, kp1, k2)

Se crean claves derivadas a partir de k0, aplicando diferentes permutaciones.
Salida del programa

Se imprime LS3, una de las combinaciones de los bits de la clave.
