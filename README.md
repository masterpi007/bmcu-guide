# bmcu-guide
This is everything I found with bmcu and my setup instructions

## BMCU

Link to the original page: https://oshwhub.com/bamboo-shoot-xmcu-pcb-team/bmcu

## PCB Components

## Mechanical Parts

| parts |  image | quantity | url|
|------|---|----|-----|
| D2x10mm shaft|![](./imgs/20250113_231050.jpg)| 16| 
| D5x22mm shaft|![](./imgs/20250113_231548.jpg)| 4| 
| D2x20mm shaft| ![](./imgs/20250113_230614.jpg) | 12| 
| 20082b gear|![](./imgs/Screenshot%202025-01-13%20233142.png)| 8| 
| 182A gear|![](./imgs/61sC1fKFzdL._AC_UF1000,1000_QL80_.jpg)| 8| 
| W6X82A gear|![](./imgs/Screenshot%202025-01-13%20232800.png)| 4| 
| 242A gear| ![](./imgs/20250113_232424.jpg)| 4| 
| FF-130SH DC motor|![](./imgs/Screenshot%202025-01-13%20233300.png)| 4| 
| 62B bushing|![](./imgs/Screenshot%202025-01-13%20233743.png)| 28| 
| PC4-M6  connector|![](./imgs/Screenshot%202025-01-13%20234100.png)| 4 (suggest 8)| 
| 0.5x6x10mm spring| ![](./imgs/20250113_225748.jpg) | 4 | 
| 0.6x4x10mm spring| ![](./imgs/20250113_224538.jpg) | 4 | 
| m2x8  screw heads|![](./imgs/Screenshot%202025-01-13%20233956.png)| 60 | 
| MBG gear set|![](./imgs/20250107_180137.jpg)| 4 | 
| MR85ZZ bearing | ![](./imgs/mr85zz-kugleleje-bmg-bearing.jpg)| 8 | 
|wires|![](./imgs/20250113_234314.jpg)|8|
|round magnet D6x2.5 (optional)|![](./imgs/20250113_234629.jpg)| 4|
|AMS cable header (dont know exactly what brand)|| 2|
|dupont female header (small)|| 8|


You will also need lubricating oil/grease, a screwdriver and soldering tools

### Setup

After printed all the parts

1. insert the D2x10 shafts into 182A gears, and D2x20 shaft into 242A gear like this

    ![](./imgs/20250113_235121.jpg)
2.  Take 2 triangle parts and insert the gears. pay attention to the direction of 242A gear (red box)

    ![](./imgs/20250114_000007.jpg)
3.  Assembling 2 part and secure with the m2 screw. You should also lubricate the gears with oil at this step

    ![](./imgs/20250114_000655.jpg)
4. Screw the pneumatic fitting to this part, and add 0.5x6x10 spring + 62B bushing at the bottom

    ![](./imgs/20250114_000901.jpg)
5. insert that block into the bottom case. You  should also add some oil into the marked regions. After everything is in place, push the component downward to make sure it is sliding smoothly.

    ![compressing the spring](./imgs/20250114_001335.jpg)
    ![](./imgs/20250114_001448.jpg)
6. take a BMG gear (the one with side screw-hole), D5x22 shaft and 2 MR85zz ball bearings and assemble like in this image.  The thick shaft at one end needs to be flush with the bearing.

    ![](./imgs/20250107_181452.jpg)
    ![](./imgs/20250114_002351.jpg)

7. insert the 62B bushing into the bottom case like this

    ![](./imgs/20250114_003110.jpg)
8. Insert the above components + 2 long shafts into the bottom case like these images. Pay attention to the direction of BMG gear and the triangle part

    ![](./imgs/20250114_003439.jpg)
    ![](./imgs/20250114_003452.jpg)

9. Add 2 20082b gears to the long shafts

    ![](./imgs/20250114_003848.jpg)
10. insert a bushing to this part and insert it into the bottom case:

    ![](./imgs/20250114_004034.jpg)
    ![](./imgs/20250114_004124.jpg)
11. insert W6X82A gear to the motor, and solder the wire from the motor to the board (V go to the red spot on motor)

    ![](./imgs/20250114_004423.jpg)
12. Insert the motor to the bottom case, (the red/ positive wire face up)

    ![](./imgs/20250114_004742.jpg)
    ![](./imgs/20250114_004818.jpg)

13. Take the top case and assemble to the bottom case (align the wire to the marked region). Add the magnet to the BMG gear

    ![](./imgs/20250114_005230.jpg)

14. place the board on the top case, and tighten with screws. secure 2 parts with 5 screws.

    ![](./imgs/20250114_005814.jpg)
    ![](./imgs/20250114_005913.jpg)
15. Assemble the BMG gear (D3x20 shaft included in BMG gear set), and insert them to this printed part (pay attention to the direction)

    ![](./imgs/20250114_010601.jpg)
    ![](./imgs/20250114_010823.jpg)

16. insert the 62B bushing to the top case and add the thin spring like this. Then insert the above part and fixed by 2 D2x10 shafts

    ![](./imgs/20250114_011141.jpg)
    ![](./imgs/20250114_011325.jpg)

17. Insert the top cover

    ![](./imgs/20250114_011802.jpg)

18. [note on making AMS cable] 1m is enough if you want to place the kit on top of the printer, or by side. the pinouts on both ends must be in the same order, shown in this image:

    ![](./imgs/20250114_012545.jpg)

### Firmware

The board is already flashed with firmware so you wont need to flash the binary into the board. However you can still load new firmware to the board with USB-TTL in case new firmware is available
