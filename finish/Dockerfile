FROM ibmjava:8-jre  

COPY target/liberty/wlp /opt/ol/wlp

EXPOSE 9080 9081 9443
CMD ["/opt/ol/wlp/bin/server", "run", "defaultServer"]

