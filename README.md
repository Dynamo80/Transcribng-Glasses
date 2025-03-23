# Transcribing Glasses (Real-Time Speech-to-Text Display)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Software & Dependencies](#software--dependencies)
- [Working Principle](#working-principle)
- [Future Improvements](#future-improvements)

---

## Introduction
The **Transcribing Glasses** is an independent, attachable device that provides **real-time speech-to-text transcription** directly on a small **OLED display**. It connects to a smartphone via **Bluetooth** and receives transcribed text from the phone, allowing users to read spoken words as text in real time.

This project is designed for **accessibility, live captions, and communication assistance**, making it useful for people with hearing impairments, live translation, and noisy environments.

---

## Features
- **Real-time Speech-to-Text**: Displays transcriptions instantly on an **OLED screen**.  
- **Bluetooth Connectivity**: Wirelessly receives transcribed text from a smartphone.  
- **Independent & Attachable**: Can be mounted on **any glasses** without modifications.  
- **Compact & Battery-Powered**: Uses a **QT Py S3** microcontroller with an OLED display.  
- **Cross-Platform Support**: Works with **Flutter-based mobile apps** on **iOS & Android**.  

---

## Hardware Components
- **QT Py S3** (Microcontroller)  
- **OLED Display** (For real-time text output)  
- **Rechargeable Battery** (Portable power supply)  
- **Bluetooth Module** (Built-in on QT Py S3)  

---

## Software & Dependencies
- **Flutter** (Mobile App for speech-to-text conversion & Bluetooth communication)  
- **Arduino** (For programming the QT Py S3 microcontroller)  
- **Bluetooth Low Energy (BLE)** (For data transfer between phone and glasses)  

---

## Working Principle
1. **Speech Capture**  
   - The smartphone records audio through its **microphone**.  
2. **Speech-to-Text Conversion**  
   - The phone **transcribes** the speech into text.  
3. **Data Transmission**  
   - The text is **converted into bytes** and sent via **Bluetooth** to the transcribing glasses.  
4. **Text Display**  
   - The QT Py S3 **receives the data**, converts it into readable text, and displays it on the **OLED screen**.  

---
## Future Improvements
- **AI-based transcription for better accuracy**  
- **Multi-language support**  
- **Custom font & text size adjustments**  
- **Longer battery life optimization**  
- **Augmented Reality (AR) features for improved usability**  
---
