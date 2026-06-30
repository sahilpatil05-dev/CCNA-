# Introduction to Cisco IOS CLI
- USB and RJ45   are two kinds of console ports are common on Cisco devices
- Rollover cable is used to connect to the RJ45 console port on a Cisco device
- Default Cisco console port settings: Parity = none
- Default Cisco console port settings:Speed (baud rate) = [9600 bits per second]
- Default Cisco console port settings:Data bits = [8]
- Default Cisco console port settings:Flow control = [None]
- Default Cisco console port settings:Stop bits = [1]
- enable secret uses type [5] (MD5) encryption.
- Encrypt current and future passwords on the device:Router(config)# [service password-encryption]
- Cisco's service password-encryption command uses type [7] encryption

# CLI

# Terminal Emulator(Putty)
- View the available commands:Router#[?]

# User Exec Mode
-  exec mode the lowest-level mode in Cisco IOS
- In Cisco IOS, user EXEC mode is indicated by Router[>]

# Privilleged Exec 
- privileged EXEC mode provides complete access to view the device's configuration files
- Enter privileged EXEC mode:Router>[enable]
- Return to privileged EXEC mode:exit
- View the running configuration:sh run/show running-config
- In Cisco IOS, privileged EXEC mode is indicated by Router[#]
- three commands can be use to save the configuration
Router# [write]
Router# [write-memory]
Router# [copy running-config startup-config]

# Global Configuration mode
- Enter global configuration mode:Router# [configure terminal]
- In Cisco IOS, global configuration mode is indicated by Router[(config)#]
- Use the 'no' keyword to remove a configured command.
- You use the [do] keyword to execute privileged EXEC commands in global configuration mode.
- View the startup configuration:Router# [show startup-config]

# Enable password
- Configure an MD5-encrypted enable password:Router(config)# [enable secret password]
- If service password-encryption is removed, currently encrypted passwords will not  be decrypted
- Configure an unencrypted password to protect privileged EXEC mode:Router(config)# [enable password password]

# Configuration files
- Runnig Config
- Start-up Config