# Total time spent: 10-12 Hours
## 6/22/25: 
- Time Spent: **2 Hours**
- I downloaded symbols/footprints for the BOM from Snapmagic, and attempted to create a schematic and PCB on KiCAD. I was unable to create a PCB due to the footprint libraries not registering when importing from the downloaded files.  
![image](https://github.com/user-attachments/assets/33f7fd63-b9b3-4d5c-b49d-5c1559e301ce)
The underlined folders all contained symbols & footprint libraries for parts on the BOM. KiCAD could detect the symbol libaries but not the footprints for some reason.
![image](https://github.com/user-attachments/assets/03af8a10-50c8-42bf-8bb3-b56d3f61d377)

### BOM Symbols & Footprints from Snapmagic
_NT3H2111W0FHKH NFC chip:_
![image](https://github.com/user-attachments/assets/ca3de108-977e-4da9-a54c-62099b7eeb35)
_0603WAF470JT5E 47Ohm Resistor:_ 
![image](https://github.com/user-attachments/assets/ae283788-45ca-4fec-9e61-d9f05e827f20)
_CL10B224KA8NNNC 220nF Capacitor:_
![image](https://github.com/user-attachments/assets/9c069510-5c3c-4d7f-b940-2dfaad27c2d3)

- A symbol/footprint for the _17-21/BHC-XL2M2TY/4T_ Blue LED could not be found, so a generic LED symbol was used.
### Full BOM in KiCAD Schematic Editor
![image](https://github.com/user-attachments/assets/00cb3fed-5fda-4e4a-9de0-4a3661680fc1)

- After failing to pull the footprints from the downloaded files, I installed EasyEDA and went to bed.

## 6/23/25:
- Time Spent: **3-5 Hours**
- After downloading EasyEDA the night before, I wired together the parts in the schematic editor, then generated an initial PCB using the Autoroute tool. I grappled for a while with the one connection that the Autoroute failed to connect, with my initial apporach being to via the wire directly on top of the NFC chip (something that came back to haunt me later on). Also added a few decorations and main text to get a general idea of how to arrange the text & decals:

### That one cursed via
  ![Screenshot 2025-06-23 225215](https://github.com/user-attachments/assets/9c3e801c-bbbd-4096-b1cc-8e0cfaaf1597)

### PCB of the initial business card:
  ![Screenshot 2025-06-24 072110](https://github.com/user-attachments/assets/d915778a-6b78-4c81-b430-91839dc5ef28)

### 3D render of the initial business card:
  ![Screenshot 2025-06-23 232943](https://github.com/user-attachments/assets/24e8edee-c9c8-4916-9545-c7dd6119ad36)


### Prototype PCB design
![Screenshot 2025-06-24 005428](https://github.com/user-attachments/assets/d618678b-63d5-4d86-9a13-10adca4263f3)

## 6/24/25:
- Time Spent: **5-6 Hours**
- After spending most of this time frame going all out on all sorts of decals and customizations (including a change in font), I started up the DRC to be absolutely hit in the face by that one via:
![image](https://github.com/user-attachments/assets/23d11111-48dc-46a0-8d7c-69381154944e)
- I decided to re-run 







