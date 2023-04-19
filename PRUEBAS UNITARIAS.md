# PRUEBAS UNITARIAS

1. **¿Qué diferencia existe entre las pruebas estáticas y dinámicas?**

   Las pruebas estáticas y dinámicas son dos tipos diferentes de pruebas de software que se utilizan para evaluar diferentes aspectos del software.

   - Las pruebas estáticas se realizan sin ejecutar el software, es decir, sin necesidad de compilar o ejecutar el código fuente. En lugar de eso, se realizan revisiones de código, análisis de documentos, diagramas y especificaciones, entre otras técnicas. El objetivo de las pruebas estáticas es detectar errores, problemas de calidad, y otros problemas en el software antes de que se compile o ejecute. Las pruebas estáticas también ayudan a mejorar la calidad del código y asegurar su mantenibilidad en el futuro.

   - Por otro lado, las pruebas dinámicas se realizan ejecutando el software y evaluando su comportamiento en diferentes situaciones. Las pruebas dinámicas pueden incluir pruebas de unidad, pruebas de integración, pruebas de sistema, pruebas de aceptación, entre otros tipos de pruebas. El objetivo de las pruebas dinámicas es asegurar que el software cumpla con los requisitos funcionales y no funcionales, y que se comporte como se espera en diferentes situaciones.

   En resumen, la principal diferencia entre las pruebas estáticas y dinámicas es que las pruebas estáticas se realizan sin ejecutar el software y se enfocan en revisar y analizar el código fuente, mientras que las pruebas dinámicas se realizan ejecutando el software y se enfocan en evaluar su comportamiento y funcionalidad en diferentes situaciones. Ambas pruebas son importantes en el proceso de desarrollo de software para garantizar la calidad del software y detectar errores en diferentes etapas del desarrollo.

   ------

2. **¿Qué diferencia existe entre las pruebas de caja negra y caja blanca?**

   Las pruebas de caja negra y caja blanca son dos técnicas de prueba de software utilizadas para evaluar diferentes aspectos del software.

   - Las pruebas de caja negra se realizan sin tener conocimiento de la estructura interna del software, es decir, el probador no sabe cómo está implementado el software. En cambio, el probador evalúa la funcionalidad del software como un usuario externo, evaluando la entrada y la salida del sistema. Las pruebas de caja negra se centran en validar si el software cumple con los requisitos del usuario y en descubrir errores que puedan afectar su uso o su calidad.

   - Por otro lado, las pruebas de caja blanca se realizan con conocimiento de la estructura interna del software. Los probadores tienen acceso al código fuente y a la lógica de negocio del software y pueden evaluar su comportamiento en diferentes situaciones. Las pruebas de caja blanca se centran en evaluar la calidad del código, la cobertura del código, la eficiencia y otros aspectos técnicos.

   En resumen, la principal diferencia entre las pruebas de caja negra y caja blanca es que las pruebas de caja negra se enfocan en evaluar la funcionalidad del software sin conocer su estructura interna, mientras que las pruebas de caja blanca se enfocan en evaluar la calidad del código y la lógica de negocio del software con conocimiento de su estructura interna. Ambas técnicas son importantes para garantizar la calidad del software y descubrir errores en diferentes etapas del proceso de desarrollo.

   ------

