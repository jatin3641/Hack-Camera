# Camera Permission Awareness Demo

## Overview

This project demonstrates how web applications can request camera permissions and how users may unknowingly grant access to websites. It is intended solely for cybersecurity education, security awareness training, and controlled laboratory environments.

The project helps learners understand:

- Browser camera permission requests
- Basic web server deployment
- Network tunneling concepts
- Security risks of social engineering
- Responsible security practices

> **Disclaimer:** This project must only be used in environments where all participants have provided explicit consent. Unauthorized access to another person's device, camera, or personal information is illegal and unethical.

---

## Features

- Multiple demonstration page templates
- Browser permission request simulation
- Network tunneling support for lab testing
- Configurable output directory
- Basic error diagnostics
- Command-line argument support

---

## Supported Platforms

- Kali Linux
- Ubuntu
- Debian-based Linux
- macOS
- Termux (Android)
- Other Linux distributions with Bash support

---

## Technologies Used

- Bash
- HTML
- CSS
- JavaScript
- PHP

---

## Educational Purpose

This repository is designed to help students and cybersecurity enthusiasts understand:

- How browser permissions work
- Why users should verify links before opening them
- The importance of granting camera permissions only to trusted websites
- Security awareness against social engineering attacks

The project should only be executed in isolated lab environments for educational demonstrations.

---

## Installation

```bash
apt update && apt upgrade -y

apt install git php curl wget -y

git clone https://github.com/IshanSEC/Hack-Camera.git

cd REPOSITORY

chmod +x hack_camera.sh

bash setup
```

---

## Running the Project

```bash
bash main.sh
```

---

## Project Structure

```
project/
│
├── templates/
├── server/
├── assets/
├── output/
├── setup
└── main.sh
```

---

## Learning Objectives

After exploring this project, users should be able to:

- Understand browser permission mechanisms
- Learn basic web hosting concepts
- Explore secure networking principles
- Recognize common social engineering techniques
- Practice responsible cybersecurity ethics

---

## Legal Notice

This repository is provided exclusively for educational and research purposes.

Users are responsible for complying with all applicable laws and regulations. The author assumes no responsibility for misuse, unauthorized activities, or damages resulting from the use of this project.

---

## License

This project is intended for educational use. Review and follow the license terms before using or modifying the source code.

---

## Contributing

Contributions that improve documentation, code quality, or educational value are welcome. Please open an issue or submit a pull request with a clear description of your proposed changes.
