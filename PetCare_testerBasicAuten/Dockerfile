# Imagen base de Java
FROM openjdk:17-jdk-slim

# Directorio de trabajo
WORKDIR /app

# Copiar el archivo JAR generado al contenedor
COPY target/tu-aplicacion.jar app.jar

# Puerto expuesto por tu aplicación
EXPOSE 8080

# Comando para ejecutar la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]
