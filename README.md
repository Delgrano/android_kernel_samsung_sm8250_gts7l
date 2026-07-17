
<h1 align="center">🎨 LineageOS Kernel for Samsung Tab S7,</h1><h1 align="center">with Droidspaces, KernelSU and NetHunter.</h1>
<div align="center">
  <p> - </p>
  <img src="https://avatars.githubusercontent.com/u/24304779?s=200&v=4" width="96" alt="LineageOS_banner">
  <img src="https://kernelsu-next.github.io/webpage/logo.png" width="96" alt="KernelSU Next Logo">
  <p> - </p>
</div>

<h1 align="center">Linux kernel</h1>

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.
See Documentation/00-INDEX for a list of what is contained in each file.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.

<h1 align="center">NetHunter Kernel - Samsung Galaxy Tab S7</h1><h1 align="center">(gts7l, gts7lwifi, gts7xl and gts7xlwifi)</h1>

![NetHunter_banner](https://github.com/user-attachments/assets/1a49a2cd-bb47-47b2-b8bd-437ad003415c)
Official lineage documentation has been moved to <a href="Documentation/README">Documentation</a>

This is a Kernel port for Kali NetHunter from LineageOS 23.2

Made for Samsung Galaxy Tab S7 (gts7l, gts7lwifi, gts7xl and gts7xlwifi)

## 📸 Screenshots

![screenshot](public/ blabla.webp)

---

## 🚦 Getting Started

You can find official build on Kali Linux website, or build it yourself from my sources.

First, clone this repository with it's submodules.

```
git clone --recurse-submodules https://github.com/    /android_kernel_samsung_sm8250.git -b nethunter-lineage-23.2
```

Enter into Kali Linux Kernel Builder and copy local.config to it.

```
cd android_kernel_samsung_sm8250/kali-nethunter-kernel-builder
cp ../nh_files/local.config .
```
Build the kernel.

```
./build.sh
```

For more informations, take a read of the official Kali Linux Nethunter documentations.

<h1 align="center">🤝 Contributions</h1>

| Technology                                      | Description                                    |
| ----------------------------------------------- | ---------------------------------------------- |
| ![LineageOS](https://github.com/LineageOS/android_kernel_samsung_sm8250)                                        | LineageOS Kernel Base                          |
| ![itzreesa](https://github.com/itzreesa)                                                                        | itzreesa the Chef                              |
| ![KernelSU-Next](https://github.com/pershoot/KernelSU-Next)                                                     | KernelSU                                       |
| ![Droidspaces-OSS](https://github.com/ravindu644/Droidspaces-OSS)                                               | Droidspaces                                    |
| ![topjohnwu](https://topjohnwu.github.io/Magisk)                                                                | Magisk                                         |
| ![Kali NetHunter](https://www.kali.org/docs/nethunter)                                                          | Mobile Penetration Testing Platform            |
| ![v0lk3n](https://github.com/v0lk3n)                                                                            | S10 Version and CAN module                     |
| ![AnyKernel3](https://github.com/osm0sis/AnyKernel3)                                                            | AnyKernel                                      |
| ![andip71](https://github.com/HELLBOY017/kernel_oneplus_sm8250/commit/657f461942430c5d8dc35674f7a363948a96e146) | Generic wakelock blocker driver v1.0.0         |
| ![rtl8188eus](https://github.com/zexceed12300/rtl8188eus)                                                       | zexceed12300 rtl8188eus                        |
| ![rtl88x2bu](https://github.com/akabul0us/rtl88x2bu)                                                            | akabul0us rtl88x2bu                            |
| [         ](https://         .com/)                                                                             |                                                |
| [         ](https://         .com/)                                                                             |                                                |
| [         ](https://         .com/)                                                                             | Code formatting                                |
| [         ](https://         .com/)                                                                             | Deployment and hosting                         |
---
Contributions are welcome!
Feel free to open issues or submit pull requests to improve the project
