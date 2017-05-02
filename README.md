Codigo: 1122073
Descripcion Repositorio:

Archivo  mpiEx2a.c
Este archivo verifica los tipos de procesos que se ejecutan, el proceso con identificador 0 (rank == 0) 
es el proceso Maestro, si se da esta condicion el mensaje debe ser:
Yo soy el maestro y existen N procesos corriendo

En los otros procesos Yo soy un proceso con identificador M(rank) de N(size) procesos en ejecucion.
Donde, N es el total de procesos en ejecucion y M es el identificador del proceso.

este program se ejecuta con 2, 4 y 8; procesos.



***********************************************************************************************************

Archivo mpiEx2b.c

Este archivo el maestro(rank) imprime el numero total de procesos(size) en ejecucion.

Ejecute este programa con 2, 4 y 8 procesos.

***********************************************************************************************************

Archivo mpiEx3a.c

Este archivo es un programa de MPI que tiene 6 procesos y se llaman en orden asi: El proceso 0 debe recibir
el valor de 5, el proceso 1 debe recibir el valor de 0 y asi sucesivamente.
en lugar de intercambiar caracteres, se intercambien enteros.



