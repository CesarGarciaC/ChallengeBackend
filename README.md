# ChallengeBackend

Respuestas:

1. Excepciones genéricas. Se deberían crear excepciones que permitan un mejor trazado del error.<br />
2. Conexiones a la BD no se están cerrando adecuadamente.<br />
3. No se utiliza un patrón adecuado para el manejo de las conexiones a BD. (Singleton)<br />
4. Se declaran variables inutilizadas.<br />
5. No se toman en cuenta los principios SOLID: <br />
    - Single Responsability (Una sola clase tiene muchas funcionalidades)<br />
    - Open/Close (El diseño no permite extensión)<br /><br />
6. Muchos parámetros por cada método<br />
7. Variables mal nombradas o que no otorgan descripción de para qué sirven o fueron creadas.<br />
8. Se ejecuta una funcion "trim()" pero no se asigna a la cadena, posible error de lógica.<br />
9. Mal manejo de credenciales para acceso a BD. Estas deberían de estar en un archivo properties o en un file system en el servidor.<br />
10. No se manejan excepciones para la manipulación de ficheros.<br />

# Ejecución

./mvnw clean test
