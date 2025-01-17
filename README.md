# :page_facing_up:Beginner M5Stick Guide
This is a Beginner Guide for the M5 Stick, held as simple as possible, for normal people to understand it! But you also should bring a bit of knowlege to understand it better. I also Hyperlinked all the Words, that are difficult to understand. All the important links will be down below.


## 💻 M5Stick in General 
The M5Stick is a compact, [ESP32](https://de.wikipedia.org/wiki/ESP32)-powered [IoT](https://www.techtarget.com/iotagenda/definition/Internet-of-Things-IoT) development board designed for rapid prototyping and creativity. It supports a wide range of modules and open-source communities, making development easier and more accessible. I recommend buying the M5Stick plus 2 because of its better chip & better battery runtime.

### ⚙️ Hardware of The M5 Stick

| **Feature**            | **Details**                             |
|------------------------|-----------------------------------------|
| **Processor**           | ESP32, 240MHz, dual-core, 600 DMIPS    |
| **Memory**              | 4MB Flash Memory                       |
| **Battery**             | 95 mAh @ 3.7V                          |
| **Screen**              | 0.96-inch TFT LCD, 80x160 resolution   |
| **Ports**               | USB Type-C, GROVE (I2C, UART)          |
| **Size & Weight**       | 48.2x25.5x13.7mm, 15.1g                |
| **Temperature Range**   | 0°C to 60°C                            |
  


## 👣 Frist-Steps
After you got ur M5Stick you can install a custom Firmware on it.
I recommend using one of these:

+ ### [Bruce](https://github.com/pr3y/Bruce) (More Features!)
+ ### [Nemo](https://github.com/n0xa/m5stick-nemo)

## 📦 Installation Guide
There are some good Youtube Tutorials out ther so I will put the link here:

**[Installing Bruce](https://www.youtube.com/watch?v=_ncMwOkbCjQ)**

**[Installing Nemo](https://www.youtube.com/watch?v=0cL40hzTiwU)**


## 🦈 Bruce Features
Bruce has more features than Nemo and overall is better in my opinion. Here is a List of the overall features Bruce offers:

- ### 🛜 Wifi Stuff                    (Wifi Attacks, Spams, ...)
- ### 🔵 BLE / Bluetooth Low Energy    (Bluetooth Attacks, Spams, ...)
- ### 📻 RF / Radio Frequenzy          (Scan/Copy Frequenzys, Jamming, ...)
- ### ⭕ IR / Infared                  (Turn TVs On or Off, ...)
- ### 📉 FM / Frequency Modulation     (Brodcast Standard, Brodcast rerserved - Warning! Educational Purpose only!)
- ### 📡 NRF24 / 2,4GHz Antenna        (For Better Jamming, need to be bought seperatly)
- ### 📃Scripts                        (Load & Run Custom Scripts)
- ### 🕒Clock

## 🐟 Nemo Features

- ### ⚠️ Spams       (Bluetooth & Wifi Spams)
- ### 🛜 Wifi Portal (Save Email & Passwords - **Warning! Educational Purpose only!**)
- ### 🕒 Clock

To see more features or more details of the Features check out the [**Bruce Detailed**](#-bruce-detailed) section. If you want to know how to install the Firmware check out [**Installation Guide**](#-installation-guide)
      
## ⚡ Wiring Diagrams

<details>
   <summary>NRF24 / CC1011</summary>
  
  ![image](https://github.com/user-attachments/assets/8791d802-6040-4425-8f46-effc2582b12d)
  
</details>

<details>
   <summary>RFID2</summary>
  
  ![image](https://github.com/user-attachments/assets/e6a85b02-9222-4bfe-89ac-5cd9106d60b3)
  
</details>

<details>
   <summary>RFID2/RC522</summary>
  
![image](https://github.com/user-attachments/assets/67ab8513-52a0-4edd-b15a-4e66e56ed747)

</details>

<details>
   <summary>IR Transmitter/Receiver </summary>
  
![image](https://github.com/user-attachments/assets/3dcb0aa6-c31f-4b21-a12d-bc83f498404a)

![image](https://github.com/user-attachments/assets/ff334803-4460-4edf-aa63-6312cde1ad4e)

</details>

<details>
   <summary>USB Module</summary>
  
![image](https://github.com/user-attachments/assets/30d13722-601f-4de0-93f8-3b7d2bb8c018)

</details>

<details>
   <summary>NFC RFID</summary>
  
![image](https://github.com/user-attachments/assets/d6984f14-2ee3-4878-8190-e142147f308b)

</details>

<details>
   <summary>SD Card Module</summary>
  
![image](https://github.com/user-attachments/assets/5aad954d-b8e1-41d2-b9b6-493b8e5075a2)

</details>

<details>
   <summary>SD Card + NRF24</summary>
  
![image](https://github.com/user-attachments/assets/73f623a1-03a9-4070-903b-9bdaad3af783)

</details>

<details>
   <summary>CC1011 + NRF24</summary>
  
![image](https://github.com/user-attachments/assets/25578c5d-4219-4071-953f-e9d0750057c2)

</details>

## 🎓 Bruce Detailed

### Here I will explain every Option for the Bruce software!
____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

- ### 🛜 WiFi
    - ### Connect Wifi
      Connect your M5Stick to your home Network or any Wifi in general
    - ### WiFi AP
      Use your M5Stick as an [Local AP](https://www.lifewire.com/wireless-access-point-816545). After enabling it will show up as Network, default password to it is `brucenet`
    - ### WiFi Atks
      - **Target Atks**
        Scans for a WiFi APs to either get more information of it (MAC adress & channel), [Deauth](https://nordvpn.com/de/blog/deauthentication-attack/) (Kick people out of the wifi), Clone AP name and make an Evil Portal.
        
      - **Beacon Spam**
        - **Funny SSID**
          Creates Many Different [SSIDs](https://nordvpn.com/blog/what-is-ssid/) with funny names
        - **Ricky Roll**
          Creates SSIDs with [Lyrics](https://www.youtube.com/watch?v=dQw4w9WgXcQ) of Never Gonna Give you up
        - **Random SSID**
          Creates many Random SSIDs
      - **Deauth Flood**
        Spams Deauth so everyone connected gets instantly kicked out
    - ### Evil Portal
         - **Default**
          Creates a simple Evil Portal where the victim needs to log in with "Google". If a Victim enters their Email and Password it will show up like this:
          
            <details>
               <summary>Image</summary>
    
           ![IMG_4822](https://github.com/user-attachments/assets/bbce7189-c6fe-4645-8ab8-39b3664927b4)
    
           </details>

        - If your device has an SD Card reader with a FAT filesystem formatted card inserted, the usernames and passwords will be logged to Bruce_creds.csv on the SD Card for you to peruse later.        
         - **Custom HTML**
           Creates an Evil Portal with custom UI, i.e. Public Free Wifis, that you can load onto your M5Stick via WebUI

    - ### Reverse Shell
        - Create a **[Reverse shell](https://www.imperva.com/learn/application-security/reverse-shell/)**
          
          **1. Setup**
           - Go to `WiFi>Reverse Shell` and start the "Reverse Shell Mode" in Bruce.
           - Start and Wait for the BruceC2 to connect.
           - Use the BadUSB option to install a Script on the Victims Computer
          
          **2. Usage**
           - Navigate to the web server (http://192.168.4.1) using your browser.
           - Use the interface to monitor the connection status or execute shell commands.

          **3. Commands**
          
          `exit`: Disconnect the ESP32 and terminate the session.
          
          `clear`: Clear the terminal on the server side.
          
          `B:<command>`: Execute a Bash command on the server (e.g., B:ls).
          
          `PS:<command>`: Execute a PowerShell command on the server (e.g., PS:Get-Process).
          
          `showConsole`: Show the console output in BruceC2.
          
          `hideConsole`: Hide the console output in BruceC2.
   - ### Tellnet
     - Connect to [TelNet](https://www.geeksforgeeks.org/introduction-to-telnet/) servers and execute remote commands.
   - ### SSH
     - Connect to [SSH](https://info.support.huawei.com/info-finder/encyclopedia/en/SSH.html) servers and execute remote commands.
   - ### DPWO
     - [DPWO](https://github.com/caioluders/DPWO) (Default Password Wifi Owner) is a tool that automatically discover passwords of nearby WiFi networks. This is possible due to the default password schemas used by Brazilian internet providers (NET, VIVO, GVT, etc).
   - ### Raw Sniffer
     - A Tool that captures and saves raw wireless network data, it will save in `.pcap` format which can be opened in [Wireshark](https://www.wireshark.org/download.html)
   - ### Scan Hosts
     - Scan and See what devices are connected to a wifi by scanning and selecting the network, the devices will appear in IP adress form.
     - After going to `WiFi>ScanHost>SelectIP>` there are 4 different options:
       
       - **SSH Connect**
         Tries connecting into the Host by using SSH
         
       - **Station Deauth**
         Spams Deauth Frames to the selected device
         
       - **[ARP](https://www.geeksforgeeks.org/how-address-resolution-protocol-arp-works/) Spoofing**
         Sends fake ARP Resonses to the host and to the Gateway, provoking communication interruption. this is the fist step of a [Man-In-The-Middle attack using the 2nd OSI layer vulnerability](https://www.valencynetworks.com/articles/cyber-attacks-explained-man-in-the-middle-attack.html).
         
       - **[ARP](https://www.geeksforgeeks.org/how-address-resolution-protocol-arp-works/) Poisoning**
         Sends fake ARP (Address Resolution Protocol) responses to all hosts and to the gateway with random MAC addresses. It can possibly cause CAOS in the network, as all devices won't find the gateway to communicate.

    - ### WireGuard
      [WireGuard tunneling](https://nordlayer.com/learn/vpn/wireguard/) is a modern, fast, and secure VPN protocol that creates encrypted tunnels for securely transmitting data over the internet.

      - Use it by going to `WiFi>WireGuard>SelectYourWiFi` then select your preffered WiFi and your connected

      - **Disconnect** by going to `WiFi>Disconnect` click on Disconnect
    - ### Brucegotchi
      Is like the name says basically a Tamagotchi but for Bruce wich does things like
      
      - Pwngrid spam (SSID spam)

      - Deauth nearby WiFi networks in different channels
        
      - Collect and save [HandShakes (EAPOL)](https://www.wifi-professionals.com/2019/01/4-way-handshake), can be used to crack WiFi Passwords

____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


## 🔧 Official M5stack Modules

- [**M5Stack FM Receiver**](https://s.click.aliexpress.com/e/_omN07yd) (Receive Different Signals, i.e. Receive Car key Signal **Warning! Educational Purpose Only!**)
- [**M5Stack FM Transmitter**](https://s.click.aliexpress.com/e/_ooJOihT) (Transmitt Diffrent Signals i.e. Use the received Car key SIgnal **Warning! Educational Purpose Only!**)
- [**M5Stack IR Module**](https://s.click.aliexpress.com/e/_olQWFCl) (Get more IR range i.e. Turn off TVs from a longe range)
- [**M5Stack RFID2**](https://s.click.aliexpress.com/e/_oDytw1x) (Read/Clone/Copy tags i.e. Clone House Key tag **Warning! Educational Purpose Only!**)

## 🔧 Unofficial M5stack Modules

- [**CC1101**](https://s.click.aliexpress.com/e/_om9uBlJ) (External Antenna for more range and more powerfull jamming **Warning! Educational Purpose Only!**)
- [**NRF24L01**](https://s.click.aliexpress.com/e/_oCg9cPR) (External Antenna for more range and more powerfull jamming **Warning! Educational Purpose Only!**)
- [**CH9329**](https://s.click.aliexpress.com/e/_onS3X9R) (USB Port)
- [**SD Reader**](https://s.click.aliexpress.com/e/_oECUXah) (SD Reader For more storage. Default one only has 8MB)
- [**SI4713**](https://s.click.aliexpress.com/e/_onSFnLx) (Basically a FM Transmitter)
- [**RFID/NFC PN532**](https://s.click.aliexpress.com/e/_oF72TlJ) (NFC Reader and Writer)
- [**RFID RC522**](https://s.click.aliexpress.com/e/_oB6vkSV) (SPI Reader and Writer)
- [**IR Transmitter/Receiver**](https://s.click.aliexpress.com/e/_oF00QaH) (More IR Range 10m)

## ➕ Additional Stuff

- [PCB Prototype](https://s.click.aliexpress.com/e/_olxA3S1)
- [Wires](https://s.click.aliexpress.com/e/_okHoOCh) (Female & Male Wires to connect Modules)
- [Needel Headers 1](https://s.click.aliexpress.com/e/_oEuUgrr)
- [Needel Headers 2](https://s.click.aliexpress.com/e/_olYspJ3)
- [SD Cards](https://s.click.aliexpress.com/e/_olEWviv) (Up to 256GB SD cards)


BlE, IR, RF, RFID, FM & Others coming soon!

**Bruce [Discord](https://discord.com/invite/WJ9XF9czVT)**










