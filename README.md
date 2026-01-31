# Hotel-Management-System
A Hotel Management System is a software application that automates hotel operations such as room booking, check-in and check-out, customer records, billing, and payments. It reduces manual work, improves accuracy, stores data securely, and helps hotel staff manage services efficiently while enhancing customer satisfaction.
CREATE DATABASE hotel_db;

USE hotel_db;

CREATE TABLE reservations (
    reservation_id INT PRIMARY KEY AUTO_INCREMENT,
    guest_id INT NOT NULL,
    guest_name VARCHAR(100),
    contact_number VARCHAR(20),
    room_number INT,
    check_in DATETIME DEFAULT CURRENT_TIMESTAMP,
    check_out DATETIME
);



