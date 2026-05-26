# DISCLAIMER
This github repo is a community project, and is not backed by AMD. All of the information you see here was found by end consumers just like you! As much as we are confident in our findings, we can only be so sure as a unofficial source. Please take everything you find with a "grain of salt"  

**This github repo assumes that your OEM has done no customization to your device and has just hidden all of the advanced options without touching them. Any of this information is bound to be false if your OEM decides to remove any of these options. This is very unlikely on laptops, though always possible. This more often happens on desktop motherboards with cheaper/weaker chipsets**

If you have any PRO variant CPUs Please contribute!

# Navigation
- If you aren't sure what this repo is about, please read the "introduction" part.
- If you want to have quick answer as to what your cpu is capable of, refer to the [Simplified Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/main#simplified-table), it will tell you what your cpu is capable of depending on your cpu generation.
- If you want to find the specific information for your CPU, search for your CPU via CTRL+F and write its full name. This will bring you to the Detailed Table where we state what each CPU is capable of instead of generilizing them according to their generation
- Most of our proof is in the "Notes" section under whichever CPU generation you are looking at. Information which does not belong to a specific kind of CPU generation will be put under the [Miscellaneous](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities/tree/main#miscellaneous) section at the bottom.


# Introduction
##  Why does this exist? What even is this repo about?
AMD Mobile cpus are tricky. AMD does not directly tell the end consumer which chips are fused off from which features, only the way the cpu is "meant to be used". However some cpus can use features such as CO, even though AMD says the opposite. Through this github we aim to help people easily figure out what their CPU is technically capable of doing.


## What is your source?
Our source is just attempt and trial by a lot of people on the internet. We gather information from other peoples experiences and put them here for everyone to have a quick way of accessing this information.
A picture will be provided as proof in the "Notes" section if applicable.
Keep in mind: newer the generation of the cpu, the less confidence we have! Except in situations where we have direct proof - contributions matter to us.

We got help from [this wikipedia page](https://en.wikipedia.org/wiki/List_of_AMD_Ryzen_processors#Mobile_processors) to get the full list of Mobile AMD Ryzen processors. 

## Please contribute!!
Do you see the question marks? That is us indicating that we arent sure of our findings, or we are going off of assumptions.
If you have the hardware for which we have written "unknown" or a question mark, you can check what your CPU is capable of and share your findings via creating a Issue!
If you think anything is false or wrong, create an issue so we can talk it out.  

[Here](https://github.com/brick2928/Check-Ryzen-Mobile-Capability?tab=readme-ov-file#cpu-undervolting) is a quick guide telling you how to test what your device is capable of!

# Simplified Table
This table generilizes cpu's by their generation. Usually the capability of the cpu mostly depends on their generation, but there are exceptions. For better accuracy you can refer to the extended section.
## Ryzen

| CPU Generation | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ------------ | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen 2000  | Yes | No | Yes | Yes? | No | No |
| Ryzen 3000 | Yes | No | Yes | Yes | No | No | 
| Ryzen 4000 | Yes | No | Yes | Yes | Depends on Device | No |
| Ryzen 5000 | Only Ryzen 9 or HX | Only Ryzen 9 or HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities?tab=readme-ov-file#ryzen-5000) | Only Ryzen 9, HX, or U | Yes | No |
| Ryzen 6000 | Only Ryzen 9 or HX | Only Ryzen 9 or HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities?tab=readme-ov-file#ryzen-6000) | Only Ryzen 9, HX, or U | Yes | No |
| Ryzen 7000 | Only Ryzen 9 or HX | Only Ryzen 9 or HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities?tab=readme-ov-file#ryzen-7000) | Only Ryzen 9, HX, or U | Yes | No |
| Ryzen 8000 | Only Ryzen 9 or HX | Only Ryzen 9 or HX | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities?tab=readme-ov-file#ryzen-8000) | Only Ryzen 9, HX, or U | Yes | No |
| Ryzen 9000 | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA |
| Ryzen 10 | No | No | No | Unknown | Yes | No |
| Ryzen 100 | No | No | No | Unknown | Yes | No |
| Ryzen 200 | Only Ryzen 9 | Only Ryzen 9 | Only Ryzen 9 | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities#ryzen-200) | Yes | No |
| Ryzen AI 300 | Only Ryzen 9 and non-pro | Only Ryzen 9 and non-pro | Yes? | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities#ryzen-ai-300) | Yes | No |
| Ryzen AI Max 300 | Yes, non-pro | Yes, non-pro | Yes? | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities#strix-halo-zen-5rdna35xdna2-based) | Yes | No |
| Ryzen AI 400 | Only Ryzen 9 | Only Ryzen 9 | Yes? | [Refer to the Detailed Table](https://github.com/brick2928/AMD-Mobile-overclocking-capabilities#ryzen-ai-400) | Yes | No |


# Detailed Table (Ryzen)

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
|AMD 3020e|Yes?|No|Yes|Yes, up to 3200MT/s|No|No|
|AMD 3015Ce|Yes?|No|Yes|Yes, up to 3200MT/s|No|No|
|AMD 3015e|Yes?|No|Yes|Yes, up to 3200MT/s|No|No|
## Notes
- Example of 3020e memory overclocking:  
  <img width="305" height="427" alt="image" src="https://github.com/user-attachments/assets/e6158c6d-960c-4f41-9623-cc80fa688fc9" />  
  Credits: abuabed5861 on discord

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
## Notes
- Example of R7 4800H Memory overclocking:  
  <img width="606" height="334" alt="image" src="https://github.com/user-attachments/assets/ee8fb3d6-084c-4839-8a88-73c48e9dc679" />  
  Credits: SmokelessCPU

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
- [Example of R9 7940HS Overclocking](https://www.youtube.com/watch?v=RfuNeC0gbBA) Credits: Eta Prime on youtube

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
| [Ryzen 9 8945HS](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-9-8945hs.html) | Yes | Yes | Yes | Yes | Yes | No
| [Ryzen 7 8845HS](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-7-8845hs.html) | No | No | No | No? | Yes | No
| [Ryzen 7 8840HS](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-7-8840hs.html) | No | No | No | No? | Yes | No
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
| [Ryzen 9 8945HX](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-9-8945hx.html) | Yes | Yes | Yes | Yes | Yes | No
| [Ryzen 9 8940HX](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-9-8940hx.html) | Yes | Yes | Yes | Yes | Yes | No
| [Ryzen 7 8840HX](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-7-8840hx.html) | Yes | Yes | Yes | Yes | Yes | No
| [Ryzen 7 8745HX](https://www.amd.com/de/products/processors/laptop/ryzen/8000-series/amd-ryzen-7-8745hx.html) | Yes | Yes | Yes | Yes | Yes | No

## Ryzen 9000
### Fire Range (Zen 5/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| [Ryzen 9 9955HX3D](https://www.amd.com/de/products/processors/laptop/ryzen/9000-series/amd-ryzen-9-9955hx3d.html) | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA
| [Ryzen 9 9955HX](https://www.amd.com/de/products/processors/laptop/ryzen/9000-series/amd-ryzen-9-9955hx.html) | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA
| [Ryzen 9 9950HX](https://www.amd.com/de/products/processors/laptop/ryzen/9000-series/amd-ryzen-9-9950hx.html) | Yes | Yes | Yes | Yes | Yes | Yes, with newer AGESA
## Notes  
### 9955HX/3D capability to increase tREFI with newer AGESA.
Folowwing picture shows a 9955HX3D system with higher tREFI than JEDEC. Picture can be found in [Legion Series Discord Server](https://discord.com/channels/761178912230473768/958336296621867038/1466577982289219697)
<img width="2548" height="1599" alt="image" src="https://github.com/user-attachments/assets/8b3841de-265f-4a98-837a-6d4deb614a9a" />

## Ryzen 10
### Mendocino (10 series, Zen 2/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| [Ryzen 5 40](https://www.amd.com/de/products/processors/laptop/ryzen/10-series/amd-ryzen-5-40.html) | No | No | No | Unknown | Yes | No
| [Ryzen 3 30](https://www.amd.com/de/products/processors/laptop/ryzen/10-series/amd-ryzen-3-30.html) | No | No | No | Unknown | Yes | No

## Ryzen 100 
### Rembrandt-R (100 series, Zen 3+/RDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| [Ryzen 7 170](https://www.amd.com/de/products/processors/laptop/ryzen/100-series/amd-ryzen-7-170.html) | No | No | No | Unknown | Yes | No
| [Ryzen 7 160](https://www.amd.com/de/products/processors/laptop/ryzen/100-series/amd-ryzen-7-160.html) | No | No | No | Unknown | Yes | No
| [Ryzen 5 150](https://www.amd.com/de/products/processors/laptop/ryzen/100-series/amd-ryzen-5-150.html) | No | No | No | Unknown | Yes | No
| [Ryzen 5 130](https://www.amd.com/de/products/processors/laptop/ryzen/100-series/amd-ryzen-5-130.html) | No | No | No | Unknown | Yes | No
| [Ryzen 3 110](https://www.amd.com/de/products/processors/laptop/ryzen/100-series/amd-ryzen-3-110.html) | No | No | No | Unknown | Yes | No
## Notes


## Ryzen 200
### Hawk Point Refresh (200 series, Zen 4/RDNA3/XDNA based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| [Ryzen 9 270](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-9-270.html) | Yes | Yes | Yes | Yes? Refer to Notes | Yes | No
| [Ryzen 7 260](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-7-260.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 7 PRO 250](https://www.amd.com/en/products/processors/laptop/ryzen-pro/200-series/amd-ryzen-7-pro-250.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 7 250](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-7-250.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 5 240](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-5-240.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 5 PRO 230](https://www.amd.com/en/products/processors/laptop/ryzen-pro/200-series/amd-ryzen-5-pro-230.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 5 230](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-5-230.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 5 PRO 220](https://www.amd.com/en/products/processors/laptop/ryzen-pro/200-series/amd-ryzen-5-pro-220.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 5 220](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-5-220.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 3 PRO 210](https://www.amd.com/en/products/processors/laptop/ryzen-pro/200-series/amd-ryzen-3-pro-210.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen 3 210](https://www.amd.com/en/products/processors/laptop/ryzen/200-series/amd-ryzen-3-210.html) | No | No | No | No? Refer to Notes | Yes | No
## Notes
- LPDDR5 lacks frequency, tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking

## Ryzen AI 300
### Strix Point and Krackan Point (Zen 5/RDNA3.5/XDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| [Ryzen AI 9 HX PRO 375](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-300-series/amd-ryzen-ai-9-hx-pro-375.html) | Unknown | Unknown | Unknown | Unknown | Yes | No
| [Ryzen AI 9 HX 375](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-9-hx-375.html) | Yes | Yes | Yes | Yes? Refer to Notes | Yes | No
| [Ryzen AI 9 HX PRO 370](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-300-series/amd-ryzen-ai-9-hx-pro-370.html) | Unknown | Unknown | Unknown | Unknown | Yes | No
| [Ryzen AI 9 HX 370](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-9-hx-370.html) | Yes | Yes | Yes | Yes? Refer to Notes | Yes | No
| [Ryzen AI 9 365](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-9-365.html) | Yes | Yes | Yes | Yes? Refer to Notes | Yes | No
| [Ryzen AI 7 PRO 360](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-300-series/amd-ryzen-ai-7-pro-360.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen AI 7 PRO 350](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-300-series/amd-ryzen-ai-7-pro-350.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen AI 7 350](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-7-350.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen AI 5 PRO 340](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-300-series/amd-ryzen-ai-5-pro-340.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen AI 5 340](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-5-340.html) | No | No | No | No? Refer to Notes | Yes | No
| [Ryzen AI 5 330](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-5-330.html) | No | No | No | No? Refer to Notes | Yes | No
## Notes
- LPDDR5 lacks frequency, tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking
- [Example of R9 HX370 overclocking instance 1](https://www.youtube.com/watch?v=4dGn8DQI5pM) Credits: Eta Prime on youtube
- [Example of R9 HX370 overclocking instance 2](https://www.youtube.com/watch?v=6gp495r-wxI) Credits: Iceberg Tech on youtube
- [Example of R9 HX365 overclocking](https://www.youtube.com/watch?v=OHMZqN-m-n4) Credits: Eta Prime on youtube

### Strix Halo (Zen 5/RDNA3.5/XDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen AI MAX+ PRO 395<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-max-pro-300-series/amd-ryzen-ai-max-plus-pro-395.html) [2](url2) [3](url3)</sup> | Unknown | Unknown | Unknown | Yes | Yes | No
| Ryzen AI MAX+ 395<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-max-plus-395.html) [2](url2) [3](url3)</sup> | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX+ 392<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-max-plus-392.html) [2](url2) [3](url3)</sup> | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX PRO 390<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-max-pro-300-series/amd-ryzen-ai-max-pro-390.html) [2](url2) [3](url3)</sup> | Unknown | Unknown | Unknown | Yes | Yes | No
| Ryzen AI MAX 390<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-max-390.html) [2](url2) [3](url3)</sup> | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX+ 388<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-max-plus-388.html) [2](url2) [3](url3)</sup> | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX PRO 385<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-max-pro-300-series/amd-ryzen-ai-max-pro-385.html) [2](url2) [3](url3)</sup> | Unknown | Unknown | Unknown | Yes | Yes | No
| Ryzen AI MAX 385<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-max-385.html) [2](url2) [3](url3)</sup> | Yes | Yes | Yes | Yes | Yes | No
| Ryzen AI MAX PRO 380<sup>[1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-max-pro-300-series/amd-ryzen-ai-max-pro-380.html) [2](url2) [3](url3)</sup> | Unknown | Unknown | Unknown | Yes | Yes | No
## Notes
- LPDDR5 lacks frequency, tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking
- [Example of R AI MAX+ 395 overclocking](https://www.youtube.com/watch?v=OK2Bq1GBi0g) Credits: Eta Prime

## Ryzen AI 400
### Gorgon Point (Zen 5/RDNA3.5/XDNA2 based)
| CPU   | Curve Optimizer capable? | Precision Boost Override capable? |iGPU CO capable?| Memory overclocking capable? | AOD_SETUP Exists? | tREFI Changable?|
| ----------- | ------------- | --------------- |---------|-------------|-----------------------------|-|
| Ryzen AI 9 <br> HX PRO 475<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-400-series/amd-ryzen-ai-9-hx-pro-475.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-9-hx-pro-475.c4313) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-9-HX-PRO-475-Processor-Benchmarks-and-Specs.1198880.0.html)</sup> | No (according to amd) | No (according to amd) | No (according to amd) | Refer to Notes | Yes | No
| Ryzen AI 9 HX 475<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-9-hx-475.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-9-hx-475.c4319) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-9-HX-475-Processor-Benchmarks-and-Specs.1197731.0.html)</sup> | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 9 HX PRO 470<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-400-series/amd-ryzen-ai-9-hx-pro-470.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-9-hx-pro-470.c4314) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-9-HX-PRO-470-Processor-Benchmarks-and-Specs.1198881.0.html)</sup> | No (according to amd) | No (according to amd) | No (according to amd) | Refer to Notes | Yes | No
| Ryzen AI 9 HX 470 <sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-9-hx-470.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-9-hx-470.c4320) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-9-HX-470-Processor-Benchmarks-and-Specs.1197753.0.html)</sup>  | Yes | Yes | Yes | Refer to Notes | Yes | No
| Ryzen AI 9 PRO 465<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-400-series/amd-ryzen-ai-9-pro-465.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-9-pro-465.c4315) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-9-PRO-465-Processor-Benchmarks-and-Specs.1198882.0.html)</sup> | No (according to amd) | No (according to amd) | No (according to amd) | Refer to Notes | Yes | No
| Ryzen AI 9 465<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-9-465.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-9-465.c4321) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-9-465-Processor-Benchmarks-and-Specs.1197759.0.html)</sup> | Yes | Yes | Yes | Refer to Notes  | Yes | No
| Ryzen AI 7 PRO 450<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-400-series/amd-ryzen-ai-7-pro-450.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-7-pro-450.c4316) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-7-PRO-450-Processor-Benchmarks-and-Specs.1198883.0.html)</sup> | No | No | No | Unknown | Yes | No
| Ryzen AI 7 450<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-7-450.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-7-450.c4322) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-7-450-Processor-Benchmarks-and-Specs.1197762.0.html)</sup> | No | No | No | Unknown | Yes | No
| Ryzen AI 7 445<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-7-445.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-7-445.c4323) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-7-445-Processor-Benchmarks-and-Specs.1197764.0.html)</sup> | No | No | No | Unknown | Yes | No
| Ryzen AI 5 PRO 440<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-400-series/amd-ryzen-ai-5-pro-440.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-5-pro-440.c4317) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-5-PRO-440-Processor-Benchmarks-and-Specs.1198884.0.html)</sup> | No | No | No | Unknown | Yes | No
| Ryzen AI 5 PRO 435<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen-pro/ai-400-series/amd-ryzen-ai-5-pro-435.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-5-pro-435.c4318) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-5-PRO-435-Processor-Benchmarks-and-Specs.1198885.0.html)</sup> | No | No | No | Unknown | Yes | No
| Ryzen AI 5 435<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-5-435.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-5-435.c4324) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-5-435-Processor-Benchmarks-and-Specs.1197770.0.html)</sup> | No | No | No | Unknown | Yes | No
| Ryzen AI 5 430<sup> [1](https://www.amd.com/en/products/processors/laptop/ryzen/ai-400-series/amd-ryzen-ai-5-430.html) [2](https://www.techpowerup.com/cpu-specs/ryzen-ai-5-430.c4325) [3](https://www.notebookcheck.net/AMD-Ryzen-AI-5-430-Processor-Benchmarks-and-Specs.1197827.0.html)</sup> | No | No | No | Unknown | Yes | No
## Notes
- LPDDR5 lacks frequency, tCMD, tRFC2 and tRFC4 control
- Pro CPUs might be incapable of Memory Overclocking
<sup>[1](url1) [2](url2) [3](url3)</sup>

# Miscellaneous
## Random
- All R9 and HX CPUs are (in regards of fuses) unlocked for overclocking out of the factory. If you have such a cpu, you can enable Precision boost override (+200 MHz) via AMD Adrenalin software
- There are cases where we simply do not have much information regarding specific kind of CPUs (e.g.: Ryzen PRO). In such cases we might source AMD's spec sheet for our information. If that is the case, we will clearly state so. Reliability of these spec sheets are questionable, as there are many cases where amd states a CPU is incapable of a feature even though it is not. Please do not take such information as of our own.
  ### Soldered DDR (Not LPDDR)
   Not all soldered ram is LPDDR, its possible to have soldered normal DDR ram. Here is everything you should know about them:
   ### Power down mode
    - Power down mode: Soldered DDR has a constantly activated power-down mode.
    - This power-down mode cannot be disabled via Smokeless UMAF becuase soldered DDR appears to ignore the DDR overclock menu until a second so-dimm stick is added.
    - Adding a second So-Dimm stick (if possible) will bring the memory back to its normal behaviour (conservative power down mode, not ignoring DDR overclock options).
   ### Overclocking
    - Unlike LPDDR, Soldered DDR can accept so-dimm sticks on top of them meaning you can run a mix of soldered DDR and so-dimm (if the motherboard has a so-dimm slot). 
    - Any SPD reading software will not work to grab the information of the soldered DDR, as the SPD information is stored in the firmware. Your best bet on AMD is using zentimings.
    - Unless you have really bad dies soldered to your system, usually soldered ram will outperform its so-dimm counterpart.
    - If you mix soldered DDR and so-dimm, the soldered ram should not bottleneck you in regards of memory frequency overclocking (as long as you dont have some top of the line so-dimm stick like samsung b-die).
    - Here is a picture of what I have achieved on my system:  
      <img width="450" height="650" alt="image" src="https://github.com/user-attachments/assets/48309684-3504-4e27-b96b-504d0e6d2039" />


## AOD proof
Below is a image showcasing 4 different bios files, each from a different generation ranging from 2000 to 5000. The bios files showcase that there is no AOD_SETUP string found in any of the BIOS files until ryzen 5000
<img width="1919" height="1050" alt="Screenshot_2" src="https://github.com/user-attachments/assets/820be143-4469-4591-9be5-36b2d6f7b13c" />
However, there is a exception. Ryzen 4000 series technically have unlocked cpus like the ryzen 9 4900h, it appears with these unlocked higher end cpus the bios does have AOD_SETUP.





