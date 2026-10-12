# Repo para EIEC - DevOps - UNIR

Este repositorio nos servirá para demostrar el uso de Git en la asignatura de EIEC y muchas cosas mas.

---

Los comandos del Makefile funcionarán en Linux y MacOS. En caso de usar Windows, necesitarás adaptarlos o ejecutarlos en una máquina virtual Linux.

## Ejecución

python3 main.py <filename> <dup>
  filename: **ruta** al fichero que contiene la lista de palabras, una por línea
  dup: **yes|no**, yes para eliminar palabras duplicadas, no para mantener la lista

## Ejecución de prueba

Lo corrí en Windows con Python, sin levantar Docker. En este punto el repositorio no trae `words.txt`, así que el script avisa y ordena la lista de ejemplo:

```
python main.py words.txt no
```

```
Se leerán las palabras del fichero words.txt
El fichero words.txt no existe
['gryffindor', 'hufflepuff', 'ravenclaw', 'slytherin']
```

El primer argumento es la ruta del fichero. El segundo es `yes` si hay que quitar duplicados, o `no` si se dejan tal cual.
