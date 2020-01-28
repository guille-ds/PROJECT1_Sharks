# PROJECT 1 - Manipulación de dataframes. Pandas. 

README in progress...
PROYECTO in progress...

Este proyecto pretende explorar y aprender mediante la práctica, métodos de manejo y modificación de los elementos (registros, columnas, series y datos) de un DataFrame.

- Se cuenta con un archivo .csv del que se extraen los datos.
- Su contenido es el registro de ataques de tiburón globalmente. 

### LECTURA Y CODIFICACIÓN DEL .CSV

- Tras un primer intento de lectura del archivo, añado el argumento encoding='latin-1' para que la lectura de los datos sea posible. Más tarde me daré cuenta que el encoding adecuado sería 'CP-1252'.

### LIMPIEZA DE REGISTROS Y COLUMNAS:

- Aparentemente, varios registros al final del dataframe tienen datos del tipo NaN, de modo que opto por eliminarlos. 
- Algunos de ellos, cuentan con algún dato en la columna 'Case Number' que no aporta ninguna información, así que los sustituyo por valores NaN y elimino dichos

