
### **Project starbie for Half life week 2**


<img width="425" height="433" alt="Screenshot 2026-10-21 172642" src="https://github.com/user-attachments/assets/788126db-018d-4f61-b13d-37e1a42bd891" />

This is a Starbie, a small motion controlled robot pet like a Tamogotchi. It uses a Seeed XIAO ESP32 C3 microcontroller and a small display(OLED) to show the pet with different stats & expressions. The buttons let the user interact with the pet, while the MPU6050 sensor changes its animation based on physical movement. I designed the circuit and PCB as a way to get my footing in learning electronics, KICAD, and some basic programming.

-----

### **FEATURES**

- XIAO ESP32 C3 for the microconcroller 
- A 0.96" OLED display
- An MPU6050 for dececting movement
- MX switches(already own them)
- 10K resistors.
- Custom PCB

-----
### **CAD MODEL**

A simple, custom PCB with an octagonal shape, logo of Half Life, and my Innitials. The Cad model only shows some of the 3D models for reasons unknown to me. But I believe it shouldn't have any problems with the actual physical project.

<img width="490" height="482" alt="Screenshot 2026-10-21 172713" src="https://github.com/user-attachments/assets/bf11313b-6d73-4d14-9d3c-804f38e38623" />

-------
### **Controls**

- Button 1: Menu/select
- Button 2: Stats of pet
- Tilt PCB: MOve menu selector

-------

### **BOM TABLE**
 ## Bill of Materials (BOM)

| Component | Quantity |Price| Purpose |link|
|---|---:|---|---|---|
|XIAO ESP32-C3 | 1 |$4.99| Main microcontroller that runs Starbie |https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html|
| SSD1306 0.96" OLED display | 1 |	$4.76| Displays the pet, menu, and stats |https://www.ebay.com/itm/800587691455?var=657520301390|
| MPU6050 accelerometer and gyroscope | 1 |$0.99| Detects tilting and shaking |https://www.ebay.com/itm/398357041293|
| DHT11 temperature and humidity sensor | 1 |$0.99| Measures ambient temperature and humidity |https://www.ebay.com/itm/158232161042|
| Momentary push buttons | 2 |$0(own them already)| Controls the menu and stats screen |N/A|
| Custom PCB | 1 |$5.20| Holds and connects the electronic components |https://cart.jlcpcb.com/quote?stencilLayer=2&stencilWidth=100&stencilLength=100&stencilCounts=5&plateType=1&spm=Jlcpcb.Homepage.1010 (Need to upload the gerber files & choose Global Standard Direct Line as shipping option)|
|10K resistor| 1 |$0(own them already)|Specific voltage|N/A|

