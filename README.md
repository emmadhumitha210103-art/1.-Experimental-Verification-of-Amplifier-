#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

<img width="653" height="407" alt="image" src="https://github.com/user-attachments/assets/98fb2537-c4bc-4606-b2a9-5d10c02f1c3e" />



MODEL GRAPH 

<img width="1280" height="682" alt="image" src="https://github.com/user-attachments/assets/ca414651-bed9-4675-a143-67218fd1e3fc" />



DESIGN:

<img width="1280" height="446" alt="image" src="https://github.com/user-attachments/assets/6d758b59-47c9-470d-965a-8a839405b700" />

<img width="1280" height="484" alt="image" src="https://github.com/user-attachments/assets/c942cbbc-f1b2-4b88-a955-63ad89a17766" />

<img width="1244" height="1013" alt="image" src="https://github.com/user-attachments/assets/45f33e22-c4ac-4fe5-b760-8f650c79c212" />




Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

<img width="653" height="340" alt="image" src="https://github.com/user-attachments/assets/a1f0ab23-9e3d-404f-8a79-06325ee0f2e9" />
		

<img width="1280" height="659" alt="image" src="https://github.com/user-attachments/assets/4ce9f4a9-8585-42c2-bd11-85186a649e2b" />



---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="807" height="1280" alt="image" src="https://github.com/user-attachments/assets/58026c41-a1d4-4233-9a92-276f860555df" />

<img width="685" height="543" alt="image" src="https://github.com/user-attachments/assets/27fd4184-e7c5-4daf-b814-cde69ad7281b" />




---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


<img width="1280" height="543" alt="image" src="https://github.com/user-attachments/assets/8fc7d0ee-b27f-45f7-bb1e-ebf33d92b3a3" />

---

## MODEL GRAPH

<img width="1280" height="669" alt="image" src="https://github.com/user-attachments/assets/3f355788-b33f-4711-9bf4-9cdc497f2f50" />

---
DESIGN:

<img width="1280" height="549" alt="image" src="https://github.com/user-attachments/assets/06e15c38-aa24-4704-acd9-3ead323e8f70" />

<img width="1206" height="1006" alt="image" src="https://github.com/user-attachments/assets/b6f36098-c311-44c7-a3f5-f327ad2bb95c" />


---

PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

<img width="1280" height="782" alt="image" src="https://github.com/user-attachments/assets/5f4fc165-f88b-4c2f-8543-209457e882a6" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="724" height="543" alt="image" src="https://github.com/user-attachments/assets/04b714ba-b7a8-4c9e-b1a7-9c64979b188d" />

<img width="860" height="1280" alt="image" src="https://github.com/user-attachments/assets/45a86de3-f3a6-44a4-8dac-ef49a3a97a80" />




---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1

## CIRCUIT DIAGRAM

<img width="1280" height="539" alt="image" src="https://github.com/user-attachments/assets/d3830ab3-2a39-4762-99d3-17e5502c24f1" />


## MODEL GRAPH

<img width="1280" height="540" alt="image" src="https://github.com/user-attachments/assets/8de414ef-339b-4e90-8c06-32475d7698d0" />

---

## DESIGN

<img width="1280" height="587" alt="image" src="https://github.com/user-attachments/assets/1ca8d105-8421-444b-a1c7-238c9f65948d" />

<img width="1134" height="1260" alt="image" src="https://github.com/user-attachments/assets/1790e829-737a-4222-943d-8d9b9d7621fe" />




### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

<img width="1280" height="742" alt="image" src="https://github.com/user-attachments/assets/5cd8b934-3901-4183-8c6f-34317eb8395c" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="894" height="1280" alt="image" src="https://github.com/user-attachments/assets/c2cdbab7-5fb7-4636-ace1-a3cfc8d98f71" />



---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="1134" height="906" alt="image" src="https://github.com/user-attachments/assets/bd8bb80e-d303-4deb-868b-1cc49323ab07" />



PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

<img width="1280" height="642" alt="image" src="https://github.com/user-attachments/assets/acf646a6-45d3-4b12-806d-99554d167ab1" />

<img width="982" height="1201" alt="image" src="https://github.com/user-attachments/assets/9b2e3d0f-6d49-4ebe-844b-362707a78707" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="924" height="1280" alt="image" src="https://github.com/user-attachments/assets/bc61d996-ca78-4278-80b1-bed00c172b5e" />



---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
