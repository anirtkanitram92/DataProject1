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

    1. Resumen Ejecutivo: El análisis de los 50.000 estudiantes muestra que, en general, usar Inteligencia Artificial ayuda a mejorar las notas. Sin embargo, esta mejora no es igual para todos: los alumnos que mejor saben usar la IA (los que saben escribir mejores instrucciones o prompts) y los que estudian ciertas carreras le sacan mucho más provecho. Además, los datos quitan un miedo común: usar más la IA no hace que los estudiantes dependan excesivamente de ella ni que sufran más ansiedad a la hora de los exámenes.

    2. Situación general: Si miramos los datos de todos los estudiantes juntos, vemos que la nota media general (GPA) subió de un 2,86 a un 3,35 tras empezar a usar la IA. Esto es una mejora notable del 17,14%. En general, el nivel de dependencia de la IA (3,51 sobre 10) y el nivel de estrés en los exámenes (4,27 sobre 10) son moderados, lo que indica que los alumnos están usando la tecnología como una ayuda equilibrada y no como una obsesión.

    3. ¿Quiénes usan la IA y para qué?: La forma de usar la IA cambia según lo que estudie el alumno, pero se mantiene muy parecida sin importar el año de carrera que esté cursando:

- Ciencias (STEM) frente a Arte: Aquí sí hay una diferencia clara por especialidad. Los estudiantes de carreras científicas y tecnológicas usan la IA principalmente para resolver problemas y corregir errores de código (Debugging). En cambio, los estudiantes de Arte la usan casi exclusivamente para redactar textos y armar borradores (Copywriting).

- Alumnos nuevos frente a veteranos: Al contrario de lo que se podría pensar, los alumnos de primer año (Freshman) y los de posgrado (Graduate) tienen exactamente las mismas prioridades. En ambos grupos, el uso principal es solucionar problemas y programar, seguido de la redacción y la búsqueda de ideas, dejando la generación de respuestas directas como la opción menos utilizada por todos.

    4. El impacto en notas y el nivel de estrés: Al separar a los estudiantes por grupos, descubrimos dos cosas muy importantes sobre sus notas y su salud mental:

 La experiencia ayuda: Los estudiantes de posgrado logran subir sus notas más (+18,24%) que los de primer año (+14,40%). Lo mejor es que lo hacen sin estresarse más, ya que sus niveles de ansiedad son prácticamente iguales.

- Saber usar la IA da ventaja: Los alumnos avanzados en el uso de prompts mejoran sus notas un 18,33%, mientras que los principiantes mejoran un 16,17%. Y aquí viene lo más interesante: dominar la tecnología no hace que dependan más de ella ni que tengan más ansiedad. Los niveles de estrés y dependencia son casi idénticos entre un estudiante experto y uno que apenas está empezando.

    5. Horas de estudio y cuentas de pago: El dinero que se invierte en la IA también cambia la forma de estudiar:

- Las cuentas de pago ahorran tiempo: Los estudiantes que pagan una suscripción pasan más horas usando la IA a la semana, pero a cambio, pasan menos tiempo en el "estudio tradicional" de hincar codos.

- Las cuentas gratis exigen más esfuerzo: Los estudiantes que usan las versiones gratuitas pasan muchísimas más horas en el estudio tradicional. Esto sugiere que la IA gratuita se queda corta y los alumnos tienen que compensarlo estudiando de la manera vieja para poder alcanzar sus metas.

    6. Caso de éxito: Al jugar con los filtros del panel, encontramos un grupo que le saca un partido espectacular a la IA: los estudiantes de Arte que están en su último año de carrera y tienen un nivel intermedio de manejo de la IA. Este grupo de 482 alumnos logró la mayor subida de notas de todo el estudio: un +23,50% (pasaron de un 2,74 a un 3,39 de nota media). Además, tienen menos estrés y menos dependencia que la media.
 
    7. Conclusiones:
- Enseñar a usar la IA: Como los estudiantes que mejor manejan la IA sacan mejores notas sin estresarse más, las universidades deberían dar cursos básicos de cómo usar estas herramientas según cada carrera.

- Ayudar con las licencias: Las versiones de pago hacen que el estudio sea más eficiente. Ofrecer licencias desde la universidad ayudaría a que todos los alumnos jueguen con las mismas ventajas.

- Herramientas distintas para cada carrera: No se debe tratar igual la IA en todas las asignaturas. En ciencias debe servir para resolver problemas lógicos, y en letras para ayudar a redactar y estructurar ideas.
       
