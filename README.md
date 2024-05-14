Name:Waseeq Ahmed Siddiqui
Reg no:FA23-BSE-195

ASSIGNMENT TITLE: SEMESTER PROJECT

OBJECT ORIENTED PROGRAMMING

                                                                                    **CAB BOOKING SYSTEM**

Abstract:
Sure, here's an abstract of the Cab Booking System presented in bullet points:

- Purpose: 
The Cab Booking System is designed to simplify and streamline the process of booking cabs for users through a user-friendly graphical interface.
- Functionality: 
•	Users can securely log in to the system using their credentials.
•	The system allows users to view available cabs and their details.
•	Users can book a cab by providing their name, phone number, and selecting a desired cab from the available options.
- Data Management: 
Robust file handling mechanisms are employed to store and retrieve user, cab, and booking data, ensuring data integrity and seamless operation.
- Features:
•	User authentication to ensure secure access to the system.
•	Display of available cabs with relevant details such as plate number and model.
•	Booking functionality with validation to ensure all required fields are filled.
- Benefits: 
•	Provides a convenient solution for users to book cabs effortlessly.
•	Ensures data integrity and security through robust file handling techniques.
•	Simplifies the cab booking process, enhancing user experience and efficiency.

Methods:

loadUsers(): This method loads user data from a file (users.txt) into a ArrayList. It reads serialized user objects using ObjectInputStream.

loadCabs(): Similar to loadUsers(), this method loads cab data from a file (cabs.txt) into another ArrayList. It reads serialized cab objects using ObjectInputStream.

loadBookings(): Responsible for loading booking data from a file (bookings.txt). It utilizes ObjectInputStream to read serialized booking objects from the file until an EOFException occurs, indicating the end of the file.

saveBooking(Booking booking): Saves booking data to the bookings.txt file. It writes the serialized booking object to the file using ObjectOutputStream.

authenticateUser(String username, String password): Checks the validity of the provided username and password by verifying them against the data loaded from the users.txt file.

openCabBookingWindow(Stage primaryStage): Displays the cab booking window upon successful user authentication. This window allows users to input their details and book available cabs.

displayAvailableCabs(): Generates a string representation of available cabs by iterating over the ArrayList of cabs and checking their availability status.

bookCab(String name, String phoneNumber, String plateNumber): Books a cab based on the provided user details and cab plate number. It marks the selected cab as unavailable and saves the booking to the bookings.txt file.

showAlert(String title, String message): Displays an alert dialog with the specified title and message.











