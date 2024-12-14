Project Documentation: Campus Event Management System
Introduction
The Campus Event Management System is a web-based platform designed to facilitate event planning, management, and participation within a campus community. The system allows administrators to create and manage events, while users can view, RSVP, and interact with events based on their preferences. The system also integrates a calendar view to visualize events.
System Features
1. User Features
•	Profile Management
o	Users can view their profile details, including username, email, and event preferences.
o	Event preferences are displayed as a comma-separated list of categories.
•	Event Interaction
o	Users can view upcoming events and RSVP.
o	An event calendar displays events in a monthly view.
•	Event Filtering
o	Users can filter events based on their preferences for easier discovery.
2. Admin Features
•	Event Creation
o	Admins can create events by providing details like title, date, time, description, and category.
•	Event Management
o	Admins can view all created events and modify or delete them as necessary.
3. Calendar Integration
•	The system integrates a calendar view using FullCalendar.js to display events by date.
•	Users and admins can see all events in a visually intuitive format.
System Design
Frontend
The frontend is developed using:
•	HTML5: For structuring web pages.
•	CSS3: For styling and responsiveness.
•	JavaScript: For dynamic interactions and DOM manipulation.
Backend
The backend is developed using:
•	Node.js: For server-side programming.
•	Express.js: For routing and handling HTTP requests.
•	MongoDB: For data storage and management.
3. Backend Routes
•	User Registration
o	Endpoint: /register
o	Validates role and hashes passwords before saving to the database.
•	User Login
o	Endpoint: /login
o	Verifies user credentials and generates a JWT token.
Screenshots Taken
        
Future Enhancements
1.	Add email notifications for RSVP'd events.
2.	Implement a search feature for events.
3.	Provide support for recurring events in the calendar.
Conclusion
The Campus Event Management System simplifies event planning and participation within a campus environment. With an intuitive user interface and robust backend, it streamlines the process of managing and attending events.



