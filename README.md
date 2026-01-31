# Amplitude-Modulation Theoretical and Hardware-Technical Systems
<p align="justify">
This Project Experimental was investigates the theoretical principles and practical implementation of Amplitude Modulation by generating, observing, and analyzing AM signals using communication system blocks and signal measurement tools.
</p>

## Objectives
- To study and implement Amplitude Modulation (AM) by generating a modulated signal, observing its waveform characteristics, and analyzing the relationship between the message signal and the carrier signal using a communication system setup.

## Materials and Components Used
- Emona Telecoms-Trainer 101 (ETT-101)
- Dual-Channel Oscilloscope 
- Power Supply
- Patch Cords / Connecting Wires
- Laptop

## Table of Contents
- [Part 1 : Introduction to Oscilloscope](https://github.com/Justine2323/Communication-2-Modulation-and-Coding-Techniques-Laboratory/edit/main/Laboratory-Respository-1/README.md#part-1--introduction-to-oscilloscope)
- [Part 2 : Introduction to Emona Trainer 101 (ETT-101)](https://github.com/Justine2323/Communication-2-Modulation-and-Coding-Techniques-Laboratory/blob/main/Laboratory-Respository-1/README.md#part-2--introduction-to-emona-trainer-101-ett-101)
- [Part 3 : Signal Manipulation using Adder Module](https://github.com/Justine2323/Communication-2-Modulation-and-Coding-Techniques-Laboratory/blob/main/Laboratory-Respository-1/README.md#part-3--signal-manipulation-using-adder-module)
- [Part 4 : Generation and Analysis of AM Signals Using Double Sideband Full Carrier](https://github.com/Justine2323/Communication-2-Modulation-and-Coding-Techniques-Laboratory/tree/main/Laboratory-Respository-1#part-4--generation-and-analysis-of-am-signals-using-double-sideband-full-carrier)

## Part 1 : Introduction to Oscilloscope
<p align="justify">
As an electronics engineering (ECE) student, the oscilloscope is one of the most essential instruments in this field, especially for observing and analyzing electrical signals. It allows the visualization of voltage variations with respect to time, making it possible to study signal amplitude, frequency, waveform shape, and timing characteristics. In communication system experiments, the oscilloscope plays a crucial role in verifying signal behavior, troubleshooting circuit connections, and confirming proper system operation.
  </p>
  
### 1.0 Horizontal & Vertical Details
#### 1.0.0. Horizontal (Time Base)
- Controls the **time scale** of the waveform on the screen
- Shows how the signal **changes over time**
- Used to measure **period** and **frequency**
- Adjusted using the **Time/Div** knob

#### 1.0.1. Vertical (Amplitude)
- Controls the **voltage scale** of the waveform
- Shows the **signal amplitude** (height of the waveform)
- Used to measure **peak-to-peak voltage (Vpp)**
- Adjusted using the **Volts/Div** knob


### 1.1 Oscilloscope Setup Procedures
#### 1.1.0. General Controls
<details>
  <summary> </summary>
  
- Set the Intensity control to about three-quarters of its travel.
- Set the Mode control to the CH1(or CH4) position.
  
</details>

#### 1.1.1. Vertical Controls
<details>
  <summary> </summary>
  
- Set the Input Coupling control for both channels to the AC position.
- Set the Vertical Attenuation control for both channels to the 1V/div position.
- Set the Vertical Attenuation Calibration control for both channels to the detent (locked) position.
- Set the Vertical Position control for both channels to about the middle of their travel.

</details>

#### 1.1.2. Horizontal Controls
<details>
  <summary> </summary>

- Set the Horizontal Timebase control to the 0.5ms/div position.
- Set the Horizontal Timebase calibration control to the detent (locked) position.
- Set the Horizontal Position control to about the middle of its travel.
  
</details>

#### 1.1.3. Triggering controls
<details>
  <summary> </summary>

- Set the Sweep Mode control to the AUTO position.
- Set the Trigger Level control to the detent (locked) position. If it doesn't have a detent position, set it to about the middle of its travel.
- Set the Trigger Source control to the CH1(or INT) position.
- Set the Trigger Source Coupling control to the AC position.
- Set the Slope(or Sync) control to the "+" position.
  
</details>

### 1.2 Documentation/Output
<details>
<summary> View Part 1 Results</summary>

![Part1_resultfig4 (1)](https://github.com/user-attachments/assets/860914ff-9fcf-4d0c-a596-e3b7087575f5)
<p align="center">
  <em>Figure 1.2.0: Shows the verified 1 Vp-p square wave.</em>
</p>

![Part1_results](https://github.com/user-attachments/assets/57e956dc-9c3d-4ae7-bfee-9499c042557c)
<p align="center">
  <em>Figure 1.2.1: Shows the results of square wave in 1kHz Frequency in 1ms Period.</em>
</p>

![Part1_resultfig6](https://github.com/user-attachments/assets/2f74e08c-b8e0-4f09-acdb-487ac01f896f)
<p align="center">
  <em>Figure 1.2.2: Shows the square wave in 1kHz Frequency in 1ms period are zoomed in.</em>
</p>

</details>

## Part 2 : Introduction to Emona Trainer 101 (ETT-101)
<p align="justify">
The Emona Telecoms-Trainer 101 (ETT-101) is an educational communication system platform designed to demonstrate the practical implementation of analog and digital communication concepts. It allows students to build, observe, and analyze real communication systems using modular blocks such as signal sources, modulators, filters, and demodulators.
</p>

### 2.0 Block Diagram
<details>
<summary> View Part 2 Setups</summary>

![Part2_2 1setupa](https://github.com/user-attachments/assets/c66ac1aa-8fc7-42bd-8d5a-0ff228330367)
<p align="center">
  <em>Figure 2.0.0: 2kHz sinewave setup.</em>
</p>

![Part2_2 1diagram](https://github.com/user-attachments/assets/eb801087-258f-4196-b5a9-7fa7abe2f3f9)
<p align="center">
  <em>Figure 2.0.1: 2kHz sinewave block diagram.</em>
</p>

![Part2_2 1setupb](https://github.com/user-attachments/assets/d1a161a3-fb7d-497a-8582-ddf2c0213263)
<p align="center">
  <em>Figure 2.0.2: 100kHz sine & cosine wave setup.</em>
</p>

![Part2_2 1setupspeechmodule](https://github.com/user-attachments/assets/17c45637-ea0f-40b5-a313-bff8aa364813)
<p align="center">
  <em>Figure 2.0.3: speech module setup.</em>
</p>

![Part2_2 1setupmodulebuffer](https://github.com/user-attachments/assets/4ad25815-9e9f-4700-aae4-e8563cd0897d)
<p align="center">
  <em>Figure 2.0.4: Buffer module setup.</em>
</p>

![Part2_2 1buffermodulediagram](https://github.com/user-attachments/assets/820d89b6-4d85-455c-9c75-71077d59b0c2)
<p align="center">
  <em>Figure 2.0.5: Buffer module block diagram.</em>
</p>

![Part2_2 2setupaddermodule](https://github.com/user-attachments/assets/59a4d590-4fa4-4ec7-8e34-27ad1d60085e)
<p align="center">
  <em>Figure 2.0.6: Adder module setup.</em>
</p>

![Part2_2 2adderdiagram](https://github.com/user-attachments/assets/db6edcb8-35fa-4be0-bec8-992b9221c0be)
<p align="center">
  <em>Figure 2.0.7: Adder module block diagram.</em>
</p>

![Part2_2 2setupPhaseshiftermodule](https://github.com/user-attachments/assets/d8691616-9516-4922-8a05-cb0e1ccb8712)
<p align="center">
  <em>Figure 2.0.8: Phase Shifter module setup.</em>
</p>

![Part2_2 2Phaseshifterdiagram](https://github.com/user-attachments/assets/ad92efb9-43e6-4440-898b-fa50242cb241)
<p align="center">
  <em>Figure 2.0.9: Phase Shifter module block diagram.</em>
</p>

</details>

### 2.1 Documentation/Output
<details>
<summary> View Part 2 Results</summary>

![Part2_resultfig3sincos](https://github.com/user-attachments/assets/b8893fb2-99a5-4d02-bea5-9c72fa624b45)
<p align="center">
  <em>Figure 2.1.0: Output results for Master Signal Module at 2kHz in sinewave.</em>
</p>

![Part2_resultfig1sincos](https://github.com/user-attachments/assets/7a79141c-22b0-4ecc-a731-48e5ae5966d6)
<p align="center">
  <em>Figure 2.1.1: Output results for Master Signal Module at 100kHz in sine and cosine wave.</em>
</p>

![Part2_resultfig2sincos](https://github.com/user-attachments/assets/f24a7b73-d07d-4d77-a16e-3cfa91280785)
<p align="center">
  <em>Figure 2.1.2: Output results for Master Signal Module at 100kHz when V/div was adjust at 5us.</em>
</p>

![Part2_resultfig1mic](https://github.com/user-attachments/assets/f098a307-6a35-4e34-b411-e1aa6ce14469)
<p align="center">
  <em>Figure 2.1.3: Output results for Speech Module.</em>
</p>

![Part2_resultfig2buffer](https://github.com/user-attachments/assets/833d3945-a346-4647-8db3-da04e5145a35)
<p align="center">
  <em>Figure 2.1.4: Output results for Buffer Module.</em>
</p>

![Part2_fig2addert2](https://github.com/user-attachments/assets/a1259de5-7623-4417-bd5d-85ad3783724d)
<p align="center">
  <em>Figure 2.1.5: Output results for Adder Module.</em>
</p>

![Part2_fig1phaseshift](https://github.com/user-attachments/assets/de730e47-3bfc-42dd-b763-58559c7c3923)
<p align="center">
  <em>Figure 2.1.6: Output results for Phase Shifter Module.</em>
</p>

</details>

## Part 3 : Signal Manipulation using Adder Module
<p align="justify">
The Adder Module is used to combine two or more input signals into a single output signal by performing signal addition. In this part of the experiment, the module demonstrates how multiple signals interact when added together, allowing observation of changes in amplitude and waveform shape. This process is essential in communication systems where signal mixing, modulation, and summation are required.
</p>

### 3.0 Adder Module Equation

The Adder Module was used to combine two input signals into a single output signal.  
The output of the adder is given by:

$$
V_{out}(t) = G \cdot V_a(t) + g \cdot V_b(t)
$$

where:
- $V_a(t)$ and $V_b(t)$ are the input signals  
- $G$ and $g$ are the respective gain factors applied to each input  

<p align="justify">
This equation shows that the output signal is a weighted sum of the input signals, depending on the selected gain settings of the Adder Module.
</p>

### 3.1 Block Diagram
<details>
<summary> View Part 3 Setups</summary>

![Part3_3 1setupaddereqn](https://github.com/user-attachments/assets/ed218ccc-6a89-4449-bd82-112e4b236517)
<p align="center">
  <em>Figure 3.1.0: Wiring Connection for Adder Module setup</em>
</p>

![Part3_3 1addereqndiagram](https://github.com/user-attachments/assets/13fa6524-9ee8-4356-b286-2f362c702c40)
<p align="center">
  <em>Figure 3.1.1: Adder Module block diagram.</em>
</p>

![Part3_3 2setupadderwithphaseshiftereqn](https://github.com/user-attachments/assets/eeb2cbf0-49d6-4e4e-8574-b610e4e742d4)
<p align="center">
  <em>Figure 3.1.2: Wiring Connection from Adder Module with Phase Shift setup.</em>
</p>

![Part3_3 2adderwithphaseshiftereqndiagram](https://github.com/user-attachments/assets/7b75ec72-0fae-4b6c-ae9f-1f9916a9f450)
<p align="center">
  <em>Figure 3.1.2: The Adder Module with Phase Shift block diagram.</em>
</p>


</details>

### 3.2 Results
<details>
<summary> View Part 3 Results</summary>

![Part3_resultsfig1modeleq](https://github.com/user-attachments/assets/5e685713-6e69-43d1-bbfb-2972b00d3e76)
<p align="center">
  <em>Figure 3.2.0: Shows that the two of sinewaves are unstable.</em>
</p>


</details>


## Part 4 : Generation and Analysis of AM Signals Using Double Sideband Full Carrier
<p align="justify">
This part of the experiment focuses on the generation of amplitude modulated signals using the Double Sideband Full Carrier (DSBFC) technique. The message signal is combined with a high-frequency carrier to produce an AM waveform whose envelope follows the message signal. The generated AM signal is observed and analyzed in the time domain to verify proper modulation and to study its characteristics.
</p>

### 4.0 System Flows and Analysis XY Mode

- The oscilloscope is set to **XY mode** to display the relationship between two input signals.
- One channel represents the **message signal**, while the other represents the **carrier or modulated signal**.
- The resulting display forms a pattern that shows how the signals interact.
- Changes in the shape of the pattern indicate variations in **amplitude and phase**.
- XY mode is used to verify correct modulation and signal synchronization.
- The X-Axis is the message signal.
- THe Y-Axis is the AM signal output.


### 4.1 Block Diagram
<details>
<summary> View Part 4 Setups</summary>

![Part4_4 1generatingammessagediagram](https://github.com/user-attachments/assets/b561c046-c080-4101-8cb7-21ae852bb6a9)
<p align="center">
  <em>Figure 4.1.0: Generating AM Message setup.</em>
</p>

![Part4_4 1setupgeneratingammessage](https://github.com/user-attachments/assets/0edef375-4900-4f24-bb27-369d3141e18e)
<p align="center">
  <em>Figure 4.1.1: Generating AM Message block diagram.</em>
</p>

![Part4_4 2generatingdsbfcdiagram](https://github.com/user-attachments/assets/51cc709d-c00d-4d86-af45-2e360f222164)
<p align="center">
  <em>Figure 4.1.0: Generating Double Side-band Full Carrier signal Setup.</em>
</p>

![Part4_4 2setupgeneratingdsbfc](https://github.com/user-attachments/assets/34f42954-e609-4acb-b4f9-4bd994b678b8)
<p align="center">
  <em>Figure 4.1.0: Generating Double Side-band Full Carrier signal block diagram.</em>
</p>

</details>

### 4.2 Documentation
<details>
<summary> View Part 4 Results</summary>

![Part4_resultsfig1VDCinput](https://github.com/user-attachments/assets/e2e9a062-3df0-4c21-8935-82c1f34b63d2)
<p align="center">
  <em>Figure 4.2.0: shows that the modulating signal act as an Vdc source input.</em>
</p>

![Part4_resultfig2Mastersignalinput](https://github.com/user-attachments/assets/5328823e-6ddf-41cb-afe6-2bf370f45d3d)
<p align="center">
  <em>Figure 4.2.1: shows that the modulating signal act as an normal sinewave .</em>
</p>

![Part4_resultfig1AMwith0 32m](https://github.com/user-attachments/assets/74b161b8-a5f6-48d6-b21e-29403f5347c0)
<p align="center">
  <em>Figure 4.2.2: shows that the AM signal in modulation index = 0.32.</em>
</p>

![Part4_resultfig2AMwith0 7m](https://github.com/user-attachments/assets/5591180f-6459-435d-b64d-b26d837eaf3b)
<p align="center">
  <em>Figure 4.2.3: AM signal at 0.7 modulation index.</em>
</p>

![Part4_resultfig3AMwith1m](https://github.com/user-attachments/assets/f1e2aafd-2ff7-48a2-bc16-6868942931d7)
<p align="center">
  <em>Figure 4.2.4: shows that the AM signal is the perfect modulation.</em>
</p>

![Part4_resultfig4AMwith1 2m](https://github.com/user-attachments/assets/7bd3e4d9-79d3-47aa-bdd7-dcb8da86557e)
<p align="center">
  <em>Figure 4.2.5: shows that the AM signal is overmodulated.</em>
</p>

</details>

## Results & Data Interpretation

| Part | Parameter / Activity | Observed Result | Interpretation |
|-----|----------------------|-----------------|----------------|
| Part 1 | Oscilloscope Signal Display | Stable square and sine waveforms | Confirms correct oscilloscope setup and signal visualization |
| Part 1 | Time Base Adjustment | 1 ms period observed at 1 kHz | Horizontal scaling correctly represents signal frequency |
| Part 1 | Voltage Measurement | 1 Vp-p verified | Vertical scaling properly calibrated |
| Part 2 | Message Signal Generation | 2 kHz sinewave output | Valid baseband signal generation |
| Part 2 | Carrier Signal Generation | 100 kHz sine and cosine signals | Proper high-frequency carrier source |
| Part 2 | Buffer Module Output | Stable and undistorted waveform | Confirms signal isolation and stability |
| Part 3 | Adder Module Output | Combined input waveforms | Demonstrates correct signal summation |
| Part 3 | Phase Shift Effect | Shifted waveform observed | Phase control influences signal alignment |
| Part 4 | AM Signal Generation | Modulated waveform observed | Successful AM generation using DSB-FC |
| Part 4 | Modulation Index (m = 0.32) | Low envelope variation | Under-modulated AM signal |
| Part 4 | Modulation Index (m = 0.7) | Clear envelope shape | Proper modulation condition |
| Part 4 | Modulation Index (m = 1.0) | Maximum envelope without distortion | Ideal AM modulation |
| Part 4 | Modulation Index (m > 1.0) | Envelope distortion present | Over-modulation observed |
| Part 4 | XY Mode Display | Symmetrical pattern | Confirms correct signal relationship |

<p align="justify">
The results from Parts 1 to 4 demonstrate a systematic progression from basic signal observation to full AM signal generation. Initial oscilloscope calibration ensured accurate measurements, while successive system blocks enabled proper signal manipulation and modulation. The observed AM waveforms and modulation index variations closely matched theoretical expectations.
</p>

## Learnings/Summary
<p align="justify"> This laboratory experiment has provided an clear understanding of the theoretical concepts and practical implementation of Amplitude Modulation (AM) using communication system modules. Through hands-on use of the oscilloscope and the Emona Telecoms-Trainer 101 (ETT-101), the relationship between the message signal and the carrier signal was successfully observed and analyzed. The experiment demonstrated how individual system blocks such as the adder, phase shifter, and signal sources work together to generate an AM signal using the Double Sideband Full Carrier (DSBFC) technique. </p> <p align="justify"> This results showed that the envelope of the AM signal follows the message signal, confirming correct modulation behavior. By varying the modulation index, different modulation conditions were observed, including under-modulation, proper modulation, and over-modulation. The use of XY mode further helped visualize the relationship between signals and verify system synchronization. Overall, this experiment strengthened practical skills in signal measurement, system setup, and waveform interpretation, while reinforcing key concepts in analog communication systems. </p>


