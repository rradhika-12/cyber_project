# cyber_project
## Honeypot based firewall 
## An integration of AI-Driven Personal Firewall & Honeypot Trap with Real-Time Visualization

 #### Project Description

        This GUI-based parser tool is built using Python and Tkinter to analyze logs from the Cowrie honeypot. Cowrie is a popular SSH and Telnet honeypot that simulates a shell for attackers, logging every command and interaction. Additionally, the project incorporates basic firewall configurations to monitor and restrict unauthorized access attempts during analysis. This tool simplifies and enhances the log analysis process by visualizing key insights like attacker IP addresses, geolocation, login attempts, and other suspicious behaviors while reinforcing security through firewall rules.

#### Project Goal

        To convert raw honeypot logs into structured, readable, and actionable threat intelligence data with a user-friendly interface—helping both technical and non-technical stakeholders understand cyber threats better.

### How It Works
            Clone or download the required extension file from given extensions.
            User selects a Cowrie log file (in .json format).
            On clicking "Parse Log", the tool reads, parses, and extracts key information.
            Output is displayed in a clean, scrollable text box.
            Users can export the output as .txt or .csv.


### A Linux based Cybersecurity Tool which captures all the activities and keeps track of it. 
### Firewall filters incoming/outgoing network packets based on rules (IP, port, protocol).

    When we run a honeypot like Cowrie on a real server/VPS, it must be isolated and protected so attackers don’t actually harm your system.


### Honeypot is data source 
## I used Cowrie honepot in my project 
    |  **Purpose**                            |     📄 **Description**                                                               
    | **Threat Intelligence Collector**       |     Cowrie simulates a vulnerable SSH/Telnet service to attract attackers.                   |
    | **Log Generator**                       |     It captures detailed logs of attacker interactions (e.g., login attempts, commands run). |
    | **Foundation for Analysis**             |     Your tool parses these logs to identify patterns, IPs, success/failure attempts, etc.    |

### This cybersecurity tool in perspective of trap the attacker easily on a GUI so that becomes easy for everyone to check what happens on their system and by whom. Ultimate goal it for extracting critical threat intelligence—enabling security researchers, analysts, and SOC teams to detect, understand, and respond to malicious activities in a proactive and visual manner besides creating trap for malicious attacker.

#### The process how it is executed:
            1. Update system and install required dependencies
            2. Check Python version
            3. Setup Python virtual environment + Create Project Folder
            4. Build Personal Firewall + add filtering rules + Run Firewall
            5. Install Cowrie honeypot + Configure Cowrie + Run Cowrie (Input: JSON-formatted Cowrie log file)
            6. Test the honeypot
            7. Redirect Suspicious Traffic to Honeypot
            8. Analyze Logs & Visualize
            9. Build Dashboard        **I used Tkinter**
            10. Develop + Debug + Test working

#### Additional features 
            1. GUI
            2. Parse logs to extract attacker info (IP, commands, timestamps)  Parser: JSON and Regex-based
            3. geocoder
            4. matplotlib
            5. Standalone Executable with PyInstaller
            6. Installable .deb package

#### Testing:
            Tested using real Cowrie logs from a deployed honeypot


#### Benefits to Stakeholder

    Cybersecurity Teams: Faster log analysis for threat detection

    SOC Analysts: View and export intelligence from attacker data

    Researchers: Collect OSINT from honeypot logs

    Students & Learners: Learn honeypot interaction patterns easily

    Law Enforcement: Identify suspicious sources via IP logs
