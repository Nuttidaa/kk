# Smart Class Check-in & Learning Reflection App


## Project Description


Smart Class Check-in & Learning Reflection is a mobile application designed to help university students check in to class and reflect on their learning experience.



The system allows students to confirm their attendance using QR code scanning and GPS location verification. After class, students can record what they learned and provide feedback about the class.



This application is built using Flutter and can run on multiple platforms including mobile devices and web browsers.

## Features
Student Login (Email and Password)

Class Check-in with QR Code

GPS Location Recording

Mood Selection before Class

Learning Reflection after Class

Class Feedback Submission

Attendance History View

Technologies Used
Flutter

Local Storage / SQLite

QR Code Scanner

GPS Location Services

Firebase Hosting (for deployment)

## Project Structure


lib/



screens/

login_screen.dart

home_screen.dart

checkin_screen.dart

finish_screen.dart

history_screen.dart



services/

location_service.dart

qr_service.dart

storage_service.dart



models/

checkin_model.dart



main.dart

Setup Instructions
Install Flutter on your system.

Clone the repository from GitHub.



git clone 

Navigate to the project folder.



cd project-name

Install dependencies.



flutter pub get

Run the application.



flutter run

Running on Web (Chrome)


To run the app on Chrome:



flutter run -d chrome

Firebase Deployment


The project includes Firebase Hosting for deployment.



Steps:

Install Firebase CLI

Login to Firebase

Deploy project



firebase deploy
Deployed URL will be generated after deployment.
