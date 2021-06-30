# Actividad 14
Paginacion Simple

# Requerimientos
1. El algoritmo de planificación a implementar es el de RR (Actividad 10).
2. Cumplir con todos los requerimientos del programa 5 (actividad 10).
3. De manera aleatoria se asignará, el tiempo, operación y tamaño de cada proceso (número
aleatorio entero entre 5 y 25).
4. El tamaño de la memoria será de 180.
5. Dividir la memoria en “Marcos” de Igual longitud (45 marcos de 4 cada uno).
6. El S.O. ocupará 3 marcos, quedando 42 disponibles para repartir entre los procesos.
7. Dividir los procesos en páginas (tamaño 4), es decir dividir los procesos de igual tamaño que
los marcos (4).
8. Teclas a utilizar:
<img src="https://cdn.discordapp.com/attachments/762088441314934794/859699714924216360/unknown.png" width="715" height="673">
9. Para que el proceso pueda estar en la cola de listos (en memoria), deberá existir espacio en
memoria, es decir, deben de existir los marcos libres necesarios para albergar el proceso.
10. Deberá mostrarse en pantalla: 
Centro Universitario de Ciencias Exactas e Ingenierías
M. en C. Violeta del Rocío Becerra Velázquez
a. La memoria dividida en “Marcos”, no olvidando contemplar el espacio que ocupa el
S. O., (se debe señalar el número de cada marco), mostrando en todo momento si
están ocupados o no, marcándolos en proporción. (Ver figura)
b. El número de procesos que están en la cola de nuevos
i. Del proceso que esta por ingresar a Listos, deberá mostrarse su ID y su
tamaño, para así visualizar cuantos marcos libres se necesitarán.
c. El proceso en ejecución mostrando todos sus datos.
d. El contador que representa el Quantum.
e. Listar los terminados, marcando los que tuvieron error
f. El contador global.
11. En la tabla de páginas, deberá observarse que página está en que marco, (es una entrada por
proceso). Además deberá mostrarse la relación de marcos libres.
12. El programa terminará cuando todos los procesos se hayan ejecutado
