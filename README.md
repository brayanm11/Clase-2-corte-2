# Sistemas Mecánicos
Los sistemas mecánicos son fundamentales en la ingeniería, ya que permiten analizar y diseñar mecanismos utilizados en diversas industrias. Estos sistemas pueden modelarse mediante ecuaciones diferenciales, las cuales describen su comportamiento dinámico en función de las fuerzas aplicadas y sus propiedades físicas. En esta clase, exploraremos la modelación de sistemas mecánicos, los elementos que los componen y su análisis mediante métodos matemáticos.
## 1.  Conceptos Fundamentales
🔑 Sistema mecánico:

Conjunto de elementos físicos interconectados que transmiten movimiento y fuerza.

🔑 Ecuación diferencial:

Expresión matemática que describe la relación entre una función y sus derivadas.

🔑 Grado de libertad (DOF):

Número mínimo de coordenadas independientes necesarias para describir el movimiento de un sistema.

🔑 Sistema masa-resorte-amortiguador:

Modelo físico que describe la oscilación de un sistema mecánico compuesto por una masa, un resorte y un amortiguador.

## 2. Modelado de Sistemas Mecánicos
El modelado matemático de un sistema mecánico se basa en las leyes de Newton y en los principios de la dinámica. En general, estos sistemas están compuestos por:

Masa $(m)$: Representa la inercia del sistema.

Resorte $(k)$: Modela la elasticidad del sistema según la Ley de Hooke.

Amortiguador $(b)$: Simula la fricción y disipación de energía.

2.1. Ecuación del Sistema Masa-Resorte-Amortiguador

Para un sistema compuesto por una masa, un resorte y un amortiguador, la ecuación diferencial se expresa como:

$$m\frac{d^{2}x}{dt^{2}}+b\frac{dx}{dt}+kx=F(t)$$

Donde:

$x$ es el desplazamiento,

$m$ es la masa,

$b$ es el coeficiente de amortiguamiento,

$k$ es la constante del resorte,

$F(t)$ es la fuerza aplicada.

2.2. Tipos de Sistemas Mecánicos

-Existen distintos tipos de sistemas mecánicos según sus características dinámicas:

-Sistemas sin amortiguamiento: Movimiento oscilatorio sin disipación de energía.

-Sistemas subamortiguados: Oscilaciones con disipación progresiva de energía.

-Sistemas críticamente amortiguados: Retorno a la posición de equilibrio sin oscilaciones.

-Sistemas sobreamortiguados: Movimiento hacia el equilibrio sin oscilaciones, pero más lento que en el caso crítico.

## 3. Subsecciones
Las subsecciones pueden utilizarse para sub dividir ciertos temas que se tienen en clases, por ejemplo si se está trabajandolos conversores D/A, puede ser necesario subdividir este en circuito de resistencias ponderadas y circuito de escalera R2R. 
### 3.1. Título de subsecciones
Para la creación de estas subsecciones debe utilizar un tamaño de letra más pequeño, por lo tanto utilice la etiqueta '###' 
### 3.2. Numeración de subsecciones
Siga la numeración de la sección seguida de un punto y luego el número de la subsección.

## 4. Ejemplos
Si en algún caso pretende dar un ejemplo explicativo ya sea a través de texto o através de ecuaciones matemáticos, utilizar la palabra 'Ejemplo' seguido de una numeración consecutiva dentro de la clase. Utilice el emoji 💡 antecediendo la palabra.

## 5. Ecuaciones
Para la edición de ecuaciones debe utilizar la etiqueta '$$' al comienzo y final de la ecuación para que la ecuación quede centrada ocupando una línea. Si se quiere que la ecuación quede integrada en el texto debe utilizar la etiqueta '$' al comienzo y final de la ecuación. Las ecuaciones pueden ser editadas utilizando el código LATEX, en el siguiente enlace encuentran un editor de ecuaciones que les genera el código. http://www.alciro.org/tools/matematicas/editor-ecuaciones.jsp . Sin embargo hay muchas otras herramientas que pueden utilizar para esto.

💡**Ejemplo 1:** si se va a representar la ecuación de la ley de Ohm se puede mostrar así $R=\frac{V}{I}$ o también,

$$R=\frac{V}{I}$$

## 6. Figuras
Todas las figuras que incluya deben ser generadas por ustedes, **no utilizar las figuras de las presentaciones**. Para incluir figuras puede seguir los siguientes pasos:
* Primero escribimos ![]().
* Después escribimos, dentro de los corchetes, el texto alternativo. Este es opcional y solo entra en acción cuando no se puede cargar la imagen correctamente.
* Después escribimos, dentro de los paréntesis, la ubicación del archivo (ya sea una url o una ubicación dentro de algun folder local). Se recomienda poner las imágenes en una carpeta que se llame imágenes dentro del repositorio github para que no tengan problemas al cargar las imágenes.

💡**Ejemplo 2:**

![Figura de prueba](images/plantilla/Captura2.PNG)

Figura 1. Figura de prueba

Incluya la respectiva etiqueta a modo de descripción de la figura y mantenga numeración consecutiva para todas las figuras de la clase.

## 7. Tablas
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

💡**Ejemplo 3:** 

| **Resultado** | **x = número de intentos hasta primer éxito** |
|---------------|-----------------------------------------------|
|       S       |                       1                       |
|       FS      |                       2                       |
|      FFS      |                       3                       |
|      ...      |                      ...                      |
|    FFFFFFS    |                       7                       |
|      ...      |                      ...                      |

Tabla 1. Tabla de ejemplo

Cada tabla debe llevar la etiqueta que describa su contenido y numeración consecutiva para todas las tablas

## 8. Código
Teniendo en cuenta que el curso requiere del desarrollo de código matlab, c, c++ u otro. Si requiere incluir pequeños segmentos de código en los apuntes hágalos de la siguiente manera:

💡**Ejemplo 4:**
```
var sumar2 = function(numero) {
  return numero + 2;
}
```

## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## Rúbrica
| 0-1                                                                                   | 1-2                                                                                  | 2-3                                                                                                                                                                               | 3-4                                                                                                                                                                       | 4-5                                                                                                                                                                               |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Presenta menos del 10% de los temas o no presenta por  el medio y formato  solicitado | Presenta menos del 40% de los temas solicitados, y  cumple parcialmente la plantilla | Presenta menos del 60% de los temas solicitados (con descripciones, gráficos tablas, etc), y cumple  parcialmente la plantilla. No presenta la totalidad  de ejercicios resueltos | Presenta menos del 80% de los temas solicitados (con descripciones, gráficos, tablas, etc) y cumple con  la plantilla. No presenta  la totalidad de ejercicios  resueltos | Presenta el 100% de los temas vistos en clase (con descripciones, gráficos, tablas, etc), siguiendo totalmente la plantilla. presenta la  totalidad de los ejercicios solicitados |

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
