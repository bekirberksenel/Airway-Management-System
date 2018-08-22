# Airway-Management-System

Airway Schedule database holds the information of airplanes, employees schedules. It also keeps other important details such as passengers and airports. <br>
The airway database system consists of different parts. The airway database has different type of planes. Plane type has two children which are commercial one and passenger one. Commercial one keeps weight capacity and passenger plane keeps passenger capacity. Each plane must be related to plane type. Ech plane has unique plane ID. <br>
The airway db. Has also keeps track of person. Person has two sub-groups called employee and passenger. Passenger has a unique passenger ID. Employee has also three sub groups; pilots, hostesses and plane mechanics. Person keeps track of gender, name and unique ssn. Employee has start date and salary. There is relationship between person and planes. Passengers take tickets to fly on planes. Tickets have seat number, ticket number, from, to, time and date. Pilots drive both of commercial and passenger plane. Hostesses also host on plane. Plane mechanics take care of planes. Many plane mechanics take care of many planes. One pilot can drive one plane and many hostesses can host at one plane. <br>
There are also airports and schedules held in database. Airport has city and airport code. Schedules has two different sub groups called airplane Schedule and airport Schedule. Every airport has a airport Schedule based on that airway. Every airport has one airport Schedule and every plane has one airplane Schedule. <br> 

<hr>
<h2> How To Run Airway Management System </h2>  
<br> 
-	Below link download Java.  <br> 
https://www.java.com/tr/download/  <br> 
-	Below link download PostgreSQL and Pgadmin3  <br> 
https://www.postgresql.org/download/  <br> 
-	Create a database on Pgadmin. Name must be ”airwaydb”  <br> 
-	Create script on airwaydb  <br> 
-	Copy codes on “airwaydb.txt” and paste them to created script  <br> 
-	Now you can click the “airwaydb.jar” and start to use them.  <br> 
-	Write your Pgadmin user name and password on opened page. (If your port number is not 5432, enter yours.) 

<hr>





