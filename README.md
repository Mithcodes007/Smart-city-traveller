**Smart-City Traveller**

Smart-City Traveller is a Java-based application that helps users explore and navigate within a city using real-time map data. It integrates Google Maps APIs to provide routes, location searches, and navigation assistance through an intuitive interface.

**🚀 Features**

Real-time navigation and route mapping

Search for nearby points of interest

Google Maps integration for directions and geolocation

User-friendly mobile and web interfaces

Secure backend powered by Spring Boot and MySQL

**🧩 Tech Stack**
Component	Technology
Frontend	Android (XML), AngularJS
Backend	Java (Spring Boot)
Database	MySQL
APIs	Google Maps (Directions, Places, Geocoding)
IDEs	Eclipse, Android Studio


**⚙️ Setup & Installation**
Prerequisites

JDK 11+

Maven or Gradle

MySQL 8.x

Android Studio

Google Maps API key

Internet connection

**Steps**

Clone the repository

git clone https://github.com/Mithcodes007/Smart-city-traveller.git

cd Smart-city-traveller


Configure application.properties with your MySQL credentials and API key.

Build and run the backend:

mvn spring-boot:run


Open the Android module in Android Studio, update the API key and backend URL, then run the app on an emulator or device.

**⚡ Usage**

Launch the backend server.

Open the Android app or web interface.

Enter your current location and destination.

The app displays the optimal route using Google Maps services.
