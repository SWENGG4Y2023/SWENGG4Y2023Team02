# Software Requirement Specification

## Table of Contents
-  [1. Introduction](#1-introduction)
   - [1.1 Purpose](#11-purpose)
   - [1.2 Document Conventions](#12-document-conventions)
   - [1.3 Intended Audience and Reading Suggestions](#13-intended-audience-and-reading-suggestions)
   - [1.4 Project Scope](#14-project-scope)
   - [1.5 Scope](#15-references)
- [2. Overall Description](#2-overall-description)
   -  [2.1 Product Perspective](#21-product-perspective)
   -  [2.2 Product Features](#22-product-features)
   -  [2.3 User Classes and Characteristics](#23-user-classes-and-characteristics)
   -  [2.4 Operating Environment](#24-operating-environment)
   -  [2.5 Design and Implementation Constraints](#25-design-and-implementation-constraints)
   -  [2.6 User Documentation](#26-user-documentation)
   -  [2.7 Assumptions and Dependencies](#27-assumptions-and-dependencies)
-  [3. System Features](#3-system-features)
   -  [3.1 Admin Features](#31-admin-features)
   -  [3.2 User Features](#32-user-features)
   -  [3.2 Trainer Features](#33-trainer-features)
-  [4. External Interface Requirements](#4-external-interface-requirements)
   -  [4.1 User Interface Requirements](#41-user-interface-requirements)
   -  [4.2 Hardware Interface Requirements](#42-hardware-interface-requirements)
   -  [4.3 Software Interface Requirements](#43-software-interface-requirements)
   -  [4.4 Communication Interface Requirements](#44-communication-interface-requirements)
-  [5. Nonfunctional Requirements](#5-nonfunctional-requirements)
   -  [5.1 Performance Requirements](#51-performance-requirements)
   -  [5.2 Safety Requirements](#52-safety-requirements)
   -  [5.3 Security Requirements](#53-security-requirements)
   -  [5.4 Software Quality Attributes](#54-software-quality-attributes)
-  [6. Other Requirements](#6-other-requirements)
## 1. Introduction

   - ### **1.1 Purpose**
      Fitbit Health & Fitness App provides the benefits of streamlined operations, enhanced
      fitness activity tracking and more. Fitbit Health & Fitness App Service is powerful, flexible and easy to use and is designed and developed to deliver real conceivable benefits to fitness enthusiasts.
   - ### **1.2 Document Conventions**
      Fitbit makes use of the following conventions: 
      Conventions | Definition
      ----------- | -----------
      RAM         | Random Access Memory 
      Members     | Person who is using the services of the gym and the mobile application 
      Stakeholders| Any person with an interest in the project who is not a developer 
      Trainers    | A person who teaches fitness skills to people, prepares them for workout activities, and motivates the users to reach their fitness goals 
      Android     | A mobile devices operating system designed by Google Inc. 
      iOS         | An operating system created and developed by Apple Inc. 
      GHz         | Gigahertz 



   -  ### **1.3 Intended Audience and Reading Suggestions**
      Developers: to be sure they are developing the right project that fulfils requirements provided in this document. 

      Testers: to have an exact list of the features and functions that must respond according to requirements and provided diagrams. 

      Users: to get familiar with the idea of the project and suggest other features that would make it even more functional. 

      Documentation writers: to know what features and in what way they must explain. What security technologies are required, how the system will response in           each user’s action etc. 

      Admin, Trainers and Customers: to know exactly what they must expect from the system, right inputs and outputs and response in error situations.

   -  ### **1.4 Project Scope**
      This system is aimed to give better out look to the user interfaces and to provide wellness information to the customers. This project is a mobile application where users can access the application while doing any physical activity. The main purpose of this system is to make users know their physical activity benefits and encourage them to work out more. This application can help users to track their fitness activities like how much calories they have burned, steps they have taken, distance they have walked, heart rate tracking etc. This application can help users who have joined gym recently in making their AI enabled workout schedule and help them in defining their fitness goal. It can also help in developing a diet and nutrition chart based on the current fitness condition of the user. The user can either be a consumer of fitness details or fitness consultant, a user can be fitness consultant only when its certification is verified. Once the user is verified as consultant, they can provide consultations to other users either for free or for a charge depending upon them and can share information with them. The consultation will be of either 30 minutes or 1 hour duration and users can rate the consultants based upon their liking. 

   -  ### **1.5 References**



##  **2. Overall Description**

   - ### **2.1 Product Perspective**
This Mobile App is an independent system designed to handle various activities related to a gym, including exercises, generating customer reports, managing trainers, and handling administrative issues. The system stores all records in a centralized database, which can only be accessed by authorized users with unique IDs and specific permissions. To ensure data integrity, users are not permitted to modify records belonging to other customers. Additionally, the system offers data recovery options in case of any lost data.
   -  ### **2.2 Product Features**
Fitbit is an app that provides fitness and wellness advice to its users through a set of exercise activities, nutritional diet charts, and even real-time health coaching. The app utilizes artificial intelligence, machine learning, and other technologies to provide personalized fitness programs to customers.
The major feature of our app includes:

  -  Footstep & Activity Tracker
  -  Heart Monitoring                             
  -  Water & Sleep Tracker
  -  BMI Calculator
  -  Altimeter - for tracking stairs climbed
  -  Online consultation with trainers
  -  Helps to Monitor Diet
  -  AI-enabled workout schedule
      
   -  ### 2.3 **User Classes and Characteristics**
Our app is available for download on both the Play Store for Android devices and the App Store for Apple devices. The app is designed to cater to three types of users: Trainers, Members, and Administrators.

   - Trainers:
       These are the users who can create and share workout schedules and activities for our customers. To ensure quality service, Trainers are required to possess at least a basic certification as an instructor.
   -  Members:
These are the individuals who are interested in improving their lifestyle and seeking guidance from our verified trainers. These individuals can access a range of consultation services through our app to achieve their fitness goals.
   -  Administrators:
The role of an Administrator in our app is to have complete access to all users, including both Customers and Trainers, as well as AI-generated workouts. Administrators should possess a sound understanding of health and fitness to ensure that they can effectively verify a Trainer's profile.


 -  ### **2.4 Operating Environment**
Fitbit will be used over smartphones:
           
           Android: Lollipop 5.1.0 or above
           IOS: 12.0.0 or above
           RAM: 512MB or above


 -  ### **2.5 Design and Implementation Constraints**
We intend to develop a mobile application as our desired solution, using Flutter for the user interface and MySQL database for data storage and management. Additionally, we will be utilizing Firebase to track daily customer interactions and to provide notifications to both our members and trainers.

   -  ### **2.6 User Documentation**
   User documentation for Fitbit includes a range of materials that are designed to help users understand how to use and get the most out of their Fitbit device and app. Some of them are as follows:

   - Quick start guide: This document provides a brief overview of the Fitbit device and how to set it up for use.

   - User manual: The user manual provides more detailed instructions for using the Fitbit device and app, including how to track activity, set goals, and use advanced features.

   - Online help center: Fitbit provides an online help center that includes articles and tutorials on how to use specific features of the app and device, as well as troubleshooting tips and frequently asked questions.
    
   - In-app help: The Fitbit app also includes in-app help, which can be accessed from within the app itself to provide users with real-time guidance on how to use specific features.

Community forums: Fitbit also maintains community forums where users can ask questions, share tips and advice, and connect with other Fitbit users.

   -  ### **2.7 Assumptions and Dependencies**
    
       -  Performance: It may include performance requirements for the  app, such as response time, scalability, and availability.
       -  User Base: It is assumed that the app is having enough pre-joined trainers who can deal with the newly joined members.
       -  Pre Knowledge :It is assumed that the administrator should have good knowledge of fitness and health so that they can validate the trainer’s profile.
       -  Platform: It is assumed that the platform on which the gym app will run, such as iOS or Android.
       -  User Interface: It is assumed that a user interface design for the gym app, including a color scheme, logo, and overall layout.
       -  Integration: Integration with other third-party services, such as fitness tracking devices, payment gateways, and social media platforms is assumed.
       -  Security: The SRS document may assume security features for the app, such as secure login, data encryption, and access control.
       -  Maintenance: The SRS document may assume maintenance requirements for the gym app, such as bug fixing, software updates, and technical support.



## 3. System Features

   - ### **3.1 Admin Features**

   The features that are available to the Admin are:  

   -   Admin can Add / Delete / Update Trainers and Customer details.  
   -   Admin has all rights to view the details of users.  
   -   Admin can also view Transaction Details and update fitness membership packages with the trainers. 
   -   Validate and verify trainers based upon their certification and feedback.

   - ### **3.2 User Features**

   The features that are available to the users are  

   -   Can view profile history and details  
   -   Makes inquiries and can take training membership.  
   -   Can schedule a fitness consultancy session. 
   -   Can view their past fitness records. 
   -   Can create their self-fitness goals. 
   -   Can give feedback to the trainers. 
   -   Can provide feedback to the trainers and the fitness consultants 
  
   - ### **3.3 Trainer Features**

   The features that are available to the Trainer are:  

   -   Trainer can view Member details who have subscribed to them.  
   -   Accept or reschedule consultancy sessions with the users. 
   -   Provide their fitness work-out details to the users. 
   -   Can charge fees from the subscribed user. 
   -   Trainers can also add blogs and videos about their activities. 

## 4. External Interface Requirements
   - ### **4.1 User Interface Requirements**
   
      Fitbit is designed to provide a user-friendly and engaging experience for users to access and manage their fitness data. The app is customizable, easy to navigate, and visually appealing, with features such as notifications and integrations with other apps to keep users motivated and engaged. The app is also accessible to users with disabilities and support multiple languages.

      - Easy navigation:** The Fitbit app should have an intuitive interface that is easy to navigate, with clear labeling of features and options.
      - Customization:** The user interface should allow users to customize their experience, such as choosing which metrics to track or setting personal goals.
      -  Visual feedback:** The app should provide clear visual feedback, such as charts and graphs, to help users track their progress and understand their fitness data.
      -  Notifications:** The app should provide notifications, such as reminders to move or congratulatory messages for hitting goals, to help motivate and engage users.
      -  Integration with other apps:** The app may integrate with other health and fitness apps, such as calorie trackers or meditation apps, to provide a comprehensive view of a user's health and wellness.
      -  Accessibility:** The app should be accessible to users with disabilities, with features such as high contrast mode or voice command options.
      -  Multilingual support:** The app should support multiple languages to make it accessible to users around the world.


   -  ### **4.2 Hardware Interface Requirements**
   
      This system doesn’t require any specific hardware interface. The one used here is a smartphone. The system should have these hardware requirements    minimum of:  

         -  Processor: Any processor with 1.5GHz speed 
         -  Android: Lollipop 5.1.0 or above 
         -  IOS: 12.0.0 or above 
         -  RAM: 512MB or above 
         -  Memory: 4GB or above 
     
   -  ### **4.3 Software Interface Requirements**
      
         -  Operating System: Windows 11 
         -  Front End: Flutter, Dart Programming Language. 
         -  Back End: MySQL, C++ 
      
   -  ### **4.4 Communication Interface Requirements**
   
      - Bluetooth connectivity: Fitbit devices use Bluetooth to connect to a user's mobile device, allowing for data to be synced between the device and the Fitbit app.

      - Wi-Fi connectivity: Fitbit devices may also be able to connect to Wi-Fi networks for more seamless data syncing and to access additional features such as music streaming and app updates.

      - USB connectivity: Fitbit devices may also be able to connect to a user's computer via USB cable to update firmware or transfer data.

      - Mobile app interface: The Fitbit app provides a user-friendly interface for users to access and manage their fitness data, set goals, and track progress. The app may also offer social features, guided programs, and third-party integrations.

      - Web interface: Fitbit also provides a web interface that allows users to access and manage their data, as well as to purchase new devices and accessories.

      - Notifications: Fitbit devices and app may use notifications, such as push notifications, to communicate with users about activity progress, reminders, and other updates.
      
## **5. Nonfunctional Requirements**

   -  ### **5.1 Performance Requirements**
   -  ### **5.2 Safety Requirements**
   -  ### **5.3 Security Requirements**
   -  ### **5.4 Software Quality Attributes**

## **6. Other Requirements**
