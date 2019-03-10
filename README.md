# SuperMicro-BIOS-Upgrade-Image
Ever want to upgrade your SuperMicro BIOS over IPMI? Bootable USBs not working? This is a bootable DOS .iso image that you can easily attach over virtual storage. 

**DOWNLOAD LINK:** https://www.dropbox.com/sh/e38wzyrxjag7epe/AAD1QLSWNZdUucBL54w5ZhiKa?dl=0

**SHA256 File Hash:** a5a2d9a7ca4c440c3f2e78b6d2fa1e5dba5812b1f22b9f79fe1843fd71c9021e

Current BIOS versions on .iso:

X9SCM ---------------------------------------------[2.3]   
X9DRD-IF ------------------------------------------[3.3]   
X9DRD-EF / X9DRD-7LN4F ----------------------------[3.3]   
X10SLM---------------------------------------------[3.2]  
X10SRH---------------------------------------------[3.1]  
X10DRI---------------------------------------------[3.1]   
X10DDW---------------------------------------------[3.0a]  
X10SRW---------------------------------------------[3.1]  
X11SSL---------------------------------------------[2.2]

Last Updated 3/10/2019

Always Update IPMI before BIOS. You can do this in the IPMI interface with the firmware upgrade option. To update BIOS, mount this iso over IPMI or KVM and select your motherboard version.

This iso also comes packed with the IPMICFG utility. You may interact with the IPMI interface directly through DOS commands. Additionally I dropped the directory that I use to compile the iso in, as well as setup instructions on how to use it. 

USE AT OWN RISK. UPGRADING BIOS ALWAYS HAS A CHANCE TO RENDER YOUR MOTHERBOARD USELESS. I WILL TAKE NO RESPONSIBILITY FOR BROKEN PROPERTY DUE TO USE OF THIS ISO.
