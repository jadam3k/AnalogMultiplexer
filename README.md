# Analog Multiplexer Project

This is a simple **analog multiplexer** I put together.  
It allows me to connect multiple analog components, like sensors, to a single input on a microcontroller.  

I built this project mainly as a **learning exercise** to get more comfortable with how multiplexers work in real-life circuits.

---

## Bill of Materials (BOM)

Here is the list of components used in this project.  
Where possible, I have added links to datasheets for reference.

| ID | Component Name             | Description                                 | Quantity | Datasheet / Link |
| -- | -------------------------- | ------------------------------------------- | -------- | ---------------- |
| 1  | 2-pin 2.54mm Female Header | Single row, 2.54 mm pitch female PCB header | 1        | [Link](https://www.mouser.com/ProductDetail/571-254-2X1?qs=sGAEpiMZZMtKAwz4oB5cEo8I%2FbL0OeGz) |
| 2  | 8-pin 2.54mm Female Header | Single row, 2.54 mm pitch female PCB header | 1        | [Link](https://www.mouser.com/ProductDetail/571-254-8X1?qs=sGAEpiMZZMtKAwz4oB5cEo8I%2FbL0OeGz) |
| 3  | 4-pin 2.54mm Female Header | Single row, 2.54 mm pitch female PCB header | 1        | [Link](https://www.mouser.com/ProductDetail/571-254-4X1?qs=sGAEpiMZZMtKAwz4oB5cEo8I%2FbL0OeGz) |
| 4  | CD74HC4052E                | 2-channel 4:1 analog multiplexer IC         | 1        | [Datasheet](https://www.ti.com/lit/ds/symlink/cd74hc4052.pdf) |
| 5  | DW127R-22-06-34            | 6-pin wire-to-board connector               | 1        | [Link](https://www.dealextreme.com/p/dw127r-wire-to-board-connector-6-pin-142327) |

---

## Project Images

Below are some pictures of the multiplexer in action:

**1. Full View of the PCB**  
<img width="652" height="596" alt="PCB Overview" src="https://github.com/user-attachments/assets/6d40bc70-c6a9-423e-afbd-5179e53d3230" />

**2. Close-up of the Headers**  
<img width="473" height="445" alt="Headers Close-up" src="https://github.com/user-attachments/assets/7089b537-dd87-413f-9e7d-c16c4ce571e3" />

**3. Multiplexer Wiring**  
<img width="570" height="527" alt="Wiring Diagram" src="https://github.com/user-attachments/assets/19c8da5b-c72e-4e09-9b3e-44f69507230c" />

---

## How it Works

1. The **CD74HC4052E** acts as a 2-channel analog multiplexer.  
2. The microcontroller selects which sensor to read vi
