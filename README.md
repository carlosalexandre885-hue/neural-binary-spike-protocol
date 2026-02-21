# Bidirectional BCI Efficiency: RBS Protocol (16-bit) 🧠⚡

[span_1](start_span)[span_2](start_span)This repository contains a **Closed-Loop** neural network simulation demonstrating the efficiency of the **Relative Binary Spikes (RBS)** protocol for high-density Brain-Computer Interfaces (BCIs)[span_1](end_span)[span_2](end_span).

## 🚀 Overview
[span_3](start_span)The scalability of current BCIs is limited by thermal and bandwidth constraints[span_3](end_span). [span_4](start_span)This project simulates the interaction between two neural populations using the **Leaky Integrate-and-Fire (LIF)** model to compare data transmission methods[span_4](end_span):
1. **[span_5](start_span)[span_6](start_span)Traditional:** Continuous bitstream transmission[span_5](end_span)[span_6](end_span).
2. **[span_7](start_span)Event-Based (RBS):** Asynchronous transmission of 16-bit packets triggered only upon a spike[span_7](end_span).

## 📊 Key Results
[span_8](start_span)By leveraging neural temporal sparsity, the RBS protocol achieved significant data savings[span_8](end_span):
* **[span_9](start_span)Traditional Bitstream:** 90,000 bits[span_9](end_span)
* **[span_10](start_span)RBS Protocol:** 23,040 bits[span_10](end_span)
* **[span_11](start_span)[span_12](start_span)Efficiency Gain:** **74.4% bandwidth reduction**[span_11](end_span)[span_12](end_span)
* **[span_13](start_span)Biological Realism:** Average firing rate of 16 Hz[span_13](end_span)

## 🛠️ Technical Details
* **[span_14](start_span)Neural Model:** 180 LIF neurons (100 Motor / 80 Sensory)[span_14](end_span).
* **[span_15](start_span)Packet Structure:** Each event transmits 16 bits containing the Neuron ID and a relative Timestamp[span_15](end_span).
* **[span_16](start_span)[span_17](start_span)Thermal Impact:** This reduction is vital for clinical implants like the **Neuralink N1** to prevent thermal neurotoxicity[span_16](end_span)[span_17](end_span).

## 📄 Documentation
The full technical paper is available in this repository: [V3 project spikes.pdf](V3%20project%20spikes.pdf).

---
*Developed for the validation of high-bandwidth communication protocols in Neuroengineering.*
