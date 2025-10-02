# 🔢 16-bit ALU 

This project implements a **16-bit ALU** in **Verilog HDL**, designed as part of an assignment to practise digital design and hardware description languages.  
The ALU integrates arithmetic, logic, shift, and comparison functionalities, and is fully tested with 28 test cases.

---

## 📑 Features
- **Signed Arithmetic Operations**  
  - Addition  
  - Subtraction  
  - Multiplication  
  - Division  

- **Logic Operations**  
  - AND  
  - OR  
  - NAND  
  - NOR  

- **Comparison Operations**  
  - Equal (`A == B`)  
  - Greater (`A > B`)  
  - Less (`A < B`)  
  - NOP  

- **Shift Operations**  
  - `A >> 1`  
  - `A << 1`  
  - `B >> 1`  
  - `B << 1`  

- **Decoder Unit** to enable each functional block based on `ALU_FUNC[3:2]`.

---

## 🏗️ Project Structure
The project is modularised into 6 Verilog files:

