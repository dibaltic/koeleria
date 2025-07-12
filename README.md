# Koeleria
![WithWithoutDisplay](https://github.com/user-attachments/assets/5347cd2f-4a27-462e-baf8-eca12eb88b1e)
![CaseAngled](https://github.com/user-attachments/assets/0bfdc4cd-698e-405d-8b22-49ff9c37bad5)

## Features
- 30 keys with splay and column stagger
- nice!nano and nice!view
- Hotswap sockets, no direct solder option for switches
- Low profile Choc V1 switches with Choc spacing
- Exclusively wireless using [ZMK firmware](https://zmk.dev/)
- Cases are designed to be low profile with recessed adhesive feet
- A variety of cases can be found in the [3d_Print](https://github.com/dibaltic/koeleria/tree/main/3d_Print) folder. Including enclosed split, minimal split, unibody, storage case, and variety of tenting angles.

![SideProfile](https://github.com/user-attachments/assets/614cac45-85cc-46bd-b43b-31ca0139accf)

### Design

- My first ergo keyboard was an MX Sweep, and then shortly after a wireless Choc Sweep. I wanted my thumbs less tucked, to use my pinky less, and reach less with my index finger. I also wanted to have the option for a display. 

- The column stagger is similar to that of the [Sweep](https://github.com/davidphilipbarr/Sweep). The index keys are situated in a spot that is easy to reach both keys from the home row, and the splay is similar to the splay on the [Luna Keyboard](https://github.com/mindhatch/keyboards).

- My goal was to make keyboard to be low profile as I could. The case adds 1mm in height to the PCB. There is a total of 1.5mm added height with the specified silicone feet installed on the case.

- In the majority of the photos I am using [KLP Lamé](https://github.com/braindefender/KLP-Lame-Keycaps) keycaps with LSDA profile thumbs, but the case was designed around clearing normal keycaps as you can see in the photos of the unibody case with a full set LSDA keycaps installed.

- All the files for the keyboard and cases have been shared if you would like to modify anything to better suit your needs.

![MinimalAndEnclosed](https://github.com/user-attachments/assets/760fe2ae-94a4-4ea8-9469-4ce1ab3aa450)

# B.O.M 

#### Required

- 1x PCB pair (production files can be found [here](https://github.com/dibaltic/koeleria/tree/main/PCB/Gerbers))
- 30x Kailh Choc V1 switches
- 30x Key caps
- 30x Kailh Choc hotswap sockets (no direct switch soldering support)
- 30x SMD diodes 1n4148w (SOD-123)
- 2x nice!nano
- 2x battery (301230)
- 2x female headers (mcu sockets)
- 48x header pins (mill-max or other solution)

#### Optional

- 2× nice!view
- 2× Reset switch (B3U-1000P(M))
- 2× Power switch (MSK 12C02)
- 10× adhesive silicone feet 8mmx2.5mm
> Note: If you are using a case from [3d_Print folder](https://github.com/dibaltic/koeleria/tree/main/3d_Print) you will need M2 hardware, heatserts, and additional non-slip feet. More information can be found in the corresponding readme.

# Firmware

For standard setup

-https://github.com/dibaltic/zmk_koeleria

For dongle setup. This saves on battery life, but requires an additional MCU. For more information on dongles in ZMK please refer to the [ZMK docs](https://zmk.dev/docs/development/hardware-integration/dongle)

-https://github.com/dibaltic/zmk_koeleria_dongle

# Pictures
  
![UnibodyAndSplit](https://github.com/user-attachments/assets/e3c732be-fe4b-47aa-b1e0-4b68c8897239)

![StorageCase](https://github.com/user-attachments/assets/79d888dd-06cd-4064-9e58-624c3f688894)

![StorageCase3](https://github.com/user-attachments/assets/59144883-f654-477b-be90-566f0af0812a)

![MinimalSide](https://github.com/user-attachments/assets/b97098fb-1001-44b1-a889-45fa9a3ba729)

# Inspirations and Credit
I took inspiration from the [Urchin](https://github.com/duckyb/urchin), [Sweep](https://github.com/davidphilipbarr/Sweep), and [Luna](https://github.com/mindhatch/keyboards). I used footprints from the Urchin, and used [ergogen](https://ergogen.ceoloide.com/) to get the physical key placement configured before designing the rest in Kicad and Freecad.
