# spring-security-authentication-autorization

Do the following things using Spring Security:

1. Secure your Spring MVC Web Apps 

2. Develop login page (default and custom) 

3. Define users and roles with simple authentication 

4. Protect URLs based on a role 

5. Use JSP tags to hide / show content based on role


The development process of Spring MVC Web App:

1. Add Maven Dependencies for Spring MVC Web App

2. Create Spring App Configuration (@Configuration) (Replacing spring-mvc-demo-servlet.xml )

3. Create Spring Dispatcher Servlet Initializer (replacing web.xml)

4. Develop Spring Controller

5. Develop JSP view page

The dependencies we need

1. spring-webmvc (spring-core, context, logging, AOP etc.)

2. jstl

3. javax.servlet-api

4. javax.servlet.jsp-api

Notice: We need to customize Maven build processs using the maven-war-plugin when we dont use web.xml.


More details about Spring Security:

http://www.zhangpeng-chen.com/2019/07/21/spring-security/

Spring Security Refenrence Manual:

https://docs.spring.io/spring-security/site/docs/current/reference/htmlsingle/
