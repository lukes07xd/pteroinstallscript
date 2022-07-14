This script was made to make the pterodactyl panel installation easier and faster.

Some of you may be asking: WHAT EVEN IS PTERODACTYL PANEL ???
Well, it's a web based control panel for hosting Game servers (Minecraft, Rust, Counter strike : Global Offensive, Ark: Survival Evolved, Garrys Mod, Team Fortress 2)
                                                 And Voice servers (Mumble, Teamspeak3)
                                                 You can also add any other servers that run on linux.

Please note that pterodactyl panel only supports: Ubuntu 18.04 and 20.04
                                                  CentOS 7 and 8
                                                  Debian 9, 10 and 11
        
How to use: 
1) Open terminal on any of the supported versions.
2) Make sure curl is installed by typing "curl" (if it's not install it with "apt install curl")
3) Switch to root user by entering "sudo -i" and hitting enter.
4) Now run this command: "bash <(curl -s https://raw.githubusercontent.com/lukes07xd/pteroinstallscript/main/pteroinstall.sh)"
5) Follow the instructions in your linux console.
6) Type "wings" to make sure wings were installed successfully, there may be an error because it's not configured yet.
7) Open web browser and enter the IP/Domain address you have set up pterodactyl panel with.
8) Log in with your credentials and password made during the installation.
9) Head into configuration in the top-right corner.
10) Create a new location.
11) Create a new node, and set up your ip addresses. (use 0.0.0.0)
12) Make sure your daemon configuration was saved by looking at the notification at the top of the screen.
13) Go into your linux console and type "reboot" to completely re-start every service and reboot the machine. (Optional, but if you want better stability do it.)
14) Head into your web-based control panel and create a new server in the same place you have created your node.
15) Your pterodactyl panel should now be fully configured and hosting a server.
