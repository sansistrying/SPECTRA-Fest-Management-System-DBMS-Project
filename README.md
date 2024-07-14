# SPECTRA-Fest-Management-System-DBMS-Project
Spectra, our Fest Management System, minimizes manual errors, enhances  operational efficiency, and streamlines fest planning. The unified platform optimizes  participant registration, event scheduling, and transparent communication, ensuring  a seamless and enjoyable festival experience for both organizers and participants.




### 1. *Flight Booking Agent*
#### Tasks:
- *Flight Search:* Find available flights based on user criteria.
- *Display Available Flights:* Present flight options to the user.
- *Select Flight:* Capture the user's flight choice.
- *Passenger Details Input:* Collect passenger information.
- *Payment Processing:* Redirect to secure payment gateway.
- *Booking Confirmation:* Confirm booking and send details via email.

#### Tools:
- *Flight API:* To search for available flights.
- *Payment Gateway API:* For handling payments.
- *Email Service:* To send confirmation emails.

### 2. *Modify Booking Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *Display Booking Details:* Show current booking information.
- *Modification Input:* Collect new booking details.
- *Check Availability:* Find available flights for new criteria.
- *Select New Flight:* Capture the user's new flight choice.
- *Payment Adjustment:* Handle payment adjustments.
- *Booking Confirmation:* Confirm modified booking and send details via email.

#### Tools:
- *Booking Management API:* To fetch and update booking details.
- *Flight API:* To check new flight availability.
- *Payment Gateway API:* For payment adjustments.
- *Email Service:* To send updated booking details.

### 3. *Cancel Booking Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *Display Booking Details:* Show current booking information.
- *Cancel Confirmation:* Confirm cancellation with the user.
- *Refund Processing:* Handle refund process.
- *Cancellation Confirmation:* Confirm cancellation and send details via email.

#### Tools:
- *Booking Management API:* To fetch and cancel bookings.
- *Payment Gateway API:* For processing refunds.
- *Email Service:* To send cancellation details.

### 4. *Add Luggage Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *Display Booking Details:* Show current booking information.
- *Add Luggage Input:* Collect information about additional luggage.
- *Payment Processing:* Redirect to secure payment gateway.
- *Luggage Confirmation:* Confirm luggage addition and send details via email.

#### Tools:
- *Booking Management API:* To fetch and update booking details.
- *Payment Gateway API:* For handling payments.
- *Email Service:* To send updated booking details.

### 5. *Seat Selection Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *Display Booking Details:* Show current booking information.
- *Display Available Seats:* Show available seats to the user.
- *Select Seat:* Capture the user's seat choice.
- *Payment Processing:* Redirect to secure payment gateway.
- *Seat Confirmation:* Confirm seat selection and send details via email.

#### Tools:
- *Booking Management API:* To fetch and update booking details.
- *Seat Management API:* To check and book available seats.
- *Payment Gateway API:* For handling payments.
- *Email Service:* To send updated booking details.

### 6. *Report Food Allergies Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *Display Booking Details:* Show current booking information.
- *Report Allergy Input:* Collect information about food allergies.
- *Confirmation:* Confirm allergy report and send details via email.

#### Tools:
- *Booking Management API:* To fetch and update booking details.
- *Email Service:* To send updated booking details.

### 7. *Customer Support Agent*
#### Tasks:
- *Connect to Human:* Facilitate connection to a human representative.
- *Retrieve Booking:* Fetch booking details if necessary.

#### Tools:
- *Booking Management API:* To fetch booking details.
- *Support Ticketing System:* To create support tickets.

### 8. *Lost Luggage Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *Report Lost Luggage:* Collect information about the lost luggage.
- *Confirmation:* Confirm lost luggage report and send details via email.

#### Tools:
- *Booking Management API:* To fetch booking details.
- *Luggage Management System:* To report and track lost luggage.
- *Email Service:* To send updated booking details.

### 9. *Complaint Handling Agent*
#### Tasks:
- *Retrieve Booking:* Fetch booking details using reference number.
- *File Complaint:* Collect details about the complaint.
- *Confirmation:* Confirm complaint filing and send details via email.

#### Tools:
- *Booking Management API:* To fetch booking details.
- *Complaint Management System:* To file and track complaints.
- *Email Service:* To send confirmation details.

### Implementation with Crews.ai and Ollama LLM
Each agent can be implemented as a separate microservice within Crews.ai, leveraging the capabilities of the Ollama LLM for natural language understanding and generation. The agents can communicate with each other and external APIs through defined interfaces, ensuring a seamless and efficient user experience.
