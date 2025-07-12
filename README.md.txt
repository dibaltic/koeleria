# Koeleria
![WithWithoutDisplay](https://github.com/user-attachments/assets/fc0226d4-2839-4319-b71d-65a62185d94b)
![CaseAngled](https://github.com/user-attachments/assets/2737f720-7f22-4d7e-846a-cafac888e786)



## Features
- 30 keys with splay and column stagger
- nice!nano and nice!view
- Hotswap sockets, no direct solder option for switches
- Low profile Choc V1 switches with Choc spacing
- Exclusively wireless using [ZMK firmware](https://zmk.dev/)
- Cases are designed to be low profile with recessed adhesive feet
- A variety of cases can be found in the [3d_Print](https://github.com/dibaltic/koeleria/tree/main/3d_Print) folder. Including enclosed split, minimal split, unibody, storage case, and variety of tenting angles.

![SideProfile](https://github.com/user-attachments/assets/c72b2ca9-5cad-4500-b71c-48445e6634a1)


### Design

- My first ergo keyboard was an MX Sweep, and then shortly after a wireless Choc Sweep. I wanted my thumbs less tucked, to use my pinky less, and reach less with my index finger. I also wanted to have the option for a display. 

- The column stagger is similar to that of the [Sweep](https://github.com/davidphilipbarr/Sweep). The index keys are situated in a spot that is easy to reach both keys from the home row, and the splay is similar to the splay on the [Luna Keyboard](https://github.com/mindhatch/keyboards).

- My goal was to make keyboard to be low profile as I could. The case adds 1mm in height to the PCB. There is a total of 1.5mm added height with the specified silicone feet installed on the case.

- In the majority of the photos I am using [KLP Lamé](https://github.com/braindefender/KLP-Lame-Keycaps) keycaps with LSDA profile thumbs, but the case was designed around clearing normal keycaps as you can see in the photos of the unibody case with a full set LSDA keycaps installed.

- All the files for the keyboard and cases have been shared if you would like to modify anything to better suit your needs.

![MinimalAndEnclosed](https://github.com/user-attachments/assets/4f8c4bd8-2b66-4404-9fb4-7520e709768f)



# B.O.M 

#### Required

- 1x PCB pair
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
  
![UnibodyAndSplit](https://github.com/user-attachments/assets/fa1e2079-ffe7-4855-9f5c-019f3f3ad02b)

![StorageCase](https://github.com/user-attachments/assets/c2ef729e-6549-4894-925c-ff22f33dfb73)

![StorageCase3](https://github.com/user-attachments/assets/47e49586-ff1b-4ce4-8ce8-bce28560d9a1)

![MinimalSide](https://github.com/user-attachments/assets/4a96faf1-6235-441d-81c7-1a1eabe0d4eb)

# Inspirations and Credit
I took inspiration from the [Urchin](https://github.com/duckyb/urchin), [Sweep](https://github.com/davidphilipbarr/Sweep), and [Luna](https://github.com/mindhatch/keyboards). I used footprints from the Urchin, and used [ergogen](https://ergogen.ceoloide.com/) to get the physical key placement configured before designing the rest in Kicad and Freecad.