# ChallengeBackend

Respuestas:

Excepciones genéricas. Se deberían crear excepciones que permitan un mejor trazado del error.
Conexiones a la BD no se están cerrando adecuadamente.
No se utiliza un patrón adecuado para el manejo de las conexiones a BD. (Singleton)
Se declaran variables inutilizadas.
No se toman en cuenta los principios SOLID: 
    - Single Responsability (Una sola clase tiene muchas funcionalidades)
    - Open/Close (El diseño no permite extensión)
Muchos parámetros por cada método
Variables mal nombradas o que no otorgan descripción de para qué sirven o fueron creadas.
Se ejecuta una funcion "trim()" pero no se asigna a la cadena, posible error de lógica.
Mal manejo de credenciales para acceso a BD. Estas deberían de estar en un archivo properties o en un file system en el servidor.
No se manejan excepciones para la manipulación de ficheros.
