# vco-circuit-modeling-deep-learning

# 🔄 VCO Circuit Modeling using Deep Learning

This project focuses on modeling analog **Voltage-Controlled Oscillators (VCOs)** using deep learning techniques. The objective is to predict VCO output waveforms using neural network architectures such as **GRU**, **Simple RNN**, and **hybrid Feedforward-RNN models**, trained on waveform data generated from SPICE simulations.

---

## 📊 Project Description

The VCO is a key building block in analog and mixed-signal circuits. Instead of traditional analytical modeling, this project explores how deep learning models can learn the dynamic voltage behavior of a VCO based on input voltage and RC parameters.

---

## 🧠 Models Used

- **Simple RNN** – For time-step-based learning of sequential data  
- **LSTM** – For handling long-term dependencies in waveform patterns  
- **GRU** – Efficient alternative to LSTM, performs best in this project  
- **Hybrid FNN-RNN** – Combines static input processing (RC values) with time-based waveform prediction

---

## 🛠️ Technologies & Tools

- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib & Seaborn  
- Google Colab  
- Data generated using SPICE simulation outputs (Waveform + Parameters)
