# 🌍 World Clock & Time Converter

**ICT171 Cloud Infrastructure Project – Murdoch University**

## 📌 Project Overview

This project is a **World Clock and Time Converter web application** developed as part of the ICT171 unit at Murdoch University. The primary objective was to demonstrate the use of **cloud infrastructure (IaaS)** by deploying a fully functional web application using **Amazon Web Services (AWS)** and **WordPress**.

The application allows users to:

* View current time across multiple global time zones
* Convert time between different cities
* Access a simple, user-friendly interface for global time management

---

## 🚀 Technologies Used

### 🌐 Frontend & CMS

* WordPress
* HTML, CSS (via WordPress themes/customization)

### ☁️ Cloud Infrastructure (AWS)

* **EC2 (Elastic Compute Cloud):** Hosting the web server
* **S3 (optional):** Static assets storage
* **Route 53 (optional):** Domain management
* **Security Groups:** Network access control
* **Elastic IP:** Static public IP for consistent access

### 🛠 Backend & Server

* Apache / Nginx (depending on setup)
* PHP (WordPress runtime)
* MySQL (WordPress database)

---

## 🏗️ Architecture Overview

The system is built using a typical **IaaS architecture**:

1. AWS EC2 instance acts as the web server
2. WordPress is installed and configured on the instance
3. Database is hosted locally (or via AWS RDS if implemented)
4. Users access the application via a public IP or domain
5. Security groups control inbound/outbound traffic

---

## ⚙️ Features

* 🌎 Real-time world clock display
* 🔄 Time zone conversion tool
* 📱 Responsive design (accessible across devices)
* ☁️ Cloud-hosted for scalability and availability
* 🔐 Basic security configurations via AWS

---

## 📥 Installation & Deployment Steps

### 1. AWS Setup

* Launch an EC2 instance (Ubuntu/Linux recommended)
* Configure security groups (allow HTTP, HTTPS, SSH)
* Assign Elastic IP (optional but recommended)

### 2. Server Configuration

* Install Apache/Nginx, PHP, and MySQL
* Download and configure WordPress
* Set up database and connect to WordPress

### 3. WordPress Configuration

* Install a suitable theme
* Add plugins or custom scripts for:

  * World clock functionality
  * Time conversion features

### 4. Deployment

* Access via public IP or domain
* Test functionality across multiple time zones

---

## 🧪 Testing

* Verified accurate time conversion across major cities
* Tested responsiveness on desktop and mobile devices
* Checked server accessibility and uptime

---

## 📚 Learning Outcomes

This project helped in understanding:

* Practical use of **Infrastructure as a Service (IaaS)**
* Deployment of web applications on AWS
* WordPress customization and plugin usage
* Basic cloud security and networking concepts
* Real-world system deployment workflow

---

## ⚠️ Limitations

* Limited scalability depending on EC2 instance type
* Basic UI/UX (dependent on WordPress theme)
* Time conversion accuracy relies on plugin/API used

---

## 🔮 Future Improvements

* Use AWS RDS for managed database
* Implement auto-scaling for high availability
* Improve UI with custom frontend (React or similar)
* Add user personalization (favorite time zones)
* Integrate APIs for enhanced accuracy and features

---

## 👤 Author

ARJUN BHASKARAN RAJ
Murdoch University
ICT171 – Introduction to Server Environment and Architectures

---

## 📄 License

This project is for academic purposes and may be reused or modified for learning and demonstration.
