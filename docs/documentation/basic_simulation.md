# Tinkercad Circuit Simulation


Today I learned how to build and simulate basic electronic circuits using Tinkercad Circuits. Tinkercad is an online simulation tool that allows us to design, test, and understand electrical circuits before assembling them physically.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1RGEqxi9l2uEQt17aYKPstkBswCZ3rUVS&sz=w400" alt="Profile Photo">



## Understanding the Components


Before creating a circuit, it is important to know the basic components used in Tinkercad Circuits:


LED (Light Emitting Diode): A light source that only allows current to flow in one direction. It has two legs: the positive terminal (Anode) and the negative terminal (Cathode).

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1ZhZWcXeNhiCkYREbEnD8H6baW3PAG-Lt
&sz=w400" alt="Profile Photo">

Resistor: Used to limit the amount of electrical current flowing through the circuit to prevent damaging components like the LED.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1MjvI3podyuZ4pGANlhhSzwuGO1ZNIYYK&sz=w400" alt="Profile Photo">


Power Source: Supplies electrical energy to the circuit (e.g., 3V Coin Cell Battery or 9V Battery).

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1oY-HtwX8x9ga9e6vftDirgrIvzrYBf1A&sz=w400" alt="Profile Photo">


## Step-by-Step Circuit Building Process
Step 1:
First, open Tinkercad Circuits and select the Basic Components panel on the right side. Drag and drop the required components onto the workspace canvas:

An LED

A Resistor

A Coin Cell 3V Battery (or a 9V Battery)

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1MjvI3podyuZ4pGANlhhSzwuGO1ZNIYYK&sz=w400" alt="Profile Photo">


Step 2:
Next, connect the components using wires by clicking on the terminals:

Connect the Positive (+) terminal of the battery to one end of the Resistor.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1W1e4ceuhareRgGOmSLy7uLoJYTFPspDW&sz=w400" alt="Profile Photo">

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1lGAzsrfJ56NFClyW9qJ_8BWA2bCpzBQp&sz=w400" alt="Profile Photo">

Connect the other end of the resistor to the Anode (+) leg of the LED.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=17hg0xiA6xnsQrLUorQAAbj_EYzUBjgfq&sz=w400" alt="Profile Photo">

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1lGAzsrfJ56NFClyW9qJ_8BWA2bCpzBQp&sz=w400" alt="Profile Photo">

Connect the Cathode (-) leg of the LED back to the Negative (-) terminal of the battery to complete the closed loop circuit.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=17hg0xiA6xnsQrLUorQAAbj_EYzUBjgfq&sz=w400" alt="Profile Photo">

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1yZz-8wuK3-CRSOgU1-7JQTIIobtbCdzu&sz=w400" alt="Profile Photo">

## What Happens Without a Resistor?

When connecting an LED directly to a power source like a 9V battery without a resistor in place :

Excessive Current Flow: Standard LEDs typically operate safely at a forward voltage of around 2.0V to 3.0V and a current of about 20mA (0.02 Amps). A 9V battery supplies far more voltage and current than a raw LED can handle on its own.

Component Burnout: When you click Start Simulation without a current-limiting resistor, an explosion/warning graphic immediately appears over the LED. In a real-world scenario, this sudden surge of high current causes the LED to instantly burn out, pop, or melt due to extreme heat generation.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1fAZxrXBt_yc-9zIk4BpJqDOMDhstlqxj&sz=w400" alt="Profile Photo">

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=12DHZTzwVtpQ2m9T7XRflDB2Mm9KPu18N&sz=w400" alt="Profile Photo">

### To fix this issue and protect our components,current-limiting resistor into the circuit is important.

Current Regulation: The resistor acts as a barrier that resists the flow of electrical current, lowering the current level to a safe operating value for the LED.

Voltage Drop: It absorbs the extra voltage provided by the 9V battery, ensuring the LED only receives the forward voltage it requires.

Component Longevity: By placing the resistor in series between the positive terminal of the 9V battery and the Anode of the LED, the circuit runs safely without overheating or destroying the LED.

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1p3yoHSbgaGqkUcjwyXZUuHJubMmuyK37&sz=w400" alt="Profile Photo">

<img class="profile-photo" src="https://drive.google.com/thumbnail?id=1RGEqxi9l2uEQt17aYKPstkBswCZ3rUVS&sz=w400" alt="Profile Photo">



