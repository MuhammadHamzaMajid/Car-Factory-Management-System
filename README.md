# Car Factory Management System

## Overview
The Car Factory Management System is a C-based console application designed to simulate and manage the production, testing, and sales processes of a car factory. It allows factory managers to plan car production according to a budget, track resource allocation, monitor testing results, and record sales data.  
This system handles multiple car types (Car A, Car B, Car C) and includes features such as material tracking, employee management, electricity consumption, manufacturing time, and testing outcomes.

---

## Features
- Budget-based production planning:  
  Calculate maximum cars that can be produced based on imported and local material costs and employee salaries.
  
- Custom production ratios:  
  Allows managers to set the production ratio of different car types or minimize the production of a specific car type.
  
- Resource tracking:  
  Automatically tracks imported and local material usage, employees required, and total cost for production.
  
- Manufacturing management:  
  Records electricity consumption and time duration for each car type in the production line.
  
- Testing management:  
  Records car failures in multiple test stages to monitor quality control.
  
- Sales tracking:  
  Tracks sales of each car type over a specified duration and highlights cars not selling in the desired quantity.
  
- Secure access:  
  Password-protected access for different managerial roles (factory manager, assembly manager, testing manager, sales manager).
  
- Persistent storage:  
  Saves production ratios, electricity consumption, manufacturing times, testing results, and sales to text files for record-keeping.

---

## Files
- Project.txt – Contains initial project parameters such as budget, costs, and minimum car production requirements.  
- Passwords.txt – Stores passwords for different managerial roles.  
- Car values.txt – Intermediate file generated from Project.txt for numeric values.  
- Ratios.txt – Records the production ratios of cars.  
- Time Duration.txt – Logs time taken for manufacturing, hiring, and parts arrival.  
- Electricity Consumption.txt – Logs electricity used for car production.  
- Testing.txt – Stores testing results of cars.  
- Car Sales.txt – Stores car sales information over time.

---

   ```bash
   gcc CarFactory.c -o CarFactory
