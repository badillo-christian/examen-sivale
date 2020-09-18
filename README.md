# examen-sivale

El candidato deberá crear una app web con las siguientes caracteristicas:

1. Se debera de construir en capas y al menos debera de contener la capa de vista y la capa de servicios.
2. Para la capa de vista se requiere:
      a)  que las vistas implementadas sean responsivas.
      b)  que se desarrollen haciendo uso de angular y typescript.
      c)  que contenga un componente de validacion de los campos de entrada.
      d)  la capa de vista debera de consumir una serie de servicios de negocio a manera de API.
3. Para la capa de servicios:
      a) Debera esta APIficada
      b) Debera utiliza un mecanismo de tickets para su autenticacín y autorizacion.
      c) Debera estar desarrollada total y completamente en Spring haciendo uso de springboot y springsecurity
      d) Dicha capa debera estar isolada de la capa de vista.
      e) para la persistencia se debera de crear una base de datos preferentemente H2, la cual debera inicializarse automaticamente al compilar e instalar la capa de servicios.
      f) la capa de persistencia se debera utilizar el JPA.
      g) Debera estar desarrollada en java 8
      
Consideraciones generales:
  * Se verificaran buenas practicas de codificacion.
  * ambas app (front y servicios) deberan estar construidas en maven.
  * se validara buenas practicas y no se revisara codigo no documentado.
  * deberan de proporcionar los comandos maven para la construccion y despliegue de los mismos.
  * para la entrega del mismo deberan de enviar un correo a bamx@praxis.com.mx con copia a begx@praxis.com.mx el cual debera contener
    la URL del repositorio con el codigo en github.
    Dicho repositorio debera agregar como colaborador de proyecto al correo: christian.badillo@gmail.com para la revision del mismo.
    
 Funcionalidad requerida:
 
  *Formulario de Registro de usuario. (nombre, apellido, edad (numerico) , sexo (combo), correoelectronico, contraseña) (todos los campos deberan ser validados)
  *Listado de usuarios registrados.
  *Pantalla de Login.
    -La pantalla de login debera de tener un boton para el registro de usuario.
    -una vez que el usario haga login (validacion previa de correo y contraseña) en la app se debera de mostrar el listado de los usuarios registrados.
  
 
 
  
  
    

      
