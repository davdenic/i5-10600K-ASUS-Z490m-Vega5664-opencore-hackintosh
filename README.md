# i5-10600K ASUS Z490m Vega56/64  opencore hackintosh

![MacOs Big Sur](system.png)

## Opencore 0.8.0 Vanilla
## MacOS Big Sur

### Hardware
- Mobo: ASUS Prime Z490m-Plus m-atx (LAN i219v audio ALC887) 
- CPU: intel i5 10600k 4.1GHz Comet lake iGPU UHD630
- GPU: ASUS Arez Strix Radeon RX VEGA 56 OC
- CPU Cooler: Noctua 15S
- RAM: 32GB (2x16) 3200GHz g.skill 
- SSD: NVME Crucial P1 1TB 
- PSU: 750W gold 
- Case: Fractal design Meshify C Mini (micro atx)
- Case fans: 2x140mm Noctua (front intake), 1x120mm Noctua (rear exhaust)
- BT Wi-fi Fenvi T919

### Kexts        
- Lilu.kext                   
- VirtualSMC.kext     
- SMCProcessor.kext       
- SMCSuperIO.kext       
- WhateverGreen.kext
- AppleALC.kext   
- IntelMausiEthernet.kext (Meize)
- USBPorts.kext (manual mapping)

### SSDT
SSDT-Basic v2 from MacOS86.it

### SMBIOS 
iMacPro1,1 (to benefit native Vega56/64)
