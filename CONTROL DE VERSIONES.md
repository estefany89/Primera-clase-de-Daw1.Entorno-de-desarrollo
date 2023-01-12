# Control de versiones

1). **Además de Git, ¿que otros sistemas de control de versiones existen?**

   CVS, Subversion, SourceSafe, ClearCase, Darcs, Bazaar, Plastic SCM, Git,  SCCS, Mercurial, Perforce, Fossil SCM, Team Foundation Server.

   ------

2). **En Git, ¿qué tres áreas existen?**

   El directorio de Git (Git directory), el directorio de trabajo (working directory), y el área de preparación (staging area).

   

   ------

3). **Busca en Internet un buen tutorial de GIT y realízalo. ¿De qué tutorial se trata?**
    
  - https://www.youtube.com/watch?v=VdGzPZ31ts8
    Aprende GIT ahora! curso completo GRATIS desde cero
   

   ------

4). **Visualiza el siguiente video y responde a las cuestiones que aparecen más abajo.**

   - https://www.youtube.com/watch?v=uR6G2v_WsRA

   ------

5). **En Git, ¿para qué sirve el comando `git config`?** 

   El comando git config es una función útil que sirve para definir valores de configuración de Git a nivel de un proyecto global o local.

   ------

6). **En Git, ¿para qué sirve el comando `git init`?** 

   Inicializa un directorio existente como un repositorio Gif


   ------

7). **En Git, ¿para qué sirve el comando `git clone`?** 

   recuperar un repositorio completo desde una URL de ubicación alojada

   

   ------

8). **En Git, ¿para qué sirve el comando `git status`?** 

   Mostrar archivos modificados en el directorio de trabajo, preparados para su próxima confirmación

   
  ------

9). **En Git, ¿para qué sirve el comando `git add`?** 

   Agrega un archivo como se ve ahora para su próxima confirmación (etapa)

![imagen](https://user-images.githubusercontent.com/113978919/212054630-a96dae71-ce0f-47ab-88fb-e823a5027edf.png)


------

10). **En Git, ¿para qué sirve el comando `git commit`?** 

    Sirve para confirmar una instantánea del directorio del entorno de ensayo en el historial de confirmaciones de los repositorios.

![imagen](https://user-images.githubusercontent.com/113978919/212054744-dc1bb5dc-a3b4-48df-83a7-8c46ba7fe1cf.png)


------

11). **En Git, ¿para qué sirve el comando `git log`?** 

    Mostrar todas las confirmaciones en el historial de la sucursal actual.

------

12). **En Git, ¿para qué sirve el comando `git reset HEAD nombrearchivo`?** 

    Es un comando potente que sirve para deshacer los cambios locales en el estado de un repositorio de Git

![imagen](https://user-images.githubusercontent.com/113978919/212054875-5ef87d3c-ecc0-4f9b-974f-9330fc4d0c8e.png)


------

13). **En Git, ¿para qué sirve el comando `git checkout -- nombrearchivo`?** 

    Te permite desplazarte entre las ramas creadas por git branch.

![imagen](https://user-images.githubusercontent.com/113978919/212055004-d47eb59f-a47f-439d-94c8-b65a1a624902.png)


------

14). **Visualiza el siguiente video y responde a las cuestiones que aparecen más abajo.**

- https://www.youtube.com/watch?v=FyAAIHHClqI

------

15). **En Git, ¿para qué sirve el comando `git branch`?** 

   Te permite crear, enumerar y eliminar ramas, así como cambiar su nombre.

------

16). **En Git, ¿para qué sirve el comando `git checkout`?** 

    Cambia a otra sucursal y lo comprueba en tu directorio de trabajo

------

**17).En Git, ¿para qué sirve el comando `git merge`?** 

    Fusiona el historial de la rama especificada en el actual.


------

18). **En Git, explica cómo funciona la fusión (merge) de tipo fast-forward.**

    Fast Forward en Git Marge, permite armonizar la rama `master`de un proyecto con los cambios realizados en una rama *`feature`*.

![imagen](https://user-images.githubusercontent.com/113978919/212055091-0b1adcba-d32b-42e6-97ba-435194964967.png)

![imagen](https://user-images.githubusercontent.com/113978919/212055146-b8c122af-0289-4994-9b9c-81437cd06da2.png)


------

19). **En Git, explica cómo funciona la fusión (merge) de tipo 3-way.**

Git identifica estas tres confirmaciones mediante instantáneas. Git compara el ancestro común con cada una de las confirmaciones de punta.
La fusión de 3-way funciona:

    -El ancestro común.
    -La punta de la rama Master.
    -La punta de la rama de funciones.

![imagen](https://user-images.githubusercontent.com/113978919/212055243-b9319bf6-70e1-44ca-8f5e-dce6736d210b.png)

![imagen](https://user-images.githubusercontent.com/113978919/212055295-22f4d475-48d8-4136-993a-ffb33f2eeb1f.png)


