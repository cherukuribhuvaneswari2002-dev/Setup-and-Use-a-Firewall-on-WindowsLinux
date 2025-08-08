This document covers step-by-step configuration of Windows Firewall using GUI and PowerShell:

1. Opened Windows Defender Firewall with Advanced Security.
2. Listed current inbound/outbound rules.
3. Added a rule to block inbound traffic on TCP port 23 (Telnet).
4. Tested the block rule using Test-NetConnection.
5. Added a rule to allow SSH on TCP port 22.
6. Tested the SSH allow rule using Test-NetConnection -Port 22.
7. Removed the test block rule to restore the original state.
8. Documented all commands and GUI actions.
9. Summarized how Windows Firewall filters network traffic.
