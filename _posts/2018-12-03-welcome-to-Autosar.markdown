---
layout: page
title:  "Introduction to Autosar !"
date:   2018-12-03 10:58:37
categories: Autosar update

description: Introduction to Autosar!
backgroundimg: /images/about.jpg
---
Automotive open system architecture(AUTOSAR) is the standardised architecture developed by some of the leading automotive companies to develop automotive softwares for ECUs.
Autosar has developed in order to abolish the application software component dependancy with the underlying hardware, so that the 
application can be indipendantly developed without worrying about the poratability to any hardware.

Autosar architecture is divided in to 3 layers

   1. Application
   2. Run time environment (RTE) 
   3. Basic software (BSW)
   
   ![](/images/autosar_basic/autosar_Snip1.jpg)
    
  Application:-
> Application layer can have many application software components (ASWC) which are interacting to the hardware with the help of a virtual
> function bus called as RTE.
> In Autosar the application software components are developed irrespective of the hardware (ECU).
    
  Run Time Environment:-
> RTE provides an interface (virtual function bus) to interact any application to the BSW/application for intra ECU and inter ECU 
> communication.
    
  Basic Software component:-
 > Basic software is divided in to-Service layer, ECU abstraction layer,Micro controller abstraction layer and Complex device drivers.
 > There are multiple components in the  BSW layers which are required  for the proper data transmission and reception.

