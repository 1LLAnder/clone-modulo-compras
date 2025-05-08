# Usar una imagen base de Tomcat
FROM tomcat:9.0

# Establecer el directorio de trabajo
WORKDIR /usr/local/tomcat/webapps/

# Copiar el archivo WAR al contenedor
COPY ./dist/ModuloCompras.war ./ModuloCompras.war

# Exponer el puerto en el que se ejecutará Tomcat
EXPOSE 8080
