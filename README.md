<div align="center">
<h3>MALWARE!!!!! FOR EVAL BY SG!!!! FOR R&D ONLY - DO NOT USE IF YOU DONT KNOW WHAT IT IS!!!!!!!!!!!!!!!!!!!!!! - LEAVE NOW!!!!!!!!!!!!! </h3>

## Table of Contents

- [Introduction](#introduction)
  - [Purpose](#purpose)
  - [Important Warnings](#important-warnings)
  - [Why This Repository?](#why-this-repository)
- [Malware Samples](#malware-samples)
- [Related Malware](#related-malware)
- [Stuxnet Overview](#stuxnet-overview)
  - [Basic Overview](#basic-overview)
  - [Fanny.bmp Overview](#fannybmp-overview)
  - [Related Articles](#related-articles)
- [Tree Overview](#tree-overview)
  - [Files in FILES.ZIP](#files-in-fileszip)
 - [Acknowledgments](#acknowledgments)
- [Password for Encrypted Files](#password-for-encrypted-files)

---

## Introduction

Stuxnet is a worm (malware) that targeted industrial control systems, specifically power plants. **That's Stuxnet in a nutshell**.

### Purpose

This repository is a collection of Stuxnet-related files I have gathered from various sources to make it more accessible for researchers and antivirus developers. The repository includes:
- **Source files**
- **Binaries**
- **PLC Sample Programs**

### Important Warnings
⚠️ This is for research and educational purposes only! Even if you run these in a Virtual Machine, USE CAUTION.⚠ Samples and reports are sourced from various contributors to provide a comprehensive collection.

### Why This Repository?

Finding actual samples of Stuxnet and related malware is relatively easy. However, finding de-obfuscated, analyzed outputs, memory dumps, etc., is difficult. This repository aims to fill that gap.


---



## Stuxnet Overview

Stuxnet is a worm that attacked nuclear power plants through unusual vulnerabilities, known as 0-day vulnerabilities.

### Basic Overview

Includes:
- Source files (PLC, etc.)
- Binaries (malware, etc.)
- PLC Sample Programs

### Fanny.bmp Overview
Fanny (known as fanny.bmp or the classical a, b, c, d, e, ..., __j__.lnk worm) is malware likely not visible on Windows XP and earlier versions. It propagates through removable USB devices, using a sophisticated rootkit that hides itself and adds itself to startup in the Windows registry. It also has the capability to reprogram hardware, such as HDD firmware, for extreme persistence. It exploited the same vulnerabilities as Stuxnet and was used before Stuxnet.


### Related Articles

- [Five Years After the Equation Group HDD Hacks](https://www.zdnet.com/article/five-years-after-the-equation-group-hdd-hacks-firmware-security-still-sucks/)
- [NSA Firmware Hacking](https://www.wired.com/2015/02/nsa-firmware-hacking/)
- [Kaspersky Labs on Equation Group](https://www.theregister.com/2015/02/17/kaspersky_labs_equation_group/)

## Tree Overview

<details>
<summary>🌻Click to Expand Tree</summary>

### Files in FILES.ZIP

|  Special files    |
|----------------|
| PLC_ROOTKIT     |


**STUXNET.DLL_EMBEDDED_RSRCS:**

| File Name      |
|----------------|
| bin201.bin     |
| bin202.bin     |
| bin203.bin     |
| bin205.bin     |
| bin208.bin     |
| bin209.bin     |
| bin210.bin     |
| bin221.bin     |
| bin222.bin     |
| bin240.bin     |
| bin241.bin     |
| bin242.bin     |
| bin250.bin     |

**STEP7:**

| File Name                             |
|---------------------------------------|
| STL-cheat-sheet-by-category.pdf       |
| STL-cheat-sheet-by-alphabet (1).pdf   |
| S_ST70_XX_00030V.TIF                  |
| SIMATIC_STEP7_Basic_software.jpg      |
| HW_e.gif                              |
| 25209116_STEP7Example.zip             |

**BINS:**

| File Name                                                                                  |
|--------------------------------------------------------------------------------------------|
| '~WTR4141_J_37FC7C5D89F1E5A96F54318DF1A2B905.dll'                                          |
| wincc_kernel32.dll.aslr.00013b86.livebin.exe                                               |
| unknown_hook_in_services_memorymod-0x006b0000-0x006b1000.livebin.exe                       |
| S_D102BDAD06B27616BABE442E14461059                                                         |
| R_98FBEBD8883021FBE6464C37ACF17938                                                         |
| Q_C1CB4117D9998C79AE10C1B890C23A4D                                                         |
| P_F9BAE53E77B31841235F698955AECE30.dll                                                     |
| O_CC1DB5360109DE3B857654297D262CA1.dll                                                     |
| N_CA9EABEAB482524E5797C684398335D5                                                         |
| mrxnet.sys.livebin.exe                                                                     |
| mrxnet.sys.593503354.mapped.livebin                                                        |
| mrxcls.sys.livebin.exe                                                                     |
| mrxcls.sys.1278394761.mapped.livebin                                                       |
| memorymod-pe-0x10000000-0x10138000.1155327658.mapped.livebin                               |
| memorymod-pe-0x00090000-0x0010a000.1990061290.mapped.livebin                               |
| memorymod-0x006b0000-0x006b1000.450210202.mapped.livebin                                   |
| maindll_dropper_memorymod-pe-0x10000000-0x10138000.livebin.exe                             |
| M_1E17D81979271CFA44D471430FE123A5                                                         |
| lsass.exe.1373553098.mapped.livebin                                                        |
| lsass2_memorymod-pe-0x00090000-0x0010a000.livebin.exe                                      |
| lsass1_lsass.exe.livebin.exe                                                               |
| L_4589EF6876E9C8C05DCF4DB00A54887B                                                         |
| kernel32.dll.aslr.00013b86.1616636409.mapped.livebin                                       |
| K_055A3421813CAF77E1387FF77B2E2E28                                                         |
| I_F8153747BAE8B4AE48837EE17172151E                                                         |
| H_A3844A1B6BE3F6FAF9C276858F40960                                                          |
| G_F979C6A3E668C5073C4C6506461B034E                                                         |
| F_335707EABBE7FF256E0650432ACCEC9B                                                         |
| E_789F6F8DE3F140CF5D73BEF0B8ABAF78                                                         |
| desktop.ini                                                                                |
| D_7A4E2D2638A454442EFB95F23DF391A1                                                         |
| C_016169EBEBF1CEC2AAD6C7F0D0EE9026                                                         |
| B_74DDC49A7C121A61B8D06C03F92D0C13                                                         |
| A_30DF51C9F0D9B010350DC09ABE1E4E97.ex$                                                    |

</details>


---

## Acknowledgments

-- OP (See forked from)



## Password for Encrypted Files
If you ABSOLUTELY POSITIVE sure you want to look into this MALWARE, below is a clickable element that will display the password to the archive. When you do, no guarantees. Aka you are on your own.
<details>
<summary>🔒I understand that this is one of the most destructive pieces of malware to ever exist, and I still want to go look...</summary>

- **INFECTEDIKNOWWHATIAMDOING**
- **infected**

```
// notes
 If you see a lot of `$\textcolor{red}{\...`, you need to enable JavaScript. It's just red text.

```
