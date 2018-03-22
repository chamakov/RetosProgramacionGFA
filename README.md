# RetosProgramacionGFA

# Reto 1
**Desarrollar un sistema de autenticación implementando JWT**

El proposito del presente ejecicio es realizar el desarrollo de una API rest sencilla, misma que implementará el sistema de autenticación mediante Json Web Token (JWT), esto utilizando un lenguaje de programación un tanto reciente como lo es Golang.

**Caracteristicas a desarrollar en el ejercicio:**
1. Debe de ser desarrollado usando Golang
2. El motor de base de datos a usar debe de ser NoSQL (Se recomienda MongoDB)
3. El API rest debe de implementar los siguientes endpoints:
    * (POST) /api/authenticate para realizar la autenticación en el sistema
    * (POST) /api/sign-up para realizar el alta de usuarios
    * (GET) /api/users para obtener los usuarios registrados en la base de datos
    * (GET) /api/user/{id} para obtener un usuario en especifico
6. Los endpoints diferentes a "/api/authenticate" no deben de ser accesibles a menos de que se provea un JWT Valido.

**Tiempo disponible para el desarrollo del ejecicio:**

Del Viernes 23 de Marzo a las 18:30 Hrs al Domingo 25 de Marzo a las 23:59 Hrs.

**Metodo de entrega:**

Via Pull Request en Github, para más información acerca de como crear un pull request consultar el siguiente enlace:
https://help.github.com/articles/creating-a-pull-request/

**Pasos para integrar el ejercicio:**

1. Crear un nuevo branch en el repositorio
   * Dar click en el boton Branch: master  
   * Comenzar a escribir el nombre del nuevo branch a agregar usando la siguiente nomenclatura: primer letra del primer nombre + primer apellido ejemplo: jortega.
   * Una vez escrito el nombre aparecerá un botón indicando la creación del branch, es necesario dar click en el para generarlo
   * Una vez generado el branch, es necesario crear un nuevo archivo, para esto es necesario dar click en el botón "Create new File" para crear un readme con la información del participante
   * Es necesario indicar el nombre del archivo de la siguiente manera: RetosProgramacionGFA/primer letra del primer nombre + primer apellido/readme.md
   * Una vez indicado el nombre, es necesario colocar en el archivo los siguientes datos:
      -Nombre completo del participante
      -Coordinación a la que pertenece.
   * Ya que se haya llenado el archivo con la información requerida, solamente es necesario dar click en el boton "Commit new file" localizado al final de la página.
   
2. Subir el código fuente generado
   * Primeramente es necesario estar localizados en el branch que se genero en el punto anterior
   * Posteriormente es necesario ingresar a la carpeta generada en el punto anterior
   * Una vez dentro de la carpeta es necesario dar click en el botón "Upload Files" para subir el/los archivos generados para solucionar el reto (Puede ser un archivo zip con todos los archivos generados)
   * Una vez seleccionados los archivos, solamente es necesario dar click en el botón "Commit Changes" para subir los archivos
