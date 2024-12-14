Project Overview
This project implements a TCP-like protocol over UDP to achieve reliable data transfer in lossy network environments. The protocol features congestion control, flow control, error handling, and optimized data transfer techniques, ensuring efficient and robust communication.

Key Features
TCP-like Reliability: Simulates TCP functionality on top of UDP, including error detection and recovery mechanisms.
AIMD Congestion Control: Implements an Additive Increase Multiplicative Decrease algorithm for efficient congestion management.
Dynamic Timeout Adjustment: Adapts retransmission timeouts dynamically based on round-trip time (RTT) observations.
Parallel Data Exchange: Enables simultaneous data transfer streams for improved throughput.
Token-Based Request Control: Handles communication coordination in lossy networks using a token mechanism.
Error Handling: Detects and retransmits lost or corrupted packets to ensure data integrity.

Technical Details
Programming Language: Python
Libraries/Modules Used:
socket for network communication
time for RTT and timeout calculation
Any additional libraries/modules if applicable
Protocol Design: Combines UDP's speed with custom mechanisms for reliability, simulating TCP behavior.

