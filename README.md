# Doctor-APP

:house:**Doctor-app**

### ***Framework***
---------
- spring boot

-------------

### ***Project management tool***
-------
- Maven


-----------------
### ***DataBase***
****************
- MySql
****************

### **use of dependency**
-----
- <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-data-jpa</artifactId>
      </dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-web</artifactId>
     </dependency>

- <dependency>
       <groupId>org.springframework.boot</groupId>
       <artifactId>spring-boot-devtools</artifactId>
	<scope>runtime</scope>
	<optional>true</optional>
	</dependency>
- <dependency>
    <groupId>com.mysql</groupId>
    <artifactId>mysql-connector-j</artifactId>
    <version>8.0.33</version>
 </dependency>

- <dependency>
       <groupId>org.projectlombok</groupId>
       <artifactId>lombok</artifactId>
       <optional>true</optional>
	</dependency>
- <dependency>
     <groupId>org.springframework.boot</groupId>
     <artifactId>spring-boot-starter-test</artifactId>
     <scope>test</scope>
     </dependency>
<!-- https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation -->
- <dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-validation</artifactId>
	<version>3.0.6</version>
	</dependency>





--------


-------------


### **Run tests**

------

⭕ postman 

:globe_with_meridians: chrome browser

********

### **Data structure And programming language**

-----

 - core java
 
 --------

  :point_down: **Summary**
*****
Appointment class represents an appointment made by a patient with a doctor. It has a composite key (AppointmentKey) consisting of appId (auto-generated ID) and time (appointment time). It has a many-to-one relationship with the Doctor class and a one-to-one relationship with the Patient class.

AppointmentKey class is an embeddable class used as a composite key for the Appointment class. It implements Serializable and consists of appId (auto-generated ID) and time (appointment time).

AuthenticationToken class represents an authentication token associated with a patient. It has an auto-generated tokenId, token (randomly generated token string), and tokenCreationDate. It has a one-to-one relationship with the Patient class.

Patient class represents a patient in the system. It has properties such as patientId, patientFirstName, patientLastName, patientEmail, patientPassword, and patientContact. It also has a one-to-one relationship with the Appointment class.

The code uses Lombok annotations (@Data, @NoArgsConstructor, @AllArgsConstructor) to generate getters, setters, constructors, and other common methods automatically. It also uses JPA annotations (@Entity, @Id, @GeneratedValue, @OneToOne, @ManyToOne, etc.) for mapping the classes to database tables and defining relationships.

The @JsonIdentityInfo annotation is used for JSON serialization to handle bidirectional relationships between entities without causing infinite recursion.

Overall, this code represents the data model for a doctor appointment booking system, including entities for appointments, patients, doctors, and authentication tokens.
*****

### **Show your Support** 
****
:star: Thankyou 

****
