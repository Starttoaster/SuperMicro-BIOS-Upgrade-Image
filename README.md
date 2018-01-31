# SuperMicro-BIOS-Upgrade-Image
Ever want to upgrade your SuperMicro BIOS over IPMI? Bootable USBs not working? This is a bootable DOS .iso image that you can easily attach over virtual storage. 

**Currently in testing but confirmed working on X8SIE, X9DRD, and X9SCM.

**DOWNLOAD LINK:** https://www.dropbox.com/sh/85pfre27c1epttp/AAB-oy_1eAiX0j59Fwu0umBDa?dl=0

**SHA256 File Hash:** bf34a3a1b1c60848276acaa5cc1d26cd1a7c1b55d00198dfc21c1de48c1f7ce0

Current BIOS versions on .iso:

X7DVL----------------------------------------------[2.1a]  
X8SIL----------------------------------------------[1.2a]  
X8SIE----------------------------------------------[1.2a]  
X8DTL----------------------------------------------[2.1b]  
X9SCM ---------------------------------------------[2.2]   
X9DRD-IF ------------------------------------------[3.2]   
X9DRD-EF / X9DRD-7LN4F ----------------------------[3.2]   
X10SLM---------------------------------------------[3.0a]  
X10SRH---------------------------------------------[2.0b]  
X10DRI---------------------------------------------[2.1a]   
X10DDW---------------------------------------------[2.0a]  
X10SRW---------------------------------------------[2.0b]  
X11SSL---------------------------------------------[2.0c]  

Last Updated 1/28/2018

Always Update IPMI before BIOS. You can do this in the IPMI interface with the firmware upgrade option. To update BIOS, mount this iso over IPMI or KVM and select your motherboard version.

This iso also comes packed with the IPMICFG utility. You may interact with the IPMI interface directly through DOS commands. Additionally I dropped the directory that I use to compile the iso in, as well as setup instructions on how to use it. 

USE AT OWN RISK. UPGRADING BIOS ALWAYS HAS A CHANCE TO RENDER YOUR MOTHERBOARD USELESS. I WILL TAKE NO RESPONSIBILITY FOR BROKEN PROPERTY DUE TO USE OF THIS ISO.
