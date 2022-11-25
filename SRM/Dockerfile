FROM eclipse-temurin:17
ADD SmpleSRMCht.jar SmpleSRMCht.jar 
RUN mkdir -p /home/andy/logCollect/srm
RUN chmod -R 777 /home/andy/logCollect/srm
#CMD ["java", "HelloWorld"]
ENTRYPOINT ["java", "-jar", "SmpleSRMCht.jar"]
