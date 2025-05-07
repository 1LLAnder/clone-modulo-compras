# Usar una imagen base de Java
FROM openjdk:11-jre-slim

# Establecer el directorio de trabajo
WORKDIR /app

# Copiar el archivo WAR al contenedor desde la carpeta dist
COPY dist/ModuloCompras.war /app/ModuloCompras.war

# Exponer el puerto en el que se ejecutará la aplicación
EXPOSE 8080

# Comando para ejecutar la aplicación
CMD ["java", "-jar", "ModuloCompras.war"]
