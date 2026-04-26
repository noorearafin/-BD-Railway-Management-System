# BD Railway Management System

## 📋 Project Overview

**BD Railway Management System** is a comprehensive desktop application developed using **Java Swing** toolkit. This is an educational project that demonstrates key concepts of software development including GUI design, database management, and user interaction patterns.

The system allows users to:
- ✅ View train schedules across Bangladesh routes
- ✅ Book train tickets online
- ✅ Manage bookings and reservations
- ✅ Check ticket availability
- ✅ Admin panel for train schedule management

---

## 🎯 Features

### User Features
- **Train Schedule Browsing**: View all available trains with departure/arrival times and routes
- **Ticket Booking**: Easy-to-use interface for booking train tickets
- **Booking Management**: View, modify, and cancel existing bookings
- **Route Information**: Complete route maps across Bangladesh
- **Payment Processing**: Secure ticket payment system
- **Booking Confirmation**: Digital ticket confirmation and receipt generation

### Admin Features
- **Train Management**: Add, edit, and delete train schedules
- **Route Management**: Manage railway routes and stations
- **Passenger Management**: View and manage all passenger bookings
- **Availability Control**: Update seat availability in real-time
- **Reports**: Generate booking and revenue reports

---

## 🛠️ Technologies Used

- **Language**: Java
- **GUI Framework**: Java Swing
- **Database**: SQL/MySQL (JDBC)
- **IDE**: NetBeans / Eclipse / IntelliJ IDEA
- **Version Control**: Git

---

## 📋 System Requirements

- **Java Version**: JDK 8.0 or higher
- **RAM**: Minimum 2 GB
- **Storage**: 500 MB free space
- **OS**: Windows, Linux, or macOS
- **Database**: MySQL Server 5.7+

---

## 🚀 Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Java Development Kit (JDK)
- MySQL Server
- Git

### Steps to Install

1. **Clone the Repository**
   ```bash
   git clone https://github.com/noorearafin/-BD-Railway-Management-System.git
   cd -BD-Railway-Management-System
   ```

2. **Extract Project Files**
   - Extract the `BD-Railway-Management-System.rar` file
   - Or import the project directly into your IDE

3. **Setup Database**
   - Create a new MySQL database
   - Import the provided SQL script (if available)
   - Configure database connection details in the application

4. **Configure Database Connection**
   - Update database credentials in the configuration file
   - Set username, password, and database name

5. **Compile and Run**
   ```bash
   javac -d bin src/*.java
   java -cp bin:. MainApplication
   ```

---

## 📁 Project Structure

```
BD-Railway-Management-System/
├── src/
│   ├── Main.java              # Entry point
│   ├── ui/                    # GUI Components
│   │   ├── LoginFrame.java
│   │   ├── MainFrame.java
│   │   ├── BookingPanel.java
│   │   └── AdminPanel.java
│   ├── models/                # Data models
│   │   ├── Train.java
│   │   ├── Passenger.java
│   │   ├── Booking.java
│   │   └── Route.java
│   ├── database/              # Database operations
│   │   ├── DatabaseConfig.java
│   │   └── DatabaseManager.java
│   └── utils/                 # Utility classes
│       └── ValidationUtil.java
├── resources/                 # Images, icons, etc.
├── sql/                       # Database scripts
│   └── schema.sql
├── BD-Railway-Management-System.rar
└── README.md

```

---

## 🔐 Default Credentials

**Admin Login** (update after first login):
- Username: `admin`
- Password: `admin123`

**Note**: Change default credentials immediately after setup for security.

---

## 📖 Usage Guide

### For Users
1. Launch the application
2. Create a new account or login with existing credentials
3. Browse available trains by selecting departure and destination cities
4. Select your preferred train and seats
5. Complete payment
6. Download/print your ticket confirmation

### For Admins
1. Login with admin credentials
2. Navigate to Admin Panel
3. Manage trains, routes, and schedules
4. View all bookings and generate reports

---

## 🐛 Known Issues & Limitations

- Current version supports single-class seat bookings
- Payment processing is simulated (not integrated with real payment gateways)
- Maximum 999 seats per train
- Single-user booking per session

---

## 🔄 Future Enhancements

- [ ] Multi-class seat management
- [ ] Real payment gateway integration (bKash, Nagad, Rocket)
- [ ] Mobile app version
- [ ] Seat map visualization
- [ ] Email/SMS notifications
- [ ] Real-time seat availability synchronization
- [ ] User ratings and reviews
- [ ] Group booking discounts

---

## 👥 Contributors

- **Noor e Arafin** - Project Lead & Developer

---

## 📄 License

This project is open source and available under the MIT License. See the LICENSE file for details.

---

## 📞 Support & Contact

For questions, bug reports, or feature requests, please:
- Open an issue on GitHub
- Contact: [Your Email]
- GitHub Profile: [https://github.com/noorearafin](https://github.com/noorearafin)

---

## 📚 References & Resources

- [Java Swing Documentation](https://docs.oracle.com/javase/tutorial/uiswing/)
- [JDBC Tutorial](https://docs.oracle.com/javase/tutorial/jdbc/)
- [MySQL Documentation](https://dev.mysql.com/doc/)

---

## ⭐ Acknowledgments

This project was developed as an academic assignment to demonstrate:
- Object-Oriented Programming (OOP) principles
- GUI development using Java Swing
- Database design and management
- Software engineering best practices

---

**Last Updated**: April 26, 2026

**Version**: 1.0.0

---

*Made with ❤️ for educational purposes*
