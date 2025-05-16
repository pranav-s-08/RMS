# 🍽 Restaurant Management System (RMS)

This is a simple desktop application built in Java to help manage restaurant operations. It allows staff and managers to log in, take and edit orders, manage menu items, handle employee data, and track payments. The project uses **Java Swing** for the GUI and stores data in plain text files — no external database is required.

---

## ▶️ How to Run the Application

To run the app, make sure you have Java installed on your system.

1. Place the `RMS_GUI.jar` file and the `dataFiles` folder in the **same directory**.
2. Open Command Prompt and run the following:

   ```bash
   cd /d "C:\Users\HP\Desktop\RMS\Restaurant-Management-System-Core-Java-Project-master\Restaurant-Management-System-Core-Java-Project-master"
   java -jar RMS_GUI.jar
Alternatively, you can simply double-click on RMS_GUI.jar to launch the application, as long as the dataFiles folder is in the same directory.

🔐 Login Information (Test Users)
The application includes test login credentials:

Manager

ID: 1000

Password: Java

Staff
ID: 1234

Password: 1234

🧩 Key Features
Managers and staff have different access levels:

Staff can:

Log in and clock in/out
Create, edit, and cancel customer orders

Managers can:

Do everything staff can
Add, edit, and delete menu items
Manage employee records
Clock out staff
View daily payment summaries

The app allows you to filter menu items by category (Drinks, Main, Dessert, Alcohol) and manage orders using a simple point-and-click interface.

📁 Project Folder Structure
Make sure your project folder looks like this:

📁 Project Folder
├── RMS_GUI.jar
├── dataFiles
│   ├── staff.txt
│   ├── orders.txt
│   └── other data files...

If you want to run the app through IntelliJ:

Go to Run > Edit Configurations

Set the Working Directory to:
- C:\Users\HP\Desktop\RMS\Restaurant-Management-System-Core-Java-Project-master\Restaurant-Management-System-Core-Java-Project-master
This ensures the app can find the dataFiles folder when running from the IDE.

✅ Final Tips
Always keep the dataFiles folder next to the .jar file.
Use the app interface to manage all data — do not edit the files manually.
Java must be properly installed to run the .jar file.

