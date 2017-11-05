# bitacora3
-  [Introducción](#introducción)
-  [Camilo](#camilo)
    -  [21 de octubre Camilo](#21_de_octubre)
    -  [22 de octubre Camilo](#22_de_octubre)
    -  [23 de octubre Camilo](#22_de_octubre)
    -  [24 de octubre Camilo](#24_de_octubre)
    -  [25 de octubre Camilo](#25_de_octubre)
    -  [28 de octubre Camilo](#28_de_octubre)
    -  [29 de octubre Camilo](#29_de_octubre)
    -  [31 de octubre Camilo](#31_de_octubre)
    -  [01 de noviembre Camilo](#01_de_noviembre)
    -  [02 de noviembre Camilo](#02_de_noviembre)
    -  [03 de noviembre Camilo](#03_de_noviembre)
    -  [04 de noviembre Camilo](#04_de_noviembre)    

## Introducción
En la siguiente entrega se realizaran planes de pruebas con Firebase (para diferentes dispositivos tanto fisicos como virtuales), Guerrilla Testing, Set de pruebas con Espresso y Espresso Record, ademas se utilizaron herramientas como Ranorex y TestComplete.

## Camilo
A contiuancion se presentan las pruebas realizadas por Camilo Forero.
### 21 de octubre Camilo
Se realizaron pruebas con firebase sobre 5 dispositivos fisicos de marca LG en su mayoria a la aplicacion Car Report, para los cuales se genero un error en un LG G3 con API 19. Al revisar el video y los screenshots generados por firebase no se puede determinar la causa del error y en el reporte este se atribuye a un error de infraestructura, dejando la prueba inconclusa:

![Alt text](/firebase_images/Firebase_tests_21-10-2017.jpg?raw=true "21 de octubre")

Tambien se hicieron pruebas a Open Source Billing de Behavior Driven Developmen con Cucumber, pero el tiempo de respuesta de la aplicacion excedi todos los timeouts configurados y no se pudieron ejecutar mas escenarios despues del login pues este nunca pudo ejecutarse correctamente. Dentro de este :

![Alt text](/firebase_images/open_sourceBilling_21-10-2017.jpg?raw=true "21 de octubre")


![Alt text](/firebase_images/error_open_sourceBilling_21-10-2017.jpg?raw=true "21 de octubre")

