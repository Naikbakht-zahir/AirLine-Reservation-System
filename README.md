✈️ SkyWings: Airline Reservation System

SkyWings is a full-stack web application built using Python (Flask) and MySQL. It provides a seamless interface for passengers to search for flights, book tickets, and manage reservations, while offering an administrative dashboard to track revenue and flight performance.

🚀 Core Functionality

Flight Search
- Users select origin and destination cities
- System queries database for matching flights
- Results display flight number, timing, and class-wise pricing

Booking Process
- User selects a flight and clicks "Book Now"
- Fills passenger details (name, passport, email, phone)
- Selects seat number and travel class (Economy/Business/First)
- System calculates price based on selected class
- Booking saved to database with 'Confirmed' status

Booking Management
- Users can view all their bookings with details
- Cancellation updates status to 'Cancelled'
- Cancelled bookings no longer count in revenue

Admin Dashboard
- Total confirmed bookings count
- Total revenue from all confirmed bookings
- Flight-wise breakdown of bookings and revenue

💾 Data Persistence

- All bookings are permanently stored in MySQL database
- No data loss on browser refresh, server restart, or system shutdown
- Real-time updates across all user sessions

🔒 Security Features

- Input validation for seat numbers (e.g., 12A format)
- Duplicate seat booking prevention
- Flash messages for user feedback
- SQL injection protection via parameterized queries

🎯 Use Cases

1. Passenger: Search and book flight tickets online
2. Admin: Monitor booking trends and revenue
3. Airline Staff: Track flight performance and occupancy

📝 Conclusion

SkyWings Airline Reservation System demonstrates a complete Database Management System (DBMS) project with:

- Full CRUD operations (Create, Read, Update, Delete)
- Relational database design with foreign keys
- Real-time data persistence
- User-friendly web interface
- Admin analytics dashboard

This project showcases practical implementation of database concepts in a real-world airline booking scenario.

👨‍💻 Author
Naikbakht

Furhther details in Project folder...
