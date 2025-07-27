# cyber_project
## Honeypot based firewall 
## An integration of AI-Driven Personal Firewall & Honeypot Trap with Real-Time Visualization

### A Linux based Cybersecurity Tool which captures all the activities and keeps track of it. 
### Firewall filters incoming/outgoing network packets based on rules (IP, port, protocol).

    When we run a honeypot like Cowrie on a real server/VPS, it must be isolated and protected so attackers don’t actually harm your system.


### Honeypot is data source 
## I used Cowrie honepot in my project 
    |  **Purpose**                            |     📄 **Description**                                                               
    | **Threat Intelligence Collector**       |     Cowrie simulates a vulnerable SSH/Telnet service to attract attackers.                   |
    | **Log Generator**                       |     It captures detailed logs of attacker interactions (e.g., login attempts, commands run). |
    | **Foundation for Analysis**             |     Your tool parses these logs to identify patterns, IPs, success/failure attempts, etc.    |

### I made this cybersecurity tool in perspective of trap the attacker easily on a GUI so that becomes easy for everyone to check what happens on their system and by whom. Ultimate goal it for extracting critical threat intelligence—enabling security researchers, analysts, and SOC teams to detect, understand, and respond to malicious activities in a proactive and visual manner besides creating trap for malicious attacker.

#### The process how it is executed:
            1. Update system and install required dependencies
            2. Check Python version
            3. Setup Python virtual environment + Create Project Folder
            4. Build Personal Firewall + add filtering rules + Run Firewall
            5. Install Cowrie honeypot + Configure Cowrie + Run Cowrie
            6. Test the honeypot
            7. Redirect Suspicious Traffic to Honeypot
            8. Analyze Logs & Visualize
            9. Build Dashboard        **I used Tkinter**
            10. Develop + Debug + Test working

#### Additional features 
            1. GUI
            2. Parse logs to extract attacker info (IP, commands, timestamps)
            3. geocoder
            4. matplotlib
            5. Standalone Executable with PyInstaller
            6. Installable .deb package
