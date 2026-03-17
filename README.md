# 🎮 Análisis de Ventas de Videojuegos

## 📊 Descripción del proyecto

Este proyecto analiza datos históricos de ventas de videojuegos para la tienda online **Ice**, que comercializa videojuegos a nivel mundial.  

Se cuenta con información abierta sobre:

- reseñas de usuarios y críticos
- géneros
- plataformas
- ventas regionales
- clasificación ESRB

El objetivo es **identificar patrones que determinen si un videojuego tiene éxito o no**, con el fin de detectar proyectos prometedores y planificar campañas publicitarias para el año **2017**.

---

## 🎯 Objetivo del proyecto

Analizar el comportamiento histórico del mercado de videojuegos para identificar:

- plataformas con mayor potencial comercial
- géneros más rentables
- impacto de las reseñas en las ventas
- diferencias entre mercados regionales
- patrones que ayuden a detectar videojuegos exitosos

---

## 📂 Dataset

El conjunto de datos incluye variables como:

- nombre del videojuego
- plataforma
- año de lanzamiento
- género
- ventas en Norteamérica, Europa y Japón
- puntuación de usuarios
- puntuación de críticos
- clasificación ESRB

La columna **rating** contiene la clasificación otorgada por la **ESRB (Entertainment Software Rating Board)**, que evalúa el contenido del videojuego y asigna categorías de edad como:

- **E** – Everyone  
- **T** – Teen  
- **M** – Mature  

---

## ⚙️ Metodología

El proyecto siguió un flujo típico de análisis de datos:

1. Carga y exploración inicial de datos  
2. Limpieza y preprocesamiento  
3. Análisis exploratorio de datos (**EDA**)  
4. Análisis de ventas por año y plataforma  
5. Evaluación de plataformas con potencial de crecimiento  
6. Análisis de correlación entre reseñas y ventas  
7. Comparación del desempeño por género  
8. Perfil regional de usuarios  
9. Pruebas de hipótesis estadísticas  

---

## 📈 Resultados principales

### 1. Tendencia de lanzamientos
Se observó que entre **2006 y 2011** se concentró la mayor cantidad de lanzamientos de videojuegos. Después de ese periodo, el número de juegos publicados disminuyó gradualmente.

### 2. Plataformas con mayor potencial
Para el análisis más reciente se trabajó con datos de **2013 a 2015**, ya que representan mejor el comportamiento del mercado moderno.  

Las plataformas con mayor potencial de crecimiento fueron:

- **PS4**
- **XOne**

Ambas mostraron una tendencia positiva en ventas, mientras que plataformas como:

- **PS3**
- **X360**

presentaron una clara disminución y fueron consideradas plataformas en declive.

### 3. Ventas por plataforma
Las plataformas con mayores ventas acumuladas en el periodo analizado fueron:

- **PS4** → 244.89
- **PS3** → 177.83
- **X360** → 135.28
- **XOne** → 133.17
- **3DS** → 128.11

### 4. Relación entre reseñas y ventas
En la plataforma **PS4** se encontró que:

- la correlación entre **user_score** y ventas fue de **0.024**
- la correlación entre **critic_score** y ventas fue de **0.432**

Esto indica que las reseñas de usuarios tienen una relación muy débil con las ventas, mientras que las reseñas de críticos muestran una relación moderada y parecen influir más en el desempeño comercial.

### 5. Géneros más rentables
Los géneros con mejores resultados de ventas fueron:

- **Action** → 291.76
- **Shooter** → 194.76
- **Role-Playing** → 127.71
- **Sports** → 127.16

Además, **Shooter** destacó por tener el promedio de ventas más alto por juego, lo que lo convierte en uno de los géneros más rentables del mercado.

### 6. Diferencias entre regiones

#### Norteamérica (NA)
- Plataformas líderes: **PS4, X360, XOne**
- Géneros más populares: **Action, Shooter, Sports**
- Clasificación dominante: **M**

#### Europa (EU)
- Plataformas líderes: **PS4, PS3, XOne**
- Géneros más populares: **Action, Shooter, Sports**
- Clasificación dominante: **M**

#### Japón (JP)
- Plataforma líder: **3DS**
- Género más popular: **Role-Playing**
- Las preferencias son distintas a NA y EU, con mayor peso de juegos portátiles y RPG

Estos resultados muestran que el mercado japonés tiene un comportamiento claramente diferente al de Norteamérica y Europa.

---

## 🧪 Pruebas de hipótesis

### Hipótesis 1
**Las calificaciones promedio de los usuarios son las mismas en Xbox One y PC.**

- **p-value = 0.2867**

Resultado:  
No se rechazó la hipótesis nula, por lo que **no hay evidencia suficiente para afirmar que las medias sean diferentes**.

### Hipótesis 2
**Las calificaciones promedio de los usuarios para los géneros Action y Sports son diferentes.**

- **p-value = 3.51e-19**

Resultado:  
Se rechazó la hipótesis nula, por lo que **sí existen diferencias significativas entre ambas medias**.

---

## 🧠 Conclusiones

El análisis muestra que el éxito de un videojuego depende principalmente de:

- la plataforma en la que se lanza
- el género
- la región de venta
- la valoración de los críticos

Las plataformas con mejor proyección para campañas futuras fueron **PS4** y **XOne**, mientras que **PS3** y **X360** mostraron una tendencia negativa.  

Los géneros **Action, Shooter, Role-Playing y Sports** concentraron la mayor parte de las ventas, aunque **Shooter** destacó por su alto promedio por título.  

También se confirmó que las preferencias regionales cambian de forma importante: mientras que en **NA** y **EU** dominan **PS4, Action y Shooter**, en **JP** sobresalen **3DS** y **Role-Playing**.  

En general, estos hallazgos permiten identificar videojuegos con mayor potencial comercial y apoyar la planeación de campañas publicitarias basadas en datos.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## 👨‍💻 Autor

**Angel Mendiola Del Angel**  
Ingeniero Industrial | Científico de Datos
