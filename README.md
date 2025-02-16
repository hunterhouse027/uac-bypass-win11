# 🔥 FUD UAC Bypass – DLL Side-Loading Exploit  

## 🚀 Overview  
This project demonstrates a **Fully Undetectable (FUD) UAC Bypass** technique leveraging **DLL Side-Loading**. It works on **Windows 10 & 11**, allowing privilege escalation without triggering UAC prompts.  

## 🎯 Features  
- **Stealthy Execution** – Bypasses UAC without user interaction.  
- **Fully Undetectable (FUD)** – Evades modern security solutions.  
- **Cross-Compatible** – Works on **Windows 10 & 11**.  
- **Multi-Language Development** – Written in **C++ & Python**.  
- **Automated Execution** – Seamless execution for privilege escalation.  

## 🛠️ Technical Approach  
This bypass relies on **DLL Side-Loading**, where a legitimate signed executable loads a malicious DLL instead of the intended one. Steps:  
1. Identify a trusted **Windows-native executable** vulnerable to side-loading.  
2. Craft a **malicious DLL** that mimics the expected DLL.  
3. Deploy both the **legitimate executable** and the **malicious DLL** in the same directory.  
4. Upon execution, the executable loads the attacker-controlled DLL, executing code with elevated privileges.  

## 📌 Requirements  
- Windows 10 / 11 (UAC enabled)  
- Administrative privileges **not required**  
- C++ Compiler (MSVC, MinGW)  
- Python 3.x (for automation)  

## 🔧 Build & Usage  
### 🔹 **Compile the C++ DLL**  
https://github.com/user-attachments/assets/c5bc8991-ae8f-475e-9b95-aad7f842091e

