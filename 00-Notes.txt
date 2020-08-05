--------------------------------------------------------------------------------
                             ___       __       __      
                            /   \     |  |     |  |     
                           /  ^  \    |  |     |  |     
                          /  /_\  \   |  |     |  |     
                         /  _____  \  |  `----.|  `----.
                        /__/     \__\ |_______||_______|
                                                        
               ___      .______     ______    __    __  .___________.
              /   \     |   _  \   /  __  \  |  |  |  | |           |
             /  ^  \    |  |_)  | |  |  |  | |  |  |  | `---|  |----`
            /  /_\  \   |   _  <  |  |  |  | |  |  |  |     |  |     
           /  _____  \  |  |_)  | |  `--'  | |  `--'  |     |  |     
          /__/     \__\ |______/   \______/   \______/      |__|     
                                                                     
                          _______.     _______. __    __  
                         /       |    /       ||  |  |  | 
                        |   (----`   |   (----`|  |__|  | 
                         \   \        \   \    |   __   | 
                     .----)   |   .----)   |   |  |  |  | 
                     |_______/    |_______/    |__|  |__| 
                     
--------------------------------------------------------------------------------
TOC:
----                           
01- ssh intro.
01.1 why? telnet vs ssh

02- ssh architecture and design
02.1 Client-Server model (ssh in Linux and windows)
02.2 ssh client side config
02.3 ssh server side config
02.4 Debugging ssh (client and server side)

03- Authentication methods.
03.1 Understanding fingerprints
03.2 Passwords
03.3 Keys (host keys, user key generation, storage, perms ssh-agent)
03.4 Keys with passphrases

04- Aditional capabilities.
04.1 SCPing
04.2 Tunneling (localforward, remote forward, dynamic)
04.3 X11 forwarding

05- Goodies.
05.1 Keychain
05.2 putty suite (puttygen, pageant, configure putty options)

Caveat emptor:
Most of the information here was extracted from the excelent book
"SSH Mastery: OpenSSH, PuTTY, Tunnels and Keys", by Michael W. Lucas.
Check it out here: https://amzn.to/3juM4vX
