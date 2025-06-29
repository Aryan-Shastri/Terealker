# 🕵️‍♂️ Tereallker Honeypot Suite

```
 _______                  _  _  _             
|__   __|                | || || |            
   | | ___ _ __ ___  __ _| || || | _____ _ __ 
   | |/ _ \ '__/ _ \/ _` | || || |/ / _ \ '__|
   | |  __/ | |  __/ (_| | || ||   <  __/ |   
   |_|\___|_|  \___|\__,_|_||_||_|\_\___|_|   
```

> "Curiosity killed the cat...  
> and satisfaction trapped it."

> "You can't kill what you can't see."  
> — Art the Clown

> "You know... you’re gonna die tonight, right?"  
> — Art the Clown

> "Smile! It’s almost over."  
> — Art the Clown

---

## Description

**Tereallker** is a multi-service honeypot that emulates SSH, FTP, HTTP, Telnet, SMTP, POP3, MySQL, and Redis servers. It logs all connection attempts, credentials, and commands, helping you detect, analyze, and study unauthorized access or scanning on your network. The tool is available as a standalone executable for both Windows and Linux.

---

## Features

- **SSH, FTP, HTTP, Telnet, SMTP, POP3, MySQL, Redis** honeypot services
- Realistic banners and responses to fool attackers and scanners
- Customizable web page for the HTTP honeypot
- Logs all credentials, commands, and requests
- Interactive console for starting/stopping services and viewing status
- Colorful themed banner

---

## How to Use

### 🪟 Windows

1. **Download `Tereallker.exe`** to your Windows machine.
2. **Open Command Prompt as Administrator:**
   - Press `Win`, type `cmd`, right-click **Command Prompt**, and select **Run as administrator**.
3. **Navigate to the folder containing `Tereallker.exe`:**
   ```sh
   cd path\to\your\Tereallker.exe
   ```
4. **Run the honeypot:**
   ```sh
   Tereallker.exe
   ```
   > *Administrator privileges are required to bind to ports 21, 22, and 80.*

---

### 🐧 Linux

1. **Download or copy the `Tereallker` binary to your Linux machine.**
2. **Make it executable (if needed):**
   ```sh
   chmod +x Tereallker
   ```
3. **Run the honeypot as root:**
   ```sh
   sudo ./Tereallker
   ```
   > *Root privileges are required to bind to ports 21, 22, and 80.*

---

## Console Commands

| Command  | Description                                   | Usage                       |
|----------|-----------------------------------------------|-----------------------------|
| help     | Show this help menu                           | help                        |
| status   | Show status of all services                   | status                      |
| clear    | Clear the console                             | clear                       |
| start    | Start a service or all                        | start (service)             |
| stop     | Stop a service or all                         | stop (service)              |
| setweb   | Set custom HTML page for HTTP service         | setweb /path/to/file.html   |
| service  | Show available services                       | service                     |
| exit     | Exit the honeypot console                     | exit                        |

---

## Available Services

| Service | Description          |
|---------|----------------------|
| ssh     | SSH honeypot server  |
| ftp     | FTP honeypot server  |
| http    | HTTP honeypot server |
| telnet  | Telnet honeypot      |
| smtp    | SMTP honeypot        |
| pop3    | POP3 honeypot        |
| mysql   | MySQL honeypot       |
| redis   | Redis honeypot       |
| all     | All services         |

---

## Logs

- SSH logs: `ssh_honeypot.log`
- FTP logs: `ftp_honeypot.log`
- HTTP logs: `http_honeypot.log`
- Telnet logs: `telnet_honeypot.log`
- SMTP logs: `smtp_honeypot.log`
- POP3 logs: `pop3_honeypot.log`
- MySQL logs: `mysql_honeypot.log`
- Redis logs: `redis_honeypot.log`

Logs are saved in the same directory as the executable.

---

## Disclaimer

**Tereallker is for educational and research purposes only.  
Deploy only on systems and networks you own or have explicit permission to monitor.  
Unauthorized deployment may violate laws or policies.**

---

## Credits

Developed by The Code Clown
