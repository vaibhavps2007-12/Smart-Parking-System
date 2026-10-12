# Smart-Parking-System
Smart Parking System is a Python-based project designed to manage 10 parking slots efficiently. It records vehicle entry and exit, automatically assigns available slots, tracks parking duration, calculates parking fees, and displays slot availability. The system reduces manual work and demonstrates a simple solution for smart parking management.
# Smart Parking System 🚗
# Smart Parking System 🚗

## 📌 Project Overview

The **Smart Parking System** is a beginner-friendly Python project developed to manage parking spaces efficiently. The system is designed for **10 parking slots** and helps keep track of available and occupied spaces.

The system records the vehicle number, automatically assigns an available parking slot, records the entry time, calculates the total parking duration when the vehicle leaves, and calculates the parking fee.

This project demonstrates how basic Python programming concepts can be used to solve a real-world problem.

---

## 🎯 Objectives

* Manage 10 parking slots.
* Automatically assign available parking slots.
* Store vehicle information.
* Record vehicle entry time.
* Record vehicle exit time.
* Calculate parking duration.
* Calculate parking charges.
* Display available and occupied slots.
* Search for a parked vehicle.
* Reduce manual parking management.

---

## ⚙️ Features

### 1. Display Parking Slots

Shows all 10 parking slots and whether each slot is available or occupied.

### 2. Park Vehicle

The system asks for the vehicle number and automatically assigns the first available parking slot.

### 3. Time Tracking

The system records the exact time when the vehicle enters the parking area.

### 4. Remove Vehicle

When a vehicle leaves, the system records the exit time and makes the parking slot available again.

### 5. Parking Duration

The system calculates how long the vehicle was parked.

Example:

```text
Parking Time: 2 hours 35 minutes
```

### 6. Parking Fee

The system calculates the parking fee according to the parking duration.

Example:

```text
Parking Rate: ₹20 per hour
Parking Time: 2 hours
Total Fee: ₹40
```

### 7. Search Vehicle

The user can enter a vehicle number to find its parking slot and entry time.

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Python Concepts:** Variables, Lists, Dictionaries, Functions, Loops, Conditional Statements
* **Library Used:** `datetime`
* **Database:** Not required for the basic version

---

## 💻 Requirements

To run this project, you need:

* Python 3.x
* Any Python editor such as:

  * VS Code
  * IDLE
  * PyCharm
  * Jupyter Notebook

No external Python packages are required.

---

## ▶️ How to Run

### Step 1: Install Python

Install Python 3.x on your computer.

### Step 2: Download or copy the project

Save the Python program as:

```text
smart_parking.py
```

### Step 3: Open the terminal

Go to the folder containing the Python file.

### Step 4: Run the program

```bash
python smart_parking.py
```

---

## 📋 Main Menu

The program provides the following options:

```text
==============================
     SMART PARKING SYSTEM
==============================

1. Display Parking Slots
2. Park Vehicle
3. Remove Vehicle
4. Search Vehicle
5. Exit
```

---

## 🧪 Example

When a vehicle enters:

```text
Enter vehicle number: MP04AB1234

Vehicle parked successfully!
Vehicle Number: MP04AB1234
Parking Slot: 1
Entry Time: 30-09-2026 10:30:15
```

When the vehicle leaves:

```text
========== PARKING RECEIPT ==========

Vehicle Number : MP04AB1234
Parking Slot   : 1
Entry Time     : 30-09-2026 10:30:15
Exit Time      : 30-09-2026 12:45:20
Parking Time   : 2 hours 15 minutes
Parking Fee    : ₹60

=====================================
```

---

## 🏗️ Working Principle

The system starts with 10 empty parking slots.

When a vehicle enters:

```text
Vehicle Entry
      ↓
Enter Vehicle Number
      ↓
Check Available Slot
      ↓
Assign Parking Slot
      ↓
Record Entry Time
```

When a vehicle leaves:

```text
Enter Vehicle Number
      ↓
Find Vehicle
      ↓
Record Exit Time
      ↓
Calculate Parking Duration
      ↓
Calculate Parking Fee
      ↓
Free Parking Slot
```

---

## 🌍 Real-World Applications

The concept can be used in:

* Colleges
* Industrial areas
* Offices
* Shopping malls
* Hospitals
* Hotels
* Railway stations
* Airports

---

## 🚀 Future Scope

The current project is a basic Python prototype. It can be improved in the future by adding:

* Database connectivity
* Graphical User Interface (GUI)
* IoT-based parking sensors
* Automatic vehicle detection
* Number plate recognition
* Online parking booking
* QR-code entry and exit
* Online payment
* Mobile application
* AI-based prediction of parking availability

---

## 👨‍💻 Learning Outcomes

Through this project, we learn:

* Python programming
* Functions
* Lists and dictionaries
* Loops and conditions
* Date and time handling
* Problem-solving
* Real-world application of programming
* Basic project development

---

## 📌 Project Limitations

This is a beginner-level prototype. It currently uses a Python console instead of physical sensors or a camera. Parking information is stored only while the program is running.

For a real-world implementation, a database, sensors, or a camera-based system would be required.

---

## 📄 Project Type

**Project:** Smart Parking System
**Domain:** Engineering / Smart Management
**Programming Language:** Python
**Parking Capacity:** 10 Vehicles
**Level:** First Semester / Beginner

---

## 👥 Conclusion

The Smart Parking System provides a simple and practical solution for managing parking spaces. It automatically assigns parking slots, tracks vehicle entry and exit times, calculates parking duration and parking fees, and displays the current parking status.

Although the current version is designed as a beginner-level Python project, it provides a foundation for developing a larger IoT- and AI-based smart parking system in the future.
