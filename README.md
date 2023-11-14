# laboratorio-openmp

El presente repositorio contiene la información necesaria para ejecutar dos algoritmos de multiplicación de matrices cuadradas y resultados obtenidos para cada uno de estos, ejecutados en dos máquinas con sistemas operativos diferentes y componentes diferentes. Este laboratorio fue ejecutado por el estudiante Pedro Escobar, como trabajo individual para la asignatura de Computación de Alto Desempeño, ofrecida por la Universidad Javeriana para la Maestría en Inteligencia Artificial.

### Directorio BIN

Contiene los archivos ejecutables compilados. Se recomienda ejecutar el Makefile para poder actualizarlos con los últimos cambios.

### Directorio Matmult

Contiene los archivos de código fuente, los encabezados creados para el laboratorio. En cada archivo se encuentra la implementación necesaria para realizar multiplicación de matrices en lenguaje C, utilizando la librería de OpenMP para la ejecución en paralelo con una cantidad de hilos determinada.

### Directorio TOOL

Contiene el archivo que lanza múltiples ejecuciones de los archivos ejecutables en secuencia, alternando los valores de hilos y el tamaño de la matriz. El lanzador ejecuta el mismo código n veces, con el fin de cumplir con el teorema del límite central, ejecutando como mínimo treinta veces el mismo código, para poder promediar los resultados, y tener una visualización mucho más precisa.

### Directorio Soluciones

Contiene un ejemplo de una solución obtenida al ejecutar el lanzador. Sólo sirve con fines de exploración. Para ver los resultados adecuados se recomienda la lectura del informe.

### Directorio utility

Contiene un archivo de Python con el cual se puede hacer tratamiento a los archivos ejecutables, finalizando en un archivo tipo csv que puede ser utilizado por programas tales como Microsoft Excel, RapidMiner, para la visualización de las estadísticas del rendimiento de los algoritmos.

Adicionalmente, en este directorio se almancenan los archivos csv de cada ejecución de las máquinas seleccionadas.

### Directorio informe

Contiene la versión más actualizada del informe del laboratorio. Fue elaborado en Latex utilizando la plataforma Overleaf
