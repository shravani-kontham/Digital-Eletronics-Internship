
# DIGITAL ELECTRONICS 
# Table of Contents

- [What is Digital Electronics](#what-is-digital-electronics)
- [Applications of Digital Electronics](#applications-of-digital-electronics)
- [Digital vs Analog Signals](#digital-vs-analog-signals)
- [Logic Levels](#logic-levels)
- [Number Systems in Digital Electronics](#number-systems-in-digital-electronics)
- [Conversion Between Number Systems](#conversion-between-number-systems) 
- [Basic Logic Gates](#basic-logic-gates)
- [Integrated Circuits-IC's](#integrated-circuits-ics)
- [Implementation of Logic Gates](#implementation-of-logic-gates)

# What is Digital Electronics
Digital electronics is a branch of electronics that deals with discrete signals and circuits, as opposed to analog electronics which handles continuous signals. Digital circuits use binary logic (0 and 1) and Boolean algebra to process and store information. These circuits are the foundation of modern computers, digital communications, and numerous other technological applications. 
# Applications Of Digital Electronics
1. computation
2. communication systems
3. Automation and robotics
4. Iot smart devices
5. Home appliances
6. medical devices
7. Transportation 
8. military
# Digital vs Analog signals
|**Digital signal**                         |**Analog Signal**                      | 
|-------------------------------------------|---------------------------------------|
|continous:They vary smoothly and continuosly over time,They can take on any value within in aspecified range|Discrete: They have specific, defined values,typically represented by 0s and 1s.|
|Infinite Values: They can take on any value within a specified range|Binary: They represent information using binary code, the foundation of digital|
|Examples: Sound waves, light waves, andthe voltage from a battery|Examples: Computer data, digital radio transmissions, and digital image|
|Susceptible to Noise: They can easily be affected by noise and interference during transmission|Noise Immunity: They are more resistant to noise and interference, making them reliable for data transmission|
|Used in: Audio systems, sensors, and traditional communication systems|Used in: Computers, digital communication systems and many modern technologies|


   ![WhatsApp Image 2025-05-09 at 03 19 03_1ac7866a](https://github.com/user-attachments/assets/6932d2d7-16cd-455e-9fc7-293fb30fb6ae)
   # Logic Levels
In digital electronics, a logic level is the voltage representing a specific state,typically a binary digit (0 or1) in a digital circuit. These levels are crucial  for how devices process and transmit data, ensuring reliable communication between components.

 Positive Logic: 0V typically represents 0, and+5V or +3.3V represents 1.
 
 Negative Logic: High voltage represents 0, and low voltage represents 1.
 # Number Systems in Digital Electronics 
 In digital electronics, number systems are crucial for representing and manipulating data within electronic circuits. The most important number systems are binary (base 2), octal (base 8), and hexadecimal (base 16), with decimal (base 10) being used for human understanding. Binary is fundamental because digital systems primarily operate using two states (0 and 1).
 
 ![WhatsApp Image 2025-05-09 at 03 32 37_88748cd3](https://github.com/user-attachments/assets/902e6919-46e9-4c58-bfe1-f86c79ba8226)

# Binary Number System(Base 2)
1. Uses only two digits: 0 and 1. 
2.  Each position represents a power of 2.
  
  Example: 10101 (binary)
  
  = 21 + 23 + 20
  
  = 101 (decimal)
# Decimal Number System(Base 10)
1.  Each position represents a power of 10.
2.  The system we commonly use in everyday life.
  
 Example: 234 (decimal) 
 
 = 2 * 10^2 + 3 * 10^1 + 4 * 10^0
 
 = 234
# Hexa Decimal Number System(Base 16)
1.  Uses digits 0-9 and letters A-F (A=10, B=11, C=12, D=13, E=14, F=15).
2.  Each position represents a power of 16.
3.  Used as a shorthand for binary (each 4-bit group of binary can be
   represented by one hexadecimal digit).

  Example: AB (hexadecimal) 

  = 10 * 16^1 + 11 * 16^0
  
  = 171 (decimal)
# Octal Number System(Base 8)
1. Uses digits 0-7. 
2. Each position represents a power of 8. 
3. Used as a shorthand for binary (each 3-bit group of binary can be represented by one octal digit).
 
Example: 234 (octal)

= 2 * 8^2 + 3 * 8^1 + 4 * 8^0

= 156 (decimal)

# Conversion Between Number Systems
 # 1.  Decimal → Binary
Method: Divide the number by 2 repeatedly, write down remainders in reverse.

Example:

 13 ÷ 2= 6 R1
 
 6 ÷ 2= 3 R0
 
 3 ÷ 2= 1 R1
 
 1 ÷ 2 = 0 R1
 
 → Binary: 1101
 
 # 2. Binary → Decimal
Method: Multiply each binary digit by 2 raised to its position (from right to left), then sum.

Example:

1101 

= 1×2³ + 1×2² + 0×2¹ + 1×2⁰ 

= 8 + 4 + 0 + 1

= 13

 # 3.  Decimal → Octal
Method: Divide the decimal by 8 repeatedly, reverse remainders.

Example:

65 ÷ 8 = 8 R1

8 ÷ 8 = 1 R0

1 ÷ 8 = 0 R1

→ Octal: 101
# 4. Octal → Decimal
Method: Multiply each octal digit by 8^position and sum.

Example:

101
= 1×8² + 0×8¹ + 1×8⁰

= 64 + 0 + 1

= 65
# 5.  Decimal → Hexadecimal
Method: Divide by 16 repeatedly, convert remainders >9 to A–F, reverse.

Example:
254 ÷ 16 = 15 R14

→ F and E

→ Hex: FE
 # 6.   Hexadecimal → Decimal
Method: Convert each digit to decimal and multiply by 16^position.

Example:

FE = F×16¹ + E×16⁰

= 15×16 + 14 

= 240 + 14

= 254
# 7.  Binary → Octal
Method: Group binary digits in 3s from right, convert each group to decimal.

Example:

110101
= 000 110 101

→ 6 5

→ Octal: 65
 # 8. Octal → Binary
Method: Convert each octal digit to 3-bit binary.

Example:

65

→ 6= 110, 5

= 101 
→ Binary: 110101
# 9. Binary → Hexadecimal
Method: Group binary digits in 4s from right, convert to hex.

Example:
11111110
= 1111 1110
→ F E 
→ Hex: FE
 # 10.  Hexadecimal → Binary
Method: Convert each hex digit to 4-bit binary.

Example:

FE
→ F= 1111,

E = 1110

→ Binary: 1111111
# 11. Octal → Hexadecimal
Method: Octal → Binary (3 bits), then Binary → Hex (4 bits).

Example:

65 (Octal) 

→ 110101 (Binary)

→ 0001 1010 1 

= 1A1 (Hex, pad as needed)
# 12.  Hexadecimal → Octal
Method: Hex → Binary (4 bits), then Binary → Octal (3 bits).

Example:

FE (Hex) 

→ 1111 1110 

→ Group in 3s: 001 111 111 0

→ pad: 000 111 111 010

→ 3 7 2 

→ Octal: 372


# BASIC LOGIC GATES

# 1. AND GATE
![WhatsApp Image 2025-05-13 at 08 25 31_ddbdedde](https://github.com/user-attachments/assets/18d879fa-c403-4ef8-8685-dae258bb596d)

# Function
An AND gate is a fundamental logic gate in digital electronics that outputs a 1 (true) only if all its inputs are 1 (true). Otherwise, it outputs a 0 (false). The output is a logical product of the inputs.

# Truth Table

|A|	B	|A AND B|
|----|-----|-----|
|0	|0|	0|
|0	|1|	0|
|1|	0|	0|
|1|	1|	1|

# 2. OR GATE
![WhatsApp Image 2025-05-13 at 08 25 31_b054052b](https://github.com/user-attachments/assets/484e0bd0-ce46-497f-9721-2c8ad620dabd)

# Function
The OR gate is a digital logic gate that implements logical disjunction. The OR gate outputs "true" if any of its inputs is "true"; otherwise it outputs "false". The input and output states are normally represented by different voltage levels.
# Truth Table
|A|B|A OR B|
|-|-|------|
|0|	0|	0|
|0|	1	|1|
|1|	0|	1|
|1|	1	|1|

# 3. NOT GATE
![WhatsApp Image 2025-05-13 at 08 32 15_99d4c0e2](https://github.com/user-attachments/assets/e53ffa18-b5f4-463b-8c36-319c97f43674)

# Function
A NOT gate, also known as an inverter, is a fundamental digital logic gate that reverses its input signal. It has one input and one output. If the input is high (1), the output is low (0), and vice versa.

# Truth Table
|INPUT|	OUTPUT|
|-----|-------|
|A	| A'|
|0|	1|
|1	|0|

# 4. NAND GATE
![WhatsApp Image 2025-05-19 at 07 29 27_a65bbb54](https://github.com/user-attachments/assets/f2c1830e-4d96-4196-8d86-d7e6631be21b)

# Function
A two-input NAND gate is a fundamental digital logic gate that produces an output only when either or both inputs are low. In simpler terms, it gives a high output (1) unless both inputs are high (1), in which case, it gives a low output (0).

# Truth Table
|A|B|X|
|--|--|-|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|

# 5. NOR GATE
![WhatsApp Image 2025-05-19 at 07 38 50_e41981bb](https://github.com/user-attachments/assets/607815ff-8aee-4696-bcf2-e28cc9bc494b)

# Function
A NOR gate is a digital logic gate that gives an output of 0 when any of its inputs are 1, otherwise 1. NOR gates can be made to produce a variety of logic gates, including OR and AND gates. The output of the NOR gate is a logic 0 as long as the input voltage is below the threshold.

# Truth Table
|A|B|OUTPUT|
|--|--|--|
|0|0|1|
|1|0|1|
|0|1|0|
|1|1|0|

 # 6. XOR GATE 
 ![WhatsApp Image 2025-05-19 at 07 42 55_7585709f](https://github.com/user-attachments/assets/692553fa-c7a1-4017-9d22-df3806c8ab24)

 # Function
 An XOR (Exclusive OR) gate is a digital logic gate that produces a high (1) output only when the inputs are different. If both inputs are the same (both 0 or both 1), the output is low (0). It's also known as an "either/or, but not both" gate.

# Truth Table
|A|B|OUTPUT|
|--|--|--|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

# 7. XNOR GATE
![WhatsApp Image 2025-05-19 at 07 49 27_c7f03487](https://github.com/user-attachments/assets/258dc465-2119-4fbf-ad59-1eb950d01acd)

# Function
An XNOR (Exclusive NOR) gate is a digital logic gate that produces a high (1) output if both inputs are the same (both 0 or both 1), and a low (0) output if the inputs are different. It's essentially the inverse of an XOR gate.

# Truth Table
|A|B|OUTPUT|
|--|--|--|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|1|

# Integrated Circuits-IC's

# What is an Integrated Circuit

Integrated circuits (ICs) also called microelectric chips are used to create a device that can perform certain electrical operations such as signal amplification which is called a transistor from the combination of words of the transfer and resistor. Solid-state electronics is the name given to the field of research into how to make electronic devices out of solid materials.

# Types of Logic Gates
| *Logic Gate* | *IC (TTL - 74 series)*   | *Gates per IC* | *No. of Inputs* |
| -------------- | ------------------------ |  ---------------- | ----------------- |
| AND            | 7408                     |    4                | 2                 |
| OR             | 7432                     | 4                | 2                 |
| NOT (Inverter) | 7404                     | 6                | 1                 |
| NAND           | 7400                     |  4                | 2                 |
| NOR            | 7402                     | 4                | 2                 |
| XOR            | 7486                     |  4                | 2                 |
| XNOR           | 74266 / 74LS266 (quad)   |  4                | 2                 |

# Applications of Logic Gates
| *Logic Gate* |  *Operation* | *Common Applications*                                                                 |
| -------------- |  ------------- | --------------------------------------------------------------------------------------- |
| AND            | A·B           | - Digital multiplication<br>- Input validation systems<br>- Alarm circuits              |
| OR             | A + B         | - Decision-making circuits<br>- Control systems<br>- Lighting systems (either/or input) |
| NOT            |¬A or A̅      | - Inverters<br>- Signal toggling<br>- Memory control systems                            |
| NAND           |  ¬(A·B)        | - Universal gate<br>- Logic circuit design<br>- Burglar alarms                          |
| NOR            |  ¬(A + B)      | - Universal gate<br>- Microprocessor control logic<br>- Simple memory storage           |
| XOR            | A ⊕ B         | - Parity checkers<br>- Adders/subtractors<br>- Data comparison                          |
| XNOR           | ¬(A ⊕ B)      | - Equality detectors<br>- Digital comparators<br>- Error detection                      |

# 1. IC 7408 - AND GATE
  ![WhatsApp Image 2025-05-23 at 08 43 58_8e6a5b6e](https://github.com/user-attachments/assets/787ca7cc-08d2-41ee-b011-b662a988db90)
![WhatsApp Image 2025-05-23 at 08 46 04_3ff86fb0](https://github.com/user-attachments/assets/02ef5524-c987-4062-a5be-acc24ed4dd37)

| *Pin No.* | *Pin Name* | *Description*              |
| ----------- | ------------ | ---------------------------- |
| 1           | A1           | Input of 1st AND gate        |
| 2           | B1           | Input of 1st AND gate        |
| 3           | Y1           | Output of 1st AND gate       |
| 4           | A2           | Input of 2nd AND gate        |
| 5           | B2           | Input of 2nd AND gate        |
| 6           | Y2           | Output of 2nd AND gate       |
| 7           | GND          | Ground (0V)                  |
| 8           | Y3           | Output of 3rd AND gate       |
| 9           | A3           | Input of 3rd AND gate        |
| 10          | B3           | Input of 3rd AND gate        |
| 11          | Y4           | Output of 4th AND gate       |
| 12          | A4           | Input of 4th AND gate        |
| 13          | B4           | Input of 4th AND gate        |
| 14          | Vcc          | Supply Voltage (+5V typical) |

![IC 7408 AND GATE](https://github.com/user-attachments/assets/00216a09-f75f-4e36-acc2-c256dfbc71f4)

# AND GATE in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/0sTppHUZUlK-ic-7408-and-gate?sharecode=t4oZbU-YAouNLIISGuMd5VM5D-to5Axt8Plmw27JkuI)
#  2. IC 7432 - OR GATE
![WhatsApp Image 2025-05-23 at 08 52 25_9e97e3cd](https://github.com/user-attachments/assets/720f202e-55c8-42eb-9d7b-f5c64329dbbf)
![WhatsApp Image 2025-05-23 at 08 56 47_0ace2b3d](https://github.com/user-attachments/assets/88664fe4-53c3-489f-b272-6945a7a24ad9)

| *Pin No.* | *Pin Name* | *Description*                |
| ----------- | ------------ | ------------------------------ |
| 1           | A1           | Input of Gate 1                |
| 2           | B1           | Input of Gate 1                |
| 3           | Y1           | Output of Gate 1               |
| 4           | A2           | Input of Gate 2                |
| 5           | B2           | Input of Gate 2                |
| 6           | Y2           | Output of Gate 2               |
| 7           | GND          | Ground (0V)                    |
| 8           | Y3           | Output of Gate 3               |
| 9           | A3           | Input of Gate 3                |
| 10          | B3           | Input of Gate 3                |
| 11          | Y4           | Output of Gate 4               |
| 12          | A4           | Input of Gate 4                |
| 13          | B4           | Input of Gate 4                |
| 14          | Vcc          | Supply Voltage (+5V typically) |

![IC 7432  OR GATE](https://github.com/user-attachments/assets/b4d8cc02-380f-4594-b276-99f4a0f39ee7)

# OR GATE in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/9w6VttJb0ST-ic-7432-or-gate?sharecode=bJLTvfweXC0uOJjEZUzCuSxNuuAlCtHPR56JA6lyeeE)

# 3. IC 7404  - NOT GATE
![WhatsApp Image 2025-05-23 at 08 59 16_bd1bbf22](https://github.com/user-attachments/assets/54d572c6-fcae-4682-b918-6916cf5741be)
![WhatsApp Image 2025-05-19 at 11 12 51_6735177f](https://github.com/user-attachments/assets/184879f4-cf82-4b95-8f92-2fb9f02517af)

| *Pin Number* | *Function*  | *Description*              |
| -------------- | ------------- | ---------------------------- |
| 1              | Input 1 (A1)  | Input of inverter 1          |
| 2              | Output 1 (Y1) | Output of inverter 1         |
| 3              | Input 2 (A2)  | Input of inverter 2          |
| 4              | Output 2 (Y2) | Output of inverter 2         |
| 5              | Input 3 (A3)  | Input of inverter 3          |
| 6              | Output 3 (Y3) | Output of inverter 3         |
| 7              | GND           | Ground (0V)                  |
| 8              | Output 4 (Y4) | Output of inverter 4         |
| 9              | Input 4 (A4)  | Input of inverter 4          |
| 10             | Output 5 (Y5) | Output of inverter 5         |
| 11             | Input 5 (A5)  | Input of inverter 5          |
| 12             | Output 6 (Y6) | Output of inverter 6         |
| 13             | Input 6 (A6)  | Input of inverter 6          |
| 14             | Vcc           | Supply Voltage (+5V typical) |

![IC 7404 NOT GATE](https://github.com/user-attachments/assets/ea3b559b-99f4-4ef9-8a65-e80bd85c688c)

# NOT GATE in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/94e2e3GHMnL-ic-7404-not-gate?sharecode=7v-_6UfH2bg5xc1Yqm_J-cg9ru8vO3FhDtAw-AzDnWs)

# 4. IC 7400 - NAND GATAE
![WhatsApp Image 2025-05-23 at 09 05 35_09ee88f3](https://github.com/user-attachments/assets/538f4d95-491e-4a82-a70a-7f807a8c7903)
![WhatsApp Image 2025-05-23 at 09 09 52_de7c06b6](https://github.com/user-attachments/assets/59497e82-a18d-4e62-979e-5ec3b266cd71)

| *Pin No.* | *Function*      | *Description*                 |
| ----------- | ----------------- | ------------------------------- |
| 1           | Input A (Gate 1)  | First input of NAND gate 1      |
| 2           | Input B (Gate 1)  | Second input of NAND gate 1     |
| 3           | Output Y (Gate 1) | Output of NAND gate 1           |
| 4           | Input A (Gate 2)  | First input of NAND gate 2      |
| 5           | Input B (Gate 2)  | Second input of NAND gate 2     |
| 6           | Output Y (Gate 2) | Output of NAND gate 2           |
| 7           | GND               | Ground (0V)                     |
| 8           | Output Y (Gate 3) | Output of NAND gate 3           |
| 9           | Input A (Gate 3)  | First input of NAND gate 3      |
| 10          | Input B (Gate 3)  | Second input of NAND gate 3     |
| 11          | Output Y (Gate 4) | Output of NAND gate 4           |
| 12          | Input A (Gate 4)  | First input of NAND gate 4      |
| 13          | Input B (Gate 4)  | Second input of NAND gate 4     |
| 14          | Vcc               | Positive Supply (+5V typically) |

![IC 7400 NAND GATE](https://github.com/user-attachments/assets/2eba25bf-057c-4f35-99d6-1eaadb502412)

# NAND GATE in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/9Po3zJ3ileW-ic-7400-nand-gate?sharecode=hhBRD_8BWjVYBdHqh130OpxsLIEZcMKDeFGPKEirxGM)
# 5. IC 7402 - NOR GATE
![WhatsApp Image 2025-05-21 at 11 47 02_afcba74d](https://github.com/user-attachments/assets/0b8f80fc-e439-4c64-9afe-4d9dbba00629)
![WhatsApp Image 2025-05-19 at 11 18 44_00aca054](https://github.com/user-attachments/assets/3a31aaaa-b3da-464b-aa34-d7b91cd6e1b7)

| *Pin No.* | *Function* | *Description*      |
| ----------- | ------------ | -------------------- |
| 1           | A1           | Input of Gate 1      |
| 2           | B1           | Input of Gate 1      |
| 3           | Y1           | Output of Gate 1     |
| 4           | A2           | Input of Gate 2      |
| 5           | B2           | Input of Gate 2      |
| 6           | Y2           | Output of Gate 2     |
| 7           | GND          | Ground (0V)          |
| 8           | Y3           | Output of Gate 3     |
| 9           | A3           | Input of Gate 3      |
| 10          | B3           | Input of Gate 3      |
| 11          | Y4           | Output of Gate 4     |
| 12          | A4           | Input of Gate 4      |
| 13          | B4           | Input of Gate 4      |
| 14          | Vcc          | Supply Voltage (+5V) |

![IC 7402 NOR GATE](https://github.com/user-attachments/assets/f6ba76a0-1227-46b5-b943-de2c3f5fe0bc)

# NOR GATE in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/jEeIWYn5v20-ic-7402-nor-gate?sharecode=laAIb4NySdVjSJcZhRA6KsCAghjzmqv-vcU799bPxb8)

# 6. IC 7486 - XOR GATE
![WhatsApp Image 2025-05-23 at 09 28 36_c7ad1fb5](https://github.com/user-attachments/assets/721d7b11-9c2c-4ecb-86d1-d3f5fd304fa2)
![WhatsApp Image 2025-05-23 at 09 27 04_7b0f2c9f](https://github.com/user-attachments/assets/17bf6330-3ed4-4d21-a0b0-3699d9207a49)

| *Pin Number* | *Function* | *Description*              |
| -------------- | ------------ | ---------------------------- |
| 1              | A1           | Input of Gate 1              |
| 2              | B1           | Input of Gate 1              |
| 3              | Y1           | Output of Gate 1             |
| 4              | A2           | Input of Gate 2              |
| 5              | B2           | Input of Gate 2              |
| 6              | Y2           | Output of Gate 2             |
| 7              | GND          | Ground (0V)                  |
| 8              | Y3           | Output of Gate 3             |
| 9              | A3           | Input of Gate 3              |
| 10             | B3           | Input of Gate 3              |
| 11             | Y4           | Output of Gate 4             |
| 12             | A4           | Input of Gate 4              |
| 13             | B4           | Input of Gate 4              |
| 14             | Vcc          | Power Supply (+5V typically) |

![IC 7486 XOR GATE](https://github.com/user-attachments/assets/ca01885a-0b7a-47aa-9f80-d56ccfe188a7)

# XOR GATE in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/l8aRbezkYcQ-ic-7486-xor-gate?sharecode=6zwSAtsK1okoJz1CPdrWznGaO_9-WbFfWCW1MiZ9e98)

# 7. IC 74266 - XNOR GATE
![WhatsApp Image 2025-05-23 at 09 25 16_6b41e107](https://github.com/user-attachments/assets/344d69bb-51e0-46e9-8a93-0b987035876d)
![WhatsApp Image 2025-05-23 at 09 25 17_50981ab5](https://github.com/user-attachments/assets/1586532c-105a-4f9a-83d5-3f1f3abff6e3)

| *Pin Number* | *Pin Name* | *Description*                   |
| -------------- | ------------ | --------------------------------- |
| 1              | A1           | Input of Gate 1                   |
| 2              | B1           | Input of Gate 1                   |
| 3              | A2           | Input of Gate 2                   |
| 4              | B2           | Input of Gate 2                   |
| 5              | Y2           | Output of Gate 2 (Open Collector) |
| 6              | Y1           | Output of Gate 1 (Open Collector) |
| 7              | GND          | Ground                            |
| 8              | Y4           | Output of Gate 4 (Open Collector) |
| 9              | Y3           | Output of Gate 3 (Open Collector) |
| 10             | A3           | Input of Gate 3                   |
| 11             | B3           | Input of Gate 3                   |
| 12             | A4           | Input of Gate 4                   |
| 13             | B4           | Input of Gate 4                   |
| 14             | Vcc          | Supply Voltage (+5V)              |

![XNOR GATE](https://github.com/user-attachments/assets/8bd4bcb1-0c88-4f48-9bc3-2330c90e8d0c)

# XNOR GATE in Tinkercad
[XNOR Gate on Tinkercad](https://www.tinkercad.com/things/1T56sEGsDOo-xnor-gate?sharecode=HB6sePxz1o4CEC5B3Y_nwg2m0epJag6ZtXwe795styg)

# Implementation of Logic Gates

# Implementation of AND OR NOT GATES USING NAND GATE
# AND GATE USING NAND GATE 
![AND USING NAND GATE (1)](https://github.com/user-attachments/assets/b607dad4-3cce-4fe4-905d-005d9b2bc488)
# Circuit in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/fQtNVhY88CC-and-using-nand-gate?sharecode=xV-sHjm4Goc_fhXU2zB4D09fx3FoC_QjgtaWYOcW65l)

# OR GATE USING NAND GATE
![OR USING NAND GATE](https://github.com/user-attachments/assets/27a2219f-0510-42cf-a887-bbab298a05e6)
# Circuit in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/3Ke6SD6kkF9-or-using-nand-gate?sharecode=u8rAeJe5eKM-kJgAlBTxgWXhpUDS1JupiziQfsllVqs)

# NOT GATE USING NAND GATE
![NOT USING NAND GATE](https://github.com/user-attachments/assets/4adbeaa5-e589-40cf-b6bd-6d3facd096ba)
# Circuit in Tinkercad
[Open in Tinkercad ](https://www.tinkercad.com/things/7FKD0IKyhpJ-not-using-nand-gate?sharecode=HvPpa)

# Implementation of AND OR NOT GATES USING NOR GATE
# AND GATE USING NOR GATE
![AND USING NOR GATE](https://github.com/user-attachments/assets/e70d8543-7dbf-4eef-8177-13a2b560db84)
# Circuit in Tinkercad
[Open in Tinkercad](https://www.tinkercad.com/things/h1zbBghokQR-and-using-nor-gate?sharecode=GeQpSz7MQrp8EG_RjMzPekr48k4taT8oeFhMIc7N5-w)

# OR GATE USING NOR GATE
![OR USING NOR GATE](https://github.com/user-attachments/assets/3c9fdac7-6258-4634-9dab-d1af2124a595)
# Circuit in Tinkercad
[Open in Tinkercad](https://www.tinkercad.com/things/faptNwFpFE1-or-using-nor-gate?sharecode=QCxizkmOR7pgj-5uIcOl29znPSDP6uJhy2xi2e7dMgM)

# NOT GATE USING NOR GATE
![NOT USING NOR GATE](https://github.com/user-attachments/assets/a1d9730c-a6a8-4672-bb8a-798d3f3a7847)
# Circuit in Tinkercad 
[Open in Tinkercad](https://www.tinkercad.com/things/b3vQq6p5kvf-not-using-nor-gate?sharecode=5maK3HQQwScx-DIWHlD3MM8Rg5SOJ8bdDlfflgIFets)
