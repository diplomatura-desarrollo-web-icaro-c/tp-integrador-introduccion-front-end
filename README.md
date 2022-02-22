# ICARO - INTRODUCCIÓN AL FRONT END

## Trabajo Integrador

Aquí están las consignas planteadas para la entrega del Trabajo Integrador de Introducción al Front End para la **Diplomatura Universitaria en Programación Web Full Stack** de Icaro.

### Maquetado de páginas de Inicio y Login 🏠👥

Se deberán crear dos vistas HTML con sus correspondientes hojas de estilo CSS. Éstas representarán dos páginas de nuestro Sitio Web.

- <u>Landing Page / Página de Inicio</u> 🏠
  
  - Este archivo llamado index.html representará el Home o Inicio de nuestra aplicación.
    
  - Deberemos utilizar un enfoque de tipo Mobile First y crear nuestras dos páginas pensadas para visualizarse desde un dispositivo móvil y luego realizar las adaptaciones necesarias para que se vea correctamente desde un monitor de computadora.
    
  - Deberá contar con tres grandes partes: un Header, un Main y un Footer
    
  - El Header tendrá dos secciones que se repartirán de manera vertical en modo mobile y horizontal para la vista de escritorio:
    
    - Un Logotipo en texto que leerá MyLandingPage
      
    - Una sección de navegación que contendrá links hacia cuatro secciones:
      
      1. Home
        
      2. Productos
        
      3. Login
        
      4. Contacto
        
  - El Main tendrá tres secciones principales:
    
    - Una sección de tipo banner que tendrá una imagen con un texto acompañatorio, que deberán mostrarse de manera vertical en vista mobile y horizontal para una vista de escritorio.
      
    - Una sección informativa, donde veremos dos pequeños bloques de texto con sus títulos correspondientes.
      
    - Una sección de comentarios con tres pequeños artículos que representarán cada comentario. Cada uno de estos tendrá un título, el comentario en sí, y finalmente el autor de dicho comentario.
      
      Estos se verán uno debajo del otro en una vista mobile y uno al lado del otro en monitores mayores a 900px.
      
  - Finalmente el Footer tendrá únicamente un mensaje centrado que leerá:
    
    - Todos los derechos reservados - MyLandingPage™
      

- <u>Login Page / Página de Login</u> 👥
  
  - Este archivo llamado login.html representará al Inicio de Sesión en nuestra aplicación.
    
  - Esta página deberá contener el mismo Header y Footer que la página de inicio, pero en su sección Main contendrá lo siguiente:
    
    - Un formulario de Inicio de sesión que deberá llevar los siguientes campos:
      
      1. **Nombre de usuario** - input de tipo text
        
      2. **Contraseña** - input de tipo password
        
      3. **Recordar Usuario** - input de tipo checkbox
        
      4. **Ingresar** - input de tipo submit
        
    - Cada input donde se tome datos del usuario deberá tener su label correspondiente y estos inputs deberán colocarse en una disposición acorde al tamaño de pantalla en que se visualice el formulario.
      
- Tanto el index.html como el login.html deberán estar estilizados siguiendo las buenas prácticas vistas en clase, respetando normas estéticas como los paddings, la alineación de los textos, la importancia semántica del peso de los textos y los colores, los colores de fondo, los tamaños y espacios en blanco de y entre los elementos, etc.
  
- También en esas hojas de CSS se deberán incorporar las reglas de estilos que permitan adaptar las páginas en sus distintas visualizaciones (mobile o desktop).
  
- Realizar el maquetado en HTML de ambas páginas, luego la adaptación de la estructura de los contenidos y alineación general según el tipo de dispositivo, y finalmente retocar y dar estilos con fines estéticos.
  

---

## Entrega 📬

- El formato de entrega será en este mismo repositorio, a través de una rama personalizada que se deberá llamar con el apellido del/los alumno/s precedido por el texto "*tp-intro-front*". Ej: _tp-intro-front-aguirre_ o *tp-intro-front-lescano-rivera-gonzalez*.
  
- Se deberá clonar o forkear este repositorio en su entorno local así se tiene la consigna disponible y ya queda seteado el remoto para empujar los cambios a medida que se vaya trabajando.
  Luego de clonarlo, se deberá crear inmediatamente una rama propia y desde allí comenzar a trabajar.
  

**IMPORTANTE** Tener cuidado de no modificar o editar la rama _master_, y de hacerlo, descartar los cambios en la misma para que a la hora de empujar los cambios no se envíen hacia aquí, para que la rama _master_ quede limpia y solamente contenga el _readme.md_. **NO EMPUJAR DESDE NI HACIA LA RAMA MASTER**

