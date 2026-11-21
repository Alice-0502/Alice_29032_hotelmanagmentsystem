# Hotel Management System

## 1. Project Information

**Project Title:** Hotel Management System  
**Student Name:** UMUTONI HIGIRO Alice  
**Student ID:** 29032  
**Course:** INSY 8311 – Database Development with PL/SQL  
**Instructor:** Eric Maniraguha  
**Academic Year:** 2026–2027, Semester I

---

## 2. Problem Statement

Many hotels face challenges managing reservations for conference halls, wedding venues, banquet halls, restaurant tables, spa services and other facilities due to manual processes and disconnected management systems. These challenges can result in booking conflicts, poor resource utilization, difficulties tracking payments and inefficient management of customer information.

## 3. Project Objectives

### Main Objective

To develop an Oracle-based Hotel Management System that centralizes hotel facility reservations, customer information, payment tracking and availability management to improve operational efficiency and customer satisfaction.

### Specific Objectives

- To design and develop a centralized database for managing hotel customers, facilities, reservations and payments.
- To implement reservation and availability management functionalities that prevent double bookings.
- To develop PL/SQL procedures, functions, triggers and packages for automating hotel reservation and payment operations.
- To generate reports that help hotel administrators monitor reservations, payments and facility utilization.
- To develop an interactive user interface for managing hotel operations efficiently.

---

## 4. Data Source

**Dataset Name:** Hotel Booking Demand Dataset

**Source:** Kaggle

**Link:** https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

The dataset contains hotel booking information, including customer details, arrival dates, booking status, cancellations, hotel types, meal preferences and other reservation-related information.

The dataset will be used for database development, data analysis, testing and generating reports.

---

## 5. Proposed Innovation

The project will implement an interactive user interface using **Oracle APEX** connected to the Oracle database.

The application will allow hotel staff to:

- Register and manage customers.
- View available facilities and services.
- Create and manage reservations.
- Check facility availability.
- Record and track payments.
- View reservation and payment reports.

The system will use PL/SQL business rules to prevent double bookings and ensure accurate reservation and payment management.

---

## 6. Planned Database Tables

The following tables are planned for the system:

| Table Name | Description |
|---|---|
| CUSTOMER | Stores customer information. |
| EMPLOYEE | Stores hotel employee information. |
| FACILITY | Stores hotel facilities such as conference halls, wedding venues and banquet halls. |
| SERVICE | Stores additional hotel services such as spa and restaurant services. |
| RESERVATION | Stores customer reservation information. |
| RESERVATION_DETAIL | Stores the facilities or services associated with each reservation. |
| PAYMENT | Stores customer payment information. |
| ROOM | Stores hotel room information. |

---

## 7. Planned PL/SQL Features

| PL/SQL Feature | Purpose |
|---|---|
| Procedures | Register customers, create reservations and record payments. |
| Functions | Calculate reservation costs, payments and outstanding balances. |
| Cursors | Retrieve reservation and payment information for reports. |
| Packages | Organize related customer, reservation and payment procedures. |
| Triggers | Prevent double bookings and automatically enforce database rules. |
| Exceptions | Handle errors such as unavailable facilities, invalid payments and incorrect reservation information. |

---

## 8. References

1. Kaggle. (n.d.). *Hotel booking demand dataset*. https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

2. Oracle. (n.d.). *Oracle Database documentation*. https://docs.oracle.com/en/database/oracle/oracle-database/

3. Oracle Hospitality. (n.d.). *Oracle Hospitality solutions*. https://www.oracle.com/hospitality/

Additional research papers and reports will be included after completing the project research.

---
