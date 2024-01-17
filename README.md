En imageViewer.js el DEFAULT_PLACEHOLDER sería la imagen que quieres mostrar por defecto si placeholderImageSource no se proporciona.

![image](https://github.com/carlosduti70/react-native/assets/116099455/283f076d-f7a1-4dca-b0d3-ab488a9996c4)
![image](https://github.com/carlosduti70/react-native/assets/116099455/2e3c3db2-f575-484b-bac6-19aa11bd93c3)


Dentro de App.js en la variable de onReset se agrego para que al momento de reiniciar la iamgen tambien se borre el emoji para poner uno nuevo.

![image](https://github.com/carlosduti70/react-native/assets/116099455/d9590be4-2c69-4f56-ad06-806e50a0b4f1)
![image](https://github.com/carlosduti70/react-native/assets/116099455/bcb0523b-eb3e-414c-a9f8-3cdc6d3baa92)



Preguntas:

¿Qué problemas específicos de rendimiento o mantenibilidad se identificaron en la aplicación original?
El problema que yo encontre fue que al querer ingresar una nueva imagen el emoji anterior se quedaba en la pantalla.

¿Cómo se aseguró que el refactoring no afectara negativamente la funcionalidad existente?
Para eso se mantiene un commit del codigo original de modo que si los cambios dan error tienen un commit del proyecto de si funciona.

¿Qué mejoras de rendimiento y mantenibilidad se lograron con el refactoring?
Creo q no pude hacer eso para nada

¿Cuáles fueron los desafíos más significativos durante el proceso de refactoring y cómo se superaron?
encontrar la parte exacta donde cambiar el codigo.

¿Qué impacto tuvo el refactoring en la experiencia del usuario final?
mejora la experiencia de los emojis al poder poner uno nuevo.

¿Cómo se podrían aplicar las lecciones aprendidas en este proyecto a futuros proyectos de desarrollo y refactoring?
usando expo go para poder visualizar los cambios desde el movil.
usando librerias externas para poder facilitar la creacion del proyecto.
