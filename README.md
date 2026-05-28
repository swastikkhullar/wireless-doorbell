# wireless-doorbell
Wireless doorbell system built using RXB6 RF receiver module, HT12E encoder, and HT12D decoder ICs. The transmitter sends a wireless signal to the receiver, which activates a relay to ring an existing household doorbell. Designed as a practical solution during house fabrication work when the original bell became inaccessible from outside.
# Wireless RF Doorbell using RXB6 + HT12E/HT12D

A simple long-range wireless doorbell made using RF transmitter/receiver modules and Holtek encoder-decoder ICs.  
This project was built as a real-life practical solution when ongoing house fabrication work blocked access to the original doorbell.  
Instead of adding wires to the existing bell switch, the existing AC doorbell was reused and controlled wirelessly through a relay. 

## Features
- Wireless doorbell using RF communication  
- Uses dedicated hardware encoder/decoder ICs  
- Reuses existing household bell  
- Relay isolation for safe switching  
- Simple and low-cost design  
- Good range with proper antenna  

## Components Used
### Transmitter Side
- HT12E Encoder IC
- 433 MHz RF Transmitter Module
- Push Button
- 1MΩ resistor (HT12E oscillator)
- 9v battery
- decoupling capacitors(100 nF, 10 µF capacitor)
### Receiver Side
- RXB6 433 MHz RF Receiver Module
- HT12D Decoder IC
- Relay Module 
- 51kΩ resistor (HT12D oscillator)
- Existing Doorbell
- Power Supply (Old Phone Charger)
- LM7805
- 0.22uF, 0.1uF capacitors
- decoupling capacitors(100 nF, 10 µF capacitor)
## Possible Improvements
- Making it compact by improving antennas
- Add customized songs using sd card 
- Use microcontroller for rolling codes/security
## Challenges Faced

- Purchased the super regenrative RF modules which required tuning , and were impossible to pair
- Added some decoupling capacitors to rf transmitter reciver modules as well as on HT12D/E.
- Proper antenna length was important for reliable operation
- Then purchased RXB6 , superheterodyne reciever.
## Circuit Diagram
[ Circuit Diagram PDF](./CircuitDiagram.pdf)
