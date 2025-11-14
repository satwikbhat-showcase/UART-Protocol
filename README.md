# UART-Protocol
A dedicated repo for design and verification of Universal Asynchronous Receiver Transmitter (UART) Communication Protocol

## UART - Universal Asynchronous Receiver Transmitter
<img width="477" height="310" alt="image" src="https://github.com/user-attachments/assets/3b7d02e8-2576-4b44-9ee8-4f1f181bf64a" />

- In UART Clock is not given for synchronisation.
- Its a two wire communication protocol.
- Suitable for low speeds.

- UART Configuration parameters:
    - Baud rate: for transmission speed (same for both devices).
    - Data length: Fixed.
    - Start and stop bits.
    - NRZ encoding for data communication.
    - Parity bit (optional): to verify if data is received correctly.

<img width="394" height="97" alt="image" src="https://github.com/user-attachments/assets/9d2f1491-61d1-4cde-8f7d-3e65258b2825" />

- Advantages: less physical interfacing, configurable (speed, data size etc), full duplex config, error identification.
- Disadvantages: low speeds, redundancy (start/stop), Asynchronous.

  ## FSM Architecture:
  
![WhatsApp Image 2025-11-14 at 22 17 00_642c5a2a](https://github.com/user-attachments/assets/33a1853a-fd68-4a1e-9fa1-1f36e94e1fc6)
FSM Based Flowchart for Transmitter and Receiver respectively

## Block Diagram
<img width="581" height="404" alt="image" src="https://github.com/user-attachments/assets/6cef6f09-3cca-4dd1-9dc8-ae9cc2c7001d" />

## Testbench Architecture
<img width="962" height="602" alt="image" src="https://github.com/user-attachments/assets/82360f2b-f432-4aa5-a096-d30fbb51a845" />

## EDA Playground implementation:
- <a href="https://edaplayground.com/x/vc4F"UART Protocol - Design & Verification </a>
## References:
- <a href="https://www.udemy.com/share/106k2a3@Jpho-VOf8wTPMeQi-Apt53UxAA9B7tMgNLXkbx1mdukUFrunTmb_XEcQ5SiTqofGcQ==/"> [Course] Verification Series Part 2: Hands-On SystemVerilog Projects </a>
- <a href="https://youtu.be/beJZ5J-Ged0?si=HuvtbFAjhy_PGDzU"> [YOUTUBE] UART Protocol by Engineering Funda </a>
- <a href="https://youtu.be/JuvWbRhhpdI?si=0mCUrSexYhoI4Syf"> [YOUTUBE] Basics of UART Communication | UART Frame Structure | RS 232 Basics by Foolish Engineer </a>
- [BOOK] Serial Communication Protocols and Standards by  Dawoud Shenouda Dawoud and Peter Dawoud

