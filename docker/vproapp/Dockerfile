FROM tomcat:8-jre11
LABEL "Author" = "Artem Udodov"
LABEL "Project" = "devopsclass"
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD rm -rf /usr/local/tomcat/webapps/ROOT && /usr/local/tomcat/bin/catalina.sh run 
VOLUME /usr/local/tomcat/webapps