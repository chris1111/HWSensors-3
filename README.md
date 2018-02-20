# HWSensors-V1-r89

### This is a Mac OS X Package

### HWSensors branch based on FakeSMC-3.x

### The package includes:
* FakeSMC.kext version 3.x
- ACPIMonitor.kext for custom making ACPI methods to access to hardware
- VoodooBatterySMC for laptop battery monitoring
- CPU sensors:
    IntelCPUMonitor
    AmdCpuMonitor
- GPUSensors
    - RadeonMonitor  for ATI/AMD Radeon card (temperature only)
    - GeforceSensors for Nvidia card Fermi, Kepler, Maxwell, Pascal
    - NVClockX for Nvidia Geforce 7xxx, 8xxx, Tesla
    - X3100 for IntelX3100 (at GM950 chipset)
- LPC chip sensors, motherboard parameters like FAM, Voltages, temperatures
   - ITEIT87x  for chips ITE 87xx, 86xx, usually present on Gigabyte motherboards
   - W836x  for chips Winbond/Nuvoton 83xxx, NCT67xx, usually present on ASUS motherboards
   - F718x  for chips Fintek 
   - PC8739x for chip SMC

### HWSensors Project (c) 2010 netkas, slice, usr-sse2, kozlek, navi, RehabMan and others. All rights reserved. NOTE: FakeSMC & Plugins starting from v915 provides additional sensors information to HWMonitor. EFIMounter script Credit:Clover team 

### Usage: (ESP) 
Option 1 Extensions ➔ (ESP) EFI System Partition
Working for 10.6  to 10.13

### Usage: (S/L/E)
Option 2 Extensions ➔ (S/L/E) System Library Extensions
Working 10.6 to 10.13

#### Download the Release [Download ➤ HWSensors V1-r89](https://github.com/chris1111/HWSensors-V1-r89/releases/tag/v-1)


Visit: [HWSensors Source Forge](https://sourceforge.net/projects/hwsensors3.hwsensors.p/files/?source=navbar)

### Packager chris1111
