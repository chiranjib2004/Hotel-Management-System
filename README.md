#  Hotel Management System (Java + MySQL)

A **desktop-based Hotel Management System** developed using **Java (Swing & AWT)** and **MySQL**, aimed at automating and managing day-to-day hotel operations such as customer handling, room allocation, employee management, pickup services, and billing.

The system provides a **clean graphical interface**, efficient database integration, and modular design, making it suitable for **academic projects and real-world use cases**.

---

##  Key Features

###  Authentication
- Secure **Admin Login**
- Controlled access to hotel operations

###  Customer & Room Management
- New customer registration with ID verification
- Room assignment during check-in
- Real-time room availability tracking
- Checkout with automatic timestamp generation
- Update room and customer status

###  Employee Management
- Add and manage employee details
- Job role, salary, contact, and Aadhaar tracking
- View all employee information

###  Pickup & Driver Services
- Add drivers with vehicle details
- Pickup service based on car type and availability
- Location-based service assignment

###  Administration
- Department-wise budget overview
- Manager and customer information panels
- Search rooms using filters (bed type, availability)

---

## 🖥️ Screenshots


###  Splash / Welcome Screen
![Splash Screen](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113547" src="https://github.com/user-attachments/assets/722b975a-253f-44bb-b09e-db0ff50f11b5" />
)
<img width="1920" height="1080" alt="Screenshot 2026-01-22 113649" src="https://github.com/user-attachments/assets/9dbfab1f-90cb-44f5-a349-fdff89dd7369" />

###  Login Screen
![Login](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113606" src="https://github.com/user-attachments/assets/1f549609-7fa5-4dee-a8db-71fb8ffb25ca" />
)

###  Admin Dashboard
![Dashboard](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113709" src="https://github.com/user-attachments/assets/dad90463-f80c-48d4-8ba1-3d7c307f437a" />
)

###  New Customer Form
![New Customer](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113734" src="https://github.com/user-attachments/assets/9d3c18a3-27f2-46eb-9f42-61922189a092" />
)

###  Add Rooms
![Add Rooms](<img width="1920" height="1080" alt="Screenshot 2026-01-22 114036" src="https://github.com/user-attachments/assets/7ad29b83-e8b0-47fc-8df4-3fd1d29485b1" />
)

###  Add Employee
![Add Employee](<img width="1920" height="1080" alt="Screenshot 2026-01-22 114020" src="https://github.com/user-attachments/assets/35e0d6ca-11a2-471b-828e-e5fb7525cfc7" />
)

###  Add Driver
![Add Driver](<img width="1920" height="1080" alt="Screenshot 2026-01-22 114056" src="https://github.com/user-attachments/assets/018e10e9-25f9-4251-8cfc-fab4776aafac" />
)

###  Search Room
![Search Room](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113942" src="https://github.com/user-attachments/assets/6dd85d07-2dc8-472b-b610-317f2ccb271c" />
)

###  Pickup Service
![Pickup Service](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113923" src="https://github.com/user-attachments/assets/12281d43-e8c2-47d1-bab6-e7857aca0e2e" />
)

###  Update Check-in Status
![Update Status](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113851" src="https://github.com/user-attachments/assets/a935a8f9-9a00-4f7a-90f5-cc4b330a2df4" />
)

###  Checkout
![Checkout](<img width="1920" height="1080" alt="Screenshot 2026-01-22 113831" src="https://github.com/user-attachments/assets/b5ef496b-0b06-4ee4-8bad-d7d1365a525f" />
)

###  Department Budget
![Department](<img width="1920" height="1080" alt="budget" src="https://github.com/user-attachments/assets/b397503d-25b9-415b-9496-137a55db641d" />
)

---

##  Tech Stack

| Technology | Usage |
|---------|------|
| **Java** | Core application logic |
| **Swing & AWT** | GUI development |
| **MySQL** | Database |
| **JDBC** | Database connectivity |
| **NetBeans IDE** | Development environment |

---

## 📁 Project Structure

```text
Hotel-Management-System/
│
├── hotel.management/
│   ├── Login.java
│   ├── Dashboard.java
│   ├── AddCustomer.java
│   ├── AddRooms.java
│   ├── AddEmployee.java
│   ├── AddDriver.java
│   ├── SearchRoom.java
│   ├── Pickup.java
│   ├── UpdateCheck.java
│   ├── Checkout.java
│   ├── CustomerInfo.java
│   ├── ManagerInfo.java
│   ├── Department.java
│   └── Conn.java
│
├── icons/
│
├── screenshots/
│   ├── splash.png
│   ├── login.png
│   ├── dashboard.png
│   ├── new_customer.png
│   ├── add_rooms.png
│   ├── add_employee.png
│   ├── add_driver.png
│   ├── search_room.png
│   ├── pickup_service.png
│   ├── update_status.png
│   ├── checkout.png
│   ├── department.png
│   ├── customer_info.png
│   ├── manager_info.png
│   └── reception.png
│
├── libraries/
│   ├── mysql-connector-java-8.0.28.jar
│   ├── rs2xml.jar
│   └── jcalendar.jar
│
└── README.md
```



---

##  Installation & Setup

### 1️. Prerequisites
- JDK 21 or compatible
- MySQL Server
- Apache NetBeans IDE

### 2️. Database Configuration
- Create a MySQL database (example: `hotelmanagementsystem`)
- Create required tables
- Update database credentials in `Conn.java`

```java
DriverManager.getConnection(
  "jdbc:mysql://localhost:3306/hotelmanagementsystem",
  "username",
  "password"
);
```


##  Run the Application

1. Open the project in **Apache NetBeans IDE**
2. Add the required `.jar` libraries:
   - `mysql-connector-java`
   - `rs2xml`
   - `jcalendar`
3. Run the `Login.java` file to start the application

---

##  Project Use Case

This project is suitable for:

-  College **Mini / Major Projects**
-  **Java + SQL** based resume projects
-  Learning **Java Swing GUI development**
-  Understanding **JDBC & MySQL database integration**

---

##  Future Enhancements

- Role-based login (**Admin / Receptionist**)
- Bill & invoice **PDF generation**
- **Online room booking** module
- Improved **input validation and security**
- Migration to **JavaFX** or **web-based UI**

---

##  Author

**Chiranjib Pradhan**  
Computer Science & Engineering  
Java | SQL | Desktop Applications