3. **¿Qué diferencia existe entre las pruebas funcionales y no funcionales?**

   Las pruebas funcionales y no funcionales son dos tipos diferentes de pruebas de software utilizados para evaluar diferentes aspectos del software.

   - Las pruebas funcionales se centran en evaluar la funcionalidad del software, es decir, si el software cumple con los requisitos funcionales del usuario. Estas pruebas se realizan para verificar si el software se comporta como se espera en diferentes situaciones, si los datos de entrada son procesados correctamente y si los resultados son precisos y consistentes. Algunos ejemplos de pruebas funcionales incluyen pruebas de unidad, pruebas de integración, pruebas de sistema y pruebas de aceptación.

   - Por otro lado, las pruebas no funcionales se centran en evaluar aspectos no relacionados con la funcionalidad del software, como su rendimiento, seguridad, estabilidad, usabilidad, entre otros aspectos. Estas pruebas se realizan para evaluar cómo el software se desempeña en diferentes situaciones que puedan afectar la calidad y la experiencia del usuario. Algunos ejemplos de pruebas no funcionales incluyen pruebas de carga, pruebas de estrés, pruebas de seguridad, pruebas de usabilidad, entre otras.

   En resumen, la principal diferencia entre las pruebas funcionales y no funcionales es que las pruebas funcionales se enfocan en evaluar la funcionalidad del software, mientras que las pruebas no funcionales se enfocan en evaluar aspectos no relacionados con la funcionalidad, pero importantes para la calidad y experiencia del usuario. Ambos tipos de pruebas son importantes para garantizar la calidad del software y detectar errores en diferentes etapas del proceso de desarrollo.

   ------

4. **Nombra al menos 4 pruebas funcionales.**

   1. Pruebas de caja negra: Esta prueba se enfoca en probar la funcionalidad del software sin conocer su estructura interna, se evalúa la entrada y salida del software y se busca validar que el software cumpla con los requisitos y expectativas del usuario.
   2. Pruebas de integración: Esta prueba se enfoca en probar la funcionalidad de las diferentes partes del software cuando se integran entre sí, buscando asegurar que todas las piezas del software funcionen juntas como un todo.
   3. Pruebas de regresión: Esta prueba se enfoca en probar si los cambios en el software han afectado a su funcionalidad original y si se han introducido errores en áreas previamente funcionales.
   4. Pruebas de aceptación: Esta prueba se enfoca en probar la funcionalidad del software desde la perspectiva del usuario final, asegurando que el software cumpla con las necesidades y expectativas del cliente y esté listo para su lanzamiento y uso en un entorno de producción.

   ------

5. **Nombra al menos 4 pruebas no funcionales.**

   1. Pruebas de rendimiento: Esta prueba se enfoca en evaluar el desempeño del software en términos de velocidad, escalabilidad, capacidad de procesamiento y capacidad de respuesta bajo cargas de trabajo y condiciones diferentes.
   2. Pruebas de seguridad: Esta prueba se enfoca en evaluar la seguridad del software, buscando detectar vulnerabilidades y errores que puedan ser explotados por un atacante malintencionado.
   3. Pruebas de usabilidad: Esta prueba se enfoca en evaluar la facilidad de uso y la accesibilidad del software para el usuario final, y buscar detectar problemas de navegación, diseño o usabilidad que puedan afectar la experiencia del usuario.
   4. Pruebas de compatibilidad: Esta prueba se enfoca en evaluar la compatibilidad del software con diferentes plataformas, sistemas operativos, navegadores web y otros componentes de software, buscando asegurar que el software se ejecute de forma adecuada en diferentes configuraciones de hardware y software.

   ------

6. **¿Qué són las pruebas unitarias o pruebas de unidad?**

   Las pruebas unitarias o pruebas de unidad son un tipo de prueba de software que se enfoca en evaluar el comportamiento de las unidades individuales de código fuente de un programa, como funciones, métodos o clases.

   Las pruebas unitarias son llevadas a cabo por los desarrolladores de software, quienes escriben pruebas automatizadas para evaluar el comportamiento de las unidades de código en un ambiente controlado. El objetivo principal de estas pruebas es asegurarse de que cada unidad de código funcione correctamente y de forma aislada, y que cumpla con los requisitos y expectativas del software.

   Las pruebas unitarias son importantes en el proceso de desarrollo de software, ya que permiten a los desarrolladores detectar y corregir errores y problemas en una etapa temprana del proceso de desarrollo. Esto ayuda a garantizar que el software cumpla con los requisitos y expectativas del usuario, y que sea más fácil y eficiente hacer mejoras y correcciones a medida que el desarrollo avanza.

   En resumen, las pruebas unitarias o pruebas de unidad son un tipo de prueba de software que se enfoca en evaluar el comportamiento de las unidades individuales de código fuente de un programa, como funciones, métodos o clases, y son llevadas a cabo por los desarrolladores de software para garantizar que cada unidad de código funcione correctamente y de forma aislada.

   ------

