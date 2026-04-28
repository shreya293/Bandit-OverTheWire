# Linux Security Fundamentals: OverTheWire Bandit

## Project Overview
This project documents my journey through the **OverTheWire Bandit** wargame, designed to build proficiency in the Linux command-line interface (CLI) and basic security principles. Through these challenges, I mastered essential tools for system administration and network troubleshooting.

## Documentation
* **[View Full Technical Report](./Report_Format.docx)**: This document contains step-by-step solutions, screenshots of successful completions, and the logic used to solve complex levels.

## Key Learning Objectives
* **CLI Navigation**: Mastering file system traversal and hidden file discovery.
* **Data Manipulation**: Using filters like `grep`, `sort`, and `uniq` to extract specific information from large datasets.
* **Permissions & Ownership**: Understanding and manipulating Linux file permissions and user groups.
* **Network Communication**: Utilizing `SSH` for secure remote access and `netcat` for port-based communication.
* **Basic Automation**: Creating simple **Bash scripts** to handle repetitive tasks and automated login attempts.

## Featured Task: Automated Brute-Force (Level 24)
In this level, I developed a Bash script to automate a brute-force attack against a network service.
* **Challenge**: Submit a 4-digit PIN (0000-9999) along with a password to a specific port.
* **Solution**: I used a `for` loop with `seq` and piped the output into `nc` (netcat).
* **Skills Demonstrated**: Scripting logic, piping, and network service interaction.

## Tools & Commands Used
* **Protocols**: SSH, Netcat (nc)
* **Text Processing**: grep, cut, tr, awk, base64
* **System Commands**: find, ls, cd, cat, file, du
* **Scripting**: Bash (loops, variables, pipes)
# Linux Fundamentals & Security Labs (OverTheWire)

## Project Overview
This repository contains my technical report documenting the completion of the **OverTheWire Bandit** challenges. [cite_start]The project focused on building a solid foundation in the Linux command-line interface (CLI), which is essential for my career goals in **Network Operations (NOC)** and **Cybersecurity**[cite: 302].


## Core Skills Demonstrated
* **Remote Management**: Using **SSH** to interact with remote Linux servers.
* **Network Tools**: Utilizing **Netcat (nc)** for service interaction and port communication.
* **Automated Logic**: Implementing **Bash loops** and sequences to automate repetitive tasks (e.g., Level 24 brute-force simulation).
* **Data Filtering**: Applying Linux commands like `grep`, `sort`, and `uniq` to isolate critical information.

## Why This Matters
[cite_start]Mastering the Linux terminal is a core requirement for troubleshooting enterprise network infrastructure and managing server environments[cite: 302, 307]. [cite_start]This lab served as a practical introduction to the tools I will use daily as a **NOC Engineer**[cite: 302].
## Conclusion
This project provided a solid foundation in Linux—a critical skill for my career goal as a **NOC Engineer**. It taught me how to approach complex problems systematically using the terminal.
