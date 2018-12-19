---
layout: post
title:  "Application software Components !"
date:   2018-12-19 11:58:37
categories: Autosar update

description: Application software Components !
backgroundimg: /images/home.jpg
---

Application  layer of autosar can contain multiple applications,  which are called as application software compoents(ASWC).
 applications can interact with each other via RTE  (Intra ECU communication)or an application from one ECU to an application in an  another ECU with help of  RTE and goes via BSW and communication protocols (Inter ECU Communication).
 Application software components are the smallest uint with certain functionality associated with.
 
 
 Application software components has well defined ports for sending and receiving information and it has an entity called as runnable(in simple term- Function which is called in OS), helpful for receiving and sending information,invoking functionalities etc either cyclically or  event triggered.
 
 
 Ex:- Application 1 is sending data to application 2 
 
 
 - Application 1 runnable entity is configured with 10ms timing event- every 10 ms the data will be sending 
   from application 1 .
 - Application 2 runnable entity is configured with 20ms timing event-So once in every 20ms the data will be read by 
   Application 2.
 
 Types of  software components
 
 
   1-Automic Application software component
   2-Sensor or Actuator Software Component
   3-Composite Software Component
 
 Automatic Software Component
  
  
