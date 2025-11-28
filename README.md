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

<img width="456" height="212" alt="image" src="https://github.com/user-attachments/assets/aae4dec2-10e2-4394-92bc-749e73e07ebd" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

<img width="521" height="219" alt="image" src="https://github.com/user-attachments/assets/847e1284-ebca-46f7-9eae-e9b385156bbd" />

MODEL GRAPH 

<img width="502" height="211" alt="image" src="https://github.com/user-attachments/assets/2f410124-0602-4fed-bb36-2b61a51e8560" />



DESIGN:
<img width="971" height="417" alt="image" src="https://github.com/user-attachments/assets/b601fba2-79bc-424f-99a4-c52ddd3a9aac" />


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

<img width="556" height="333" alt="image" src="https://github.com/user-attachments/assets/de091d1e-2b39-439c-968c-f9e8ad495e15" />



---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="697" height="694" alt="image" src="https://github.com/user-attachments/assets/6f9bc0be-f617-4121-ac45-d05d3cea4856" />



---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


<img width="1108" height="493" alt="image" src="https://github.com/user-attachments/assets/7a242951-6f3d-46bf-b65b-926c249a76b1" />

---

## MODEL GRAPH


<img width="1067" height="438" alt="image" src="https://github.com/user-attachments/assets/473f29c9-6ae4-458a-8d8d-0fd80778b901" />

Design:

<img width="937" height="372" alt="image" src="https://github.com/user-attachments/assets/99cefae4-cfb6-401e-9e35-067a3de982c2" />

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

<img width="1151" height="619" alt="image" src="https://github.com/user-attachments/assets/be3a7541-823c-4db6-8f1b-4759c6626207" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="647" height="713" alt="image" src="https://github.com/user-attachments/assets/f6af2016-ca50-4d26-98c6-e034ab87372c" />



---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
<img width="511" height="248" alt="image" src="https://github.com/user-attachments/assets/ee7a53fb-23c7-4ff7-9f60-6139577fc736" />

## MODEL GRAPH
<img width="509" height="228" alt="image" src="https://github.com/user-attachments/assets/6a497d81-d257-42a8-840a-f96243dc6bcc" />

---

## DESIGN

<img width="1130" height="608" alt="image" src="https://github.com/user-attachments/assets/a22c742c-8e2f-4940-8643-30dff39a2761" />



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

<img width="510" height="274" alt="image" src="https://github.com/user-attachments/assets/2357dd47-8cd9-4cdc-be76-e98647cec5cb" />


---
## OUT PUT WAVEFORM AND DISCUSSION 
<img width="675" height="578" alt="image" src="https://github.com/user-attachments/assets/8ba2b301-68d9-4a0f-8d6c-610fbe60874b" />



---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

<img width="672" height="736" alt="image" src="https://github.com/user-attachments/assets/43204ce1-de7c-492b-9e23-e651a8ee5d61" />

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

<img width="551" height="336" alt="image" src="https://github.com/user-attachments/assets/da10d045-6584-47d1-8ddf-698b7b869fac" />


---
## OUT PUT WAVEFORM AND DISCUSSION 

<img width="691" height="714" alt="image" src="https://github.com/user-attachments/assets/24c57863-5a0a-4561-818e-e2fb8f3793a0" />


---
## RESULT

<img width="1233" height="705" alt="image" src="https://github.com/user-attachments/assets/3fd049b9-5534-4f97-9ebf-ee153a6721f7" />

<img width="1036" height="543" alt="image" src="https://github.com/user-attachments/assets/d5b0d26d-b8b7-4ba6-abac-2b7855ce3a0f" />

---
