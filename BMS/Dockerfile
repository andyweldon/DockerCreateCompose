FROM eclipse-temurin:17
ADD SmpleBMSCht.jar SmpleBMSCht.jar 
RUN mkdir -p /home/andy/logCollect/bm
RUN chmod -R 777 /home/andy/logCollect/bm
#CMD ["java", "HelloWorld"]
ENTRYPOINT ["java", "-jar", "SmpleBMSCht.jar"]
