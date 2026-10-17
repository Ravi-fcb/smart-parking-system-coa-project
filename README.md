# 🚗 Parking Management System in Assembly Language

A menu-driven **Parking Management System** developed using x86 Assembly Language as part of the Computer Organization and Architecture (COA) project. The program manages vehicle parking, slot allocation, parking duration, billing, and revenue records through a command-line interface.

## 📌 Features

- **Vehicle Categories:** Supports 2-wheelers, 4-wheelers, and 8-wheelers.
- **Customizable Capacity:** Set parking capacity between 10 and 99 slots.
- **Automatic Slot Allocation:** Assigns available parking slots based on vehicle category.
- **Parking Duration:** Accepts parking duration in days or hours.
- **Automated Billing:** Calculates parking charges according to vehicle type and duration.
- **Vehicle Exit:** Removes vehicles from occupied slots and updates records.
- **Parking Records:** Displays total vehicles, category-wise counts, available spaces, and revenue.
- **Zone Management:** Divides parking spaces into separate zones for different vehicle categories.
- **Record Reset:** Clears parking records and resets the system.

## 🚘 Vehicle Categories and Charges

| Vehicle Type | Daily Charge | Hourly Charge |
|---|---:|---:|
| 2-Wheeler | 100 | 10 |
| 4-Wheeler | 200 | 20 |
| 8-Wheeler | 300 | 30 |

*Note: Charges are defined in the source code and can be modified as required.*

## 🛠️ Technologies Used

- **Language:** x86 Assembly Language
- **Assembler Syntax:** MASM/TASM-style syntax
- **Execution Environment:** DOS-compatible 16-bit environment
- **System Services:** DOS interrupts (`INT 21h`)

## ⚙️ How It Works

1. Enter the total parking capacity.
2. Select an operation from the menu.
3. Choose a vehicle category to park a vehicle.
4. Enter the parking duration in days or hours.
5. The program assigns an available slot and records the vehicle details.
6. When a vehicle leaves, enter its slot number to calculate the parking fee.
7. View parking records to check revenue, occupied slots, and available spaces.
8. Reset records or exit the program when required.

## 📋 Menu Options

| Option | Operation |
|---|---|
| 1 | Park a 2-wheeler |
| 2 | Park a 4-wheeler |
| 3 | Park an 8-wheeler |
| 4 | View parking records |
| 5 | Delete/reset records |
| 6 | Remove a vehicle and calculate its fee |
| 7 | Exit the program |

## 🧠 Concepts Demonstrated

- Assembly language programming
- Registers and memory addressing
- Arrays and indexed addressing
- Procedures and subroutines
- Conditional and unconditional jumps
- Loops and arithmetic operations
- Keyboard input and console output using DOS interrupts
- Slot allocation and capacity management
- Billing calculations and record tracking

## ▶️ How to Run

This program uses 16-bit DOS-style assembly instructions and DOS interrupts. It requires a compatible assembler and execution environment.

1. Install a compatible assembler, such as **TASM or MASM**, or use an appropriate DOS development environment.
2. Save the source code as `parking.asm`.
3. Assemble and link the program using your chosen toolchain.
4. Run the generated executable in DOSBox or another compatible DOS environment.

The exact commands depend on the assembler and linker being used.

## 🎯 Project Objective

The objective of this project is to apply Computer Organization and Architecture concepts through a practical assembly language application. It demonstrates how low-level programming can be used to manage memory, process user input, perform arithmetic calculations, and implement a functional parking management system.
