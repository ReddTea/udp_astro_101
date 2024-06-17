# udp_astro_101

## Una Reevaluación del Primer Sistema Planetario Confirmado Descubierto Mediante el Método RV, 51 Pegasi
En este proyecto, el estudiante obtendrá y analizará los datos de series temporales de velocidad radial de alta precisión (PRV) más recientes y actualizados sobre el primer sistema planetario confirmado, 51 Pegasi. En 1995, el campo de los estudios de planetas extrasolares se lanzó hacia un nuevo paradigma con el descubrimiento y posterior confirmación del planeta 51 Pegasi b (Mayor & Queloz 1995, Nature). Este sistema ha seguido siendo observado en los años posteriores mediante instrumentos PRV, con el objetivo de refinar aún más los parámetros planetarios y buscar planetas adicionales. Aquí usaremos nuestro código de análisis bayesiano EMPEROR para examinar este conjunto de datos denso y de largo plazo, para mejorar aún más nuestra comprensión de este sistema y cómo se pueden usar los métodos bayesianos para buscar señales Doppler en datos ruidosos.


## ¿Qué se hará?
El estudiante debe realizar un análisis estadístico de los datos observados, incluidas estimaciones de parámetros, modelización de ruido e inferencia estadística, proporcionando respuestas coherentes a algunas preguntas amplias que se enumeran a continuación. En comparación con el formato típico en papel para el informe escrito, el estudiante se centrará principalmente en los resultados científicos del estudio realizado. Se espera que se incluyan debates sobre los valores de los parámetros de EMPEROR, en particular de las características de la órbita del planeta 51 Pegasi b.  Qué tipo de orbita tiene?  Qué masa mínima tiene el planeta?  Qué tipo de planeta es?  Hay la posibilidad de tener otros planetas en la sistema también?  Explica que sabes de la estadística bayesiana y probabilidades.  

## Empezando
El código EMPEROR se ha trasladado a Google Collab, de modo que las pruebas de 51 Pegasi se pueden ejecutar directamente en los servidores de Google. Esto hace que ejecutar EMPEROR por primera vez sea bastante sencillo y todos los resultados se pueden descargar desde el sitio de Collab.
Puede encontrar el Proyecto de colaboración EMPEROR en el siguiente enlace, y todos los archivos de ayuda deberían facilitar el proceso para comenzar a ajustar los datos del RV.

Colab EMPEROR: https://colab.research.google.com/drive/1K4SvaK94-b30K0FCKXtFvCS9t0J_v3Xh?usp=sharing

EMPEROR GitHub: https://github.com/ReddTea/astroEMPEROR

## Preguntas a abordar
¿Qué forma tienen las estimaciones posteriores marginadas bajo diferentes supuestos de cómo se aplican los modelos de ruido?
¿Cómo funciona el muestreador al analizar un único conjunto de datos de series temporales PRV, frente a varios conjuntos de datos o todos los conjuntos de datos combinados?
¿Qué modelo de ruido funciona mejor al analizar estos datos? ¿Y por qué?
¿Qué antecedentes son los más adecuados para los parámetros necesarios para modelar dichos datos y descubrir planetas?
¿Cómo actúan las métricas aplicadas al incluir o no un modelo de planeta kepleriano en lugar de un modelo de ruido plano? ¿Cómo continúa esto cuando se avanza hacia múltiples planetas?
¿Qué métricas cree que son las más adecuadas para este tipo de análisis? Sugerencia: compare y analice las probabilidades extraídas de diferentes estimadores como BIC, AIC, RMS, etc., y explique lo que cree que está sucediendo.
¿Cómo se comparan las estimaciones de los parámetros finales con los valores determinados cuando se utiliza un procedimiento de ajuste más estándar de Lomb-Scargle y Kepleriano? Tenga en cuenta que puede utilizar herramientas como ExoStriker para esta parte, pero no es estrictamente necesario para hacer este comparación.

ExoStriker GitHub: https://github.com/3fon3fonov/exostriker 

**Nota que no es necesario a responder de todos de las preguntas, son para dar ideas principalmente!!