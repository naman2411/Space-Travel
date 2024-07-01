# Space Travel System

## Overview

The Space Travel System (STS) is a C++ project that simulates a commercial space travel booking system using Object-Oriented Programming (OOP) concepts. This system allows travellers to book tickets to various planets, manage bookings, and view travel details. The system supports different types of travellers, including Astronauts, Passengers, and Commanders, each with unique attributes and functionalities.

## Features

### Traveller Management

- **Booking Tickets:** Travellers can book tickets to a specified planet from a source planet on a specified date, with an optional return ticket.
- **Ticket Validity:** Each ticket has a default validity of ten years. Astronauts and Commanders have infinite ticket validity.
- **Identification Numbers:** Travellers set their identification numbers, and each travel is assigned a unique identity number upon creation.
- **Ticket Operations:** Travellers can book, delete, and update tickets. They can also print or view ticket details, including the traveller's name and ID.

### Types of Travellers

- **Astronauts:** Have years of experience and a unique license ID. They also possess flying or space travel licenses.
- **Commanders:** Have an authority field and can check upcoming travel details.
- **Passengers:** Regular travellers with standard ticket validity.

### Space Travel Class

- **Traveller List:** Maintains a list of up to 10 travellers, including one Astronaut and one Commander per travel.
- **Methods:** Includes methods to add travellers, list all travellers, set and update Astronaut and Commander IDs. A Space Travel object is created only when more than two passengers book a ticket for the same travel itinerary.

### Ticket Class

- **Validity Check:** Ensures passenger validity before booking a ticket.
- **Price Calculation:** Determines ticket price based on the travel date and distance between planets.
- **Operations:** Includes methods to book, delete, update, and print/view tickets.

### Planet Class

- **Attributes:** Includes planet name and coordinates (x, y, z).
- **Methods:** Includes a method to get coordinates and creates different planets for travel purposes.

## Implementation Details

### Universe Setup

- Created a universe with at least three planets.
- Created 15 passengers, including two astronauts and two commanders.

### Booking Process

- Each travel has one astronaut and one commander assigned.
- Implemented functionality to check and prevent travel conflicts for astronauts and commanders (bonus feature).

### Additional Features

- Added various attributes for planets (optional enhancement).
- Ensured no conflicts in the schedules of astronauts and commanders, cancelling travel if no available personnel are present (bonus feature).

## Conclusion

This project demonstrates the use of C++ and OOP concepts to create a comprehensive Space Travel System. It showcases how different traveller types with unique attributes can interact within a system to manage space travel bookings. The implementation includes robust traveller management, ticket operations, and conflict resolution to ensure a smooth travel experience.

Feel free to explore the code, and enhance or customize the system by adding your own data members and member functions to further extend its functionality.

