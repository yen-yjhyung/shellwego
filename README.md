# ShellWeGo - A Golang-Based CLI for Simplified Linux Commands  

[![License](https://img.shields.io/github/license/yen-yjhyung/ShellWeGo)](LICENSE)
[![Go Version](https://img.shields.io/badge/Go-1.20%2B-blue)](https://golang.org/)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)](#-contributing)

ShellWeGo is an open-source **Golang-based CLI tool** that simplifies Linux commands, allowing users to execute essential system operations without memorizing complex syntax.  

Designed for **both beginners and experienced users**, ShellWeGo provides an **interactive, customizable menu** based on user preferences.  

---

## Features  

**User-Friendly Interface** – No need to memorize commands  
**Dynamic Service Detection** – Automatically lists and manages running/non-running services  
**Customizable Shortcuts** – Tailor command execution based on your workflow  
**Fast & Lightweight** – Optimized for quick execution without unnecessary bloat  
**Cross-Platform** – Works on Linux and MacOS (**Windows WSL support planned**)  

---

## Installation  

### **Prerequisites**  
- [Go](https://golang.org/doc/install) **(1.20+ recommended)**  
- **Linux or MacOS terminal** (**Windows WSL supported**)  

### **Install via Go**  
```sh
go install github.com/yourusername/shellwego@latest
```

### **Clone & Build Manually**
```sh
git clone https://github.com/yourusername/ShellWeGo.git
cd ShellWeGo
go build -o shellwego
./shellwego
```

### **Usage**
```sh
shellwego [command] [options]
shellwego --help
```

### **Contributing**
We welcome contributions from the community! 

### **How to Contribute:**  
1. **Fork the repo**  
2. **Create a new branch**  
   ```sh
   git checkout -b feature-xyz
   ```
3. **Commit your changes**
   ```sh
   git commit -m "Added feature example...."
   ```
4. **Push to your branch**
  ```sh
  git push origin feature-example
  ```
5. **Submit a Pull Request**

### **Licensing**
ShellWeGo is released under the Apache 2.0 License, allowing free use, modification, and distribution.

Additionally, project-specific conditions apply under the ShellWeGo Additional License, which includes:

Attribution Requirement – Modifications and distributions must credit the original author.
Prohibited Uses – The software cannot be used for illegal, unethical, or malicious purposes.
By using ShellWeGo, you agree to both licenses.
