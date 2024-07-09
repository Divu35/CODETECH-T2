NAME:DEEPANKER ACHARYA COMPANY:CODTECH IT SOLUTIONS DOMAIN:VLSI CODTECH IT SOLUTIONS ID:CT6WDS282 DURATION:JUNE TO JULY(6 WEEKS) MENTOR:SHRAVANI GOUNI

OVERVIEW:

PROJECT:DESIGNING A UART (UNIVERSAL ASYNCHRONOUS RECEIVER/TRANSMITTER) USING VERILOG.

KEY ACTIVITIES: UART Transmitter (uart_tx):This module takes in data (tx_data) and transmits it serially over the tx line.The tx_start signal initiates the transmission.The transmitter follows a state machine with states for IDLE, START, DATA, and STOP.It sends a start bit, followed by 8 data bits, and then a stop bit.

UART Receiver (uart_rx):This module receives serial data on the rx line and reconstructs the original byte (rx_data).It detects the start bit, reads 8 data bits, and then checks for the stop bit.When data reception is complete, it asserts rx_done.

Testbench (tb_uart):The testbench instantiates both the transmitter and receiver modules.It generates a clock signal and a reset signal.It sends a byte of data (0x55) from the transmitter to the receiver.It monitors the signals to verify the correct operation of the UART modules.


![image](https://github.com/Divu35/CODETECH-T2/assets/175091673/0de6db51-2170-4952-9ee1-a79362d4959a)
