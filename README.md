# AMD-Mobile-overclocking-capabilities
A repo documenting what each AMD Mobile cpu gen is allowed to do in the area of overclocking.
Simply making information more accessible.

##  Why does this exist?
AMD Mobile cpus are tricky. AMD does not directly tell the end consumer which chips are fused off for what features. Through this github I aim to help people easily figure out what their CPU is technically capable of doing

## What is the source of this information?
The source is a serious amount of BIOS modding and testing a lot of machines.
A picture will be provided as proof if applicable.


## The table

| CPU Generation | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 1000 - mobile doesnt exist | N/A | N/A | N/A | N/A | N/A | N/A |
| Ryzen 2000  | Yes | No | Yes | Yes? | No | No |
| Ryzen 3000 | Yes | No | Yes | Yes | No | No | 
| Ryzen 4000 | Yes | No | Yes | Yes | No| No |
| Ryzen 5000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unkown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 6000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unkown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 7000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unkown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 8000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unkown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 9000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unkown | Only Ryzen 9, HX, and U | Yes | Yes, with newer AGESA |
| Ryzen 10 | No | No | Only Ryzen 9, HX, and U | No | Yes | No |
| Ryzen 100 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unkown | Only Ryzen 9, HX, and U | Yes | No|
| Ryzen 200 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Only Ryzen 9, HX, and U | Yes | No|
| Ryzen 300 (STXH not included) | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Only Ryzen 9, HX, and U | Yes | No|
| Ryzen 400 | Unkown | Unkown | Unkown | Yes | No|



## Proof

# AOD proof
Below is a image showcasing 4 different bios files, each from a different generation ranging from 2000 to 5000. The bios files showcase that there is no AOD_SETUP string found in any of the BIOS files until ryzen 5000
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a7d02139-1c38-40d4-95d8-a2bfc03685db" />


# 9955HX/3D capability to increase tREFI with newer AGESA.
Folowwing picture shows a 9955HX3D system with higher tREFI than JEDEC. Picture can be found in Legion Series Discord Server: https://discord.com/channels/761178912230473768/958336296621867038/1466577982289219697
<img width="2548" height="1599" alt="image" src="https://github.com/user-attachments/assets/8b3841de-265f-4a98-837a-6d4deb614a9a" />


