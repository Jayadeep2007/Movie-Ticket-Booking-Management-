

---

# **📘 MOVIE TICKET BOOKING SYSTEM –  COURSE PROJECT **

---

## **1️⃣ ABSTRACT**

This project is a Movie Ticket Booking System written in C. It allows users to view movies, check seat availability, book tickets, and cancel bookings. The program uses **structures**, **arrays**, and **functions** to store and manage all data during runtime. A unique booking ID and booking time are also generated for each ticket. This project shows how basic C concepts can be used to build a small, working management system with a simple menu interface.

---

## **2️⃣ FEATURES OF THE PROGRAM**

1. 🎬 **View Movie List** (title, show time, ticket price)
2. 💺 **Check Available Seats** (20 seats per movie)
3. 🧾 **Book Tickets** with validation
4. 🆔 **Auto-generated Booking ID**
5. 👤 **Stores Customer Details**
6. 🕒 **Saves Booking Time** using `time.h`
7. 📄 **View All Bookings**
8. ❌ **Cancel a Booking** using booking ID
9. 📌 **Simple Menu System** using `switch` and loops

---

## **3️⃣ TECHNICAL REQUIREMENTS**

### **📌 Software Requirements**

* Any **C compiler**: GCC, Code::Blocks, Dev-C++, Turbo C, etc.
* Basic **text editor / IDE**

### **📌 Header Files Used**

* `stdio.h` → input/output
* `stdlib.h` → `exit()`
* `string.h` → `strcpy`, `strcmp`, `memset`
* `time.h` → `time()`, `ctime()`

### **📌 Language Used**

* **ANSI C (Standard C)**

---

## **4️⃣ FUNCTIONAL REQUIREMENTS**

### **🔹 FR1: Initialize Movies**

* Preloads movie titles, timings, prices
* Sets all 20 seats to available (0)

### **🔹 FR2: View Movies**

* Prints movie number, name, time, and price

### **🔹 FR3: Display Seats**

* Shows all free seats (those with value 0)

### **🔹 FR4: Book Ticket**

* Takes customer name
* Validates movie number
* Validates seat number
* Marks seat as booked (1)
* Stores booking details in a structure

### **🔹 FR5: View Bookings**

* Displays ID, name, movie, time, seat, price, and booking time

### **🔹 FR6: Cancel Booking**

* User enters booking ID
* System finds booking
* Frees that seat
* Removes booking from array

### **🔹 FR7: Exit Program**

* Exits using `exit(0)`

---

## **5️⃣ HOW TO RUN THE PROGRAM**

### **✔ Step 1: Save the Program**

Save your code as:
`movie_ticket_booking.c`

### **✔ Step 2: Compile the Program**

Using GCC:

```
gcc movie_ticket_booking.c -o booking
```

### **✔ Step 3: Run the Program**

Windows:

```
booking.exe
```

Linux/Mac:

```
./booking
```

### **✔ Step 4: Use the Menu**

You will see:

```
1. View Movies
2. Book Ticket
3. View Bookings
4. Cancel Booking
5. Exit
```

Choose any option and follow the instructions.

## SCREENSHOTS ## 


1️⃣ Project Overview Screenshot

![image alt](https://github.com/Jayadeep2007/Movie-Ticket-Booking-Management-/blob/main/screenshot1.png?raw=true)

2️⃣ Movie List Display Screenshot

![image alt](

3️⃣ Seat Availability Screenshot

![image alt]

4️⃣ Ticket Booking Process Screenshot

![image alt]

5️⃣ Booking Confirmation Screenshot

![image alt]

6️⃣ View All Bookings Screenshot

![image alt]

7️⃣ Cancel Booking Screenshot

![image alt]

8️⃣ Exit Screen Screenshot

![image alt]

