myserveletsspringsecurity
=========================

Spring Security Example with HTTPServlet

This is a very simple Spring Security example, using a simple basic helloworld servlet which is protected by a basic authentication


Following are the steps to run the project

1. mvn jetty:run
run the url , and type user name as testuser and password as 123456 to test the url
url : http://localhost:8080/myserveletsspringsecurity

2. To Run from eclipse
a. mvn eclipse:eclipse -Dwtpversion=2.0
b. import project in eclipse as Existing Eclipse Project
c. make sure build automatically is selected
d. right click on project , and click on Run as --> Run on Server