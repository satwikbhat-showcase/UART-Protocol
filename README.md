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
  

