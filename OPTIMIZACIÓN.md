# Optimización

**¿Qué se entiende por hediondez del código? Pon al menos 5 ejemplos.**

En programación de computadores, la hediondez del código (*code smell* en inglés, o también conocido por código que huele o apesta) es cualquier síntoma en el código fuente Código_fuente de un programa que posiblemente indica un problema más profundo. Las hediondeces del código usualmente no son bug de programación (errores) -- no son técnicamente incorrectos y en realidad no impiden  que el programa funcione correctamente. En cambio, indican deficiencias  en el diseño de software que puede ralentizar el desarrollo o aumentan el riesgo de errores o fallos en el futuro.

- Código duplicado: existe código idéntico o muy similar en más de una ubicación.
- Clase grande: una clase que ha crecido hasta hacerse demasiado grande. 
- Demasiados parámetros: una larga lista de parámetros de un procedimiento o función empeora la legibilidad y la calidad del código.
- Supercallback: callback excesivos.
- Complejidad artificiosa: Uso forzado de patrones de diseño demasiado complicados, donde uno más simple sería suficiente.

------

**¿Qué tipo de herramienta utilizamos para hacer análisis estático del código?**

Las herramientas de **Parasoft** están disponibles para estos lenguajes de programación. Ejecute  análisis estático integrándose estrechamente en su entorno de desarrollo C y C ++ para detectar defectos lo antes posible.

------

**¿Qué sitios web nos permiten hacer análisis estático del código o Continuous Inspection?**

- Review Board
- Crucible
- Phabricator
- Collaborator
- CodeScene
- Visual Expert
- Rhodecode
- Reviewable
- Veracode

------

**Instala en Netbeans el plugin FindBugs, si no lo tienes aún instalado.**

![imagen](https://user-images.githubusercontent.com/113978919/212056595-9a2dbcbc-02a3-4f25-8cef-af2f1efb5df1.png)
------

**Realiza análisis estático de código para las clases del proyecto *miapp*. Consulta el siguiente enlace: [análisis estático con FindBugs]**
![imagen](https://user-images.githubusercontent.com/113978919/212056544-12604947-062b-4939-9933-0006f4fd8ea9.png)
------

**Indica al menos un `code smell` relevante de cada clase. Explica cómo podría solucionarse.**

- Análisis estático (lint)

Sin ejecutar el código, mediante una serie de métodos de análisis que se pueden ejecutar sobre el código fuente de una aplicación para detectar problemas potenciales.

- Análisis dinámico (unit tests)

Identificar etapas,  estados y variable de decisión: Cada etapa debe tener asociada una o más decisiones (problema de optimización).



**¿Qué es la refactorización?**

La refactorización es una técnica de la ingeniería de software para reestructurar un código fuente, alterando su estructura interna sin cambiar su comportamiento externo.

------

**¿Qué técnicas se utilizan a menudo a la hora de refactorizar?**

- Renombrado de variables
- Pasar código duplicado a funciones
- Eliminación de código inalcanzable
- Eliminación de código redundante
- Eliminación de código muerto
