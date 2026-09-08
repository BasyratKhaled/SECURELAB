# SEC-LAB v2.0 — Interactive Terminal Portfolio & Security Lab Simulation

An interactive, terminal-styled portfolio and simulation tool built for cybersecurity enthusiasts, penetration testers, and security researchers. **SEC-LAB v2.0** mimics a retro Linux/Unix shell interface, allowing users to explore professional skills, run simulated security scans, view files, and execute custom scripts directly from their browser or terminal.

---

## Features

- **Boot Sequence Simulation:** Custom boot process loading kernel modules, encrypted filesystems, and simulated secure uplinks.
- **ASCII Art Branding:** Embedded green-themed ASCII banner artwork.
- **Command Parser:** Fully functional terminal-like command interpreter with inline help documentation.
- **Interactive File System Exploration:** Standard file inspection utilities (`ls`, `cat`) to view profile files like `about.txt`, `projects.sh`, and `contact.cfg`.
- **Simulated Security Tools:** Built-in scanner (`scan [url]`) and execution wrapper (`run [scriptname]`) for dynamic terminal interactions.

---

## Available Commands

| Command | Usage | Description |
| :--- | :--- | :--- |
| `help` | `help` | Displays all available shell commands and basic usage guide. |
| `ls` | `ls` | Lists directory contents. |
| `cat` | `cat [filename]` | Reads and prints the content of a target text file. |
| `run` | `run [scriptname]` | Executes a simulated executable script. |
| `scan` | `scan [url]` | Runs a simulated automated vulnerability assessment on a target URL. |
| `whoami` | `whoami` | Prints current user privileges and user context. |
| `sudo` | `sudo [command]` | Executes commands with elevated root/superuser permissions. |
| `clear` | `clear` | Clears the terminal screen buffer. |

---

## File System Overview
- **`about.txt`**: Contains professional summary, skills (Network Exploitation, Web App Sec, Reverse Engineering), and active status.
- **`projects.sh`**: Lists active security projects, tools, and research repositories.
- **`sandbox.sh`**: Environment setup script for running isolated security tests.
- **`contact.cfg`**: Config file containing secure communication links and contact details.

---

