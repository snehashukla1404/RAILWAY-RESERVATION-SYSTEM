# 🚆 Railway Reservation System

A console-based application developed in **C** for managing train reservations. This system allows users to book, cancel, and view train reservations efficiently.

## ✨ Features
- **Book Tickets**: Reserve seats for available trains.
- **Cancel Tickets**: Cancel previously booked tickets.
- **View Reservations**: Check current reservations and their statuses.
- **Simple Console Interface**: Easy-to-use text-based interface for user interaction.

## 🛠️ Tech Stack
- **Programming Language**: C

## 📂 Project Structure
Railway-Reservation-System/
├── main.c              # Main application logic
├── reservation.c       # Functions related to reservation operations
├── cancellation.c      # Functions related to cancellation operations
├── view.c              # Functions to view reservations
└── README.md           # Project documentation (this file)


## 🚀 Getting Started

### Prerequisites
Ensure you have a C compiler installed. You can use:
- **GCC**: Available on Linux and Windows (via MinGW)
- **Clang**: Available on macOS and Linux

### Installation
Clone the repository to your local machine:
```bash
git clone https://github.com/snehashukla1404/RAILWAY-RESERVATION-SYSTEM.git
cd RAILWAY-RESERVATION-SYSTEM
```

### Compilation
- Compile the C source files:
```bash
gcc main.c reservation.c cancellation.c view.c -o railway_reservation
```

### Running the Application
- Run the compiled application:
  ```bash
  ./railway_reservation
  ```

🧩 Future Improvements
- Implement a file-based database to store reservations persistently.
- Add user authentication for secure access.
- Enhance the user interface with color coding and better formatting.
- Implement a graphical user interface (GUI) using libraries like GTK or Qt.


