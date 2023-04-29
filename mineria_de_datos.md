# Mineria de Datos
**Docente: Chavarry Chancay Mariana** 

## Clase 1  marzo 28, 2023

### Por qué Mineria de Datos

* Procesamiento para obtener datos utiles y obtener conocimiento
* Se apoya en: Estadistica, matematica, ciencias computacionales (algoritmos, bases de datos)
* Puede trabajar con datos estructurados y no estructurados
* datos estructurados:
    * bases de datos
* datos no estructurados:
    * redes sociales
    * informes meteorologicos
    * multimedia
* datos semiestructurados: 

### Introducción a la Mineria de Datos

#### Definición

* dato: simbolo, letra, valor
* mineria: extracción de minerales
* mineria de datos: disciplina de la informatica que estudia grandes cantidades de datos para obtener conocimiento

#### Historia

* data fishing: 
    * Analisis de grandes volumenes de datos para encontrar posibles relaciones entre datos para luego establecer hipotesis de por qué existen estas relaciones
    * Analisis de datos sin realizar preguntas de investigación
    * no necesariamente datos informaticos
* data mining: 
    * Analisis automatico de grandes volumenes de datos que permite encontrar patrones y generar predicciones
    * boom debido al internet
    * capacidad de computo y almacenamiento a costo razonable
    * grandes volumenes de datos (negocio / cientifico)

#### Tipos de datos 

El data mining establecce tipos de datos según lo que representan y la forma en que serán tratados a partir de estructurados

* Categorical (Categoricos)
    * Nominales (No tiene orden especifico) 
    * Ordinales (primero, segundo ...)
* Numerical (Numericos)
    * Discrete (Discretos)
    * Continuous (Continuos)
* No convencionales
    * series temporales
    * documentos
    * datos espaciales
    * multimedia
    * datos proecedentes de la web 

#### Relación con otras areas

![](https://i.imgur.com/ljwDTqd.png)

#### Utilidad de la minería de datos

* Agrupamiento (por salario, num Hijos, gasto estimado)
* Clasificación (Por nivel de riesgo alto, medio, bajo)
* Asociación (Productos de la canasta basica)

#### Aplicaciones de la minería de datos

* Negocios
    * publicidad personalizada
* Banca y finanzas
    * predicción de valores bursatiles
* Compañias de seguros
    * Detección de fraudes
* Supermercados
    * Analisis de cesta de compras
    * Ubicación de productos
* Educación
    * Mejora del proceso de enseñanza/aprendizaje
* Medicina
    * Diagnostico de enfermedades
* otras ciencias
    * Predicción meteorologica
    * Estudio de patrones en genes
* Internet
    * Análisis del comportamiento de usuarios
    * Estudio del contenido y estructura de sitios web
    * Detección de spam

#### Resumen 
![](https://i.imgur.com/1HF5ECa.png)

#### Tarea 

Investiga sobre las tendencias de la minería de datos en la actualidad y hacia el futuro, luego elabora un mapa mental en donde se plasme lo investigado.

Puedes diseñar el mapa metal con alguna herramienta digital para elaborar diagramas en línea, exportas el archivo como imagen y lo envías como archivo PDF.

La presente tarea se considera como parte de la evaluación formativa de la asignatura.

El plazo para entregar la  presente tarea es hasta el domingo 02 abril  11:59pm.

## Clase 2  abril 4, 2023

### Proceso KDD (knowledge Discovery in Databases)

Es la extracción **automatizada** de conocimiento a partir de grandes volúmenes de datos. 

**El conocimiento es:**
* importante
* implicito
* nuevo
* útil

**Las fases del KDD son:**
* Recopilación de datos
* Selección, limpieza y transformación de datos
* data Mining
* interpretación y evaluación de modelos

![](https://i.imgur.com/YYGRvYI.png)
---
![](https://i.imgur.com/BuO99YC.png)

#### Recopilación de datos

![](https://i.imgur.com/fWnDJ05.png)

El data warehouse también se puede usar para:
* generar reportes 
* sistemas de apoyo a la toma de decisiones 
* OLAP

#### Selección, limpieza y transformación de datos:
![](https://i.imgur.com/ciBhCw8.png)

* se da formato
* se reparan datos
* se seleccionan datos

#### Data Mining

![](https://i.imgur.com/14OceRt.png)

* Modelos predictivos
    * clasificación
    * regresión
* Modelos descriptivos
    * clústering
    * asociación

#### Interpretación y evaluación de modelos

* se interpreta pe :v 

### Metodología CRISP-DM

**Significado:** Cross-Industry Standard process for data mining
**Fecha Inicio:** septiembre 1996

* Objetivos
    * Aumentar inter operabilidad 
    * disminuir costos
* Ventajas
    * no-propietario
    * independiente de aplicación, industria o herramienta
    * Enfocado en problemas de negocio
    * Enfocado en analisis técnico
    * Plataforma guía
    * Experiencia base
    * Plantillas para análisis
* Proceso
    * Comprensión del problema
    * Comprensión de los datos
    * Preparación de los datos
    * Modelación
    * Evaluación de los resultados
    * Despliegue de los resultados
---
![](https://i.imgur.com/OBLgA18.png)
---
![](https://i.imgur.com/1oXjWi6.png)
---

### Metodología SEMMA



## Clase 3  abril 11, 2023

---
![](https://i.imgur.com/R3IQYLF.png)
---

#### Comprensión del Problema 

  * Variables independientes
    * el problema 
    * nombres:
      * features
      * drivers 
      * covariables 
  * Variables dependientes 
    * el negocio
    * nombres: 
      * label
      * target
      * Objetivo de estudio 
  * Conjuntos de Datos:
    * Total
    * contiene las Variables dependientes e independientes
    
    Esquema de 4 niveles de CRISP-DM 

    ---
    ![](https://i.imgur.com/WrCVTZv.png)
    ---
    ![](https://i.imgur.com/JLST2U1.png)
    ---

## Clase 4 - 04/18/2023

### Comprensión de Datos




### Preparación de los datos: 


## Clase 5 - 04/25/2023

### Modelado 

**tareas generales** 
  * seleccionar técnica de modelado 
    * **algoritmos**
      * a ser implementados (de acuerdo al metodo)
      * Ejemplos
        * arbol de clasificación
        * cvm 
        * red neuronal
        * r. lineal simple/compuesta/logistica
    * **Metodos**
      * Supervisados
        * Tiene variable dependiente (target, de estudio, salida)
          * si compra 
          * no compra 
        * Tiene variables independientes (features, drivers, entrada)
          * genero
          * rango de edad 
          * ingresos 
          * estado civil 
      * No supervisados
        * no tiene variable dependiente
        * **el fin no se conoce, se descubre**

  * generar el plan  de pruebas
  * construir el modelo
  * evaluar el modelo
    * verificar la precisión del modelo
 




 








