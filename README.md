# Introducción a R

Primera clase de introducción al lenguaje R: conceptos básicos,
comentarios, asignación de variables y operaciones fundamentales. Es el
punto de partida para estudiantes que nunca han programado.

## Contenido

- **Clase 1:** introducción a R: conceptos básicos, comentarios,
  asignación de variables y operaciones fundamentales.
- **Clase 2:** objetos y vectores: qué es un objeto, tipos de datos
  (numeric, character, logical), crear vectores con `c()`, `:` , `seq()`
  y `rep()`, consultar elementos por posición y por nombre, filtrar con
  vectores lógicos y operar con vectores, con las mediciones de OD680,
  temperatura y pH de un cultivo de *Chlorella vulgaris* durante 7 días.
  Incluye el archivo `datos_clase_02.csv` con las mediciones y un
  gráfico de la OD680 frente al día de cultivo.
- **Clase 3:** data frames: qué es un data frame, construirlo con
  `data.frame()`, explorarlo con `str()`, `head()`, `summary()` y
  `dim()`, consultar filas y columnas, filtrar con condiciones y con
  `subset()`, agregar columnas calculadas, resumir por grupos con
  `aggregate()` y ordenar con `order()`, y leer y escribir archivos CSV
  con `read.csv()` y `write.csv()`. Trabaja con las mediciones de pH,
  temperatura, turbidez, DQO y conductividad de 10 muestras de agua
  residual tomadas a la entrada y a la salida de un sistema de
  tratamiento durante 5 días. Incluye el archivo `datos_clase_03.csv`
  con las mediciones y un gráfico de la DQO frente a la turbidez.
- **Clase 4:** leer y escribir archivos: el directorio de trabajo con
  `getwd()` y `list.files()`, comprobar que un archivo existe con
  `file.exists()`, leer archivos CSV con `read.csv()`, escribir
  resultados con `write.csv()`, leer y escribir texto con `readLines()`
  y `writeLines()`, y guardar y cargar objetos de R con `saveRDS()` y
  `readRDS()`. Trabaja con la curva de calibración de un ensayo de
  Bradford (patrones de BSA de 0 a 400 µg/mL, absorbancia a 595 nm) y
  con cuatro muestras problema cuya concentración se calcula con la
  recta ajustada (pendiente 0.00252, R2 0.999). Incluye los archivos
  `datos_clase_04.csv` y `muestras_clase_04.csv` con las mediciones, el
  archivo `resultados_clase_04.csv` con las concentraciones calculadas y
  un gráfico de la curva de calibración.
- **Clase 5:** funciones: qué es una función con `function()`, valor de
  retorno con `return()`, funciones con varios argumentos, argumentos
  con valor por omisión, funciones que llaman a otras funciones,
  funciones que devuelven varios resultados en una lista, `mapply()` y
  `sapply()`, y el ámbito de las variables. Trabaja con soluciones
  preparadas en el laboratorio (molaridades de 0.0999 a 0.4000 mol/L),
  diluciones de NaCl 1.00 mol/L a 100 mL (concentraciones finales de
  0.05 a 0.30 mol/L, pendiente 0.01 mol/L por mL, R2 = 1) y tres
  réplicas de absorbancia a 595 nm de cuatro muestras de proteína.
  Incluye los archivos `datos_clase_05.csv`, `diluciones_clase_05.csv`
  y `replicas_clase_05.csv` con las mediciones y un gráfico de la
  concentración final frente al volumen de solución madre tomado.

## Cómo usarlo

Abre el archivo en R o RStudio y ejecútalo línea por línea, leyendo los
comentarios. Solo necesitas R instalado.

## Autor

**Dr. José Juan Torres Martínez**
Docente de Ciencias Químicas
Universidad Autónoma de San Luis Potosí (UASLP), México

Material académico para estudiantes.
