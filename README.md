# 🚗 Parking Lot Management System

**Project by [codewithaimii](https://github.com/codewithaimii)**  
📅 *Developed in (2022) 
💻 *Language Used: C*

## 📌 Project Overview

The **Parking Lot Management System** is a console-based application developed in C that manages the parking of four types of vehicles: **Cars, Bikes, Auto Rickshaws, and Buses**. It keeps track of each vehicle's entry and exit, computes parking fees, and monitors space availability.

This project is implemented using **Dynamic Data Structures (Linked Lists)** and basic **DSA concepts**.

## 💡 Features

- 🚘 Add or remove Cars, Bikes, Rickshaws, and Buses
- 💰 Calculate total money collected per vehicle type
- 📊 Check real-time availability of parking space
- 📃 User-friendly terminal interface
- 📦 Uses linked lists to manage vehicle records

## 🧑‍💻 Functions Implemented

- `Addcar()`, `Findcar()`, `Carcost()`
- `Addbike()`, `Findbike()`, `Bikecost()`
- `Addrickshaw()`, `Findrickshaw()`, `Rickcost()`
- `Addbus()`, `Findbus()`, `Buscost()`
- `Total()` – Total revenue calculation  
- `Space()` – Displays count of each parked vehicle type

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/codewithaimii/parking-management-system.git
   cd parking-lot-management-system
//compile and run
gcc parking_system.c -o parking_system
./parking_system
