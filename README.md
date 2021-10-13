# cessna-radio-panel

Radio panel for COM or NAV for a Cessna 172 to use with MSFS2020, XPlane and Prepar3D using the software MobiFlight.

# Repo contents

## Cessna-radio-stack-pcb
This folder contents the PCB design for the radio module. The design is the same for COM and NAV, it only changes on the frame. This PCB needs to be connected to the Arduino Mega using the Mega-pro-mini module designed in this repository. There is a GERBER folder to send the design to JLCPCB (www.jlcpcb.com) or you can ask me to buy it finished (augustosamuelhdezmartin@gmail.com).

![Render PCB radio](https://github.com/AugustoS97/cessna172-radio-panel/blob/main/Cesna-Radio-Stack-pcb/3D%20Model/Cesna_Radio_Stack_lat.png)

To make this PCB you need this components (you can find the list in cessna172-radio-panel/Cesna-Radio-Stack-pcb/Docs/Cesna_Radio_Stack.csv):
- 4x Display 7 segments 0.36" 1 bit Common Cathode red (https://www.aliexpress.com/item/1005001852229452.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 2x Display 7 segments 0.36" 4 bit Common Cathode red AS3161 (https://www.aliexpress.com/item/32673704841.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1).
- 2x Rottary Encoder EC11 (https://es.aliexpress.com/item/1005002931777351.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1) 
- 1x Button 8x8 (https://www.aliexpress.com/item/32467872702.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 2x MAX7219 DIP24 (https://www.aliexpress.com/item/32874536319.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 1x PinHeader 2x36 pins (https://www.aliexpress.com/item/33004522737.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 8x 1k Resistor THT
- 7x 10nF Ceramic Capacitor THT
- 2x 150nF Ceramic Capacitor THT
- 2x 22uF Electrolitic Capcitor 16V

## Mega2560-pro-mini-radio
This folder contents the PCB design for the microcontroller. The design connects 2 NAV modules, 2 COM modules or 1 NAv and 1 COM modules. There is a GERBER folder to send the design to JLCPCB (www.jlcpcb.com) or you can ask me to buy it finished (augustosamuelhdezmartin@gmail.com).

![Render PCB radio](https://github.com/AugustoS97/cessna172-radio-panel/blob/main/Mega2560-pro-mini-radio/3dModels/Mega2560-pro-mini-radio.png)

To make this PCB you need this components (you can find the list in cessna172-radio-panel/Mega2560-pro-mini-radio/docs/Mega2560-pro-mini-radio.csv):
- 1x Mega 2650 Pro mini (https://www.aliexpress.com/item/1005001798708448.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 3x PinHeader male 2x36 pins 2.54 mm (https://www.aliexpress.com/item/32993182990.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 3x PinHeader Female 1x40 pins 2.54mm (https://www.aliexpress.com/item/32993182990.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1)
- 2x IDC 2x20 pins 2.54mm Cable (https://www.aliexpress.com/item/33029492417.html?spm=a2g0o.cart.0.0.44e13c00yVY6Ir&mp=1): One for each module

## Frame Design
This folders contents the FreeCAD design for the exterior panel. It is based on the c172-xpndr design (https://github.com/kkr0kk/c172-xpndr), so it must be use with this Transponder and AutoPilot modules.

![FreeCAD design](https://github.com/AugustoS97/cessna172-radio-panel/blob/main/Frame-Design/render_COM.png)

Also the 3D model are available in STL folder, so you can print this panels with 2 colors or you can also contact me to buy a finished panel (augustosamuelhdezmartin@gmail.com).

## Assembly 
Finallly, the COM panel is assembly as shown in the next picture.
