# mpg25

# 🚗 Análisis del Consumo de Combustible: Dataset MPG

Este proyecto explora el dataset `mpg` (millas por galón), incluido en la librería `seaborn` de Python. El análisis se enfoca en el consumo de combustible de automóviles fabricados entre 1970 y 1982, incluyendo variables como cilindrada, peso y potencia del motor.

## 📚 Contexto

El dataset proviene del *Auto MPG dataset*, originalmente recopilado por la U.S. Environmental Protection Agency (EPA), y forma parte del UCI Machine Learning Repository.

Durante el análisis, se incorporó contexto histórico relevante, como la crisis del petróleo de 1973, que afectó directamente la industria automotriz global y generó una transición hacia vehículos más eficientes en consumo de combustible.

## 🛠️ Herramientas

- Python (Pandas, Numpy, Matplotlib, Seaborn, Scipy)

## 📈 Objetivos

Analizar la relación entre las variables del dataset y su impacto en el rendimiento de combustible (MPG).
Identificar patrones y tendencias en la eficiencia de los vehículos según cilindrada, peso y caballos de fuerza.
Evaluar las diferencias de rendimiento entre autos de distintos orígenes y configuraciones mecánicas.
Determinar los factores más influyentes en la aceleración de los vehículos.
Extraer hallazgos clave que permitan tomar decisiones informadas en el ámbito automotriz.

METODOLOGÍA
Para desarrollar el análisis del dataset se utilizó el que se llama “mpg”, integrado en Python con la librería de Seaborn que se ejecuta con sns.load_dataset("nombre").
1. VARIABLES:
❖ mpg: millas por galón
❖ cylinders: número de cilindros
❖ displacement: desplazamiento
❖ horsepower: Potencia (caballos de fuerza)
❖ acceleration: aceleración
❖ model_year: año del modelo
❖ origin: país
❖ name: nombre

2. EXPLORACIÓN DE INFORMACIÓN
Para analizar el dataset se utilizaron las librerías de pandas, numpy, matplotlib, seaborn y scipy (stats).
Después de ejecutar el procesamiento de la información, se obtuvo que el dataset contiene 398 datos con 9 variables y se determinó que la columna de “horsepower” tenía 6 valores nulos, que fueron eliminados, dado que representan un 1,51% de toda la información y no eran valores influyentes para el análisis.

3. VISUALIZACIONES
A partir de la exploración del dataset se crearon las siguientes visualizaciones, que se realizaron utilizando las siguientes paletas de colores: coolwarm, magma, YlGnBu, YlGn, inferno (Ver anexos).
3.1 Distribución de MPG según caballos de fuerza
3.2 Millas por galón vs. desplazamiento según cilindros
3.3 Heatmap: relación entre desplazamiento, caballos de fuerza y peso
3.4 Distribución de aceleración según cilindros
3.5 Top 5 autos con menor mendimiento de combustible
3.6 Top 5 autos más livianos con mejor desplazamiento
3.7 Top 5 autos con alta potencia y menor desplazamiento
3.8 Top 10 autos con mejor rendimiento de combustible (MPG) por país
3.9 Potencia promedio por número de cilindros en cada país
3.10 Matriz de correlación: factores que afectan el MPG

ANÁLISIS DE DATOS
El análisis conjunto de estas visualizaciones permite observar patrones claros en la eficiencia de los vehículos. Se confirma que el consumo de combustible está fuertemente influenciado por factores como el peso, la cilindrada y la potencia del motor. Los autos con menor cantidad de cilindros tienden a ser más eficientes y tienen mejor aceleración.
Los datos también muestran que los vehículos más livianos y con menor desplazamiento logran mejores rendimientos en MPG, especialmente aquellos de origen japonés y europeo. En contraste, los autos estadounidenses tienden a tener motores más grandes y potentes, lo que se traduce en un menor rendimiento en combustible.
Por otro lado, la relación entre potencia y desplazamiento indica que algunos modelos optimizan su eficiencia al ofrecer más caballos de fuerza sin aumentar drásticamente el tamaño del motor. 
Esto sugiere que el diseño y la tecnología del motor juegan un papel crucial en la eficiencia energética.

RESULTADOS
● Existe una relación inversa entre caballos de fuerza y rendimiento de combustible.
● Los vehículos con mayor número de cilindros presentan menor eficiencia y aceleración más baja.
● El peso del automóvil es un factor determinante en el consumo de combustible.
● Los autos más ligeros con menor cilindrada presentan mejor rendimiento en MPG.
● Se identificaron patrones consistentes en las diferencias de rendimiento según la región de origen del vehículo.
● Los autos japoneses y europeos tienen mejor eficiencia de combustible en comparación con los estadounidenses.
● Los modelos con alta relación potencia/desplazamiento logran un mejor aprovechamiento energético sin sacrificar rendimiento.

CONCLUSIONES Y RECOMENDACIONES
El análisis confirma que los motores más pequeños y livianos ofrecen una mejor eficiencia de combustible, mientras que los motores más grandes y potentes consumen más gasolina. Se recomienda considerar estos factores al diseñar estrategias para la optimización del consumo de combustible en la industria automotriz.
Para futuros estudios, se sugiere:
● Incluir variables adicionales como aerodinámica y tecnología de transmisión para un análisis más profundo.
● Analizar la evolución histórica de estas tendencias para comprender cómo han cambiado los estándares de eficiencia con el tiempo.
● Evaluar el impacto de nuevas tecnologías como motores híbridos y eléctricos en comparación con los modelos tradicionales.
● Realizar un análisis más detallado por país para entender cómo las regulaciones afectan el diseño de los vehículos.
● Estos hallazgos pueden ser útiles para fabricantes y consumidores al tomar decisiones informadas sobre eficiencia y desempeño en la compra y producción de automóviles.






















