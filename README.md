# Vehicle Breakdown Assistance

## Introduction

Imagine you are driving on the highway, and your car suddenly breaks down or you are end up with fuel. You're miles away from the nearest town and you have no help service. What do you do?

**Vehicle Breakdown Assistance** is an Android application designed to help users quickly find nearby mechanics during unexpected vehicle breakdowns. The app uses real-time location tracking with Google Maps and cloud-based Firebase services to connect users with service providers efficiently.

## Functional Requirements:
Main modules:
1.Sign-Up and log in.
2.Information of major Service stations/ petrol pumps near intercity roads and a database of their contacts.
3.SOS signal in case of availability of nearby help.
4.Pinpoint of the current location on GPS/ Integration of location service in-app.

Sign-Up and log in: 
1.First of all, the user (Mechanic/Helper, Customer) will encounter the login screen which requires the user to log in to the application.
2.The login system for each user (Mechanic/Helper, Customer) shows its dashboard correctly with appropriate functionality.
3.For new users, there will be an option to create an account on the login screen, which will lead the user towards the further process. 
4.Using email or phone numbers, it should be easy for customers to register and log in.
5.Forgot password and Remember me options should be available.

Customer dashboard:
1.The customer should be able to login into the application.
2.The customer should be able to add his basic information including name/ contact number/location/ Vehicle number. 
3.The customer should be able to access and pinpoint his/her current location inside the application.
4.Customers should be able to find any nearby help according to location.
5.The customer should be able to call/ SOS the helper via available information.
6.The customer can see the location and arrival time of the helper.

Helper dashboard:
1.Helpers should be able to login into the application.
2.Helpers should be able to add their information in their profile including name/contact number/location/specialty/ experience/vehicle number in case of vehicle help.
3.The helper should receive SOS/ call/ message sent by the customer.
4.The helper can see the location of the customer by accessing GPS in the application.
5.The helper can see the information of his/her approached customer.
6.The helper can update the task status once he/she helped the customer.

##  Features:
1. User and Mechanic Login with Firebase Authentication.
2. Mechanic Registration with name, phone, location, and service information.
3. Google Maps integration to display user and mechanic locations.
4. Real-time data storage using Firebase Realtime Database.
5. Mechanic profile image upload via Firebase Storage.
6. One-tap emergency call feature for quick help.
7. Image loading using Picasso library.

## Technologies:
1. Programming Language : Java
2. IDE                  : Android Studio
3. Database             : Firebase Realtime Database
4. Authentication       : Firebase Authentication
5. Storage              : Firebase Storage
6. Location Services    : Google Maps API
7. Image Handling       : Picasso Library
8. Permissions          : Permiso Library

## Conclusion:
Vehicle Breakdown Assistance provides a practical solution to a common real-world problem faced by vehicle owners. By combining Android technologies with cloud-based Firebase services and real-time location tracking, the app bridges the gap between stranded users and nearby mechanics. This project demonstrates effective use of mobile development, cloud integration, and user-centric design to improve emergency response on the road. It has strong potential for further enhancements like service ratings, real-time tracking, and multilingual support.