7. **¿Qué són las pruebas de regresión?**

   Las pruebas de regresión son un tipo de prueba de software que se realiza para verificar que los cambios en una aplicación o sistema de software no hayan afectado negativamente su funcionamiento previo. Es decir, se ejecutan pruebas de regresión para asegurarse de que las modificaciones realizadas en el software no hayan introducido errores o defectos nuevos o hayan impactado negativamente en la funcionalidad previamente establecida.

   En general, las pruebas de regresión se realizan después de realizar cambios en el código fuente del software, tales como correcciones de errores, mejoras de características o actualizaciones de versiones. Las pruebas de regresión se diseñan para verificar que el software aún funciona como se espera después de los cambios, y que no se han introducido nuevos errores o comportamientos no deseados.

   Para realizar pruebas de regresión, se pueden emplear diferentes técnicas y herramientas de prueba, incluyendo la automatización de pruebas. El objetivo principal es garantizar la calidad y estabilidad del software, a través de una verificación completa de su comportamiento antes y después de cualquier cambio.

   ------

8. **¿Qué son las pruebas de integración?**

   Las pruebas de integración son un tipo de prueba de software que se realiza para evaluar cómo los diferentes componentes de un sistema interactúan entre sí y cómo funcionan en conjunto. Estas pruebas se enfocan en las interfaces entre los módulos o componentes del sistema, y tienen como objetivo detectar errores en la interacción de dichos componentes.

   Las pruebas de integración se realizan para asegurarse de que el sistema completo funciona de manera coherente y cumple con los requisitos establecidos. Por lo general, estas pruebas se llevan a cabo después de las pruebas unitarias (que se centran en la funcionalidad de cada componente individualmente) y antes de las pruebas de sistema (que se enfocan en la funcionalidad del sistema completo).

   Para realizar pruebas de integración, se utilizan diferentes técnicas y herramientas de prueba, incluyendo la automatización de pruebas. El objetivo principal es garantizar que los diferentes componentes del sistema funcionen correctamente juntos y que la integración sea exitosa, para asegurar la calidad y la estabilidad del software.

   ------

9. **¿Qué son las pruebas de humo?**

   Las pruebas de humo, también conocidas como pruebas de sanity, son un tipo de prueba de software que se realiza para comprobar rápidamente si una nueva versión o actualización del software tiene errores graves o críticos que impidan su funcionamiento básico.

   Este tipo de pruebas se realizan generalmente después de realizar cambios significativos en el software, como una actualización importante o una revisión importante del código, y se llevan a cabo antes de las pruebas de integración y de las pruebas más exhaustivas. Las pruebas de humo son una forma rápida de asegurarse de que el software todavía funciona básicamente correctamente después de los cambios realizados.

   El objetivo principal de las pruebas de humo es detectar errores graves que puedan impedir el correcto funcionamiento del software, y así permitir a los desarrolladores identificar rápidamente los problemas y corregirlos antes de proceder con pruebas más exhaustivas. Por lo general, estas pruebas se centran en las funciones críticas o de mayor impacto del software.

   Las pruebas de humo no son exhaustivas y no cubren todas las posibles fallas o errores del software, pero son útiles para identificar rápidamente problemas importantes y evitar que los errores críticos se propaguen a las siguientes etapas de pruebas y, finalmente, al usuario final.

   ------

