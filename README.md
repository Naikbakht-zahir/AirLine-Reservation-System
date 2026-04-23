✈️ SkyWings: Airline Reservation System

SkyWings is a full-stack web application built using Python (Flask) and MySQL. It provides a seamless interface for passengers to search for flights, book tickets, and manage reservations, while offering an administrative dashboard to track revenue and flight performance.

🌟 Features:

Passenger Interface
* Dynamic Flight Search: Filter flights by origin and destination cities.
* Seamless Booking: Integrated booking form for passenger details, passport info, and seat selection.
* Booking Management: View all past and current bookings with real-time status updates (Confirmed/Cancelled).
* Instant Cancellation: One-click booking cancellation directly from the user dashboard.

Administrative Features:
* Operational Dashboard: Real-time metrics showing total confirmed bookings and total revenue.
* Flight Performance: Detailed breakdown of revenue and booking counts per specific flight route.
* Visual Analytics: Performance bars to track seat occupancy at a glance.

🛠️ Tech Stack:

* Backend: Python 3.x, Flask
* Database: MySQL
* Database Connector: PyMySQL
* Frontend: HTML5, CSS3 (Custom), Bootstrap 5, FontAwesome 6
* Templating: Jinja2

📊 Database Schema:

The system relies on a relational database named `airline_db`. Below are the core entities:

1.  Airports: Stores airport codes and city names.
2.  Aircraft: Details about the fleet (Model, capacity).
3.  Flights: Contains schedules, routes (origin/destination IDs), and base pricing.
4.  Passengers: Stores personal information and contact details.
5.  Bookings: Links passengers to flights, including seat numbers, travel class, and status.

🚀 Getting Started:

Prerequisites
* Python 3.8+
* MySQL Server
* Pip (Python package manager)

Installation

1.  Clone the repository:
    git clone https://github.com/yourusername/airline-reservation-system.git
    cd airline-reservation-system

2.  Install dependencies:
    pip install flask pymysql
    
4.  Database Setup:
    * Create a database named `airline_db` in your MySQL server.
    * Import your SQL schema file (if provided) or create the tables based on the `app.py` queries.
    * **Update Credentials:** Open `app.py` and update the `get_db()` function with your MySQL password:
   
    password='YOUR_PASSWORD'

5.  Run the application:
    python app.py
    The app will be available at `http://127.0.0.1:5001`.

📝 Future Enhancements
* User Authentication: Secure login/signup for passengers.
* Seat Map: Interactive UI to select specific seats on the aircraft.
* Payment Gateway: Integration with Stripe or PayPal for real-time transactions.
* PDF Tickets: Auto-generate and email flight tickets upon confirmation.
