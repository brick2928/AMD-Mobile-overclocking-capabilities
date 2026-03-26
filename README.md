# DISCLAIMER
This github repo is a community project, and is not backened by AMD. All of the information you see here was found by end consumers just like you! As much as we are confident in our findings, we can only be so sure as a unofficial source. Please take everything you find with a "grain of salt"  

**This github repo assumes that your OEM has done no customization to your device and has just hidden all of the advanced options without touching them. Any of this information is bound to be false if your OEM decides to remove any of these options. This is very unlikely on laptops, though always possible. This more often happens on desktop motherboards with cheaper/weaker chipsets**

If you have any PRO variant CPUs Please contribute!

# Navigation
- If you aren't sure what this repo is about, please read the "introduction" part.
- If you want to have quick answer as to what your cpu is capable of, refer to the [Simplified Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#simplified-table), it will tell you what your cpu is capable of depending on your cpu generation.
- If you want to find the specific information for your CPU, search for your CPU via CTRL+F and write its full name. This will bring you to the Detailed Table where we state what each CPU is capable of instead of generilizing them according to their generation
- You can find some proof of our findings at [the proof section](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#proof)


# Introduction
##  Why does this exist? What even is this repo about?
AMD Mobile cpus are tricky. AMD does not directly tell the end consumer which chips are fused off from which features, only the way the cpu is "meant to be used". However some cpus can use features such as CO, even though AMD says the opposite. Through this github we aim to help people easily figure out what their CPU is technically capable of doing.


## What is your source?
Our source is just attempt and trial by a lot of people on the internet. We gather information from other peoples experiences and put them here for everyone to have a quick way of accessing this information.
A picture will be provided as proof if applicable.
Keep in mind: newer the generation of the cpu, the less confidence we have! Except in situations where we have direct proof - contributions matter to us.

We got help from [this wikipedia page](https://en.wikipedia.org/wiki/List_of_AMD_Ryzen_processors#Mobile_processors) to get the full list of Mobile AMD Ryzen processors. 

## Please contribute!!
Do you see the question marks? That is us indicating that we arent sure of our findings, or we are going off of assumptions.
If you have the hardware for which we have written "unknown" or a question mark, you can check what your CPU is capable of and share your findings via creating a Issue!
If you think anything is false or wrong, create an issue so we can talk it out.  

[Here](https://github.com/brick2928/Check-Ryzen-Mobile-Capability?tab=readme-ov-file#cpu-undervolting) is a quick guide telling you how to test what your device is capable of!

# Simplified Table
This table generilizes cpu's by their generation. Usually the capability of the cpu mostly depends on their generation, but there are exceptions. For better accuracy you can refer to the extended section.

| CPU Generation | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 2000  | Yes | No | Yes | Yes? | No | No |
| Ryzen 3000 | Yes | No | Yes | Yes | No | No | 
| Ryzen 4000 | Yes | No | Yes | Yes | Depends on Device | No |
| Ryzen 5000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#ryzen-5000) | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 6000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#ryzen-6000) | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 7000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#ryzen-7000) | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 8000 | Only Ryzen 9 and HX | Only Ryzen 9 and HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/bricked-branch?tab=readme-ov-file#ryzen-8000) | Only Ryzen 9, HX, and U | Yes | No |
| Ryzen 9000 | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA |
| Ryzen 10 | No | No | No | Unknown | Yes | No |
| Ryzen 100 | No | No | No | Unknown | Yes | No |
| Ryzen 200 | Only Ryzen 9 | Only Ryzen 9 | Unknown | Yes | Yes | No |
| Ryzen AI 300 | Only Ryzen 9 and non-pro | Only Ryzen 9 and non-pro | Yes? | Yes | Yes | No |
| Ryzen AI Max 300 | Yes, non-pro | Yes, non-pro | Yes? | Yes | Yes | No |
| Ryzen AI 400 | Only Ryzen 9 | Only Ryzen 9 | Yes? | Yes | Yes | No |



# Proof

## AOD proof
Below is a image showcasing 4 different bios files, each from a different generation ranging from 2000 to 5000. The bios files showcase that there is no AOD_SETUP string found in any of the BIOS files until ryzen 5000
<img width="1919" height="1050" alt="Screenshot_2" src="https://github.com/user-attachments/assets/820be143-4469-4591-9be5-36b2d6f7b13c" />
However, there is a exception. Ryzen 4000 series technically have unlocked cpus like the ryzen 9 4900h, it appears with these unlocked higher end cpus the bios does have AOD_SETUP.


# Detailed Table


## Ryzen 2000
### Raven Ridge (Zen/GCN5 based)
| CPU  | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 7 2800H|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 7 2700U|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 5 2600H|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 5 2500U|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 3 2300U|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 3 2200U|Yes?|No|Yes?|Yes?|No|No|

## Ryzen 3000
### Dalí (Zen/GCN5 based)
| CPU  | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 3 3250U|Yes|No|Yes|Yes, up to 3200MT/s|No|No|
|Ryzen 3 3250C|Yes?|No|Yes?|Yes?|No|No|
|Ryzen 3 3200U|Yes|No|Yes|Yes, up to 3200MT/s|No|No|

### Picasso (Zen+/GCN5 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 7 3780U|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 7 3750H|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 7 3700C|Yes?|No|Yes?|Yes?|No|No
|Ryzen 7 3700U|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 5 3580U|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 5 3550H|Yes|No|Yes|Yes|No|No
|Ryzen 5 3500C|Yes?|No|Yes?|Yes?|No|No
|Ryzen 5 3500U|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 5 3450U|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 3 3350U|Yes|No|Yes|Yes, up to 3200MT/s|No|No
|Ryzen 3 3300U|Yes|No|Yes|Yes, up to 3200MT/s|No|No


## Ryzen 4000
### Renoir (Zen 2/GCN5 based)

| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
|Ryzen 9 4900H|Yes|Yes|Yes|Yes|Depends on device|No
|Ryzen 9 4900HS|Yes|Yes|Yes|Yes|Depends on device|No
|Ryzen 7 4800H|Yes|No|Yes|Yes, up to 4400MT/s|Depends on device|No
|Ryzen 7 4800HS|Yes|No|Yes|Yes, up to 4400MT/s|Depends on device|No
|Ryzen 7 4980U|Yes|No|Yes|Yes|Depends on device|No
|Ryzen 7 4800U|Yes|No|Yes|Yes|Depends on device|No
|Ryzen 7 4700U|Yes|No|Yes|Yes|Depends on device|No
|Ryzen 5 4600H|Yes|No|Yes|Yes, up to 4400MT/s|Depends on device|No
|Ryzen 5 4600HS|Yes|No|Yes|Yes, up to 4400MT/s|Depends on device|No
|Ryzen 5 4680U|Yes|No|Yes|Yes, up to 3200MT/s|Depends on device|No
|Ryzen 5 4600U|Yes|No|Yes|Yes, up to 3200MT/s|Depends on device|No
|Ryzen 5 4500U|Yes|No|Yes|Yes, up to 3200MT/s|Depends on device|No
|Ryzen 3 4300U|Yes|No|Yes|Yes, up to 3200MT/s|Depends on device|No

## Ryzen 5000
### Lucienne (Zen 2/GCN5 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 7 5700U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 5 5500U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 3 5300U | No | No | No | Yes, up to 3200MT/s | Yes | No

### Cezanne and Barceló (Zen 3/GCN5 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 5980HX | Yes | Yes | Yes? | Yes | Yes | No
| Ryzen 9 5980HS | Yes | Yes | Yes? | Yes | Yes | No
| Ryzen 9 5900HX | Yes | Yes | Yes? | Yes | Yes | No
| Ryzen 9 5900HS | Yes | Yes | Yes? | Yes | Yes | No
| Ryzen 7 5800H | No | No | No | No | Yes | No
| Ryzen 7 5800HS | No | No | No | No? | Yes | No
| Ryzen 7 5825U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 7 5800U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 5 5600H | No | No | No | No | Yes | No
| Ryzen 5 5600HS | No | No | No | No? | Yes | No
| Ryzen 5 5625U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 5 5600U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 5 5560U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 5 5500H | No | No | No | No | Yes | No
| Ryzen 3 5425U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 3 5400U | No | No | No | Yes, up to 3200MT/s | Yes | No
| Ryzen 3 5125C | No | No | No | Yes? | Yes | No

## Ryzen 6000
### Rembrandt (Zen 3+/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 6980HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 6980HS | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 6900HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 6900HS | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 6800H | No | No | No | No? | Yes | No
| Ryzen 7 6800HS | No | No | No | No? | Yes | No
| Ryzen 7 6800U | No | No | No | Yes | Yes | No
| Ryzen 5 6600H | No | No | No | No? | Yes | No
| Ryzen 5 6600HS | No | No | No | No? | Yes | No
| Ryzen 5 6600U  | No | No | No | Yes | Yes | No

## Ryzen 7000
### Mendocino (7020 series, Zen 2/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 5 7520U | No | No | No | Yes | Yes | No
| Ryzen 5 7320U | No | No | No | Yes | Yes | No

### Barcelo-R (7030 series, Zen 3/GCN5 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 7 PRO 7730U | No | No | No | No | Yes | No
| Ryzen 7 7730U | No | No | No | Yes | Yes | No
| Ryzen 5 PRO 7530U | No | No | No | No | Yes | No
| Ryzen 5 7530U | No | No | No | Yes | Yes | No
| Ryzen 5 7430U | No | No | No | Yes | Yes | No
| Ryzen 3 PRO 7330U | No | No | No | No | Yes | No
| Ryzen 3 7330U | No | No | No | Yes | Yes | No
  
### Rembrandt-R (7035 series, Zen 3+/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 7 7735HS | No | No | No | No? | Yes | No
| Ryzen 7 7735H | No | No | No | No? | Yes | No
| Ryzen 7 7736U | No | No | No | Yes | Yes | No
| Ryzen 7 7735U | No | No | No | Yes | Yes | No
| Ryzen 7 7435HS | No | No | N/A | No? | Yes | No
| Ryzen 7 7435H | No | No | No | No? | Yes | No
| Ryzen 5 7535HS | No | No | No | No? | Yes | No
| Ryzen 5 7533HS | No | No | No | No? | Yes | No
| Ryzen 5 7535H | No | No | No | No? | Yes | No
| Ryzen 5 7535U | No | No | No | Yes | Yes | No
| Ryzen 5 7235HS | No | No | No | No? | Yes | No
| Ryzen 5 7235H | No | No | No | No? | Yes | No
| Ryzen 3 7335U | No | No | No | Yes | Yes | No

### Phoenix (7040 series, Zen 4/RDNA3/XDNA based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 PRO 7940HS | Unkown | Unkown | Unkown | Unkown | Yes | No
| Ryzen 9 7940HS | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 7940H | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 PRO 7840HS | No | No | No | No | Yes | No
| Ryzen 7 7840HS | No | No | No | No? | Yes | No
| Ryzen 7 7840H | No | No | No | No? | Yes | No
| Ryzen 7 PRO 7840U | No | No | No | No | Yes | No
| Ryzen 7 7840U | No | No | No | Yes | Yes | No
| Ryzen 7 7445HS | No | No | No | No? | Yes | No
| Ryzen 5 PRO 7640HS | No | No | No | No | Yes | No
| Ryzen 5 7640HS | No | No | No | No? | Yes | No
| Ryzen 5 7640H | No | No | No | No? | Yes | No
| Ryzen 5 PRO 7640U | No | No | No | No | Yes | No
| Ryzen 5 7640U | No | No | No | Yes | Yes | No
| Ryzen 5 PRO 7545U | No | No | No | No | Yes | No
| Ryzen 5 7545U | No | No | No | Yes | Yes | No
| Ryzen 5 PRO 7540U | No | No | No | No | Yes | No
| Ryzen 5 7540U | No | No | No | Yes | Yes | No
| Ryzen 3 7440U | No | No | No | Yes | Yes | No
## Notes

### Dragon Range (7045 series, Zen 4/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 7945HX3D | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 7945HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 7940HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 7845HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 7840HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 7745HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 5 7645HX | Yes | Yes | Yes | Yes | Yes | No
## Notes

## Ryzen 8000
### Hawk Point (8040 series, Zen 4/RDNA3/XDNA based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 8945HS | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 8845HS | No | No | No | No? | Yes | No
| Ryzen 7 8840HS | No | No | No | No? | Yes | No
| Ryzen 7 8840U | No | No | No | Yes | Yes | No
| Ryzen 7 8745HS | No | No | No | No? | Yes | No
| Ryzen 7 8745H | No | No | No | No? | Yes | No
| Ryzen 5 8645HS | No | No | No | No? | Yes | No
| Ryzen 5 8640HS | No | No | No | No? | Yes | No
| Ryzen 5 8640U | No | No | No | Yes | Yes | No
| Ryzen 5 8540U | No | No | No | Yes | Yes | No
| Ryzen 3 8440U | No | No | No | Yes | Yes | No

### Dragon Range (8045 series, Zen4/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 8945HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 9 8940HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 8840HX | Yes | Yes | Yes | Yes | Yes | No
| Ryzen 7 8745HX | Yes | Yes | Yes | Yes | Yes | No

## Ryzen 9000
### Fire Range (Zen 5/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 9955HX3D | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA
| Ryzen 9 9955HX | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA
| Ryzen 9 9950HX | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA
## Notes  
### 9955HX/3D capability to increase tREFI with newer AGESA.
Folowwing picture shows a 9955HX3D system with higher tREFI than JEDEC. Picture can be found in Legion Series Discord Server: https://discord.com/channels/761178912230473768/958336296621867038/1466577982289219697
<img width="2548" height="1599" alt="image" src="https://github.com/user-attachments/assets/8b3841de-265f-4a98-837a-6d4deb614a9a" />

## Ryzen 10
### Mendocino (10 series, Zen 2/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 5 40 | No | No | No | Unknown | Yes | No
| Ryzen 3 30 | No | No | No | Unknown | Yes | No

## Ryzen 100 
### Rembrandt-R (100 series, Zen 3+/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 7 170 | No | No | No | Unknown | Yes | No
| Ryzen 7 160 | No | No | No | Unknown | Yes | No
| Ryzen 5 150 | No | No | No | Unknown | Yes | No
| Ryzen 5 130 | No | No | No | Unknown | Yes | No
| Ryzen 3 110 | No | No | No | Unknown | Yes | No
## Notes


## Ryzen 200
### Hawk Point Refresh (200 series, Zen 4/RDNA3/XDNA based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 9 270 | Yes | Yes | Yes | Yes? | Yes | No
| Ryzen 7 260 | No | No | No | Unknown | Yes | No
| Ryzen 7 PRO 250 | No | No | No | Unknown | Yes | No
| Ryzen 7 250 | No | No | No | Unknown | Yes | No
| Ryzen 5 240 | No | No | No | Unknown | Yes | No
| Ryzen 5 PRO 230 | No | No | No | Unknown | Yes | No
| Ryzen 5 230 | No | No | No | Unknown | Yes | No
| Ryzen 5 PRO 220 | No | No | No | Unknown | Yes | No
| Ryzen 5 220 | No | No | No | Unknown | Yes | No
| Ryzen 3 PRO 210 | No | No | No | Unknown | Yes | No
| Ryzen 3 210 | No | No | No | Unknown | Yes | No
## Notes
- LPDDR5 lacks tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking

## Ryzen AI 300
### Strix Point and Krackan Point (Zen 5/RDNA3.5/XDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen AI 9 HX PRO 375 | Unknown | Unknown | Unknown | Unknown | Yes | No
| Ryzen AI 9 HX 375 | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 9 HX PRO 370 | Unknown | Unknown | Unknown | Unknown | Yes | No
| Ryzen AI 9 HX 370 | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 9 HX 365 | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 7 PRO 365 | No | No | No | Refer to Notes | Yes | No
| Ryzen AI 7 PRO 350 | No | No | No | Refer to Notes | Yes | No
| Ryzen AI 7 350 | No | No | No | Refer to Notes | Yes | No
| Ryzen AI 5 PRO 340 | No | No | No | Refer to Notes | Yes | No
| Ryzen AI 5 340 | No | No | No | Refer to Notes | Yes | No
| Ryzen AI 5 330 | No | No | No | Refer to Notes | Yes | No
## Notes
- LPDDR5 lacks tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking

### Strix Halo (Zen 5/RDNA3.5/XDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen AI MAX+ PRO 395 | Unknown | Unknown | Unknown | Yes | Yes | No
| Ryzen AI MAX+ 395 | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX+ 392 | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX PRO 390 | Unknown | Unknown | Unknown | Yes | Yes | No
| Ryzen AI MAX 390 | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX+ 388 | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX PRO 385 | Unknown | Unknown | Unknown | Yes | Yes | No
| Ryzen AI MAX 385 | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX PRO 380 | Unknown | Unknown | Unknown | Yes | Yes | No
## Notes
- LPDDR5 lacks tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking

## Ryzen AI 400
### Gorgon Point (Zen 5/RDNA3.5/XDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen AI 9 HX PRO 475 | Unknown | Unknown | Unknown | Refer to Notes | Yes | No
| Ryzen AI 9 HX 475 | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 9 HX PRO 470 | Unknown | Unknown | Unknown | Refer to Notes | Yes | No
| Ryzen AI 9 HX 470 | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 9 PRO 465 | Unknown | Unknown | Unknown | Refer to Notes | Yes | No
| Ryzen AI 9 465 | Yes | Yes | Yes | Refer to Notes  | Yes | No
| Ryzen AI 7 PRO 450 | No | No | No | Unknown | Yes | No
| Ryzen AI 7 450 | No | No | No | Unknown | Yes | No
| Ryzen AI 7 445 | No | No | No | Unknown | Yes | No
| Ryzen AI 5 PRO 440 | No | No | No | Unknown | Yes | No
| Ryzen AI 5 PRO 435 | No | No | No | Unknown | Yes | No
| Ryzen AI 5 435 | No | No | No | Unknown | Yes | No
| Ryzen AI 5 430 | No | No | No | Unknown | Yes | No
## Notes
- LPDDR5 lacks tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking








