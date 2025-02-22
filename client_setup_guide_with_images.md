# Legend  
- [**Full Manual Setup (Option 1)**](#full-manual-setup-option-1) - Step-by-step manual setup where users configure RustDesk settings manually.  
- [**Copy/Paste Config (Option 2)**](#copy-paste-config-option-2) - Users copy and paste a pre-configured string into RustDesk, simplifying the setup.  
- [**Automatic Install via Script (Option 3)**](#automatic-install-via-script-option-3) - A script automates the installation and configuration process for RustDesk on Windows and Linux.  

# Full Manual Setup (Option 1)
1. Download from https://github.com/rustdesk/rustdesk/releases/
2. [Linux Install](https://rustdesk.com/docs/en/client/linux/), [Windows Install](https://rustdesk.com/docs/en/client/windows/)
3. Open up RustDesk
4. ![It should look like this](./img/default_home_screen.png)
5. ![Open Settings](./img/howto_open_settings.png)
6. ![Select Network Tab](./img/how_to_select_network_tab.png)
7. ![Enable Network Settings](./img/howto_enable_network_settings.png)
8. ![Select the Network Tab](./img/how_to_select_correct_network_tab.png)
9. ![Enter the Network Config](./img/enter_network_config.png)
- ID-Server: `138.2.137.178`
- Relay-Server: `138.2.137.178`
- API-Server: `https://138.2.137.178`
- Key: `NkhBuhnirkBxeidDNyLU5MVo955yyq51K8x3LHTipPk=`
10. ![Enter the Network Config](./img/verify_network_config.png)
11. ![Connect To Remote Pc](./img/connect_to_remote_pc.png)
12. ![Enter the Password](./img/how_to_enter_password.png)
13. ![Fix the video size](./img/how_to_fix_video_size.png)


# Copy/Paste Config (Option 2)
1. Download from https://github.com/rustdesk/rustdesk/releases/
2. [Linux Install](https://rustdesk.com/docs/en/client/linux/), [Windows Install](https://rustdesk.com/docs/en/client/windows/)
3. Open up RustDesk
4. ![It should look like this](./img/default_home_screen.png)
5. ![Open Settings](./img/howto_open_settings.png)
6. ![Select Network Tab](./img/how_to_select_network_tab.png)
7. ![Enable Network Settings](./img/howto_enable_network_settings.png)
8. ![Select the Network Tab](./img/how_to_select_correct_network_tab.png)
9. Copy `=0nI9sGUwlGVIx0M4hzSxUTc5lXN1kzbW1UNVxUeOREZpVGeCtmcp5Ga1JEar5kI6ISeltmIsICO3EjL3MTMuIjL4MTMv8iOzBHd0hmI6ISawFmIsICO3EjL3MTMuIjL4MTMiojI5FGblJnIsICO3EjL3MTMuIjL4MTMiojI0N3boJye`
10. ![Paste the config](./img/paste_network_config.png)
11. ![Automatically entered Network Config](./img/enter_network_config.png)
12. ![Verify the Network Config](./img/verify_network_config.png)
13. ![Connect To Remote Pc](./img/connect_to_remote_pc.png)
14. ![Enter the Password](./img/how_to_enter_password.png)
15. ![Fix the video size](./img/how_to_fix_video_size.png) 

# Automatic install via script (Option 3)
1. Download and run script from [github](https://github.com/JohnnyElaine/RustDeskSetup)
2. Windows: `WindowsAgentAIOInstall.ps1`, Linux: `linuxclientinstall.sh`