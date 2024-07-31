Hotel Management System

This is a comprehensive web application designed to streamline various hotel operations, such as making reservations, checking in and out, and handling special requests. The system is built using React and offers a user-friendly interface for both hotel staff and guests.

Features

ReservationForm: A form where users can enter their reservation details, such as name, email, check-in and check-out dates, number of guests, and any special requests.
ReservationList: Displays a list of all reservations made by different users, including details like reservation ID, guest name, check-in and check-out dates, and status.
ReservationDetails: Provides detailed information about a specific reservation, including room type, room number, special requests, and other relevant details.
CheckInForm: A form for users to check in for their reservation, which includes fields for entering guest information, verification, and other necessary details.
CheckOutForm: A form for users to check out after their stay, including fields for entering guest information, finalizing any outstanding payments, and gathering feedback.
SpecialRequests: Allows users to specify any special requests during their reservation, such as dietary restrictions, room preferences, or other accommodations.
RoomList: Displays a list of available rooms, including their types, amenities, and possibly their availability status.

Demo

You can view a live demo of the project here: [Hotel Management System](http://localhost:5173/)

Installation and Setup

Follow these steps to set up the project locally:

1. Clone the repository:

   bash
   git clone https://github.com/Mohaabdalle/Hotel-Management-system.git
   cd Hotel-Management-system
   

2. Install dependencies:

   Make sure you have Node.js and npm installed. Then, run:

   bash
   npm install
   

3. Start the development server:

   bash
   npm start
   

   The application will be available at `http://localhost:5173/`.

Project Structure

- `src/components/`: Contains all the React components used in the project.
- `src/App.js`: The main application file where components are integrated.
- `src/App.css`: Contains the styling for the application.

 Usage

- Making a Reservation: Users can fill out the ReservationForm with their details and submit to create a new reservation.
- Viewing Reservations: All reservations can be viewed in the ReservationList, and detailed information about each reservation can be accessed through ReservationDetails.
- Check-In and Check-Out: Users can check in and out of their reservations using the respective forms.
- Managing Special Requests: Users can specify special requests when making a reservation, which can be managed and viewed by hotel staff.
- Viewing Available Rooms: The RoomList component displays all available rooms, helping users and staff make informed decisions.

 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more information.

