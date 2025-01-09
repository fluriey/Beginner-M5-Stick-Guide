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

To see more features or more details of the Features check out the Github of Bruce or Nemo (Detailed showcase coming soon!). If you want to know how to install the Firmware check out **Installation Guide**

## ⚡Wiring Diagrams

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


## 🔧 Official M5stack Attachments

- [**M5Stack FM Receiver**](https://www.aliexpress.us/item/3256803111064973.html?aff_fcid=b9d7840bfc0c450897368406859f5cdc-1734271698334-04109-_DdvzW8h&tt=CPS_NORMAL&aff_fsk=_DdvzW8h&aff_platform=shareComponent-detail&sk=_DdvzW8h&aff_trace_key=b9d7840bfc0c450897368406859f5cdc-1734271698334-04109-_DdvzW8h&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt) (Receive Different Signals, i.e. Receive Car key Signal **Warning! Educational Purpose Only!**)
- [**M5Stack FM Transmitter**](https://www.aliexpress.us/item/3256803111130499.html?aff_fcid=6d604ea874f84735b5fe73f6e36d8d01-1734271704602-02749-_DlhHGw5&tt=CPS_NORMAL&aff_fsk=_DlhHGw5&aff_platform=shareComponent-detail&sk=_DlhHGw5&aff_trace_key=6d604ea874f84735b5fe73f6e36d8d01-1734271704602-02749-_DlhHGw5&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt) (Transmitt Diffrent Signals i.e. Use the received Car key SIgnal **Warning! Educational Purpose Only!**)
- [**M5Stack IR Module**](https://www.aliexpress.us/item/3256806277070733.html?aff_fcid=2ee3c6959d494fbb93e9abc8c99fb79e-1734271705699-05822-_DFhWFNB&tt=CPS_NORMAL&aff_fsk=_DFhWFNB&aff_platform=shareComponent-detail&sk=_DFhWFNB&aff_trace_key=2ee3c6959d494fbb93e9abc8c99fb79e-1734271705699-05822-_DFhWFNB&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt) (Get more IR range i.e. Turn off TVs from a longe range)
- [**M5Stack RFID2**](https://www.aliexpress.us/item/3256803294601566.html?aff_fcid=e127d93cab124003939204a0b992be18-1734271706832-05764-_DEGMyCv&tt=CPS_NORMAL&aff_fsk=_DEGMyCv&aff_platform=shareComponent-detail&sk=_DEGMyCv&aff_trace_key=e127d93cab124003939204a0b992be18-1734271706832-05764-_DEGMyCv&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=glo2usa4itemAdapt) (Read/Clone/Copy tags i.e. Clone House Key tag **Warning! Educational Purpose Only!**)

## 🔧 Unofficial M5stack Attachments

- [**CC1101**](https://de.aliexpress.com/item/1005004333776584.html?businessType=ProductDetail&srcSns=sns_Copy&spreadType=socialShare&bizType=ProductDetail&social_params=60906761349&aff_fcid=c972a1490b2b4101ae7fffbfd0fe7897-1734271394437-05997-_EzBvF1e&tt=CPS_NORMAL&aff_fsk=_EzBvF1e&aff_platform=shareComponent-detail&sk=_EzBvF1e&aff_trace_key=c972a1490b2b4101ae7fffbfd0fe7897-1734271394437-05997-_EzBvF1e&shareId=60906761349&businessType=ProductDetail&platform=AE&terminal_id=ec4331db37424feaa5a63d422bee1666&gatewayAdapt=glo2deu) (External Antenna for more range and more powerfull jamming **Warning! Educational Purpose Only!**)
- [**NRF24L01**](https://de.aliexpress.com/item/1005006179466246.html?businessType=ProductDetail&srcSns=sns_Copy&spreadType=socialShare&bizType=ProductDetail&social_params=60906809295&aff_fcid=9b35110bf51a4f8e9a2b12b9ab9df5cf-1734271398149-04082-_EIjrOjA&tt=CPS_NORMAL&aff_fsk=_EIjrOjA&aff_platform=shareComponent-detail&sk=_EIjrOjA&aff_trace_key=9b35110bf51a4f8e9a2b12b9ab9df5cf-1734271398149-04082-_EIjrOjA&shareId=60906809295&businessType=ProductDetail&platform=AE&terminal_id=ec4331db37424feaa5a63d422bee1666&gatewayAdapt=glo2deu) (External Antenna for more range and more powerfull jamming **Warning! Educational Purpose Only!**)
- [**CH9329**](https://de.aliexpress.com/item/1005007511100935.html?businessType=ProductDetail&srcSns=sns_Copy&spreadType=socialShare&bizType=ProductDetail&social_params=60901460840&aff_fcid=62e5a8673bb347aeb4160e058404ccda-1734271399162-04234-_EvYgKtS&tt=CPS_NORMAL&aff_fsk=_EvYgKtS&aff_platform=shareComponent-detail&sk=_EvYgKtS&aff_trace_key=62e5a8673bb347aeb4160e058404ccda-1734271399162-04234-_EvYgKtS&shareId=60901460840&businessType=ProductDetail&platform=AE&terminal_id=ec4331db37424feaa5a63d422bee1666&gatewayAdapt=glo2deu) (USB Port)
- [**SD Reader**](https://de.aliexpress.com/item/1005006247350757.html?aff_fcid=7b0c51d1535043b1843dd3a4409325bb-1734271400283-06554-_DBKndJx&tt=CPS_NORMAL&aff_fsk=_DBKndJx&aff_platform=shareComponent-detail&sk=_DBKndJx&aff_trace_key=7b0c51d1535043b1843dd3a4409325bb-1734271400283-06554-_DBKndJx&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y) (SD Reader For more storage. Default one only has 8MB)
- [**SI4713**](https://www.aliexpress.us/item/3256805591067924.html?businessType=ProductDetail&srcSns=sns_Copy&spreadType=socialShare&bizType=ProductDetail&social_params=60904598631&aff_fcid=01c9dc6d50184543bbff6edc5e357202-1734271402053-01108-_EuYAdMy&tt=CPS_NORMAL&aff_fsk=_EuYAdMy&aff_platform=shareComponent-detail&sk=_EuYAdMy&aff_trace_key=01c9dc6d50184543bbff6edc5e357202-1734271402053-01108-_EuYAdMy&shareId=60904598631&businessType=ProductDetail&platform=AE&terminal_id=ec4331db37424feaa5a63d422bee1666&gatewayAdapt=glo2usa) (Basically a FM Transmitter)

## ➕ Additional Stuff

- [PCB Prototype](https://www.aliexpress.us/item/3256806052763508.html?spm=a2g0o.order_list.order_list_main.11.43ca5e5b1u4qqL&aff_fcid=04079b811578485ab8b3c19a9c1d4083-1734274480098-00809-_DFCCeE5&tt=CPS_NORMAL&aff_fsk=_DFCCeE5&aff_platform=portals-tool&sk=_DFCCeE5&aff_trace_key=04079b811578485ab8b3c19a9c1d4083-1734274480098-00809-_DFCCeE5&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=fra2usa4itemAdapt)
- [Wires](https://www.aliexpress.us/item/3256803454873245.html?businessType=ProductDetail&srcSns=sns_Copy&spreadType=socialShare&bizType=ProductDetail&social_params=60906813246&aff_fcid=ec5e4fbca32548d881858d95eac50b1b-1734274481207-03197-_Exj1feg&tt=CPS_NORMAL&aff_fsk=_Exj1feg&aff_platform=shareComponent-detail&sk=_Exj1feg&aff_trace_key=ec5e4fbca32548d881858d95eac50b1b-1734274481207-03197-_Exj1feg&shareId=60906813246&businessType=ProductDetail&platform=AE&terminal_id=ec4331db37424feaa5a63d422bee1666&gatewayAdapt=glo2usa4itemAdapt) (Female & Male Wires to connect Modules)
- [Needel Headers](https://www.aliexpress.us/item/3256806596801005.html?spm=a2g0o.order_list.order_list_main.17.43ca5e5b1u4qqL&aff_fcid=2b6b8f93342b4dde89421c5041e12dd7-1734274482745-05649-_DCfiTkV&tt=CPS_NORMAL&aff_fsk=_DCfiTkV&aff_platform=portals-tool&sk=_DCfiTkV&aff_trace_key=2b6b8f93342b4dde89421c5041e12dd7-1734274482745-05649-_DCfiTkV&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=fra2usa4itemAdapt)
- [SD Cards](https://www.aliexpress.us/item/3256805307825732.html?spm=a2g0o.order_list.order_list_main.28.43ca5e5b1u4qqL&aff_fcid=4c4c85ea16ff4d9381368135a4cf5808-1734274484158-07310-_DnS6Hkl&tt=CPS_NORMAL&aff_fsk=_DnS6Hkl&aff_platform=portals-tool&sk=_DnS6Hkl&aff_trace_key=4c4c85ea16ff4d9381368135a4cf5808-1734274484158-07310-_DnS6Hkl&terminal_id=ec4331db37424feaa5a63d422bee1666&afSmartRedirect=y&gatewayAdapt=fra2usa4itemAdapt) (Up to 256GB SD cards)

## 💡 Tutorials

Coming soon!

**Bruce [Discord](https://discord.com/invite/WJ9XF9czVT)**

**Inspired by [@popp.n](www.tiktok.com/@popp.n_). His Linktree is [here](https://linktr.ee/popp.n).**










