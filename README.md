## vivado-2018-3-installation-guide
Complete guide to install Xilinx Vivado 2018.3 WebPACK for VHDL (free Version)
step by step on how to install Vivado 2018.3 WebPack for VHDL completely free

## Before Installing You Must Do and Check This:
- Have atleast 40GB free (19GB zip file + 14GB installation file ~~ 33GB space needed)
- Create an AMD account first (important)

## Step 1: Download from AMD/Xilinx

1. Go to the official Xilinx archive page:  
https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools/archive.html

2. Select **2018.3** from the archive list.

3. **Create a free AMD/Xilinx account** if you don't have one — this is required to download.

4. Under **"Vivado Design Suite - HLx Editions - 2018.3 Full Product Installation"**, click:  
   `Vivado HLx 2018.3: All OS installer Single-File Download (TAR/GZIP - ~19 GB)`

> 💡 Use the **web installer** if you want to save bandwidth — it only downloads what you select during installation.

> ⚠️ Download verification (MD5/digest) is only supported on **Google Chrome** and **Microsoft Edge**.

---

## Step 2: Extract the Installer

Once downloaded, you will have a file named:
```
Xilinx_Vivado_SDK_2018.3_1207_2324.tar.gz
```

**On Windows:**
- Use **7-Zip** or **WinRAR** to extract
- Right-click the file → Extract Here (or Extract to folder)

## Step 3: Run the Installer

**On Windows:**
- Open the extracted folder
- Navigate to the `bin` folder
- Double-click **`xsetup.bat`**
- A Windows Security Warning will appear — this is **normal and safe**
- Click **"Run"**

## Step 4: Select Edition

When the installer reaches the **"Select Edition to Install"** screen:

- Select **"Vivado HL WebPACK"** — the free, no-cost edition
- Click **Next**

> Do NOT select Design Edition or System Edition — these require a paid license.

---

## Step 5: Customize Components

On the **"Vivado HL WebPACK"** customization screen, recommended selections for academic VHDL use:

**Design Tools:** (click check on the below files) 
- Vivado Design Suite — **required**
- DocNav — optional but useful
- Software Development Kit (SDK) — uncheck to save ~3 GB (only needed for embedded C programming)

**Devices:**
- 7 Series — covers Artix-7, Spartan-7 (Basys3, Nexys4 boards commonly used in colleges)
- SoCs - (important remember to check this) 
- UltraScale, UltraScale+ — uncheck if not needed to save disk space

## Step 6: Select Install Directory

- Default: `C:\Xilinx`
- You can change this to another drive (e.g., `D:\Vivado`) — **no issues with functionality**
- Make sure the target drive has at least **20 GB of free space**

**Shortcut options:**
- Create desktop shortcuts ✅
- Create file associations ✅
- Apply to: Current user (for personal PC) or All users (for shared PC)

---

## Step 7: Install

- Review the **Installation Summary** screen
- Verify edition, devices, tools, and install path
- Click **"Install"**
- Installation takes approximately **15–30 minutes**

> ⚠️ Do NOT close the installer or shut down your PC during installation.

---
## Post-Installation Notes
- The below pop-ups or system request will open up while installing
 
### Prompts you may see during installation:

| Pop-ups/System Request | What to do |
|---|---|
| Windows Security Warning (xsetup.bat) | Click **Run** — safe and official |
| Cable Drivers (Xilinx Inc.) | Click **Install** — needed for FPGA programming via USB |
| WinPcap installation | Click **Don't Install** unless you need Ethernet co-simulation |
| MATLAB / System Generator | Click **Ok** — only needed if you have MATLAB installed |

---

## AFTER THAT VOILA YOU ARE GOOD TO GO NOW YOU CAN USE VIVADO FOR FREE ##

