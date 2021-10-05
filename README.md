# Ejercicios 2.1
## Creación del juego del ahorcado
El juego del "ahorcado" es un juego de lápiz y papel, en el que el objetivo es adivinar una palabra. Luego el jugador restante deberán ir diciendo letras que les parece que puede contener la frase. Si aciertan, se escriben todas las letras coincidentes.  Si la letra no está, se resta un intento, agregando una parte al cuerpo (cabeza, brazo, etc.) hasta que queda dibujado todo el cuerpo del "ahorcado". 

Gana el juego si se completa la palabra, y se pierde si se completa el número de intentos antes de completar la palabra. 


En nuestra versión del ahorcado, no dibujaremos el cuerpo, sino que esta parte se simulará estableciendo un número de intentos, por ejemplo 5.

### ¿Qué vamos a necesitar?
Para poder generar las contraseñas necesitamos varias cosas:
- Un conjunto de caracteres a escoger para la contraseña
  (*investiga si hay alguna manera de obtener todos los caracteres sin
  escribirlos a mano*)
    + Todas las mayúsculas
    + Todas las minúsculas
    + Los caracteres numéricos: 0123456789
    + Los caracteres de puntuación: !"#$%&\'()*+,-./:;<=>?@[\\]^_`{|}~
      <BR>(No todos los sitios aceptan todo tipo de caracteres de puntuación)
- Una forma aleatoria de escoger esos caracteres (para una longitud dada)
    + Funciones del package kotlin.random (*investiga que clases/funciones tiene y cuáles nos pueden ser más útiles*)

### ¿Qué vamos a hacer?
- Dividirnos en grupos
- Pensar cómo habría que hacerlo
- ¿Tenemos todas las herramientas necesarias para conseguirlo?
- *NO es necesario programar la solución*, voy a poner una propuesta de solución para discutirla.


~~~ kt
...

~~~
