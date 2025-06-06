FROM tomcat:9.0-jdk17-temurin

# Elimina las apps por defecto de Tomcat
RUN rm -rf /usr/local/tomcat/webapps/*

# Copia tu archivo WAR al directorio de despliegue de Tomcat
COPY UPOCulturaWEB.war /usr/local/tomcat/webapps/ROOT.war

# Expone el puerto por defecto de Tomcat
EXPOSE 8080

# Arranca Tomcat
CMD ["catalina.sh", "run"]

