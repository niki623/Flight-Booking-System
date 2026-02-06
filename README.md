# Flight Booking System

## Description
A command-line airline reservation system written in **C**, allowing users to browse flights, reserve seats, apply discounts, and generate receipts.

This project demonstrates low-level programming, arrays, functions, input validation, loops, and string handling while simulating a real-world booking system.

---

## Features
- User login with predefined credentials:  
  - **Username:** STUDENT  
  - **Password:** TAFT2401
- Browse available flights with details: origin, destination, departure/arrival time, available seats, and price
- Reserve tickets with seat selection
- Apply discounts:  
  - Senior Citizen / PWD (20%)  
  - Manager’s Discount (30%)  
  - No discount
- Multiple payment methods: Cash or Card
- Generate detailed receipts including:  
  - Flight number  
  - Seats booked  
  - Original price, discount applied, final price per seat  
  - Total amount
- Tracks seat availability to prevent overbooking

---

## Technologies & Skills
- **Language:** C  
- **Concepts:** Arrays, functions, loops, input validation, string handling  
- **Tools:** Terminal / command-line interface

---

## Installation & Running
1. Clone the repository:  
```bash
git clone https://github.com/niki623/Flight-Booking-System.git
```
2. Navigate into the project folder:
```bash
cd Flight-Booking-System
```
3. Compile the program (example using GCC):
```bash
gcc flight_booking.c -o flight_booking
```
4. Run the program:
```bash
./flight_booking   # Linux/macOS
flight_booking.exe # Windows
```
## Usage
1. Login with username and password  
2. View available flights and select a flight code  
3. Enter the number of seats to book  
4. Choose discount type (if applicable)  
5. Select payment method: Cash or Card  
6. View the generated receipt
