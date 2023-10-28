 # Doctor_Appointment_Booking_System
  ![Screenshot (26)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/bf75ed16-69b1-4323-94cc-b6752d4099d5)
  

## Functionalities
- Admin Login
- Admin Dashboard
- Doctor Add
- Doctor Login
- Patient view
- Patient Login
- Appointment Booking

## Backend Work
- Manage Database for Doctor and Patient 
- Create Servlets for differnt Modules
- Proper Exception Handling
- Authentication using DataBase

## Tech Stacks
- Java
- Advance Java (Servlet,Jsp)
- Mysql
- BootStrap
- Tomcat
- Maven

## Db Configuration
````
  package com.Db;

import java.sql.Connection;
import java.sql.DriverManager;

public class DBConnect {

	private static Connection conn;

	public static Connection getConn() {
		try {
			Class.forName("com.mysql.cj.jdbc.Driver");
			conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/hospital_2", "root", "root123");

		} catch (Exception e) {
			e.printStackTrace();
		}

		return conn;
	}

}
````

## Project Snippets

### User Interface 
  ![Screenshot (26)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/bf75ed16-69b1-4323-94cc-b6752d4099d5)


### User Login
![Screenshot (27)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/5c1cc89c-761a-47c5-99c7-0574e2f637dd)

### User Appointment

![Screenshot (28)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/346206c1-58e5-4db7-9d2c-4ef9afec682c)



### Doctor Login
![Screenshot (29)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/5669130d-018e-4834-a107-f3c58bc52033)

### Admin Login

![Screenshot (30)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/9706c4f1-4bf3-446c-9c23-a3496c1c2d01)



### Patient Detail
![Screenshot (31)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/c82f4119-75bd-4a1f-a1ed-a60586ec2daf)


### Admin DashBoard
![Screenshot (32)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/5c52b5cc-9548-43a0-b33e-4e76bbfef3ea)


### Doctor Detail
![Screenshot (33)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/18524ba6-725a-4ae2-9e8f-a5a92a95287a)


### Add Doctor
![Screenshot (34)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/4b8fa76f-7f02-41a1-b187-ffbfcff25866)


### Admin Logout
![Screenshot (36)](https://github.com/arpit5220/Doctor_Appointment_Booking_System/assets/94009815/f977c5de-3fa8-40c9-b472-b762f127bbae)

