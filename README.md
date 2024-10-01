Project from course Docker for Java Developers- John Thompson • 500,000+ Enrollments Worldwide - Udemy: https://www.udemy.com/course/docker-for-java-developers/

# Running project
- The first step is to change the <docker.image.prefix> in the pom.xml file to match your Docker Hub account
  ![image](https://github.com/user-attachments/assets/9f69f59c-5236-40dc-b8b2-66be3ad02a53)

- The second step is to add Docker properties to the settings.xml file from Maven. In my case, I modified the settings.xml file locally on my computer, not through the IDE, as I am using Eclipse.

![image](https://github.com/user-attachments/assets/909a8076-a5c0-479b-bc90-c053dfb434f2)

- Click on 'Open File' and add the Docker properties to the settings.xml file from Maven inside tag <servers>.

  ![image](https://github.com/user-attachments/assets/e5a7c594-28f8-4163-bfe1-09c6ef29be30)

- Run this command ``mvn clean package docker:build docker:push`` to send image to dockerhub
  
  ![image](https://github.com/user-attachments/assets/89910383-5fbf-4a68-92c3-82c1b6620a83)

- Now, check if the image has been pushed to Docker Hub.

  ![image](https://github.com/user-attachments/assets/98307d1c-c677-4fac-878f-ef71db2ffce2)


#Spring Boot and Docker

Source code in this repo is to support my on line course for Docker and Spring Boot. 

You can learn more about my course [here](http://courses.springframework.guru).
