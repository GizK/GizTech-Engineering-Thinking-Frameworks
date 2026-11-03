Data Pipeline for Desk Booking system

Ingestion: Stage where raw data is collected
- Username and password input from user interface
- Desk bookings from other users on a database
- The layout of the office is collected with the desks and rooms
- Realtime streaming of the rooms that are blocked
Cleaning
- Block seats that are booked
- Ensure users information is not shared or open
- Ensure only users linked to the company can access the website
- Ensure empty entries don't break the system
Transformation
- Remove inaccuracies - bookings that overlap from new users and bookings already made
- Ensure seats are not double booked - no duplicates
- Bookings that are unrealistic should be flagged - ie the whole office
- Enrich the data - seating areas for company groups/departments
Storage
- Cleaned data is stored for use later
- Storing all the data for bookings, users and available rooms on a database
- Use a PostgreSQL because the booking system relies on relationships between users, desks and bookings
Reporting
- Delivers the final data to BI tools or machine learning models
- Where the data is analyzed at the next level for decision making.
- User dashboard is made allowing users a simple interface
- Booking confirmation issued
- Data used to track how often office workers come into office
