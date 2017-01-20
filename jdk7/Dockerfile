FROM maven:3-jdk-7
ADD settings.xml /root/.m2/settings.xml

ENTRYPOINT ["/usr/local/bin/mvn-entrypoint.sh"]
CMD ["mvn"]

