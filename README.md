✅ My First Stage of Learning Spring Boot

In the first stage of learning Spring Boot, I set up a new project in IntelliJ IDEA using Spring Initializr. While creating the project, I selected the Spring Web dependency, which allows me to build REST APIs easily.

After the project was created, I built a simple REST API using the @RestController and @GetMapping annotations. This API returns a simple message when accessed through the browser or Postman. I used the default Spring Boot server port 8080, which runs automatically when the application starts.

✔ Steps I followed
1. Setup Project Using Spring Initializr

Open IntelliJ IDEA → New Project → Spring Initializr
Project Type: Maven
Language: Java
Dependency Added: Spring Web
Project was then generated and opened in IntelliJ.

2. Created a Simple API

Inside the controller package, I created a class using @RestController and added a @GetMapping to return a simple message.

3. Started the Server on Port 8080

I run the main application file.
Spring Boot automatically started the embedded Tomcat server on
http://localhost:8080

4. Tested the API

I opened:
👉 http://localhost:8080
