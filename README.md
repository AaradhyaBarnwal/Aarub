# Aarub
A 4 downstream port USB-Hub with 2 USB-A ports and 2 USB-C ports for downstream. I made this while learning from the guide
This is my first hardware project . It is a usb hub . I struggled a lot but some figured everything out . I loved it . It helped me understand hardware and this way I tried someting new.The view-only [link](https://oshwlab.com/aaradhyeahh/project_izbmkmjg) (the project is in oshwlab's background review)
<img width="987" height="621" alt="image" src="https://github.com/user-attachments/assets/29f74519-9719-45e1-b25e-2646e491370d" />
and, this is the schematic <img width="2362" height="1672" alt="SCH_Schematic1_1-P1_2026-07-31" src="https://github.com/user-attachments/assets/34d9db74-e9db-4d7f-ae90-378badec01f3" />

and the pcb's front and back side
<img width="954" height="508" alt="image" src="https://github.com/user-attachments/assets/44866ce1-42c3-434d-8705-b1da10645980" />
<img width="890" height="436" alt="image" src="https://github.com/user-attachments/assets/15fb1569-dbd5-4957-9dc4-dc16f35edf19" />

and the bom-


Designator,No.,Quantity,Comment,Footprint,Value,Manufacturer Part,Manufacturer,Supplier Part,Supplier,Price
"C1,C2,C3,C4,C5,C6,C8,C10",1,8,1uf,C0603,1uf,,,,,$0.6160
"C7,C9,C11",2,3,100nF,C0603,100nF,,,,,$0.3615
"R1,R2,R3,R4,R5,R6",3,6,10K,R0603,10K,,,,,$0.0630
U1,4,1,SL2.1s,SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL,,SL2.1s,CoreChips(和芯润德),C2684433,LCSC,$1.2540
"USB1,USB2,USB5",5,3,TYPE-C 16PIN 2MD(073),USB-C-SMD_TYPE-C-16PIN-2MD-073,,TYPE-C 16PIN 2MD(073),SHOU HAN(首韩),C2765186,LCSC,$1.1776
"USB3,USB4",6,2,10.0 QHHTZB6.3,USB-A-TH_10.0QHHTZB6.3,,10.0 QHHTZB6.3,SHOU HAN(首韩),C668591,LCSC,$0.7944
,,,,,,,,,,
PCB manufacturing,,,,,,,,,JLCPCB,$2
PCBA,,,,,,,,,JLCPCB,$25.37
Shipping,,,,,,,,,,$23.07
,,,,,,,,,,
,,,,,,,,Total,,$50.44


# The below file is a interactive file of the bom
[InteractiveBOM_PCB1_2026-7-20.html](https://github.com/user-attachments/files/30184428/InteractiveBOM_PCB1_2026-7-20.html)


and the gerber
| File                                 | Purpose                 | Status  |
| ------------------------------------ | ----------------------- | ------- |
| ✅ `Gerber_TopLayer.GTL`              | Top copper              | Present |
| ✅ `Gerber_BottomLayer.GBL`           | Bottom copper           | Present |
| ✅ `Gerber_TopSilkscreenLayer.GTO`    | Top silkscreen          | Present |
| ✅ `Gerber_BottomSilkscreenLayer.GBO` | Bottom silkscreen       | Present |
| ✅ `Gerber_TopSolderMaskLayer.GTS`    | Top solder mask         | Present |
| ✅ `Gerber_BottomSolderMaskLayer.GBS` | Bottom solder mask      | Present |
| ✅ `Gerber_BoardOutlineLayer.GKO`     | Board outline           | Present |
| ✅ `Drill_PTH_Through.DRL`            | Through-hole drill file | Present |
| ✅ `Drill_NPTH_Through.DRL`           | Non-plated drill file   | Present |
| ✅ `Drill_PTH_Through_Via.DRL`        | Via drill file          | Present |


My lapse videos:
https://lapse.hackclub.com/timelapse/hZQMbSfOvOiV

# How to use 
Connect the downstream type-C port of the Aarub to the PC using USB cable and then you can use two type-A device and two type-C devices by connecting them to Aarub
https://lapse.hackclub.com/timelapse/cVap4bYE5v2C
https://lapse.hackclub.com/timelapse/O_YezGmjKD0o
