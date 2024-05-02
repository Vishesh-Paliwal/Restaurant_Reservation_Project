# **RESTAURANT RESERVATION SYSTEM**

This is a Spring boot Project , that handles the backend for Restaurent Reservation System .

It provides support for both Client side and Employee Management for the Restaurent .


# TO RUN PROJECT ON YOUR LOCAL SETUP :

First Fork and clone this repo . 

* Preffered IDE : IntelliJ , 

* Make all sure dependencies in POM.xml are in sync

* Make sure you Set up MySQL on your Local.

* Having Postman is also preffered for Testing Purposes

# Testing Your Set-Up 

  * Try creating a customer
    
          POST Request :

          localhost:8080/customers

          Pass Request Body :

          {
              "name" : "Deepak",
              "contactNumber" : "1234567890",
              "e-Mail" : "Deepak@Gmail.com"
          }

  * Try Getting All customers

          GET REQUEST :

          localhost:8080/customers

  * Try Getting customer with ID
   
          GET REQUEST :

          localhost:8080/customers/1

  * Update the Customer

          PATCH REQUEST :

          localhost:8080/customers/1

           Pass Request Body :

          {
              "name" : "Deepak",
              "contactNumber" : "1234567890",
              "e-Mail" : "Deepak@Yahoo.com"
          }

  * Delete a customer

          DELETE REQUEST :

          localhost:8080/customers/1




    
