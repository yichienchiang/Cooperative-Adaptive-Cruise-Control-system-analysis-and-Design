# Cooperative Adaptive Cruise Control system analysis and Design

THis project is for designing and simulating a whole Cooperative Adaptive Cruise Control system by using AWR sofeware to practice how to design a RF system. The project need to build the Transmitter and Receiver Block Diagram first and calculate TX and RX parameter to build the RF system. Therefore, selecting the electronic component and using the real value into the system design. Finally, simulating TX and RX gain, node power and noise figure.

#### Transmitter and Receiver Block Diagram- Radar
![Transmitter and Receiver Block Diagram- Radar](https://github.com/yichienchiang/Cooperative-Adaptive-Cruise-Control-system-analysis-and-Design/blob/3d7d270258e9bdbc7cb04cc29ff84a9139c3e5b0/1.PNG)

#### Radar Transmitter
![Radar Transmitter](https://github.com/yichienchiang/Cooperative-Adaptive-Cruise-Control-system-analysis-and-Design/blob/4768d76485ed45d6c285e9936f0d2683906e46fb/2.PNG)

## Radar TX Calculation
|    parameter  | Value          | 
| ------------- | -------------  | 
|     Pin          |     31.62mW           |
|     Pout          |     636.76mW           |
|      Pdc         |      12375mW          |
|       PAE(%)        |      4.9%          |
|        Gt       |       20dBi         |
|       EIRP        |     48.04dBm           |
|     MDS          |     4.1*10-9 mW         | 
fo                  77GHz        


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




#### Radar Transmitter
![]()

#### Radar Transmitter
![]()


#### Radar Transmitter
![]()


#### Radar Transmitter
![]()


#### Radar Transmitter
![]()


#### Radar Transmitter
![]()


#### Radar Transmitter
![]()


#### Radar Transmitter
![]()