10. **¿Qué son las pruebas alpha?**

    Las pruebas alpha son un tipo de prueba de software que se lleva a cabo internamente por el equipo de desarrollo del software antes de su lanzamiento público. Este tipo de prueba se realiza en una etapa temprana del proceso de desarrollo y se enfoca en identificar problemas y errores en el software antes de que se entregue a los usuarios finales.

    Las pruebas alpha son especialmente importantes en el desarrollo de software complejo, ya que permiten a los desarrolladores identificar y corregir problemas antes de que el software se entregue a los usuarios finales. Al realizar estas pruebas en una etapa temprana del proceso de desarrollo, se pueden ahorrar costos y tiempo en la corrección de errores y en la implementación de mejoras.

    Las pruebas alpha pueden incluir una variedad de técnicas de prueba, como pruebas unitarias, pruebas de integración, pruebas de regresión y pruebas de aceptación, y se llevan a cabo en un entorno controlado y limitado. Los usuarios finales no tienen acceso al software en esta etapa, y las pruebas se realizan con el objetivo de detectar problemas y errores que podrían afectar el rendimiento, la estabilidad y la seguridad del software.

    En resumen, las pruebas alpha son un tipo de prueba de software que se  lleva a cabo internamente por el equipo de desarrollo del software antes de su lanzamiento público, con el objetivo de identificar problemas y  errores en una etapa temprana del proceso de desarrollo.

    ------

11. **¿Qué son las pruebas beta?**

    Las pruebas beta son un tipo de prueba de software que se lleva a cabo después de las pruebas alfa y antes del lanzamiento público del software. Estas pruebas implican la liberación del software a un grupo limitado de usuarios finales seleccionados para probarlo en un ambiente real de uso, en lugar de un entorno controlado y limitado como en las pruebas alfa.

    El objetivo principal de las pruebas beta es recopilar comentarios, opiniones y sugerencias de los usuarios finales sobre el software y su rendimiento en un ambiente real, y utilizar esa retroalimentación para corregir cualquier problema o error y hacer mejoras en el software antes de su lanzamiento oficial. Además, las pruebas beta también ayudan a determinar la aceptación y popularidad del software entre los usuarios finales.

    Las pruebas beta pueden durar desde unos pocos días hasta varias semanas, dependiendo del alcance del software y la cantidad de usuarios beta involucrados.  Son una etapa importante en el proceso de desarrollo de software, ya que permiten a los desarrolladores obtener una retroalimentación valiosa de los usuarios finales y asegurarse de que el software cumpla con las expectativas y necesidades de los usuarios antes de su lanzamiento oficial.

    ------

12. **¿Qué son las pruebas de aceptación?**

    Las pruebas de aceptación son un tipo de prueba de software que se realiza para determinar si el software cumple con los requisitos y expectativas del cliente y si está listo para su lanzamiento y uso en un entorno de producción.

    Las pruebas de aceptación pueden ser llevadas a cabo tanto por el equipo de desarrollo como por el cliente o usuario final del software. Estas pruebas se realizan en una etapa avanzada del proceso de desarrollo, después de las pruebas alfa y beta, y se centran en evaluar el software desde la perspectiva del usuario final.

    Las pruebas de aceptación pueden incluir la validación de funciones específicas del software, la comprobación de la interfaz de usuario, la simulación de casos de uso reales, la evaluación del rendimiento y la escalabilidad, y la validación de los requisitos técnicos y no técnicos del software.

    El objetivo principal de las pruebas de aceptación es asegurarse de que el software cumpla con las necesidades y expectativas del cliente y esté listo para su lanzamiento y uso en un entorno de producción. Si se identifican problemas o errores en esta etapa, se pueden hacer los ajustes necesarios antes de la implementación del software en el ambiente de producción.

    En resumen, las pruebas de aceptación son un tipo de prueba de software que se realiza para determinar si el software cumple con los requisitos y expectativas del cliente y si está listo para su lanzamiento y uso en un entorno de producción.