Flight Booking System
Description

A command-line airline reservation system written in C, allowing users to browse flights, reserve seats, apply discounts, and generate receipts.

This project demonstrates low-level programming, arrays, functions, input validation, loops, and string handling while simulating a real-world booking system.

Features

User login with predefined credentials (Username: STUDENT, Password: TAFT2401)

Browse available flights with details: origin, destination, time, seats, and price

Reserve tickets with seat selection

Apply discounts:

Senior Citizen / PWD (20%)

Manager’s Discount (30%)

No discount

Multiple payment methods: Cash or Card

Generates detailed receipts including:

Flight number

Seats booked

Original price, discount applied, final price per seat

Total amount

Tracks seat availability to prevent overbooking

Technologies & Skills

Language: C

Concepts: Arrays, functions, loops, input validation, string handling

Tools: Terminal / command-line interface

Installation & Running

Clone the repository:

git clone https://github.com/niki623/Flight-Booking-System.git


Navigate into the project folder:

cd Flight-Booking-System


Compile the program (example using GCC):

gcc flight_booking.c -o flight_booking


Run the program:

./flight_booking   # Linux/macOS
flight_booking.exe # Windows

Usage

Login with username and password

View available flights and select a flight code

Enter the number of seats to book

Choose discount type (if applicable)

Select payment method: Cash or Card

View generated receipt
