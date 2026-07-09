# ANÁLISIS DEL IMPACTO DE LA IA EN ESTUDIANTES
Análisis exploratorio del uso de IA en un conjunto de estudiantes. 

*Objetivo:* Identificar patrones y su impacto.

*Estructura Repositorio:*
> *Data:* URL de la fuente de datos + archivo csv con el dataset

> *Analisis:* Fichero Excel con los datos procesados

> *Readme:* Descripción del proyecto

*Descripción del proyecto:*

> *Transformación y limpieza de datos*

    1. Sustitución de "." por "," a través de Power Query para evitar problemas de formato con los números decimales.
   
    2. Revisión de duplicados en la columna "Student_ID" (no se encontraron).

    3. Inclusión de numerales para ordenar las categorías dentro de "Year of Study" por antigüedad.

    4. Inclusión de numerales para ordenar las categorías dentro de "Prompt Engineering Skills" de menor a mayor habilidad.

> *Análisis descriptivo de los datos*

    1. Pestaña "Dataset": la base de datos "ai_student_impact_dataset" nos ofrece información sobre 50.000 estudiantes estadounidenses de diferentes ramas (desde arte hasta STEM) y niveles (desde freshman hasta graduate) que hacen uso de la IA, ofreciendo información sobre el nivel de promp engineering que tienen, su uso principal, si pagan o no suscripción, cuántas horas le han dedicado, así como algunos datos para valorar su impacto a través de las notas antes y después del semestre, el nivel de dependencia que tienen de la IA, el nivel de ansiedad durante los exámenes o el riesgo de Burnout. 

    2. Pestaña "Pivot Tables": pestaña intermedia donde están alojadas todas las pivot tables que sirven de base a los gráficos y big numbers del dashboard.

    3. Pestaña "Dashboard": pestaña final con los gráficos y big numbers que sirven para explorar los datos del dataset.

> *Dashboard*

    El dashboard está diseñado para analizar el impacto, los hábitos de uso y la influencia de la inteligencia artificial en el rendimiento académico y el estado psicológico de los estudiantes universitarios en Estados Unidos. En la parte superior, el cuadro de mando destaca de forma global la evolución de las calificaciones académicas de los alumnos antes y después de integrar la IA en su rutina, complementado con indicadores que miden su nivel de dependencia hacia estas herramientas y el nivel de ansiedad que experimentan frente a los exámenes.

El cuerpo central y los gráficos de la izquierda se enfocan en caracterizar sociodemográfica y técnicamente a la población estudiantil analizada. El dashboard segmenta a los alumnos según su área de estudio (como ciencias, humanidades o salud), el año de carrera que cursan y su nivel de destreza técnica en la redacción de instrucciones (prompting). Además, incluye un desglose que identifica el propósito principal para el cual utilizan la IA en su día a día académico, como la resolución de problemas técnicos, la redacción de textos o la generación de ideas.

Por último, el panel incluye un módulo comparativo que examina el balance entre el tiempo dedicado al uso de la inteligencia artificial y las horas destinadas al estudio tradicional, diferenciando los hábitos de los alumnos en función de si utilizan versiones de IA de pago o gratuitas.

Toda esta información se puede ver desde distintos ángulos gracias a los segmentadores situados en la esquina inferior derecha.

> *Informe explicativo del análisis*
