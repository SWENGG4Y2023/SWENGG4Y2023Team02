# Software Requirement Specification

## Table of Contents
-  [1. Introduction](#1-introduction)
   - [1.1 Purpose](#11-purpose)
   - [1.2 Document Conventions](#12-document-conventions)
   - [1.3 Intended Audience and Reading Suggestions](#13-intended-audience-and-reading-suggestions)
   - [1.4 Intended Use](#14-project-scope)
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
   -  [3.1 Functional Requirements](#31-functional-requirements)
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

   - ### **1.2 Document Conventions**

   -  ### **1.3 Intended Audience and Reading Suggestions**

   -  ### **1.4 Project Scope**

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

-  Trainers
Trainers are the users who can create and share workout schedules and activities for our customers. To ensure quality service, Trainers are required to possess at least a basic certification as an instructor.
-  Members
These are the individuals who are interested in improving their lifestyle and seeking guidance from our verified trainers. These individuals can access a range of consultation services through our app to achieve their fitness goals.
-  Administrators
The role of an Administrator in our app is to have complete access to all users, including both Customers and Trainers, as well as AI-generated workouts. Administrators should possess a sound understanding of health and fitness to ensure that they can effectively verify a Trainer's profile.


 -  ### **2.4 Operating Environment**
Fitbit will be used over smartphones:
     -  Android: Lollipop 5.1.0 or above
     -  IOS: 12.0.0 or above
     -  RAM: 512MB or above


 -  ### **2.5 Design and Implementation Constraints**
We intend to develop a mobile application as our desired solution, using Flutter for the user interface and MySQL database for data storage and management. Additionally, we will be utilizing Firebase to track daily customer interactions and to provide notifications to both our members and trainers.

   -  ### **2.6 User Documentation**

   -  ### **2.7 Assumptions and Dependencies**
    
       -  Performance: It may include performance requirements for the  app, such as response time, scalability, and availability.
       -  User Base: It is assumed that the app is having enough pre-joined trainers who can deal with the newly joined members.
       -  Pre Knowledge :It is assumed that the administrator should have good knowledge of fitness and health so that they can validate the trainer’s profile.
       -  Platform: It is assumed that the platform on which the gym app will run, such as iOS or Android.
       -  User Interface: It is assumed that a user interface design for the gym app, including a color scheme, logo, and overall layout.
       -  Integration: Integration with other third-party services, such as fitness tracking devices, payment gateways, and social media platforms is assumed.
       -  Security: The SRS document may assume security features for the app, such as secure login, data encryption, and access control.
       -  Maintenance: The SRS document may assume maintenance requirements for the gym app, such as bug fixing, software updates, and technical support.


      **Assumptions:**

      **Dependencies:**


## 3. System Features

   - ### **3.1 Functional Requirements**

## 4. External Interface Requirements
   - ### **4.1 User Interface Requirements**

   -  ### **4.2 Hardware Interface Requirements**
     
   -  ### **4.3 Software Interface Requirements**
      
   -  ### **4.4 Communication Interface Requirements**
     
## **5. Nonfunctional Requirements**

   -  ### **5.1 Performance Requirements**

   -  ### **5.2 Safety Requirements**
 
   -  ### **5.3 Security Requirements**

   -  ### **5.4 Software Quality Attributes**

## **6. Other Requirements**
