# 🏥 Doctor Appointment Booking System

A web-based application for hospitals and clinics to streamline doctor appointment scheduling. This system enables patients, doctors, and administrators to interact efficiently through a user-friendly interface.

## 🔧 Technology Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap  
- **Backend**: PHP  
- **Database**: MySQL  
- **Hosting Environment**: XAMPP Control Panel (Apache + MySQL)

## 🚀 Features

### 👨‍⚕️ Patients
- Register and log in
- View available doctors and their schedules
- Book and cancel appointments

### 🩺 Doctors
- Log in to manage availability
- Accept/reject appointments
- View patient appointments

### 🛠️ Admin
- Manage doctor and patient records
- Oversee all appointments
- Maintain the system data

## 💻 Installation & Setup (Local - XAMPP)

1. **Download and Install [XAMPP](https://www.apachefriends.org/index.html)**
2. **Extract the project folder**
   - Place the `dabs` folder inside `htdocs` (e.g., `C:\xampp\htdocs\dabs`)
3. **Import the database**
   - Open [phpMyAdmin](http://localhost/phpmyadmin)
   - Create a new database (e.g., `dabs`)
   - Import the `.sql` file located in the `database` folder of the project
4. **Run the Application**
   - Start Apache and MySQL from XAMPP Control Panel
   - Open your browser and go to: [http://localhost/dabs](http://localhost/dabs)

## 🧪 Usage Guide

- **Patient Login**: Book appointments, view history
- **Doctor Login**: Manage patient appointments
- **Admin Login**: Access management dashboard

## 📁 Project Structure
dabs/
├── admin/ # Admin dashboard
├── doctor/ # Doctor dashboard
├── patient/ # Patient interfaces
├── includes/ # PHP includes/configs
├── css/ # Stylesheets
├── js/ # JavaScript files
├── database/ # SQL dump file
└── index.php # Entry point

## 🙌 Contribution

You're welcome to suggest improvements or add features. Fork the project, make changes, and open a pull request.

## 📄 License

This project is for academic/demo use.

---

### 💡 Developed by Manish Kumar

