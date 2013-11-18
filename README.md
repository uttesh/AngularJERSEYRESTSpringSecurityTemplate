AngularJS JERSEY REST SpringSecurity Template
=======================================

Basic template for web application with front end angularJS framework and REST as backend with spring security, With Bootstrap 3.0 css and fontAwesome


Technologies
============

1. Java 1.6
2. Spring 2.3.4
3. Spring Security 2
4. Jersey REST
5. Json
6. Angularjs
7. Jquery
8. Bootstrap 3.0 css
9. FontAwesome
10. Maven


 This template provide the spring security login i.e no need to implement the role base code, By using spring security plugin we can achieve the role base implementation for application.
 here frontend is handling by angularjs, i took angularjs seed sample and modified with Spring implemetation with jersey.
 
 
Flow 
=====

Admin Role : admin can view all pages and components
User Role : user can view/action related user role only.

   Login credentials for admin : admin/admin , user : user/user
   
   when admin login it will load LoginController of app.js which angularjs controller and using $resource tag of angular which will call the spring jerseycontroller class and which validate the user with role.
   

Test 
=====

  URL : http://localhost:8080/AngularRESTSpringSecurity/#!/login
  
  
   



