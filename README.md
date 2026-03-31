# MATLAB BER Performance Analyzer

This project implements an **object-oriented BER (Bit Error Rate) analyzer in MATLAB** for digital communication systems.  
It supports multiple modulation schemes and channel models with **BER vs SNR performance visualization**.

---

##  Features
- BPSK, QPSK, and M-QAM support
- AWGN, Rayleigh, and Rician channel models
- BER vs SNR performance plots
- Theoretical vs simulated BER comparison
- Modulation order comparison
- Required SNR estimation for target BER
- OOP-based reusable MATLAB framework

---

##  Project Structure
```text
matlab-ber-performance-analyzer/
│
├── BERAnalyzer.m
├── testBERAnalyzer.m
├── README.md
├── command_line_output.txt
│
├── results/
│   ├── ber_vs_modulation_order.png
│   ├── required_snr_analysis.png
│   └── test_result.png
```

---

##  How to Run
Run the test script in MATLAB:

```matlab
run('testBERAnalyzer.m')
```

---

##  Output
The project generates:
- BER vs SNR plots
- Modulation order comparison
- Required SNR analysis
- Simulation result validation

---

##  Applications
- Digital communication systems
- Wireless receiver analysis
- OFDM performance study
- 5G physical layer simulation
- BER validation and testing

---

