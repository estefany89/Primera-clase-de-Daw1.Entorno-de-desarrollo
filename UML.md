# UML

1. **¿Qué significan las siglas UML? Busca información acerca de su  historia y las versiones que han existido y el año de publicación.**

**UML (Lenguaje de modelado unificado)**

UML muestra la arquitectura física de un sistema informático. Puede representar a los equipos y a los dispositivos, y también mostrar sus interconexiones y el software que se encontrará en cada máquina.
UML es una notación que se originó como resultado de la unificación de la técnica de modelado de objetos (OMT por sus siglas en inglés Rumbaugh et al., 1991, Booch Booch  1941 e ingeniería de software orientada a objetos (OOSE, por sus siglas en inglés Jacobson et al., 1992).  LVersiones 
      
Versiones:

Lenguaje Unificado de Modelado (UML) Versión 0.8 y 0.9 (1995)

Lenguaje Unificado de Modelado (UML) Versión 1.0 y 1.1 (Año 1997)

Lenguaje Unificado de Modelado (UML) Versión 1.3 (2000)

Lenguaje Unificado de Modelado (UML) Versión 1.4 (2001)

Lenguaje Unificado de Modelado (UML) Versión 1.5 (2003)

Lenguaje Unificado de Modelado (UML) Versión 1.4.2 y 2.0 (Año 2005)

Lenguaje Unificado de Modelado (UML) Versión 2.1 (2006)

Lenguaje Unificado de Modelado (UML) Versión 2.1.1 y 2.1.2 (2007)

Lenguaje Unificado de Modelado (UML) Versión 2.2 (2009)

Lenguaje Unificado de Modelado (UML) Versión 2.3 (2010)

Lenguaje Unificado de Modelado (UML) Versión 2.4.1 (2011)

Lenguaje Unificado de Modelado (UML) Versión 2.5 (2015
   
Lenguaje Unificado de Modelado (UML) Versión 2.5.1 (2017) 


--------
2. **Indica los tipos de diagramas de estructura que existen en UML.**

- Diagramas de estructura (aspecto estático):

- Diagrama de Clases

- Diagrama de Componentes

- Diagrama de Objetos

- Diagrama de estructura compuesta

- Diagrama de Despliegue

- Diagrama de Paquetes

   ------

3. **Indica los tipos de diagramas de comportamiento que existen en UML.**

- Diagramas de comportamiento (aspecto dinámico)
- Diagrama de Actividad
- Diagrama de Casos de uso
- Diagrama de maquina de estado
- Diagrama de Interacción
- Digrama de Tiempos
- Diagrama de Secuencias
- Diagrama de Comunicacion
- Diagrama Global de Interacciones

```


```
#   Diagramas de clases

1. **Siguiendo la notación UML, pon 2 ejemplos de clases distintos a los vistos en este tema.**

![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D8.png)

![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D7.png)


2. **Siguiendo la notación UML, pon 2 ejemplos de interfaces distintos a los vistos en este tema.**
 
![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D10.png)

![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D9.png)

3. **Indica los tipos de relaciones que pueden darse y explica brevemente.**

**relaciones en los diagramas de casos de uso:**

**Comunicación:** Relación (asociación) entre un actor y un caso de uso. El estereotipo de la relación de comunicación es: <<communicate>> aunque generalmente no se estipula ningún nombre, como podemos apreciar en el siguiente ejemplo de comunicación:
      

**Inclusión:** Un caso de uso base incorpora explícitamente el comportamiento de otro en algún lugar de su secuencia. La relación de inclusión sirve para enriquecer un caso de uso con otro y compartir una funcionalidad común entre varios casos de uso, también puede utilizarse para estructurar un caso de uso describiendo sus subfunciones. El caso de uso incluido existe únicamente con ese propósito, ya que no responde a un objetivo de un actor.

Estas relaciones se representan mediante una flecha discontinua con el estereotipo <<include>>. Algunos casos de uso típicos de inclusión son: comprobar, verificar, buscar, validar, autentificar o login… En principio, no deberíamos abusar de este tipo de relación, para no hacer una descomposición funcional del sistema. A partir de UML 1.3 la relación <<include>> reemplazó al denominado <<uses>>.

 

Veamos un ejemplo de inclusión entre casos de uso:

Ejemplo de inclusión

 

**Extensión:** Un caso de uso base incorpora implícitamente el comportamiento de otro caso de uso en el lugar especificado indirectamente por este otro caso de uso. En el caso de uso base, la extensión se hace en una serie de puntos concretos y previstos en el momento del diseño, llamados puntos de extensión, los cuáles no son parte del flujo principal. La relación de extensión sirve para modelar: la parte opcional del sistema, un subflujo que sólo se ejecuta bajo ciertas condiciones o varios flujos que se pueden insertar en un punto determinado. Este tipo de relación produce confusión y no debería utilizarse en exceso. Conviene su uso sólo para insertar un nuevo comportamiento no previsto en un caso de uso existente. Estas relaciones se representan mediante una flecha discontinua con el estereotipo <<extend>>.

Veamos un ejemplo de extensión:

 

En este ejemplo usamos la relación de extensión entre los casos de uso Abrir acción de mejora y Resolver consulta. En este caso tendremos el punto de extensión “resolución retrasada” (en el caso de uso Resolver consulta) debido a que cuando haya pasado un tiempo estipulado por la organización (por ejemplo 3 días laborales) se abrirá una acción de mejora para dejar constancia del retraso y realizar posteriormente las acciones pertinentes, de ahí que digamos que el caso de uso Abrir acción de mejora es una subfunción de uso que puede extender al caso de uso Resolver consulta.

 

**Especialización y generalización de los casos de uso:** Un caso de uso (subcaso) hereda el comportamiento y significado de otro, es decir las relaciones de comunicación, inclusión y extensión del super-caso de uso. En muchas ocasiones este super-caso de uso es abstracto y corresponde a un comportamiento parcial completado en el subcaso de uso. O dicho de otra manera, Los casos de uso “hijo” son una especialización del caso de uso “padre”. En la medida de lo posible debería evitarse puesto que produce cierta confusión en algunas ocasiones.

 

Veamos un ejemplo de generalización:

 

Como podemos ver en este último ejemplo también pueden existir vínculos de generalización o herencia entre actores. Los actores especializados (Abogado y Psicólogo) heredan los casos de uso del actor general (Profesional). La punta de flecha apunta al actor más general. Hay que reseñar que los actores especializados pueden tener otros casos de uso propios que no estarán disponibles para los demás actores. Este tipo de herencia entre actores si que se usa frecuentemente puesto que nos simplifica considerablemente el diagrama, nos ahorra un número importante de relaciones de comunicación entre actores y casos de uso y nos sirve para esclarecer visualmente la jerarquía entre actores del sistema.


  

4. **Siguiendo la notación UML, indica la representación gráfica de las relaciones de la actividad anterior.**

   ------

```

```

#   Software

1. **En EasyUML usa IDEA, instala el plugin Diagrams.net Integration:**
 ![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/da6fb919d3472cecea1ae2fc161d2abc998360a6/imagenes/D1.png)
  
   ------

2. **Escoge uno de tus proyectos realizado en Java que disponga de varias clases. Genera el diagrama de clases haciendo uso del plugin EasyUML.**
 ![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/d2bc5404f47392eb68ca04cada06fb8a805609f8/imagenes/D2.png)
 ![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/d2bc5404f47392eb68ca04cada06fb8a805609f8/imagenes/D3.png)
   

3. **Haciendo uso del plugin Diagrams.net Integration: diseña un proyecto con varias clases y genera el código automáticamente.**
   ![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D4.png)
   ![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D5.png)
   ![imagen](https://github.com/estefany89/Primera-clase-de-Daw1.Entorno-de-desarrollo/blob/0ea98da720371b24e8b46f52f2ee6f48874e0438/imagenes/D6.png)
   

   
