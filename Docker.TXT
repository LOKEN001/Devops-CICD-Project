FROM openJdk:8
COPY jarstaging/com/valaxy/demo-workshop/2.1.2/demo-workshop-2.1.2.jar valaxy.jar
ENTRYPOINT ["java","-jar", "valaxy.jar"]