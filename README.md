# DISCLAIMER
This github repo is a community project, and is not backened by AMD. All of the information you see here was found by end consumers just like you! As much as we are confident in our findings, we can only be so sure as a unofficial source. Please take everything you find with a "grain of salt"

# Navigation
If you arent sure what this repo is about, please read the "introduction" part.
If you want to have quick answer as to what your cpu is capable of, refer to the https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#simplified-table


# Introduction
##  Why does this exist?
AMD Mobile cpus are tricky. AMD does not directly tell the end consumer which chips are fused off for what features. Through this github we aim to help people easily figure out what their CPU is technically capable of doing.


## What is the source of this information?
The source is just attempt and trial by a lot of people on the internet, we gather information from other peoples experiences and put them here for everyone to have a quick way of accessing this information
A picture will be provided as proof if applicable.




# Simplified Table
This table generilizes cpu's by their generation. Usually the capability of the cpu mostly depends on their generation, but there are exceptions. For better accuracy you can refer to the extended section.

| CPU Generation | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 1000 - Mobile doesnt exist | N/A | N/A | N/A | N/A | N/A | N/A |
| Ryzen 2000  | Yes | No | Yes | Yes? | No | No |
| Ryzen 3000 | Yes | No | Yes | Yes | No | No | 
| Ryzen 4000 | Yes | No | No | Yes | Depends on Device | No |
| Ryzen 5000 | Only Ryzen 9 | Only Ryzen 9 and HX | Unknown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 6000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unknown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 7000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unknown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 8000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | Unknown | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 9000 | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA |
| Ryzen 10 | No | No | Unknown | Unknown | Yes | No |
| Ryzen 100 | No | No | Unknown | Unknown | Yes | No |
| Ryzen 200 | Only Ryzen 9 | Only Ryzen 9 | Unknown | Yes | Yes | No |
| Ryzen AI 300 | Only Ryzen 9 and non-pro | Only Ryzen 9 and non-pro | Yes? | Yes | Yes | No |
| Ryzen AI Max 300 | Yes, non-pro | Yes, non-pro | Yes? | Yes | Yes | No |
| Ryzen AI 400 | Only Ryzen 9 and non-pro | Only Ryzen 9 and non-pro | Yes? | Yes |Yes| No |



# Proof

## AOD proof
Below is a image showcasing 4 different bios files, each from a different generation ranging from 2000 to 5000. The bios files showcase that there is no AOD_SETUP string found in any of the BIOS files until ryzen 5000
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a7d02139-1c38-40d4-95d8-a2bfc03685db" />
However, there is a exception. Ryzen 9 4000 devices technically have unlocked cpus, it appears with these unlocked higher end cpus the bios does have AOD_SETUP.


## 9955HX/3D capability to increase tREFI with newer AGESA.
Folowwing picture shows a 9955HX3D system with higher tREFI than JEDEC. Picture can be found in Legion Series Discord Server: https://discord.com/channels/761178912230473768/958336296621867038/1466577982289219697
<img width="2548" height="1599" alt="image" src="https://github.com/user-attachments/assets/8b3841de-265f-4a98-837a-6d4deb614a9a" />


# Detailed Table


## Ryzen 2000
### Raven Ridge (Zen/GCN5 based)
| CPU  | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 7 2800H|Yes|No|Yes|Yes|No|No|
|Ryzen 7 2700U|Yes|No|Yes|Yes|No|No|
|Ryzen 5 2600H|Yes|No|Yes|Yes|No|No|
|Ryzen 5 2500U|Yes|No|Yes|Yes|No|No|
|Ryzen 3 2300U|Yes|No|Yes|Yes|No|No|
|Ryzen 3 2200U|Yes|No|Yes|Yes|No|No|

## Ryzen 3000
### Dalí (Zen/GCN5 based)
| CPU  | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 3 3250U|Yes|No|Yes|Yes|No|No|
|Ryzen 3 3250C|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 3 3200U|Yes|No|Yes|Yes|No|No|

### Picasso (Zen+/GCN5 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 7 3780U|Yes|No|Yes|Yes|No|No
|Ryzen 7 3750H|Yes|No|Yes|Yes|No|No
|Ryzen 7 3700C|Yes?|No|Yes?|Yes?|No|No
|Ryzen 7 3700U|Yes|No|Yes|Yes|No|No
|Ryzen 5 3580U|Yes|No|Yes|Yes|No|No
|Ryzen 5 3550H|Yes|No|Yes|Yes|No|No
|Ryzen 5 3500C|Yes?|No|Yes?|Yes?|No|No
|Ryzen 5 3500U|Yes|No|Yes|Yes|No|No
|Ryzen 5 3450U|Yes|No|Yes|Yes|No|No
|Ryzen 3 3350U|Yes|No|Yes|Yes|No|No
|Ryzen 3 3300U|Yes|No|Yes|Yes|No|No

## Ryzen 4000
### Renoir (Zen 2/GCN5 based)

| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 9 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 9 4900HS|Yes|No|No|Yes|Depends on device|No
|Ryzen 7 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 7 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 7 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 7 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 7 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 7 4900H|Yes|No|No|Yes|Depends on device|No
|Ryzen 5 4600H|Yes|No|No|Yes|Depends on device|No
|Ryzen 5 4600HS|Yes|No|No|Yes|Depends on device|No
|Ryzen 5 4680H|Yes|No|No|Yes|Depends on device|No
|Ryzen 5 4600U|Yes|No|No|Yes|Depends on device|No
|Ryzen 5 4500U|Yes|No|No|Yes|Depends on device|No
|Ryzen 3 4300U|Yes|No|No|Yes|Depends on device|No

## Ryzen 5000
### Lucienne (Zen 2/GCN5 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
















