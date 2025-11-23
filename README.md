# Movie-Ticket-Booking-Management-
It helps us to select the movie and let us book the wanted tickets 
ABSTRACT:

This project is a simple Movie Ticket Booking System written in C. It allows users to view movies, check available seats, book tickets, view booking details, and cancel bookings. The program uses structures, arrays, functions, and basic input/output in C to manage movie data and bookings. It stores seat status, ticket prices, and booking information using in-memory arrays.

FEATURES OF THE PROGRAMME:

Shows a list of movies with time and ticket price

Displays available seats for each movie

Books tickets by checking seat availability

Generates a unique booking ID

Stores customer name, seat number, movie, and time

Shows all bookings made

Cancels a booking and frees the seat

Simple menu-driven interface using switch and loops

TECHNICAL REQUIREMENTS:

Software used

~C Compiler (GCC, MinGW, Code::Blocks, Dev-C++, Turbo C, etc.)

~Any text editor or IDE that supports C

Headers Used

~stdio.h → input/output

~stdlib.h → functions like exit()

~string.h → strcpy, strcmp, memset

~time.h → booking time using time() and ctime()

Language

~ANSI C (no external libraries required)

Functional Requirements

FR1 – Initialize Movies

~Loads all movie titles, show times, empty seats (20 per movie), and ticket prices.

FR2 – View Movies

~Displays movie number, title, show time, and price.

FR3 – Display Seats

~Shows available seat numbers for the selected movie using an integer array.

FR4 – Book Ticket

~Get name, movie number, and seat number

~Validate inputs

~Mark seat as booked (set seat array value to 1)

~Store booking in a structure with ID, name, movie, time, seat, and price

FR5 – View Bookings

~Shows all saved booking records stored in an array.

FR6 – Cancel Booking

~Enter booking ID

~Find booking

~Free that seat in the movie

~Remove the booking from the array

FR7 – Exit

~Ends the program using exit(0).

HOW TO RUN THE PROGRAMME:

Save the code as:

movie_ticket_booking.c

Compile using GCC:

gcc movie_ticket_booking.c -o booking

Run the program:

./booking

(Windows: booking.exe)

Use the menu to:

~View movies

~Book a ticket

~View bookings

~Cancel booking

~Exit
