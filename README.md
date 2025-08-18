# 👋 Hi, I'm Tushar Mali

I'm an **🚀 Senior Embedded Engineer**. 
I specialize in bare-metal programming by directly working with microcontroller datasheets and reference manuals. With hands-on experience in low-level hardware interaction, I write efficient, resource-optimized code without relying on high-level libraries or auto-generated code. Passionate about building reliable embedded solutions from the ground up.

---

## 💻 Programming Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-green?style=for-the-badge)

- 🟢 **C**           
- 🔷 **C++**       
- ⚙️ **Embedded C**  
  
---

## 🔧 Microcontrollers I Work With
![MSP430](https://img.shields.io/badge/MSP430-TI-990000?style=for-the-badge&logo=TexasInstruments&logoColor=white)
![PIC](https://img.shields.io/badge/PIC-Microchip-red?style=for-the-badge&logo=microchip)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=STMicroelectronics&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![8051](https://img.shields.io/badge/8051-MCU-blue?style=for-the-badge)

- 🔴 **MSP430 Series** (Ultra-low-power TI MCU)
- 🟢 **PIC Series**: PIC18, PIC24, PIC32  
- 🔵 **STM32 Series** (ARM Cortex-M)  
- 🔸 **Arduino** (ATmega328, ESP32, etc.)  
- ⚙️ **8051 Microcontrollers**

---

## 🛠️ IDEs & Development Environments

![MPLAB X IDE](https://img.shields.io/badge/MPLAB%20X-IDE-red?style=for-the-badge&logo=microchip)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-blue?style=for-the-badge&logo=STMicroelectronics)
![KEIL](https://img.shields.io/badge/Keil-uVision-green?style=for-the-badge)
![Arduino IDE](https://img.shields.io/badge/Arduino-IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Code Composer Studio](https://img.shields.io/badge/Code%20Composer%20Studio-TI-990000?style=for-the-badge&logo=TexasInstruments&logoColor=white)

- 💡 **MPLAB X IDE**  (Microchip)
- ⚙️ **STM32CubeIDE** (ST Microelectronics) 
- 🧠 **KEIL uVision** (8051, ARM) 
- 🛠️ **Arduino IDE**  
- ✍️ **VS Code** (with PlatformIO, etc.)
- 🔧 **Code Composer Studio** (TI MSP430, C2000, etc.)

---

## 🧪 Simulation & Debugging Tools
![Proteus](https://img.shields.io/badge/Proteus-Simulation-purple?style=for-the-badge)
![Logic Analyzer](https://img.shields.io/badge/Logic%20Analyzer-Tool-yellow?style=for-the-badge)
![CAN Bus Analyzer](https://img.shields.io/badge/CAN%20Bus-Analyzer-blue?style=for-the-badge)
![Modbus Poll](https://img.shields.io/badge/Modbus-Poll-orange?style=for-the-badge)
![Modbus Slave](https://img.shields.io/badge/Modbus-Slave-orange?style=for-the-badge)

- 🔄 **Proteus Design Suite** (Circuit simulation & PCB design)  
- 🔍 **Logic Analyzer**  
- 🚌 **CAN Bus Analyzer**  
- ⚙️ **Modbus Poll & Modbus Slave** (for Modbus simulation & testing)

---

## 🔧 Platforms and tool I Work With

<p align="left"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="50" height="50" style="margin-right:20px;" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azuredevops/azuredevops-original.svg" alt="Azure DevOps" width="50" height="50" style="margin-right:20px;" /> </p>

- 🟣 **GitHub** (Source control, project collaboration, and GitHub Actions for automation)
- 🔵 **Azure DevOps** (Continuous Integration and Deployment with GitHub Actions and Azure Pipelines)
  
---

## 🔧 Projects I've Worked On

### 🚗 TiltGuard-MSP430
- **Description**: TiltGuard-MSP430 is a low-power tilt detection system using the MSP430G2553 microcontroller and the ADXL362 ultralow power accelerometer. This project detects tilt or orientation change and can be used in tamper detection, anti-theft alarms, or motion-based control systems. The MSP430G2553 communicates with the ADXL362 via SPI and uses GPIO interrupts to detect motion. Designed for minimal power consumption and suitable for battery-powered applications.
  
- **Tech**: MSP430, SPI Protocol, ADXL362 Accelerometer
  
- **Key Features**:  
 🔸 SPI communication with ADXL362
 🔸 Ultralow power operation
 🔸 Tilt detection with configurable threshold
 🔸 Easily customizable for different microcontrollers or platforms
 🔸 Code written using Code Composer Studio (CCS)


### 🚗 Ethernet Card
- **Description**: Developed a communication gateway that bridges a serial MODBUS-enabled embedded system with a remote GUI using Ethernet. The Ethernet card receives data from the embedded system via UART using the MODBUS RTU protocol, then repackages and transmits the collected data over the network to a GUI using MODBUS TCP/IP. This architecture enables legacy embedded systems with UART-only communication to interface with modern TCP/IP-based applications.
  
- **Tech**: PIC32, Ethernet Protocol using MODBUS TCP/IP, MODBUS RTU
  
- **Key Features**:  
 🔸 UART-to-TCP/IP conversion with MODBUS protocol support  
 🔸 MODBUS RTU data parsing and validation  
 🔸 MODBUS TCP/IP frame construction and transmission over Ethernet  
 🔸 Real-time data relay to GUI for monitoring and control  


### 🎛️ TLV320AIC3204 Audio Codec Interfacing with PIC24
- **Description**: Engineered an embedded audio processing system by interfacing the TLV320AIC3204 ultra-low power stereo audio codec with a PIC24F microcontroller. The system utilizes I2C for codec configuration and I2S for real-time audio data transmission, enabling high-quality stereo audio playback and recording. This setup is ideal for applications like voice command systems, audio streaming devices, and digital audio processing units.
  
- **Tech**: PIC24, TLV320AIC3204 audio codec, I2C (control interface) + I2S (audio interface)
  
- **Key Features**:  
 🔸 Codec configuration via I2C for sampling rate, volume, input/output routing, and power settings  
 🔸 Real-time stereo audio data transmission using I2S interface  
 🔸 Support for both ADC (audio input) and DAC (audio output) functionality  
 🔸 Efficient data buffering and interrupt-driven audio stream handling  

---

## 📜 Certifications

- [Leadership: Practical Leadership Skills](https://www.udemy.com/certificate/UC-04a2fd29-ec1c-4463-8c9b-2ab69faaeeeb/)
- [Microcontroller Embedded C Programming](https://www.udemy.com/certificate/UC-f07fb1c8-35b9-4719-8743-88872d371155/)
- [C Programming Callbacks](https://verify.skilljar.com/c/d25sqt4x79w6)
- [CAN and CAN FD Protocol and Physical Layer Basics](https://verify.skilljar.com/c/2oczr9aus9x6)
- [Advanced Embedded C Tips, Tricks, and Cautions](https://verify.skilljar.com/c/ycwdfwxreocj)
- [Debugging Techniques for Serial Communications (I2C/SPI/UART)](https://verify.skilljar.com/c/2ozwegopcvpq)
- [MPLAB® Harmony v3 Fundamentals](https://verify.skilljar.com/c/n4zq2x9ubr34)
  
---

## 📊 GitHub Stats

![Tushar's GitHub Stats](https://github-readme-stats.vercel.app/api?username=tusharmali017&show_icons=true&theme=radical)

---

## 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tushar-mali-692230139/)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tusharmali017)

---

