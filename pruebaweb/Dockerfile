FROM tomcat:9.0-jdk11

# Borra las apps por defecto de Tomcat
RUN rm -rf /usr/local/tomcat/webapps/*

# Copia tu WAR a la carpeta webapps
COPY ./TuProyecto.war /usr/local/tomcat/webapps/ROOT.war
