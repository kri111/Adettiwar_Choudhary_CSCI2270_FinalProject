# Adettiwar_Choudhary_CSCI2270_FinalProject

# Summary
Krishna Adettiwar and Tanay Choudhary will be working together for the CSCI 2270 Final Project. For our project, we are going to design and build a program for the customers of mailing services (FedEx, UPS, USPS, etc.). We are going to primarily be working with doubly linked lists. We are going to first build a network of cities in which each node of the linked list represents a city. Depending on how the customer wants to send his/her package, details about the shipment will be given by the program. The customer can choose whether to do ground shipping or 2-day air shipping, and depending on which option is chosen, the path the package will take to reach its destination will change. The cost services within the program will also change accordingly. The cost will be dependant on the shipping type and weight. The program can be accessed as the administrator of the company or a customer. The admin password is "12345" and through this the user can build a network, edit it by adding or deleting a city or completely change it. As a customer they can chose to search through nodes and returns the linked list. Theres also a support function that uses a random integer as the phone number for different cities. 

# How to Run
Clone this repository. Depending on what compiler and program you are using, link the two .cpp and the one .h files together and run the program. If you are using CodeBlocks on Ubuntu, open CodeBlocks. Then, create a new project as a "Console Application." Then, copy and paste contents from the main.cpp file from Github into your new project main.cpp file. Then, create a new class called "mail" in CodeBlocks with no arguments. Copy and paste the contents of mail.h and mail.cpp files accordingly.

# Dependencies
This program relies on no third-party libraries. There are no dependencies. It should compile anywhere as long as the driver, header, and main file are linked and compiled together.

# System Requirements
Only tested on Ubuntu. Should compile anywhere though. If there are any issues are does not compile in a speific environment, please file an issue and we will try to resolve it.

# Group Members
Krishna Adettiwar, Tanay Choudhary

# Contributors
Github username: RaphaelHythloday

# Open Issues/Bugs
Currently, the phone number support feature (for customers) does not work reliably, but a fix is on the way.
