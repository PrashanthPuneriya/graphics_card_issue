# graphics_card_issue
**Introduction:**

If you have encountered a dedicated graphics card issue like the driver isn&#39;t showing up in the Device Manager, GPU disappears if the computer sits idle, graphics card isn&#39;t detected this page serves the purpose. You may have to follow the given procedure if you need to update the graphics card drivers until the manufacturer of the graphics card releases an update which fixes this issue.

### Reasons for the problem:

The most common reasons for the occurrence of the problem are as follows:

- Incompatible Drivers
- Graphics card isn&#39;t properly connected
- Graphics card not being used
- Doesn&#39;t has any dedicated graphics card

**[NOTE]** _This blog demonstrates the solution for the RadeonT RX 560X graphics card used in ASUS TUF FX505DY Laptop. You may even try the solution given below, but don&#39;t blindly follow the links given in this blog as you may have different graphics card and  different manufacturer._

**[CAUTION]** _Backup your system as this might not work as expected._

### So lets get started

_Follow the instructions given below in a step-by-step process._

**1. Update the Windows and BIOS**

**     **

For those who have AMD drivers this is an important step as the _latest version_ of the windows now has updates which fixes the issues with the compatibility of the drivers and boosts the performance by _10%_.

Search for the latest version of windows [as of now _1903_]  and download and install it. After the updation of the windows go to the _Check for Updates_ settings window and proceed on to upgrade the system.

Now, update the [_BIOS_](https://www.asus.com/Laptops/ASUS-TUF-Gaming-FX505DY/HelpDesk_Download/) of the system. BIOS allows the motherboard to work with new hardware. It must be installed cautiously. You can refer to this [_link_](https://www.asus.com/support/FAQ/1008276/) for the updation process of the BIOS.

**2. Update the Graphics Card Drivers**

If you have already installed the graphics card drivers uninstall it by [_this_](https://www.amd.com/en/support/kb/faq/gpu-601) process _(AMD clean-up utility)_ or by [_this_](https://www.youtube.com/watch?v=ZxiLwLCxmkk) process _(DDU)_. Then go to the [_AMD_](https://www.amd.com/en/support/kb/faq/gpu-131) website and download the [auto-detect tool](https://www.amd.com/en/support/kb/faq/gpu-131) which installs the latest graphics card drivers _(as of now 19.6.1)_ supported by your system. [Note] Use the custom installation process and select the latest driver to install.

**3. Update/Install the AMD PSP driver**

This is the most _important step_ as this driver helps the compatible systems to recognize the graphics card properly. Thus, solving the problem.

After the completion of the first _2_ steps if you navigate to the device manager most of them would be getting a PCI encryption/decryption controller device driver issue _(due to the AMD PSP driver)_. So, whether you get an issue or not you need to install the AMD PSP driver

To install the AMD PSP driver download the whole file uploaded in this repo and install the driver manually. If you haven&#39;t got any PCI driver issue the most preferable way to install the driver by opening the setup file contained in the WT64A file as opposed to the installation through Device Manager.

_If these instructions hasn&#39;t yet solved the problem you may need to wait for the official  update which fixes this issue._
