FROM jboss/wildfly:24.0.0.Final

COPY ./startup.sh /opt/startup.sh
#COPY ./standalone.xml /opt/jboss/wildfly/standalone/configuration/standalone.xml
USER root
RUN chmod +x /opt/startup.sh

CMD ["/opt/startup.sh"]