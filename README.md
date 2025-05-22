# Flight-Ticket-Booking-using-Java
This project is a console-based Flight Ticket Booking System developed in Java, designed to simulate the core functionalities of booking and cancelling flight tickets in real-time. It allows users to interact with a simple menu-driven interface to manage ticket reservations across multiple flights.

🚀 Features
✅ Book Tickets: Reserve flight tickets based on availability. Each booking generates a unique passenger ID.

❌ Cancel Tickets: Cancel existing bookings using passenger ID and receive a refund based on the original fare.

📋 Flight Overview: View real-time summaries of all flights, including current ticket prices, remaining seats, and passenger details.

💰 Dynamic Pricing: Ticket prices increase by ₹200 for every ticket booked, simulating real-world demand-driven pricing.

🧾 Refund System: Refunds are automatically calculated and displayed when bookings are cancelled.

🧠 How It Works
The system maintains:

A list of available flights

The number of available seats, passenger records, and booking details

When a booking is made:

The available ticket count is reduced

Ticket price increases dynamically

Passenger booking details are stored

Upon cancellation:

Ticket count is restored

Price is adjusted

Refund amount is calculated and displayed

🛠️ Technologies Used
Java (Core)

Object-Oriented Programming

ArrayLists for dynamic data management

Scanner for input handling

