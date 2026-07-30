# Cuestionario Semana 02: Pandas basico

## Pregunta 1

Que objeto de Pandas representa una tabla con filas y columnas?

a. Array
b. DataFrame
c. Lista
d. Tupla

> solucion: B

## Pregunta 2

Que funcion se usa comunmente para leer un archivo CSV con Pandas?

a. `pd.read_csv()`
b. `pd.open_csv()`
c. `pd.load_table()`
d. `pd.import_csv()`

> solucion: A

## Pregunta 3

Que metodo permite ver las primeras filas de un DataFrame?

a. `.tail()`
b. `.info()`
c. `.head()`
d. `.shape()`

> solucion: C

## Pregunta 4

Que atributo entrega el numero de filas y columnas de un DataFrame?

a. `.columns`
b. `.shape`
c. `.index`
d. `.size_table`

> solucion: B

## Pregunta 5

Como se selecciona la columna `ventas` desde un DataFrame llamado `df`?

a. `df(ventas)`
b. `df[ventas]`
c. `df["ventas"]`
d. `df.select("ventas")`

> solucion: C

## Pregunta 6

Que metodo entrega un resumen de tipos de datos y valores no nulos?

a. `.describe()`
b. `.info()`
c. `.groupby()`
d. `.sort_values()`

> solucion: B

## Pregunta 7

Que metodo se utiliza para eliminar filas duplicadas?

a. `.drop_duplicates()`
b. `.remove_duplicates()`
c. `.delete_duplicates()`
d. `.unique_rows()`

> solucion: A

## Pregunta 8

Para filtrar filas donde `ventas` sea mayor que 100, cual opcion es correcta?

a. `df[df["ventas"] > 100]`
b. `df["ventas" > 100]`
c. `df.filter("ventas" > 100)`
d. `df.where ventas > 100`

> solucion: A

## Pregunta 9

Que metodo permite agrupar datos por una o mas columnas?

a. `.merge()`
b. `.concat()`
c. `.groupby()`
d. `.pivot()`

> solucion: C

## Pregunta 10

Que hace `df.sort_values("ventas", ascending=False)`?

a. Elimina la columna `ventas`
b. Ordena el DataFrame por `ventas` de mayor a menor
c. Agrupa el DataFrame por `ventas`
d. Convierte `ventas` a texto

> solucion: B
