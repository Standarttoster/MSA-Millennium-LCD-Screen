# MSA-Millennium-LCD-Screen
Adds a RP2040-Touch-LCD-1.28 Screen to the Voice amplifier Port of an MSA Millennium Gasmask and the ability to play GIFs

### If you want to know how to set up the software for the screen go to my other [Repository](https://github.com/Standarttoster/RP2040-Touch-LCD-1.28-GIF-Player)

---

# Parts List

### 3D Prints
- [RP2040 LCD 1.28" MSA 3D Model](https://www.printables.com/de/model/538771-rp2040-lcd-128-msa)

### Screen
- [Waveshare RP2040 Touch LCD 1.28"](https://www.waveshare.com/rp2040-touch-lcd-1.28.htm)

### Screws
- M2x4 heat set inserts
- M2x20 screws

### Battery
- Any small 3.7V battery will work. I used [this 350mAh battery](https://eckstein-shop.de/LiPo-Battery-Lithium-Ion-Polymer-Battery-37V-350mAh-with-JST-PHR-2-Connector-LP552035-EN) (tight fit, so avoid larger sizes).

### Small Switch
- [Adafruit Breadboard-Friendly SPDT Slide Switch](https://eckstein-shop.de/AdafruitBreadboard-friendlySPDTSlideSwitchSchiebeschalterEN)

### Tools
- 3D Printer (or order from an online 3D printing service if needed)
- Soldering iron and soldering wire
- Specialized soldering tip for heat inserts (optional but helpful)
- Spare wire for connecting parts

# Instructions:

## 3D printing:

Download and print `Light v23.stl` and `vpu_threaded.3mf` marked below

<img src="https://github.com/user-attachments/assets/d1518134-8b0c-4663-b8be-b0923c18dbfb" width="400" />


IMPORTANT:
The original creator of the 3D model did not include the switch, because I didn't want it to run out of battery all the time to turn it off, I cut a small hole in the bottom of the 3D print so I can flip the switch that i glued inside

`My plan is to remake the 3D files when i have time so its a bit easier to work with`

---

## Preparing the prints:

### Assembly Step: Inserting Heat Set Inserts:

1. **Prepare the Parts**: Take the **M2x4 heat set inserts** and locate the **3D printed part** with the cutout for the USB-C port.

2. **Heat the Inserts**: Using a **hot soldering iron**, carefully place each insert over its corresponding hole on the 3D printed part.

3. **Set the Inserts in Place**: Gently press down with the soldering iron to melt the insert into the plastic until it’s flush with the surface. Ensure each insert is secure and aligned.

<img src="https://github.com/user-attachments/assets/d8947823-7643-4ec5-81c9-1db0262bc0d9" width="400" />

---

### Switch and batterie assembly

- In the **3D printed part with the threads**, cut a small hole to fit the **switch**.

- Place the switch into the hole so it’s accessible from the bottom, then glue it in place to hold it securely.

- **Connect the Wires**:
   - Attach the **red wire** to one terminal on the switch.
   - Connect another wire from the switch’s output terminal as shown in the reference picture.


<img src="https://github.com/user-attachments/assets/899489cf-2522-4e00-b52f-35ff77ba4919" width="400" />

---

- Take the **3D printed part with the hole** and route the cable through it as needed.

- To hold everything in place, push the screws through the designated holes in the part. This will keep it securely positioned.


<img src="https://github.com/user-attachments/assets/4cd733fa-c053-4127-ac90-b0d9fd04bc93" width="400" />

---

### Soldering and final assembly

#### Soldering:

1. Take the **screen/microcontroller** and look for the **battery connector** on its back.

2. **Solder the Wires**: 
   - Solder the **red wire** to the marked **+** pin on the back of battery connector.
   - Solder the **black wire** to the marked **-** pin on the back of battery connector.

`Refer to the image for proper wiring placement. (please don't judge me for my bad soldering job><)`

<img src="https://github.com/user-attachments/assets/f6302fa5-0ccc-4143-8352-860437cd3a3f" width="400" />

---

#### Final Assembly: Attaching the Screen

**Insert the Screen**:
   - Start by inserting the **top of the screen** first.
   - Gently push from the **opposite side** on the top to ensure it sits flush on the holding pins while simultaneously pushing the **backside** with the USB port in.

**Caution**: 
   - **IMPORTANT**: Do not force the screen into place, as this could damage the screen or the digitizer. (This is one of the reasons for wanting to remake the 3D printed components.)
   - **Tip**: Take your time during this step to avoid any potential damage.

<img src="https://github.com/user-attachments/assets/cc74d1bd-d655-4803-bba1-665dc32f9067" width="400" />


