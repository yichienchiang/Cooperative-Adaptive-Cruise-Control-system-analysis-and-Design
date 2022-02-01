# Cooperative Adaptive Cruise Control system analysis and Design

THis project is for designing and simulating a whole Cooperative Adaptive Cruise Control system by using AWR sofeware to practice how to design a RF system. The project need to build the Transmitter and Receiver Block Diagram first and calculate TX and RX parameter to build the RF system. Therefore, selecting the electronic component and using the real value into the system design. Finally, simulating TX and RX gain, node power and noise figure.

#### Transmitter and Receiver Block Diagram- Radar
![Transmitter and Receiver Block Diagram- Radar](https://github.com/yichienchiang/Cooperative-Adaptive-Cruise-Control-system-analysis-and-Design/blob/3d7d270258e9bdbc7cb04cc29ff84a9139c3e5b0/1.PNG)

#### Radar Transmitter
![Radar Transmitter](https://github.com/yichienchiang/Cooperative-Adaptive-Cruise-Control-system-analysis-and-Design/blob/4768d76485ed45d6c285e9936f0d2683906e46fb/2.PNG)

Pin = 15dBm = 31.62mW

Pout = 28.04dBm = 636.76mW

Pdc = 1500mw + 6750mw + 4125mw = 12375mW

PAE(%) = 4.9%

Gt = 20dBi

EIRP = Pt + Gt = 28.04dBm + 20dBi = 48.04dBm

MDS = N0 = KTB = -113.86dBm = 4.1*10-9 mW

fo = 77GHz

𝜎 = 1m2

𝜆 = 0.0392m

R_𝑚𝑎𝑥 =〖[ (Pt 𝐺2 𝜆 𝜎)/(Pmin (4𝜋)3 )  ]" " 〗^(1/4) = 76.8m

FSPL = 〖(4πR_𝑚𝑎𝑥)〗^2/(𝜆^2  ) = 107.87dB

#### Radar TX Gain and Node Power Yield Simulation
![Radar TX Gain and Node Power Yield Simulation](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/a26db1a7437296c16df7e0c22db43ca4d42a5dc4/3.PNG)

#### Radar Receiver
![Radar Receiver](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/06c251d78e4d27f84565faa13ff92453888c0cd5/12.PNG)


#### Radar RX Yield Analysis: Gain
![Radar RX Yield Analysis: Gain](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/30758d53515bade6c09e8ef6931d68ed92aa05d3/g.PNG)


#### Radar RX Yield Analysis: Noise Figure
![Radar RX Yield Analysis: Noise Figure](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/30758d53515bade6c09e8ef6931d68ed92aa05d3/NF.PNG)


#### Radar RX Yield Analysis: IP3
![Radar RX Yield Analysis: IP3](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/30758d53515bade6c09e8ef6931d68ed92aa05d3/IP3.PNG)


## Transmitter and Receiver Block Diagram- 5G
![Transmitter and Receiver Block Diagram- 5G](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/19ebd157307b6f9b3df02edad725d6befbffee9e/block.PNG)


#### 5G Communication Transmitter 
![5G Communication Transmitter](https://github.com/yichienchiang/RF-Low-Noise-Amplifier/blob/0cf1284d63c46709f72b42ab8e8b700e1addb323/3333.PNG)


#### Radar Transmitter
![]()
