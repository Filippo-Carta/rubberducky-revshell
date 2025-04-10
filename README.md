# rubberducky-revshell
- Simple reverse shell installer (using hoaxshell).
# About:
- Title: RubberDucky-RevShell
- Description: Rubberducky payload that install hoaxshell on the target system.
- AUTHOR: Filippo-Carta 
- Version: 1.0
- Category: Remote shell
- Target: Tested: Windows 10 Untested: Windows 11
- Attackmodes: HID
- Duration: 7/15 seconds
- Persistent: No
- Detected by Microsoft windows defender: No (MWD will be temporarily deactivated).
- WARNING (It may be flagged by other antivirus programs)
- Need Admin Privildedges.
# Workflow:
- Add an ExclusionPath on TEMP folder and powershell.exe (window: hidden).
- Download the reverseshell.ps1 and execute it.
- The script disable (temporarily) windows defender.
- Use the encrypted payload (with base64) given from the hoaxshell tool (aviable at https://github.com/t3l3machus/hoaxshell).
- Connected to attacker's computer.
# Usage:
1. Complete with your payload at line 3 in the reverseshell.ps1 file.
2. Upload to https://www.dropbox.com the file just modified.
3. Copy the link of the reverseshell.ps1 and paste it at line 16 in PAYLOAD.txt.
4. Encode the PAYLOAD.txt at https://payloadstudio.com/community/.
5. Upload it to the rubberducky.
6. RUN.
# Tips
Use ngrok tunnelling for better connection.
# Warning: Potential Misuse of Script
This script is provided solely for educational purposes. It is intended to demonstrate specific programming techniques and concepts. Any misuse or application of this script for malicious purposes is strictly prohibited. Users should exercise caution and responsibility when utilizing this code. The authors and contributors are not liable for any damage or legal issues that may arise from improper use of this script. Always ensure that you have the necessary permissions and legal rights before running scripts on any system or network.
