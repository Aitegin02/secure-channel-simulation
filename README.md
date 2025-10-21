# Secure channel simulation
A Python-based project demonstrating the design and implementation of a **secure communication system** with a focus on encryption, encoding, and statistical verification of secrecy.

## Overview
This project implements a simplified cryptographic pipeline that simulates message transmission over a communication channel while modeling a potential eavesdropper. It combines matrix-based encryption, non-linear substitution layers, and information-theoretic evaluation of secrecy.

## Features
- **Custom Encryption System:** Combines matrix transformations and non-linear S-boxes to securely encode and decode messages.  
- **Channel Simulation:** Models sender–receiver communication with random key generation and interception by an eavesdropper.  
- **Statistical Analysis:** Performs mutual information and entropy-based evaluation to verify no correlation between plaintext and intercepted data.  
- **Data Visualization:** Uses Matplotlib to visualize message distributions and information leakage metrics.


## Results
Empirical analysis confirmed **no data leakage** between transmitted and intercepted data across 10,000 simulated transmissions, validating the model’s theoretical secrecy.
