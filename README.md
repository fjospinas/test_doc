# Template discoveries 
Este template surge como una necesidad de estandarizar los entreganbles producidos por los procesos de discoveries. Este obedece mas al formato de la presentación ya que el contenido de cada sección se describe en [este documento](https://docs.google.com/document/d/1TgFzPLYT_qFdj7ggjiRgjtoAoNQH9LI-CQ9OSRLbCh0/edit?usp=sharing).

Adicional a esto, al final se añaden apendices con algunas ayudas relacionadas con markdown que han sido recurrentes en procesos de discoveries previos.

## Tabla de contenido

1. [ Glosario ](#glosario)
2. [ Caso de negocio ](#caso_negocio)
3. [ Formulación del problema](#formulacion)
4. [ Hipótesis ](#hipotesis)
5. [ Priorización de hipótesis](#priorizacion)
6. [ Validación de la hipótesis](#validacion_hipotests)
7. [ Conclusiones y propuestas](#conclusiones)
8. [ Referencias ](#referencias)
 
<a name="glosario"></a>
## 1. Glosario.

- **Item 1**: Definición de item 1.
- **Item 2**: Definición de item 1.

<a name="caso_negocio"></a>
## 2. Caso de negocio.

### 2.1. Contexto
### 2.2. Problema
### 2.3. Objetivo
#### 2.3.1 Objetivo principal
#### 2.3.2 Objetivos secundarios
### 2.4. Datos disponibles
### 2.5. Scope
<a name="formulacion"></a>
## 3. Formulación del problema
<a name="hipotesis"></a>
## 4. Hipótesis
<a name="priorizacion"></a>
## 5. Priorización de hipótesis
<a name="validacion_hipotests"></a>
## 6. Validación de la hipótesis
### 6.1. Preprocesamiento de datos
### 6.2. Análisis de datos
#### 6.2.1. Prueba modelo 1 (Iteración 0)
#### 6.2.2. Prueba modelo 2 (Iteración 1)
#### 6.2.1. Prueba modelo 3 (Iteración 2)
### 6.3. Entregable.
## 6.4. Visualización de outputs de los notebooks.
<a name="conclusiones"></a>
## 7. Conclusiones y propuestas
### 7.1. Conclusiones 
### 7.2. Propuestas
<a name="referencias"></a>
## 8. Referencias (Ejemplo)

- [Documentación del módulo de AutoScikitLearn](https://automl.github.io/auto-sklearn/master/)
- [Documentación del módulo de AutoPytorch](https://www.automl.org/automl/autopytorch/)
- [Principal Component Analysis, Second Edition](https://link.springer.com/book/10.1007/b98835)
- [Mutual Information between Discrete and Continuous Data Sets](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3929353/)
- [Documentación scalers ScikitLearn](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.preprocessing)
- [Documentacion del módulo impyute](https://impyute.readthedocs.io/en/master/)

## Apéndices.

A continuación se añaden algunas funcionalidades de markdown usadas previamente en otros discoveries.

### Apendice I. Creación de listas (Ejemplo)

Las variables se listan a continuación:

- Item 1
- Item 2
- Item 3
  - Item 3.1
  - Item 3.2

### Apendice II. Inserción y referenciación de imágenes.

Los pronosticos realizados con prophet conservan la estacionalidad observada en los datos de entrenamiento, tal como se observa en la Figura 1.

<p align="center">
  <img src="images/prophet.png" width=500>
</p>
<h5 align="center">Figura 1. Mejores modelos AdaBoost - Feature selection</h5>

### Apendice III. Inserción y referenciación de tablas.

En la Tabla 1 se pueden apreciar los resultados de las pruebas llevadas a cabo.

| Columna 1 | Columna 1 |
| --- | --- |
| Valor fila 1 columna 1 | Valor fila 1 columna 2 |
| Valor fila 2 columna 1 | Valor fila 2 columna 2 |
| Valor fila 3 columna 1 | Valor fila 3 columna 2 |
| Valor fila 4 columna 1 | Valor fila 4 columna 2 |

<h5 align="center"> Tabla 1. Resultados de pruebas</h5>

### Apendice IV. Inserción de ecuaciones de Latex.

La inserción de contenido de Latex en los markdown de github se toca en detalle en el siguiente gist.

A continuación se añade el ejemplo de una ecuación el Latex.

<img src="https://render.githubusercontent.com/render/math?math=\begin{equation}\sum_{n=0}^\infty\frac{1}{2^n}\end{equation}">

### Apendice V. Inserción de enlaces.

Ejemplo de enlace a [Mercadolibre Colombia](https://www.mercadolibre.com.co/)

### Apendice VI. Documentación oficial de markdown de github.

[Documentación de syntaxis para markdown proporcionada por Github](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
