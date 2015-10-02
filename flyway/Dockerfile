FROM java

RUN wget http://repo1.maven.org/maven2/org/flywaydb/flyway-commandline/3.2.1/flyway-commandline-3.2.1.zip && unzip flyway-commandline-3.2.1.zip -d /opt && chmod a+x /opt/flyway-3.2.1/flyway
ENV PATH $PATH:/opt/flyway-3.2.1
RUN mkdir /src
WORKDIR /src
