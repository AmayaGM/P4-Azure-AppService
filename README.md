# Practica 4 con "AppServices"

*Crear una pagina web con App Services*

**Paso 1 _App Services_**
- Poner en la barra de busqueda "App Service" y elegir la opcion 
![Paso 1](/imagenes/img1.png)

**Paso 2 _Crear App Services_**
- Primero debemos elegir el boton "Crear" 
![Paso 2](/imagenes/img2.png)

- Ir a datos basicos
  ![Paso 2.1](/imagenes/img2_1.png)

  - Debemos elegir en detalles del proyecto:
      - La suscripcion
      - El grupo de recursos previamente creado
      ![Paso 2.1.1](/imagenes/img2_1_1.png)

  - Debemos elegir en detalles de instancia:
      - Nombre con el que queremos llamar la apliacion web
      - Elegir si queremos codigo, contenedor docker o apliacion web estatica
      - El entorno de ejecucion, en este caso PHP 8.0
      - El sistema operativo
      - La region donde deseamos crearla
      ![Paso 2.1.2](/imagenes/img2_1_2.png)

  - Debemos elegir en el plan de app service:
      - El plan (podemos crear uno donde dice "crear nuevo")
      - El tamaño (Es posible modificarlo donde dice "Cambiar el tamaño", ahi podemos elegir el mas conveniente)
      ![Paso 2.1.3](/imagenes/img2_1_3.png)

- Ir a revisar y crear
  ![Paso 2.2](/imagenes/img2_1_4.png)

- Dar en crear
  ![Paso 2.3](/imagenes/img2_1_5.png)
      
**Paso 3 Abrir el recurso**
- Ir al grp de recurso
![Paso 3](/imagenes/img3.png)

- Ir a centro de implementacion
  ![Paso 3.1](/imagenes/img3_1.png)

- Seleccionar codigo fuente, en este caso GitHub e iniciar sesion
  ![Paso 3.2](/imagenes/img3_2.png)

- Posteriormente seleccionar la organizacion, el repositorio de donde se va clonar y la rama
    ![Paso 3.3](/imagenes/img3_3.png) 

- Damos en guardar
     ![Paso 3.4](/imagenes/img3_4.png)
     ![Paso 3.5](/imagenes/img3_5.png)
     
**Paso 4 Pagina web**
- Vamos a nuestro repositorio en Git en el apartado de "actions"
![Paso 4.1](/imagenes/img4.png)

- Ahi vamos a elegir la accion terminada
![Paso 4.2](/imagenes/img4_1.png)

- A continuacion damos clic en la url que ahi aparece
  ![Paso 4.3](/imagenes/img4_2.png)

- Podemos visualizar nuestra pagina web creada en azure
  ![Paso 4.4](/imagenes/img4_3.png)

>NOTA: Cualquier cambio realizado en el git de la pagina web, se vera reflejado automaticamente en mi Azure.
