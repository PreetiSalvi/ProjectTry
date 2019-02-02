FROM dpatriot/docker-awscli-java8
#RUN apt-get update 
#RUN apt-get install -y maven
#COPY pom.xml /usr/local/service/pom.xml 
#COPY src /usr/local/service/src
WORKDIR /usr/local/service
#RUN mvn package
CMD ["java","-cp","target/MavenHelloWorldProject-1.0-SNAPSHOT.jar","com.jcg.maven.App" ]

