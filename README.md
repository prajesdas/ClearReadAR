# ClearReadAR: Augmented Reality–Based Dyslexia Reading Assistance System

## 📌 Project Overview

ClearReadAR is an **augmented reality–based assistive reading system** designed to improve accessibility, fluency, and comprehension for individuals with **dyslexia, low vision, and related reading challenges**. The system combines **real-time OCR, dyslexia-optimized text transformation, augmented reality overlay anchoring, and text-to-speech output** into a lightweight, wearable, and adaptive solution.

Unlike conventional tools that depend on source file modification or app-level integration, ClearReadAR works **seamlessly on any printed or digital text**, including books, signage, handwritten notes, and screens, without altering the original content.

---

## 🚀 Key Features

* **Real-Time OCR & AR Overlay**: Captures text via camera and reprojects reformatted content directly in the user’s field of view using AR waveguides.
* **Adaptive Dyslexia Formatting**: Customizable fonts, spacing, syllable highlighting, color coding, and contrast adjustments for improved readability.
* **Text-to-Speech (TTS) Integration**: Bone-conduction audio output ensures safe and discreet auditory assistance without blocking environmental sounds.
* **Multilingual Support**: Works across multiple languages and scripts with dyslexia-friendly formatting rules.
* **Offline Functionality**: Full OCR and formatting pipeline runs locally, ensuring privacy and usability in low-connectivity environments.
* **AI-Powered Personalization**: Learns user reading patterns and adapts formatting for maximum comfort and comprehension.
* **Hands-Free Control**: NLP-based voice commands enable seamless adjustments while reading.
* **Lightweight Wearable Design**: Ergonomic AR glasses (<120 g) for continuous, discreet use in classrooms, workplaces, or public settings.

---

## 🔧 System Components

| Category             | Component                            | Utilisation Description                  |
| -------------------- | ------------------------------------ | ---------------------------------------- |
| Imaging Subsystem    | 4K 8MP IMX219 Autofocus Camera       | Captures physical/digital text for OCR   |
| Tracking & Alignment | 9-Axis IMU (MPU9250)                 | Maintains AR overlay alignment           |
| Processing Unit      | ARM-based SoC / SBC with NPU         | Runs OCR, formatting, and AR rendering   |
| Display Subsystem    | AR Optical Waveguide (1280x720)      | Projects reformatted text in user’s view |
| Audio Output         | Bone-Conduction / Mini Speaker       | Provides synchronized TTS output         |
| Power Management     | Li-ion Battery + Power IC            | Portable power with extended runtime     |
| Connectivity         | Wi-Fi / Bluetooth LE (Telit WE310F5) | Pairs with smartphones/cloud OCR         |
| User Interface       | Touchpad / Microphone / Buttons      | Mode switching and voice commands        |
| Enclosure            | Lightweight AR Glasses Frame         | Ergonomic, portable design               |

---

## 📊 Results & Testing

* **32% faster reading speed** in controlled classroom tests.
* **40% fewer decoding errors** and **27% better comprehension**.
* **45% quicker interpretation** of public signage in field tests.
* Stable AR overlay alignment via **IMU + SLAM**.
* **Multilingual support validated** (English, Spanish, French).
* **Infrared-assisted imaging** for low-light readability with <5% OCR accuracy drop.

---

## ✅ Advantages Over Prior Solutions

1. Works on **any physical or digital text** without source file modification.
2. **Real-time AR overlay** aligned with original content.
3. **Adaptive formatting** tailored to each user.
4. **Wearable and hands-free**, unlike phone/tablet apps.
5. Supports **multiple languages and scripts**.
6. **Fully offline functionality**, no cloud dependency.
7. **Bone-conduction audio** for discreet TTS.
8. **Low-latency OCR** (<50 ms rendering).
9. Works in **varied lighting conditions** with IR support.
10. **AI-driven learning engine** improves personalization over time.

---

## 📐 System Flow (Conceptual)

1. **Capture Text** → Camera acquires live imagery
2. **Preprocessing** → Perspective correction & noise removal
3. **OCR Processing** → Converts to digital text
4. **Dyslexia Formatting** → Applies custom fonts, spacing, color coding
5. **AR Overlay** → Reformatted text aligned with original content
6. **Optional TTS** → Audio playback through bone conduction
7. **Adaptive AI** → Learns user preferences for continuous optimization

---

## 📷 Figures

## flowchart

<img width="788" height="1175" alt="image" src="https://github.com/user-attachments/assets/d2c58c03-58e6-4fab-95f9-0f6ca2dfd481" />

---

## **Figure 1**: Conceptual Design of AR-Based Smart Reading Aid

<img width="788" height="518" alt="image" src="https://github.com/user-attachments/assets/70ec6055-575d-475b-8221-4567a1170ac4" />


---
## **Figure 2**: Hardware Components Utilized in the Prototype

<img width="852" height="490" alt="image" src="https://github.com/user-attachments/assets/83206013-5de3-48b4-bccb-427849b7dded" />


---
## **Figure 3**: Final Prototype Design of Smart AR Glasses
<img width="667" height="273" alt="image" src="https://github.com/user-attachments/assets/ac56a4ac-6059-4c3c-a351-898786829f99" />


---


## 📝 Abstract

ClearReadAR is a **portable, AI-enhanced, AR-based reading assistance system** that captures text from any source, applies **dyslexia-optimized formatting**, and overlays it in real time within the reader’s field of view. With integrated **OCR, TTS, adaptive personalization, multilingual processing, and lightweight wearable design**, it delivers a **scalable, inclusive, and privacy-preserving solution** for educational, professional, and everyday reading environments.

---

## 👨‍🔬 Inventors

1. **Prajes Das**

---


