# Aarub
A 4 downstream port USB-Hub with 2 USB-A ports and 2 USB-C ports for downstream. I made this while learning from the guide
This is my first hardware project . It is a usb hub . I struggled a lot but some figured everything out . I loved it . It helped me understand hardware and this way I tried someting new.The view-only [link](https://oshwlab.com/aaradhyeahh/project_izbmkmjg) (the project is in oshwlab's background review)
<img width="987" height="621" alt="image" src="https://github.com/user-attachments/assets/29f74519-9719-45e1-b25e-2646e491370d" />
and, this is the schematic <img width="2362" height="1672" alt="SCH_Schematic1_1-P1_2026-07-31" src="https://github.com/user-attachments/assets/34d9db74-e9db-4d7f-ae90-378badec01f3" />

and the pcb's front and back side
<img width="954" height="508" alt="image" src="https://github.com/user-attachments/assets/44866ce1-42c3-434d-8705-b1da10645980" />
<img width="890" height="436" alt="image" src="https://github.com/user-attachments/assets/15fb1569-dbd5-4957-9dc4-dc16f35edf19" />

and the bom-
| No. | Qty | Component                       | Designators                     | Footprint                      | Manufacturer / Supplier       |
| --: | --: | ------------------------------- | ------------------------------- | ------------------------------ | ----------------------------- |
|   1 |   8 | **1 µF Capacitor**              | C1, C2, C3, C4, C5, C6, C8, C10 | C0603                          | Not specified                 |
|   2 |   3 | **100 nF Capacitor**            | C7, C9, C11                     | C0603                          | Not specified                 |
|   3 |   6 | **10 kΩ Resistor**              | R1–R6                           | R0603                          | Not specified                 |
|   4 |   1 | **SL2.1s USB Hub IC**           | U1                              | SSOP-16                        | CoreChips (LCSC **C2684433**) |
|   5 |   3 | **USB Type-C 16-pin Connector** | USB1, USB2, USB5                | USB-C-SMD_TYPE-C-16PIN-2MD-073 | SHOU HAN (LCSC **C2765186**)  |
|   6 |   2 | **USB Type-A Connector**        | USB3, USB4                      | USB-A-TH_10.0QHHTZB6.3         | SHOU HAN (LCSC **C668591**)   |



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
