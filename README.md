# 🤖 Desk Buddy

> A low-cost, Wi-Fi-enabled smart desk companion designed to display useful information and gradually evolve into an AI-powered voice assistant.

![Project Status](https://img.shields.io/badge/Status-Planning-yellow)
![Budget](https://img.shields.io/badge/Budget-Under%20₹2000-green)
![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Language](https://img.shields.io/badge/Language-C%2B%2B-orange)

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Project Vision](#-project-vision)
- [Core Features](#-core-features)
- [Development Phases](#-development-phases)
- [System Architecture](#-system-architecture)
- [How It Works](#-how-it-works)
- [Hardware Overview](#-hardware-overview)
- [Software Stack](#-software-stack)
- [Project Structure](#-project-structure)
- [Internet Dependency](#-internet-dependency)
- [Budget Goal](#-budget-goal)
- [Future Improvements](#-future-improvements)
- [Project Status](#-project-status)

---

# 🤖 About the Project

**Desk Buddy** is a compact smart desk companion built around an ESP32-based microcontroller.

The project starts as a simple smart display capable of showing:

- ⏰ Current time
- 📅 Current date
- 🌤️ Current weather
- 📍 Weather information for a predefined location

The project will gradually evolve into a voice-controlled assistant capable of:

- 🎤 Listening to voice commands
- 📝 Converting speech into text
- 🧠 Understanding user requests
- 🔊 Replying through a speaker
- 🤖 Answering general questions using an AI service
- 🖥️ Displaying responses on a screen

The main goal is to build the project **step by step** while keeping the total hardware cost close to **₹2000**.

---

# 🎯 Project Vision

The long-term goal is to create a small device that can permanently sit on a desk and work independently.

Once the device is programmed and connected to power and Wi-Fi, it should work without requiring a computer to remain turned on.

```mermaid
flowchart TD
    A[Power On] --> B[ESP32 Starts]
    B --> C[Connect to Wi-Fi]
    C --> D[Initialize Services]
    D --> E[Desk Buddy Ready]

    E --> F[Idle Mode]
    F --> G[Show Time]
    F --> H[Show Date]
    F --> I[Show Weather]

    E --> J[Voice Interaction]
    J --> K[Process Request]
    K --> L[Generate Response]

    L --> M[Display Response]
    L --> N[Speak Response]
```
