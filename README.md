<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9aEIxRNmjmw3kDtnzU7-rLZ5kikuQzS1Cz_FBRIUYPg&s" alt="Italian Trulli">
<h1>Taxi Service</h1>
This project is simulating of taxi service where we can add, delete cars, manufactures, drivers and assign dtivers to 
car and realised login and logout logic which don`t allow unregistered users change or see some details.
<h2>Features</h2>
<ul>
<li>Authentication</li>
<li>Create and delete drivers</li>
<li>Create and delete cars</li>
<li>Create and delete car manufacturer</li>
<li>View all cars of the current driver</li>
<li>Add drivers to specific cars</li>
</ul>
<h2>Getting Started</h2>
<ul>
<li>Firstly you should copy repository to your local machine</li>
<li>Replace values in ConnectionUtil to your data</li>
<li>Then run Mysql server and /init_db.sql file</li>
<li>Deploy the generated WAR file to servlet container such as Tomcat</li>
</ul>
<h2>Structure</h2>
<ul>
<li>controller - Servlets that contains requests and responces</li>
<li>dao - Classes which contains all requests to database</li>
<li>exception - Just simple custom exceptions</li>
<li>model - Classes which describe objects as Car, Driver, Manufacturer</li>
<li>service - Service interfaces and their implementations that perform business logic</li>
<li>util - Utility class to create a database connection</li>
<li>resources - Files such as database scripts and configuration files</li>
<li>webapp - Contains web resources such as CSS, and JSP files</li>
<li>WEB-INF - Contains files for the web application</li>
<li>views - Contains JSP pages of project</li>
</ul>
<h2>Used Technologies</h2>
<ul>
<li>Java v.17.0.5</li>
<li>Maven v.3.8.6</li>
<li>JDBC v.4.2</li>
<li>MySql v.8.0.24</li>
<li>Java Servlets v.4.0.1</li>
<li>Tomcat v.9.0.73</li>
</ul>
<h2>Author</h2>
Andrew Kluchnik
