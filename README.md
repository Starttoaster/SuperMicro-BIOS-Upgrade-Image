# SuperMicro-BIOS-Upgrade-Image
Ever want to upgrade your SuperMicro BIOS over IPMI? Bootable USBs not working? This is a bootable DOS .iso image that you can easily attach over virtual storage. 

**Currently in testing but confirmed working on X8SIE, X9DRD, and X9SCM.

**DOWNLOAD LINK:** https://www.dropbox.com/sh/pp82xcv063zg014/AAB6F3IaVhW5fLDd8Al5bPI7a?dl=0
**SHA256 File Hash:** 2f82965c4f8af21c94c0ab5f1ea6a335b268298714a117d22bd2bf5c39011ebd

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

Additional options include: IPMICFG utility and LSI RAID firmware+MegaCLI.

USE AT OWN RISK. UPGRADING BIOS ALWAYS HAS A CHANCE TO RENDER YOUR MOTHERBOARD USELESS. I WILL TAKE NO RESPONSIBILITY FOR BROKEN PROPERTY DUE TO USE OF THIS ISO.
