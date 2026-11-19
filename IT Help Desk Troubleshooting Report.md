# IT Help Desk Troubleshooting Report

## 1. Internet Connection

- **Issue:** The internet connection needed to be checked to determine whether the computer could communicate with an external network.
- **Commands used:** `ipconfig` and `ping 8.8.8.8`
- **Results:** The `ipconfig` command displayed the computer's network configuration. The Wi-Fi adapter showed an IPv4 address, subnet mask, and default gateway. The ping test successfully received all four replies, with 0% packet loss and an average response time of 23 milliseconds.
- **Findings:** The computer successfully communicated with Google's public IP address. The test showed that the network connection was working at the time of testing.
- **Resolution:** No network repair was necessary because the ping test was successful.

## 2. Slow Computer

- **Issue:** The computer's performance was inspected to determine whether applications were using excessive system resources.
- **Tools used:** Windows Task Manager.
- **Results:** Task Manager showed approximately 2% CPU usage, 56% memory usage, 1% disk usage, and 0% network usage. Windows Explorer was using approximately 228.9 MB of memory, while ChatGPT Classic was using approximately 480 MB.
- **Findings:** Overall CPU usage was low during the inspection. Memory usage was at 56%. No unusually high CPU usage was visible in the screenshot.
- **Resolution:** No immediate performance correction was necessary based on the information observed. Task Manager can be used for additional monitoring if the computer experiences slow performance.

## 3. Printer Problems

- **Issue:** The available printer devices were inspected to determine which printing options were configured on the computer.
- **Tools used:** Windows Control Panel and Devices and Printers.
- **Results:** The computer displayed two available printers: Microsoft Print to PDF and OneNote (Desktop). No physical printer was displayed.
- **Findings:** The computer had virtual printing options available, but no physical printer appeared in the device list.
- **Resolution:** No physical printer troubleshooting could be completed because a physical printer was not available for testing.

## 4. Application Problems

- **Issue:** Running applications were inspected to understand how Windows manages applications and their system resources.
- **Tools used:** Windows Task Manager.
- **Results:** Task Manager displayed several running applications, including Notepad, Settings, Task Manager, Terminal, and Windows Explorer. The screenshot did not show an application marked as not responding.
- **Findings:** The applications were visible in Task Manager, and their CPU and memory usage could be monitored. No frozen application was confirmed during this inspection.
- **Resolution:** No application needed to be closed during the recorded test. If an application becomes unresponsive, Task Manager can be used to investigate and safely close it when appropriate.

## 5. Password and Account Settings

- **Issue:** Windows sign-in settings were inspected to identify the available account authentication options.
- **Tools used:** Windows Settings and Accounts > Sign-in options.
- **Results:** Facial recognition, fingerprint recognition, and PIN sign-in were displayed as currently unavailable. A physical security key was listed as another sign-in option. The setting requiring Windows Hello sign-in for Microsoft accounts was turned on.
- **Findings:** Several Windows Hello sign-in methods were unavailable on the device. The sign-in settings also showed an option to require sign-in again after 15 minutes away.
- **Resolution:** No account settings were changed. I identified the available sign-in options and documented which authentication methods were unavailable.

## Conclusion

- **What I learned:** I learned how to check network connectivity using Command Prompt, review computer performance using Task Manager, inspect available printer devices, monitor running applications, and locate Windows sign-in settings.
- **Skills practiced:** Windows troubleshooting, basic networking, Command Prompt, IP configuration, ping testing, system performance monitoring, printer configuration, application management, and Windows account settings.
