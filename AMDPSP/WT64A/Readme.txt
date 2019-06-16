====================================================================
Copyright 2018 ADVANCED MICRO DEVICES, INC. All Rights Reserved.
====================================================================

AMDPSP Package:
---------------
This package provides host driver stack for Cryptographic Acceleration and Trusted Execution Environment (TEE).

Supported Chip-sets:
-------------------
Mullins/Beema
Carrizo-L
Carrizo/Bristol/Stoney
Summit/Naples/ThreadRipper/Pinnacle
Raven


Supported Operating Systems:
----------------------------

Windows 10 32-bit
Windows 10 64-bit


Installation Instructions:
--------------------------
1. Open Windows Device Manager through Control Panel
2. Find “PCI Encryption/Decryption Controller”, right click and select “Update Driver Software”
3. Then select:
    a.  Browse my computer for Driver Software
    b.  Let me pick from a list of devices driver on my computer
    c.  Have Disk
4. Browse to the directory of this package
5. Navigate to amdpsp.inf file and click Open

Un-installation Instructions:
----------------------------
1. Open Windows Device Manager
2. Find “Security Devices” -> "AMD PSP x.x Device", right click and select “Un-install”