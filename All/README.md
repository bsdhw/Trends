BSD Hardware Trends
-------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by BSD users at https://BSD-Hardware.info.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [OPNsense](/Dist/OPNsense), [helloSystem](/Dist/helloSystem), [OpenBSD](/Dist/OpenBSD).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/bsdhw/TestCoverage)

Period: Apr, 2022.

Contents
--------

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)

![OS](./images/line_chart_bsd/os_name.svg)

| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| OPNsense 22.1.6       | 122       | 26.35%  |
| OPNsense 22.1.4       | 74        | 15.98%  |
| OPNsense 22.1.5       | 61        | 13.17%  |
| helloSystem 0.7.0     | 40        | 8.64%   |
| FreeBSD 13.0-p11      | 27        | 5.83%   |
| OpenBSD 7.1           | 16        | 3.46%   |
| OPNsense 21.7.8       | 14        | 3.02%   |
| FreeBSD 13.0-p10      | 10        | 2.16%   |
| FreeBSD 12.3          | 9         | 1.94%   |
| OpenBSD 7.0           | 7         | 1.51%   |
| NomadBSD 5806f915     | 6         | 1.3%    |
| FreeBSD 13.0          | 6         | 1.3%    |
| helloSystem 0.8.0     | 5         | 1.08%   |
| FreeBSD 14.0-CURRENT  | 5         | 1.08%   |
| FreeBSD 12.3-p5       | 5         | 1.08%   |
| FreeBSD 13.0-p5       | 4         | 0.86%   |
| OPNsense 22.7         | 3         | 0.65%   |
| GhostBSD 22.04.06     | 3         | 0.65%   |
| FreeBSD 13.1-RC4      | 3         | 0.65%   |
| FreeBSD 13.1-RC2      | 3         | 0.65%   |
| FreeBSD 13.0-p7       | 3         | 0.65%   |
| FreeBSD 12.3-STABLE   | 3         | 0.65%   |
| TrueNAS 12.2-p12      | 2         | 0.43%   |
| OPNsense 22.1.3       | 2         | 0.43%   |
| OPNsense 22.1.2       | 2         | 0.43%   |
| MidnightBSD 2.1.8     | 2         | 0.43%   |
| GhostBSD 22.01.12     | 2         | 0.43%   |
| FreeBSD 13.1-STABLE   | 2         | 0.43%   |
| FreeBSD 13.1-RC3      | 2         | 0.43%   |
| FreeBSD 13.0-p9       | 2         | 0.43%   |
| FreeBSD 13.0-p8       | 2         | 0.43%   |
| OPNsense 22.4         | 1         | 0.22%   |
| OPNsense 22.1         | 1         | 0.22%   |
| OPNsense 21.7.7       | 1         | 0.22%   |
| OPNsense 21.1.9       | 1         | 0.22%   |
| NetBSD 9.99.94        | 1         | 0.22%   |
| helloSystem 13.0-p11  | 1         | 0.22%   |
| helloSystem 0.6.0     | 1         | 0.22%   |
| helloSystem 0.5.0     | 1         | 0.22%   |
| helloSystem 0.4.0     | 1         | 0.22%   |
| GhostBSD 22.04.22     | 1         | 0.22%   |
| FuryBSD 13.0-p10      | 1         | 0.22%   |
| FreeBSD 13.1-RC1      | 1         | 0.22%   |
| FreeBSD 13.0-p4       | 1         | 0.22%   |
| FreeBSD 12.3-p4       | 1         | 0.22%   |
| FreeBSD 12.3-p3       | 1         | 0.22%   |
| FreeBSD 12.1-p22-HBSD | 1         | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)

![OS Family](./images/line_chart_bsd/os_family.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 282       | 60.91%  |
| FreeBSD     | 91        | 19.65%  |
| helloSystem | 49        | 10.58%  |
| OpenBSD     | 23        | 4.97%   |
| NomadBSD    | 6         | 1.3%    |
| GhostBSD    | 6         | 1.3%    |
| TrueNAS     | 2         | 0.43%   |
| MidnightBSD | 2         | 0.43%   |
| NetBSD      | 1         | 0.22%   |
| FuryBSD     | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)

![Arch](./images/line_chart_bsd/os_arch.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 455       | 98.27%  |
| arm64  | 6         | 1.3%    |
| macppc | 1         | 0.22%   |
| i386   | 1         | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)

![DE](./images/line_chart_bsd/os_de.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 324       | 69.98%  |
| helloDesktop  | 64        | 13.82%  |
| XFCE          | 18        | 3.89%   |
| KDE5          | 14        | 3.02%   |
| MATE          | 12        | 2.59%   |
| TWM           | 9         | 1.94%   |
| Openbox       | 8         | 1.73%   |
| i3            | 3         | 0.65%   |
| GNOME         | 3         | 0.65%   |
| LXQt          | 2         | 0.43%   |
| Enlightenment | 2         | 0.43%   |
| xfwm          | 1         | 0.22%   |
| fvwm          | 1         | 0.22%   |
| Cinnamon      | 1         | 0.22%   |
| AwesomeWM     | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)

![Display Server](./images/line_chart_bsd/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 331       | 71.49%  |
| X11     | 131       | 28.29%  |
| Wayland | 1         | 0.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)

![Display Manager](./images/line_chart_bsd/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 361       | 77.97%  |
| SLiM    | 65        | 14.04%  |
| LightDM | 16        | 3.46%   |
| SDDM    | 12        | 2.59%   |
| XDM     | 4         | 0.86%   |
| GDM     | 4         | 0.86%   |
| Ly      | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)

![OS Lang](./images/line_chart_bsd/os_lang.svg)

| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 306       | 66.09%  |
| C                | 67        | 14.47%  |
| en_US            | 58        | 12.53%  |
| ru_RU            | 12        | 2.59%   |
| fr_FR            | 5         | 1.08%   |
| en_GB            | 3         | 0.65%   |
| de_DE            | 3         | 0.65%   |
| zh_CN            | 2         | 0.43%   |
| it_IT            | 2         | 0.43%   |
| es_ES            | 2         | 0.43%   |
| ru_RU.KOI8-R     | 1         | 0.22%   |
| no_NO.ISO8859-15 | 1         | 0.22%   |
| en_NZ            | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)

![Boot Mode](./images/line_chart_bsd/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 398       | 85.96%  |
| BIOS | 65        | 14.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)

![Filesystem](./images/line_chart_bsd/os_filesystem.svg)

| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 240       | 51.84%  |
| Zfs    | 175       | 37.8%   |
| Cd9660 | 25        | 5.4%    |
| Ffs    | 23        | 4.97%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)

![Part. scheme](./images/line_chart_bsd/os_part_scheme.svg)

| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 422       | 91.14%  |
| MBR     | 35        | 7.56%   |
| Unknown | 4         | 0.86%   |
| BSD     | 2         | 0.43%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)

![Vendor](./images/line_chart_bsd/node_vendor.svg)

| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell                       | 50        | 10.8%   |
| ASUSTek Computer           | 39        | 8.42%   |
| Lenovo                     | 38        | 8.21%   |
| Hewlett-Packard            | 38        | 8.21%   |
| Unknown                    | 31        | 6.7%    |
| Intel                      | 26        | 5.62%   |
| Supermicro                 | 25        | 5.4%    |
| Gigabyte Technology        | 23        | 4.97%   |
| Protectli                  | 22        | 4.75%   |
| PC Engines                 | 22        | 4.75%   |
| ASRock                     | 21        | 4.54%   |
| MSI                        | 20        | 4.32%   |
| Sophos                     | 10        | 2.16%   |
| AMI                        | 10        | 2.16%   |
| Deciso                     | 7         | 1.51%   |
| Apple                      | 7         | 1.51%   |
| Fujitsu                    | 6         | 1.3%    |
| BESSTAR Tech               | 6         | 1.3%    |
| Shuttle                    | 4         | 0.86%   |
| TUXEDO                     | 3         | 0.65%   |
| Sony                       | 3         | 0.65%   |
| Seeed Studio               | 3         | 0.65%   |
| Biostar                    | 3         | 0.65%   |
| AWOW                       | 3         | 0.65%   |
| ZOTAC                      | 2         | 0.43%   |
| Raspberry Pi Foundation    | 2         | 0.43%   |
| Panasonic                  | 2         | 0.43%   |
| OEM                        | 2         | 0.43%   |
| Notebook                   | 2         | 0.43%   |
| Jetway                     | 2         | 0.43%   |
| HPE                        | 2         | 0.43%   |
| Datto                      | 2         | 0.43%   |
| Acer                       | 2         | 0.43%   |
| Winston Marriot            | 1         | 0.22%   |
| VIT                        | 1         | 0.22%   |
| Toshiba                    | 1         | 0.22%   |
| Timi                       | 1         | 0.22%   |
| System76                   | 1         | 0.22%   |
| ShenZhen MinWin Technology | 1         | 0.22%   |
| Samsung Electronics        | 1         | 0.22%   |
| Quanmax                    | 1         | 0.22%   |
| Pegatron                   | 1         | 0.22%   |
| Packard Bell               | 1         | 0.22%   |
| MW                         | 1         | 0.22%   |
| LG Electronics             | 1         | 0.22%   |
| KOHJINSHA                  | 1         | 0.22%   |
| IceWhale Technology        | 1         | 0.22%   |
| HUAWEI                     | 1         | 0.22%   |
| Framework                  | 1         | 0.22%   |
| eMachines                  | 1         | 0.22%   |
| DNS                        | 1         | 0.22%   |
| DEXP                       | 1         | 0.22%   |
| CompuLab                   | 1         | 0.22%   |
| CheckPoint                 | 1         | 0.22%   |
| AZW                        | 1         | 0.22%   |
| ASRockRack                 | 1         | 0.22%   |
| Alienware                  | 1         | 0.22%   |
| Acidanthera                | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)

![Model](./images/line_chart_bsd/node_model.svg)

| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 31        | 6.7%    |
| PC Engines APU2                     | 14        | 3.02%   |
| Supermicro Super Server             | 10        | 2.16%   |
| AMI Aptio CRB                       | 8         | 1.73%   |
| Sophos SG                           | 7         | 1.51%   |
| Protectli FW6                       | 7         | 1.51%   |
| Intel Nobilis                       | 7         | 1.51%   |
| Protectli FW4B                      | 6         | 1.3%    |
| PC Engines apu4                     | 5         | 1.08%   |
| HP t620 PLUS Quad Core TC           | 5         | 1.08%   |
| Protectli VP2410                    | 4         | 0.86%   |
| ASUS All Series                     | 4         | 0.86%   |
| Lenovo ThinkCentre M725s 10VUS19H00 | 3         | 0.65%   |
| Intel Q3XXG4-P V1.0                 | 3         | 0.65%   |
| HP t730 Thin Client                 | 3         | 0.65%   |
| HP EliteDesk 800 G1 SFF             | 3         | 0.65%   |
| Dell OptiPlex 7040                  | 3         | 0.65%   |
| Dell G5 5090                        | 3         | 0.65%   |
| Deciso Netboard A20                 | 3         | 0.65%   |
| BESSTAR Tech GK41                   | 3         | 0.65%   |
| AWOW PC BOX                         | 3         | 0.65%   |
| TUXEDO Aura 15 Gen1                 | 2         | 0.43%   |
| Supermicro X9SCL/X9SCM              | 2         | 0.43%   |
| Supermicro X10SLH-N6-ST031          | 2         | 0.43%   |
| Sophos UTM                          | 2         | 0.43%   |
| Seeed Studio ODYSSEY-X86J4105       | 2         | 0.43%   |
| RPi Raspberry Pi                    | 2         | 0.43%   |
| Protectli FW1                       | 2         | 0.43%   |
| PC Engines APU3                     | 2         | 0.43%   |
| MSI MS-7C37                         | 2         | 0.43%   |
| Jetway 1.0                          | 2         | 0.43%   |
| Intel CRESCENTBAY                   | 2         | 0.43%   |
| HP ProDesk 600 G3 SFF               | 2         | 0.43%   |
| HP Compaq 8200 Elite SFF PC         | 2         | 0.43%   |
| Gigabyte X570 AORUS PRO             | 2         | 0.43%   |
| Gigabyte 990FXA-UD3                 | 2         | 0.43%   |
| Dell PowerEdge R220                 | 2         | 0.43%   |
| Dell OptiPlex 9020                  | 2         | 0.43%   |
| Dell OptiPlex 790                   | 2         | 0.43%   |
| Dell OptiPlex 7010                  | 2         | 0.43%   |
| Dell OptiPlex 5040                  | 2         | 0.43%   |
| Deciso DEC2700 - OPNsense Appliance | 2         | 0.43%   |
| ASRock X570 Phantom Gaming 4        | 2         | 0.43%   |
| ZOTAC ZBOX-CI327NANO-GS-01          | 1         | 0.22%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.22%   |
| Winston Marriot PICO PC             | 1         | 0.22%   |
| VIT M2420                           | 1         | 0.22%   |
| TUXEDO Pulse 15 Gen1                | 1         | 0.22%   |
| Toshiba Satellite Pro T130          | 1         | 0.22%   |
| Timi TM1612                         | 1         | 0.22%   |
| System76 Lemur Pro                  | 1         | 0.22%   |
| Supermicro X9SAE                    | 1         | 0.22%   |
| Supermicro X9DAL                    | 1         | 0.22%   |
| Supermicro X8SIL                    | 1         | 0.22%   |
| Supermicro X8DTU-LN4+               | 1         | 0.22%   |
| Supermicro X7SPA-HF                 | 1         | 0.22%   |
| Supermicro X10SLQ                   | 1         | 0.22%   |
| Supermicro SYS-6028R-TRT            | 1         | 0.22%   |
| Supermicro SYS-5018D-MF             | 1         | 0.22%   |
| Supermicro Pro546267                | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)

![Model Family](./images/line_chart_bsd/node_model_family.svg)

| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 31        | 6.7%    |
| Lenovo ThinkPad               | 18        | 3.89%   |
| Dell OptiPlex                 | 15        | 3.24%   |
| PC Engines APU2               | 14        | 3.02%   |
| Dell PowerEdge                | 13        | 2.81%   |
| Lenovo ThinkCentre            | 11        | 2.38%   |
| Supermicro Super              | 10        | 2.16%   |
| AMI Aptio                     | 9         | 1.94%   |
| ASUS PRIME                    | 8         | 1.73%   |
| Sophos SG                     | 7         | 1.51%   |
| Protectli FW6                 | 7         | 1.51%   |
| Intel Nobilis                 | 7         | 1.51%   |
| Dell Latitude                 | 7         | 1.51%   |
| Protectli FW4B                | 6         | 1.3%    |
| HP EliteDesk                  | 6         | 1.3%    |
| PC Engines apu4               | 5         | 1.08%   |
| HP t620                       | 5         | 1.08%   |
| HP ProLiant                   | 5         | 1.08%   |
| HP Compaq                     | 5         | 1.08%   |
| Dell Precision                | 5         | 1.08%   |
| Protectli VP2410              | 4         | 0.86%   |
| Deciso Netboard               | 4         | 0.86%   |
| ASUS All                      | 4         | 0.86%   |
| Intel Q3XXG4-P                | 3         | 0.65%   |
| HP t730                       | 3         | 0.65%   |
| Fujitsu ESPRIMO               | 3         | 0.65%   |
| Dell G5                       | 3         | 0.65%   |
| BESSTAR Tech GK41             | 3         | 0.65%   |
| AWOW PC                       | 3         | 0.65%   |
| ASUS TUF                      | 3         | 0.65%   |
| TUXEDO Aura                   | 2         | 0.43%   |
| Supermicro X9SCL              | 2         | 0.43%   |
| Supermicro X10SLH-N6-ST031    | 2         | 0.43%   |
| Sophos UTM                    | 2         | 0.43%   |
| Seeed Studio ODYSSEY-X86J4105 | 2         | 0.43%   |
| RPi Raspberry                 | 2         | 0.43%   |
| Protectli FW1                 | 2         | 0.43%   |
| PC Engines APU3               | 2         | 0.43%   |
| MSI MS-7C37                   | 2         | 0.43%   |
| Jetway 1.0                    | 2         | 0.43%   |
| Intel CRESCENTBAY             | 2         | 0.43%   |
| HPE ProLiant                  | 2         | 0.43%   |
| HP ProDesk                    | 2         | 0.43%   |
| HP EliteBook                  | 2         | 0.43%   |
| Gigabyte X570                 | 2         | 0.43%   |
| Gigabyte B560M                | 2         | 0.43%   |
| Gigabyte 990FXA-UD3           | 2         | 0.43%   |
| Fujitsu FUTRO                 | 2         | 0.43%   |
| Dell Wyse                     | 2         | 0.43%   |
| Dell Inspiron                 | 2         | 0.43%   |
| Deciso DEC2700                | 2         | 0.43%   |
| ASUS ROG                      | 2         | 0.43%   |
| ASUS M5A97                    | 2         | 0.43%   |
| ASRock X570                   | 2         | 0.43%   |
| ZOTAC ZBOX-CI327NANO-GS-01    | 1         | 0.22%   |
| ZOTAC ZBOX-CI323NANO          | 1         | 0.22%   |
| Winston Marriot PICO          | 1         | 0.22%   |
| VIT M2420                     | 1         | 0.22%   |
| TUXEDO Pulse                  | 1         | 0.22%   |
| Toshiba Satellite             | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)

![MFG Year](./images/line_chart_bsd/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 68        | 14.69%  |
| 2019    | 58        | 12.53%  |
| 2020    | 54        | 11.66%  |
| 2018    | 54        | 11.66%  |
| 2016    | 43        | 9.29%   |
| 2014    | 29        | 6.26%   |
| 2011    | 29        | 6.26%   |
| 2015    | 26        | 5.62%   |
| 2013    | 23        | 4.97%   |
| 2017    | 15        | 3.24%   |
| 2022    | 14        | 3.02%   |
| 2012    | 12        | 2.59%   |
| 2010    | 12        | 2.59%   |
| 2008    | 10        | 2.16%   |
| 2009    | 8         | 1.73%   |
| Unknown | 6         | 1.3%    |
| 2007    | 2         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)

![Form Factor](./images/line_chart_bsd/node_formfactor.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 296       | 63.93%  |
| Notebook       | 76        | 16.41%  |
| Mini pc        | 36        | 7.78%   |
| Server         | 36        | 7.78%   |
| Firewall       | 10        | 2.16%   |
| Convertible    | 4         | 0.86%   |
| All in one     | 3         | 0.65%   |
| System on chip | 2         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)

![Coreboot](./images/line_chart_bsd/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 436       | 94.17%  |
| Yes  | 27        | 5.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)

![RAM Size](./images/line_chart_bsd/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 162       | 34.99%  |
| 4.01-8.0    | 104       | 22.46%  |
| 16.01-24.0  | 96        | 20.73%  |
| 32.01-64.0  | 48        | 10.37%  |
| 64.01-256.0 | 27        | 5.83%   |
| 2.01-3.0    | 12        | 2.59%   |
| 3.01-4.0    | 5         | 1.08%   |
| 0.51-1.0    | 4         | 0.86%   |
| 24.01-32.0  | 3         | 0.65%   |
| 1.01-2.0    | 2         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)

![RAM Used](./images/line_chart_bsd/node_ram_used.svg)

| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 245       | 52.92%  |
| 0.51-1.0    | 131       | 28.29%  |
| 1.01-2.0    | 62        | 13.39%  |
| 2.01-3.0    | 9         | 1.94%   |
| 3.01-4.0    | 6         | 1.3%    |
| 4.01-8.0    | 4         | 0.86%   |
| 0           | 3         | 0.65%   |
| 64.01-256.0 | 1         | 0.22%   |
| 8.01-16.0   | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)

![Total Drives](./images/line_chart_bsd/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 331       | 71.49%  |
| 2      | 55        | 11.88%  |
| 0      | 27        | 5.83%   |
| 4      | 15        | 3.24%   |
| 3      | 14        | 3.02%   |
| 5      | 8         | 1.73%   |
| 6      | 4         | 0.86%   |
| 14     | 2         | 0.43%   |
| 9      | 2         | 0.43%   |
| 16     | 1         | 0.22%   |
| 13     | 1         | 0.22%   |
| 10     | 1         | 0.22%   |
| 8      | 1         | 0.22%   |
| 7      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart_bsd/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 376       | 81.21%  |
| Yes       | 87        | 18.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart_bsd/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 446       | 96.33%  |
| No        | 17        | 3.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)

![Has WiFi](./images/line_chart_bsd/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 308       | 66.52%  |
| Yes       | 155       | 33.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart_bsd/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 361       | 77.97%  |
| Yes       | 102       | 22.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)

![Country](./images/line_chart_bsd/node_location.svg)

| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 123       | 26.57%  |
| Germany             | 69        | 14.9%   |
| Russia              | 31        | 6.7%    |
| France              | 25        | 5.4%    |
| UK                  | 24        | 5.18%   |
| Canada              | 18        | 3.89%   |
| Netherlands         | 15        | 3.24%   |
| Italy               | 12        | 2.59%   |
| Romania             | 10        | 2.16%   |
| Poland              | 10        | 2.16%   |
| Australia           | 9         | 1.94%   |
| Switzerland         | 8         | 1.73%   |
| Norway              | 7         | 1.51%   |
| Belgium             | 6         | 1.3%    |
| Sweden              | 5         | 1.08%   |
| Spain               | 5         | 1.08%   |
| Slovenia            | 5         | 1.08%   |
| Portugal            | 5         | 1.08%   |
| Denmark             | 5         | 1.08%   |
| Taiwan              | 4         | 0.86%   |
| China               | 4         | 0.86%   |
| Brazil              | 4         | 0.86%   |
| Austria             | 4         | 0.86%   |
| New Zealand         | 3         | 0.65%   |
| Israel              | 3         | 0.65%   |
| Indonesia           | 3         | 0.65%   |
| India               | 3         | 0.65%   |
| Belarus             | 3         | 0.65%   |
| Argentina           | 3         | 0.65%   |
| Ukraine             | 2         | 0.43%   |
| Turkey              | 2         | 0.43%   |
| Trinidad and Tobago | 2         | 0.43%   |
| Singapore           | 2         | 0.43%   |
| Hungary             | 2         | 0.43%   |
| Hong Kong           | 2         | 0.43%   |
| Egypt               | 2         | 0.43%   |
| Czechia             | 2         | 0.43%   |
| Chile               | 2         | 0.43%   |
| Albania             | 2         | 0.43%   |
| U.S. Virgin Islands | 1         | 0.22%   |
| Thailand            | 1         | 0.22%   |
| South Africa        | 1         | 0.22%   |
| Slovakia            | 1         | 0.22%   |
| Serbia              | 1         | 0.22%   |
| Peru                | 1         | 0.22%   |
| Panama              | 1         | 0.22%   |
| Pakistan            | 1         | 0.22%   |
| Mexico              | 1         | 0.22%   |
| Japan               | 1         | 0.22%   |
| Iceland             | 1         | 0.22%   |
| Guadeloupe          | 1         | 0.22%   |
| Greece              | 1         | 0.22%   |
| Finland             | 1         | 0.22%   |
| Cyprus              | 1         | 0.22%   |
| Colombia            | 1         | 0.22%   |
| Bulgaria            | 1         | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)

![City](./images/line_chart_bsd/node_city.svg)

| City                | Computers | Percent |
|---------------------|-----------|---------|
| Grand Rapids        | 9         | 1.94%   |
| Paris               | 7         | 1.51%   |
| Vladivostok         | 6         | 1.3%    |
| Oslo                | 6         | 1.3%    |
| Moscow              | 5         | 1.08%   |
| Cologne             | 5         | 1.08%   |
| Cluj-Napoca         | 5         | 1.08%   |
| Zurich              | 4         | 0.86%   |
| London              | 4         | 0.86%   |
| Berlin              | 4         | 0.86%   |
| Vienna              | 3         | 0.65%   |
| Stuttgart           | 3         | 0.65%   |
| St. Albert          | 3         | 0.65%   |
| Scottsdale          | 3         | 0.65%   |
| Portland            | 3         | 0.65%   |
| Milan               | 3         | 0.65%   |
| Melbourne           | 3         | 0.65%   |
| Kranj               | 3         | 0.65%   |
| Bucharest           | 3         | 0.65%   |
| Brooklyn            | 3         | 0.65%   |
| Armavir             | 3         | 0.65%   |
| Ypsilanti           | 2         | 0.43%   |
| Wroclaw             | 2         | 0.43%   |
| Washington          | 2         | 0.43%   |
| Umeå               | 2         | 0.43%   |
| Toulouse            | 2         | 0.43%   |
| Toronto             | 2         | 0.43%   |
| Tampa               | 2         | 0.43%   |
| Tainan City         | 2         | 0.43%   |
| Singapore           | 2         | 0.43%   |
| Seattle             | 2         | 0.43%   |
| Schmallenberg       | 2         | 0.43%   |
| Salem               | 2         | 0.43%   |
| Royal Oak           | 2         | 0.43%   |
| Redmond             | 2         | 0.43%   |
| Québec             | 2         | 0.43%   |
| Potsdam             | 2         | 0.43%   |
| Perth               | 2         | 0.43%   |
| Ospel               | 2         | 0.43%   |
| Omsk                | 2         | 0.43%   |
| Newcastle upon Tyne | 2         | 0.43%   |
| Minsk               | 2         | 0.43%   |
| Milton Keynes       | 2         | 0.43%   |
| Los Angeles         | 2         | 0.43%   |
| Lisbon              | 2         | 0.43%   |
| Krasnodar           | 2         | 0.43%   |
| Jakarta             | 2         | 0.43%   |
| Independence        | 2         | 0.43%   |
| Hoeselt             | 2         | 0.43%   |
| Fremont             | 2         | 0.43%   |
| Frankfurt am Main   | 2         | 0.43%   |
| Edmonton            | 2         | 0.43%   |
| Denver              | 2         | 0.43%   |
| Cleveland           | 2         | 0.43%   |
| Changzhou           | 2         | 0.43%   |
| Champlin            | 2         | 0.43%   |
| Cairo               | 2         | 0.43%   |
| Brookline           | 2         | 0.43%   |
| Aurora              | 2         | 0.43%   |
| Amsterdam           | 2         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)

![Drive Vendor](./images/line_chart_bsd/drive_vendor.svg)

| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Samsung Electronics                | 87        | 105    | 15.88%  |
| WDC                                | 79        | 121    | 14.42%  |
| Seagate                            | 49        | 79     | 8.94%   |
| Kingston                           | 42        | 42     | 7.66%   |
| Crucial                            | 34        | 39     | 6.2%    |
| Toshiba                            | 23        | 39     | 4.2%    |
| SanDisk                            | 23        | 23     | 4.2%    |
| Intel                              | 23        | 25     | 4.2%    |
| Transcend                          | 21        | 21     | 3.83%   |
| China                              | 15        | 16     | 2.74%   |
| Hitachi                            | 12        | 27     | 2.19%   |
| Hoodisk                            | 9         | 9      | 1.64%   |
| A-DATA Technology                  | 9         | 10     | 1.64%   |
| HGST                               | 8         | 8      | 1.46%   |
| Micron Technology                  | 7         | 8      | 1.28%   |
| PNY                                | 6         | 6      | 1.09%   |
| OCZ                                | 6         | 6      | 1.09%   |
| Dogfish                            | 6         | 6      | 1.09%   |
| Protectli                          | 5         | 5      | 0.91%   |
| NVMe                               | 5         | 6      | 0.91%   |
| Intenso                            | 5         | 6      | 0.91%   |
| SK Hynix                           | 4         | 4      | 0.73%   |
| Hewlett-Packard                    | 4         | 5      | 0.73%   |
| FORESEE                            | 4         | 4      | 0.73%   |
| Corsair                            | 4         | 4      | 0.73%   |
| LITEON                             | 3         | 3      | 0.55%   |
| Innostor                           | 3         | 3      | 0.55%   |
| Innodisk                           | 3         | 3      | 0.55%   |
| Gigabyte Technology                | 3         | 3      | 0.55%   |
| BIWIN                              | 3         | 3      | 0.55%   |
| Apple                              | 3         | 3      | 0.55%   |
| Apacer                             | 3         | 3      | 0.55%   |
| SPCC                               | 2         | 2      | 0.36%   |
| ShiJi                              | 2         | 2      | 0.36%   |
| Patriot                            | 2         | 3      | 0.36%   |
| OPENBSD                            | 2         | 2      | 0.36%   |
| LITEONIT                           | 2         | 2      | 0.36%   |
| Leven                              | 2         | 3      | 0.36%   |
| XPG                                | 1         | 1      | 0.18%   |
| WD MediaMax                        | 1         | 1      | 0.18%   |
| Valuetech                          | 1         | 2      | 0.18%   |
| UMIS                               | 1         | 1      | 0.18%   |
| Team                               | 1         | 1      | 0.18%   |
| SSSTC                              | 1         | 1      | 0.18%   |
| Silicon Power                      | 1         | 1      | 0.18%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.18%   |
| Phison                             | 1         | 1      | 0.18%   |
| Pccooler                           | 1         | 1      | 0.18%   |
| Netac                              | 1         | 1      | 0.18%   |
| Mushkin                            | 1         | 1      | 0.18%   |
| LSI                                | 1         | 4      | 0.18%   |
| Lexar                              | 1         | 1      | 0.18%   |
| Lenovo                             | 1         | 1      | 0.18%   |
| Kston                              | 1         | 1      | 0.18%   |
| KIOXIA-EXCERIA                     | 1         | 1      | 0.18%   |
| KIOXIA                             | 1         | 1      | 0.18%   |
| KingSpec                           | 1         | 1      | 0.18%   |
| Kingchuxing                        | 1         | 1      | 0.18%   |
| KimMiDi                            | 1         | 1      | 0.18%   |
| HPT                                | 1         | 15     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)

![Drive Model](./images/line_chart_bsd/drive_model.svg)

| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB         | 11        | 1.81%   |
| WDC WD800JD-75MSA3 80GB              | 9         | 1.48%   |
| Samsung SSD 860 EVO 500GB            | 6         | 0.99%   |
| Kingston SA400S37120G 120GB          | 6         | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 0.82%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.82%   |
| Kingston SUV500MS120G 120GB          | 5         | 0.82%   |
| Kingston SA400S37240G 240GB          | 5         | 0.82%   |
| A-DATA SU650 120GB                   | 4         | 0.66%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 3         | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 0.49%   |
| Transcend TS256GMTS952T2 256GB       | 3         | 0.49%   |
| Transcend TS256GMSA230S 256GB        | 3         | 0.49%   |
| Transcend TS128GMSA230S 128GB        | 3         | 0.49%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.49%   |
| Seagate ST3500413AS 500GB            | 3         | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB       | 3         | 0.49%   |
| Samsung SSD 980 PRO 500GB            | 3         | 0.49%   |
| Samsung SSD 980 PRO 1TB              | 3         | 0.49%   |
| Samsung SSD 970 EVO Plus 250GB       | 3         | 0.49%   |
| Samsung SSD 870 EVO 1TB              | 3         | 0.49%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.49%   |
| Samsung MZ7LN256HAJQ-000L7 256GB     | 3         | 0.49%   |
| Kingston SV300S37A120G 120GB         | 3         | 0.49%   |
| Intel SSDSC2BW180A4 180GB            | 3         | 0.49%   |
| Innostor SSD 15GB                    | 3         | 0.49%   |
| Hoodisk SSD 64GB                     | 3         | 0.49%   |
| Hitachi HUA723020ALA640 2TB          | 3         | 0.49%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.49%   |
| HP RAID 1(1+0) 146GB                 | 3         | 0.49%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.49%   |
| China SATA SSD 32GB                  | 3         | 0.49%   |
| China SATA SSD 16GB                  | 3         | 0.49%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 2         | 0.33%   |
| WDC WDS200T2B0A-00SM50 2TB           | 2         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB         | 2         | 0.33%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.33%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.33%   |
| WDC WD80EFAX-68LHPN0 8TB             | 2         | 0.33%   |
| WDC WD2503ABYX-01WERA1 256GB         | 2         | 0.33%   |
| WDC PC SN520 NVMe 256GB              | 2         | 0.33%   |
| Transcend TS64GMSA230S 64GB          | 2         | 0.33%   |
| Transcend TS256GMTE652T2 256GB       | 2         | 0.33%   |
| Toshiba HDWD110 1TB                  | 2         | 0.33%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.33%   |
| ShiJi SSD 128GB                      | 2         | 0.33%   |
| Seagate ST8000DM004-2CX188 8TB       | 2         | 0.33%   |
| Seagate ST4000DM000-1F2168 4TB       | 2         | 0.33%   |
| Seagate ST3750640NS 752GB            | 2         | 0.33%   |
| Seagate ST2000DM006-2DM164 2TB       | 2         | 0.33%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.33%   |
| SanDisk X400 M.2 2280 128GB          | 2         | 0.33%   |
| SanDisk SSD U100 24GB                | 2         | 0.33%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.33%   |
| SanDisk SD8TB8U-256G-1006 256GB      | 2         | 0.33%   |
| Samsung SSD PM830 2.5-inch 7mm 128GB | 2         | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.33%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.33%   |
| Samsung SSD 960 EVO 250GB            | 2         | 0.33%   |
| Samsung SSD 860 PRO 256GB            | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart_bsd/drive_hdd_vendor.svg)

| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 56        | 89     | 34.57%  |
| Seagate                            | 47        | 77     | 29.01%  |
| Toshiba                            | 19        | 35     | 11.73%  |
| Hitachi                            | 12        | 27     | 7.41%   |
| HGST                               | 8         | 8      | 4.94%   |
| Samsung Electronics                | 7         | 8      | 4.32%   |
| Hewlett-Packard                    | 3         | 4      | 1.85%   |
| OPENBSD                            | 2         | 2      | 1.23%   |
| NVMe                               | 2         | 2      | 1.23%   |
| WD MediaMax                        | 1         | 1      | 0.62%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.62%   |
| LSI                                | 1         | 4      | 0.62%   |
| HPT                                | 1         | 15     | 0.62%   |
| HPE                                | 1         | 6      | 0.62%   |
| Apple                              | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart_bsd/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 58        | 67     | 18.18%  |
| Kingston            | 37        | 37     | 11.6%   |
| Crucial             | 31        | 35     | 9.72%   |
| SanDisk             | 23        | 23     | 7.21%   |
| Intel               | 19        | 21     | 5.96%   |
| Transcend           | 17        | 17     | 5.33%   |
| China               | 15        | 16     | 4.7%    |
| WDC                 | 11        | 12     | 3.45%   |
| Hoodisk             | 9         | 9      | 2.82%   |
| A-DATA Technology   | 8         | 8      | 2.51%   |
| OCZ                 | 6         | 6      | 1.88%   |
| Micron Technology   | 6         | 7      | 1.88%   |
| Dogfish             | 6         | 6      | 1.88%   |
| Protectli           | 5         | 5      | 1.57%   |
| PNY                 | 5         | 5      | 1.57%   |
| Intenso             | 5         | 6      | 1.57%   |
| FORESEE             | 4         | 4      | 1.25%   |
| LITEON              | 3         | 3      | 0.94%   |
| Innostor            | 3         | 3      | 0.94%   |
| Innodisk            | 3         | 3      | 0.94%   |
| Gigabyte Technology | 3         | 3      | 0.94%   |
| Corsair             | 3         | 3      | 0.94%   |
| BIWIN               | 3         | 3      | 0.94%   |
| Apacer              | 3         | 3      | 0.94%   |
| Toshiba             | 2         | 2      | 0.63%   |
| SK Hynix            | 2         | 2      | 0.63%   |
| ShiJi               | 2         | 2      | 0.63%   |
| Patriot             | 2         | 3      | 0.63%   |
| NVMe                | 2         | 3      | 0.63%   |
| LITEONIT            | 2         | 2      | 0.63%   |
| Leven               | 2         | 3      | 0.63%   |
| Apple               | 2         | 2      | 0.63%   |
| XPG                 | 1         | 1      | 0.31%   |
| Valuetech           | 1         | 2      | 0.31%   |
| Team                | 1         | 1      | 0.31%   |
| SSSTC               | 1         | 1      | 0.31%   |
| SPCC                | 1         | 1      | 0.31%   |
| Silicon Power       | 1         | 1      | 0.31%   |
| Pccooler            | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| Lexar               | 1         | 1      | 0.31%   |
| Lenovo              | 1         | 1      | 0.31%   |
| Kston               | 1         | 1      | 0.31%   |
| KingSpec            | 1         | 1      | 0.31%   |
| Kingchuxing         | 1         | 1      | 0.31%   |
| KimMiDi             | 1         | 1      | 0.31%   |
| Hewlett-Packard     | 1         | 1      | 0.31%   |
| Fujitsu             | 1         | 1      | 0.31%   |
| EMTEC               | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)

![Drive Kind](./images/line_chart_bsd/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 293       | 342    | 58.48%  |
| HDD  | 133       | 280    | 26.55%  |
| NVMe | 75        | 85     | 14.97%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)

![Drive Connector](./images/line_chart_bsd/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 390       | 622    | 83.87%  |
| NVMe | 75        | 85     | 16.13%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)

![Drive Size](./images/line_chart_bsd/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 337       | 389    | 74.23%  |
| 0.51-1.0   | 56        | 68     | 12.33%  |
| 1.01-2.0   | 26        | 54     | 5.73%   |
| 3.01-4.0   | 13        | 35     | 2.86%   |
| 4.01-10.0  | 13        | 39     | 2.86%   |
| 10.01-20.0 | 5         | 14     | 1.1%    |
| 2.01-3.0   | 3         | 19     | 0.66%   |
| 20.01-50.0 | 1         | 4      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)

![Space Total](./images/line_chart_bsd/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 194       | 41.9%   |
| 251-500        | 69        | 14.9%   |
| 1-20           | 59        | 12.74%  |
| 21-50          | 46        | 9.94%   |
| 51-100         | 45        | 9.72%   |
| 501-1000       | 28        | 6.05%   |
| 1001-2000      | 9         | 1.94%   |
| More than 3000 | 8         | 1.73%   |
| 2001-3000      | 4         | 0.86%   |
| Unknown        | 1         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)

![Space Used](./images/line_chart_bsd/drive_space_used.svg)

| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 409       | 88.34%  |
| 21-50     | 24        | 5.18%   |
| 51-100    | 14        | 3.02%   |
| 101-250   | 7         | 1.51%   |
| 501-1000  | 4         | 0.86%   |
| 2001-3000 | 2         | 0.43%   |
| 251-500   | 1         | 0.22%   |
| 1001-2000 | 1         | 0.22%   |
| Unknown   | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart_bsd/drive_malfunc.svg)

| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST3750640NS 752GB                | 2         | 4      | 2.94%   |
| Seagate ST3500413AS 500GB                | 2         | 2      | 2.94%   |
| Seagate ST2000DM006-2DM164 2TB           | 2         | 2      | 2.94%   |
| SanDisk SD8TB8U-256G-1006 256GB          | 2         | 2      | 2.94%   |
| Samsung Electronics SSD 870 EVO 1TB      | 2         | 2      | 2.94%   |
| XPG SX950U 240GB                         | 1         | 1      | 1.47%   |
| WDC WDS120G2G0A-00JH30 120GB             | 1         | 1      | 1.47%   |
| WDC WD60EZRZ-00RWYB1 6TB                 | 1         | 1      | 1.47%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 1         | 1      | 1.47%   |
| WDC WD3200BEVT-22A23T0 320GB             | 1         | 1      | 1.47%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1         | 3      | 1.47%   |
| WDC WD1600BEVE-00UYT0 160GB              | 1         | 1      | 1.47%   |
| WDC WD1600AAJS-40H3A0 160GB              | 1         | 1      | 1.47%   |
| Toshiba MK3261GSYN 320GB                 | 1         | 1      | 1.47%   |
| Toshiba MK1637GSX 160GB                  | 1         | 1      | 1.47%   |
| SSSTC CVB-8D128-HP 128GB                 | 1         | 1      | 1.47%   |
| SK Hynix SC308 SATA 128GB                | 1         | 1      | 1.47%   |
| Seagate ST9250827AS 250GB                | 1         | 1      | 1.47%   |
| Seagate ST8000NM0055-1RM112 8TB          | 1         | 1      | 1.47%   |
| Seagate ST6000DM003-2CY186 6TB           | 1         | 1      | 1.47%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 1.47%   |
| Seagate ST4000LM024-2AN17V 4TB           | 1         | 1      | 1.47%   |
| Seagate ST3250310AS 250GB                | 1         | 1      | 1.47%   |
| Seagate ST320LT014-9YK142 320GB          | 1         | 1      | 1.47%   |
| Seagate ST3160310CS 160GB                | 1         | 1      | 1.47%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1         | 1      | 1.47%   |
| Seagate ST1000DM003-1ER162 1TB           | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 960 PRO 512GB    | 1         | 1      | 1.47%   |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 1.47%   |
| Samsung Electronics SP2004C 200GB        | 1         | 1      | 1.47%   |
| Samsung Electronics HM160HI 160GB        | 1         | 1      | 1.47%   |
| Samsung Electronics HD204UI 2TB          | 1         | 1      | 1.47%   |
| Samsung Electronics HD161HJ 160GB        | 1         | 1      | 1.47%   |
| OCZ VERTEX3 120GB                        | 1         | 1      | 1.47%   |
| OCZ VERTEX 32GB                          | 1         | 1      | 1.47%   |
| OCZ VECTOR150 240GB                      | 1         | 1      | 1.47%   |
| Micron Technology 1100 SATA 256GB        | 1         | 1      | 1.47%   |
| LITEON CV8-8E128-HP 128GB                | 1         | 1      | 1.47%   |
| Kingston SV300S37A60G 64GB               | 1         | 1      | 1.47%   |
| Kingston SMS200S360G 64GB                | 1         | 1      | 1.47%   |
| Kingston SA400S37240G 240GB              | 1         | 1      | 1.47%   |
| Kingchuxing SSD 60GB                     | 1         | 1      | 1.47%   |
| Intel SSDSC2KF256H6L 256GB               | 1         | 1      | 1.47%   |
| Intel SSDSC2KB480G7K 480GB               | 1         | 1      | 1.47%   |
| Intel SSDSC2BW120H6 120GB                | 1         | 1      | 1.47%   |
| Hitachi HUA722020ALA331 2TB              | 1         | 2      | 1.47%   |
| Hitachi HTS725032A9A364 320GB            | 1         | 1      | 1.47%   |
| Hitachi HTS723216L9SA60 160GB            | 1         | 1      | 1.47%   |
| Hitachi HTS543232A7A384 320GB            | 1         | 1      | 1.47%   |
| Hitachi HTS541612J9SA00 120GB            | 1         | 1      | 1.47%   |
| HGST HUS726040ALE610 4TB                 | 1         | 1      | 1.47%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 1.47%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 1.47%   |
| HGST HTS541075A7E630 752GB               | 1         | 1      | 1.47%   |
| Dogfish SSD 128GB                        | 1         | 1      | 1.47%   |
| Crucial M4-CT256M4SSD2 256GB             | 1         | 1      | 1.47%   |
| Crucial M4-CT064M4SSD2 64GB              | 1         | 1      | 1.47%   |
| Crucial CT480M500SSD1 480GB              | 1         | 1      | 1.47%   |
| Crucial CT128M550SSD1 128GB              | 1         | 1      | 1.47%   |
| Corsair Force 3 SSD 180GB                | 1         | 1      | 1.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart_bsd/drive_malfunc_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 23.53%  |
| Samsung Electronics | 8         | 8      | 11.76%  |
| WDC                 | 7         | 9      | 10.29%  |
| Hitachi             | 5         | 6      | 7.35%   |
| HGST                | 4         | 4      | 5.88%   |
| Crucial             | 4         | 4      | 5.88%   |
| OCZ                 | 3         | 3      | 4.41%   |
| Kingston            | 3         | 3      | 4.41%   |
| Intel               | 3         | 3      | 4.41%   |
| Toshiba             | 2         | 2      | 2.94%   |
| SanDisk             | 2         | 2      | 2.94%   |
| A-DATA Technology   | 2         | 2      | 2.94%   |
| XPG                 | 1         | 1      | 1.47%   |
| SSSTC               | 1         | 1      | 1.47%   |
| SK Hynix            | 1         | 1      | 1.47%   |
| Micron Technology   | 1         | 1      | 1.47%   |
| LITEON              | 1         | 1      | 1.47%   |
| Kingchuxing         | 1         | 1      | 1.47%   |
| Dogfish             | 1         | 1      | 1.47%   |
| Corsair             | 1         | 1      | 1.47%   |
| Apacer              | 1         | 1      | 1.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart_bsd/drive_malfunc_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 43.24%  |
| WDC                 | 6         | 8      | 16.22%  |
| Hitachi             | 5         | 6      | 13.51%  |
| Samsung Electronics | 4         | 4      | 10.81%  |
| HGST                | 4         | 4      | 10.81%  |
| Toshiba             | 2         | 2      | 5.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart_bsd/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 42     | 53.73%  |
| SSD  | 29        | 29     | 43.28%  |
| NVMe | 2         | 2      | 2.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)

![Failed Drives](./images/line_chart_bsd/drive_failed.svg)

| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB | 1         | 1      | 33.33%  |
| Seagate ST4000NM0025 4TB     | 1         | 2      | 33.33%  |
| Hitachi HUS724040ALE641 4TB  | 1         | 7      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)

![Failed Drive Vendor](./images/line_chart_bsd/drive_failed_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Hitachi | 1         | 7      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)

![Drive Status](./images/line_chart_bsd/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 383       | 588    | 82.54%  |
| Malfunc  | 63        | 73     | 13.58%  |
| Detected | 15        | 36     | 3.23%   |
| Failed   | 3         | 10     | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)

![Storage Vendor](./images/line_chart_bsd/storage_vendor.svg)

| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 310       | 55.06%  |
| AMD                         | 112       | 19.89%  |
| Samsung Electronics         | 32        | 5.68%   |
| Sandisk                     | 19        | 3.37%   |
| Broadcom / LSI              | 14        | 2.49%   |
| ASMedia Technology          | 13        | 2.31%   |
| Marvell Technology Group    | 7         | 1.24%   |
| Kingston Technology Company | 6         | 1.07%   |
| JMicron Technology          | 6         | 1.07%   |
| Nvidia                      | 5         | 0.89%   |
| Hewlett-Packard             | 5         | 0.89%   |
| Toshiba                     | 4         | 0.71%   |
| Phison Electronics          | 4         | 0.71%   |
| Micron/Crucial Technology   | 3         | 0.53%   |
| KIOXIA                      | 3         | 0.53%   |
| Unknown                     | 3         | 0.53%   |
| SK Hynix                    | 2         | 0.36%   |
| Silicon Motion              | 2         | 0.36%   |
| Seagate Technology          | 2         | 0.36%   |
| Micron Technology           | 2         | 0.36%   |
| ADATA Technology            | 2         | 0.36%   |
| VIA Technologies            | 1         | 0.18%   |
| Union Memory (Shenzhen)     | 1         | 0.18%   |
| Silicon Image               | 1         | 0.18%   |
| Realtek Semiconductor       | 1         | 0.18%   |
| HighPoint Technologies      | 1         | 0.18%   |
| ATP ELECTRONICS             | 1         | 0.18%   |
| Adaptec                     | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)

![Storage Model](./images/line_chart_bsd/storage_model.svg)

| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 77        | 12.03%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 29        | 4.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 26        | 4.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 22        | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19        | 2.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17        | 2.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 17        | 2.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 15        | 2.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14        | 2.19%   |
| Unknown                                                                                 | 14        | 2.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13        | 2.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12        | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12        | 1.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 11        | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11        | 1.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 10        | 1.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8         | 1.25%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 8         | 1.25%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 1.09%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.94%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 0.94%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6         | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6         | 0.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 0.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 0.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 0.78%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 4         | 0.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4         | 0.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.63%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 4         | 0.63%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 0.47%   |
| Sandisk PC SN520 NVMe SSD                                                               | 3         | 0.47%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 3         | 0.47%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 3         | 0.47%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.47%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 3         | 0.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3         | 0.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3         | 0.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.47%   |
| AMD FCH IDE Controller                                                                  | 3         | 0.47%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 2         | 0.31%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 2         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)

![Storage Kind](./images/line_chart_bsd/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 379       | 67.2%   |
| NVMe | 87        | 15.43%  |
| IDE  | 60        | 10.64%  |
| RAID | 27        | 4.79%   |
| SAS  | 10        | 1.77%   |
| SCSI | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)

![CPU Vendor](./images/line_chart_bsd/cpu_vendor.svg)

| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 334       | 72.14%  |
| AMD     | 121       | 26.13%  |
| ARM     | 6         | 1.3%    |
| PowerPC | 1         | 0.22%   |
| 11th    | 1         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)

![CPU Model](./images/line_chart_bsd/cpu_model.svg)

| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                            | 21        | 4.54%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 13        | 2.81%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 11        | 2.38%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 7         | 1.51%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 6         | 1.3%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5         | 1.08%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 5         | 1.08%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5         | 1.08%   |
| AMD GX-420CA SOC with Radeon HD Graphics    | 5         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 0.86%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4         | 0.86%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 0.86%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 4         | 0.86%   |
| Intel Celeron J4105 CPU @ 1.50GHz           | 4         | 0.86%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 4         | 0.86%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 0.86%   |
| AMD Athlon 5350 APU with Radeon R3          | 4         | 0.86%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 3         | 0.65%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3         | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 3         | 0.65%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3         | 0.65%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 3         | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3         | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 0.65%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3         | 0.65%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 3         | 0.65%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 3         | 0.65%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 0.65%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 0.65%   |
| ARM Cortex-A53 r0p4                         | 3         | 0.65%   |
| AMD Ryzen Embedded V1500B                   | 3         | 0.65%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3         | 0.65%   |
| AMD RX-427BB with AMD Radeon R7 Graphics    | 3         | 0.65%   |
| AMD PRO A10-8770 R7, 10 COMPUTE CORES 4C+6G | 3         | 0.65%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 2         | 0.43%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 2         | 0.43%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2         | 0.43%   |
| Intel Xeon CPU E3-1220L V2 @ 2.30GHz        | 2         | 0.43%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 2         | 0.43%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2         | 0.43%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 2         | 0.43%   |
| Intel CPU Version                           | 2         | 0.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 0.43%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 2         | 0.43%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.43%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 2         | 0.43%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.43%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 2         | 0.43%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 2         | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.43%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 0.43%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 2         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)

![CPU Model Family](./images/line_chart_bsd/cpu_family.svg)

| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 92        | 19.87%  |
| Intel Celeron           | 76        | 16.41%  |
| Intel Xeon              | 42        | 9.07%   |
| Intel Core i7           | 35        | 7.56%   |
| AMD GX                  | 30        | 6.48%   |
| Intel Core i3           | 25        | 5.4%    |
| AMD Ryzen 7             | 19        | 4.1%    |
| Intel Atom              | 13        | 2.81%   |
| Other                   | 12        | 2.59%   |
| Intel Pentium           | 11        | 2.38%   |
| Intel Core 2 Duo        | 11        | 2.38%   |
| AMD Ryzen 5             | 8         | 1.73%   |
| AMD FX                  | 8         | 1.73%   |
| AMD Ryzen 9             | 7         | 1.51%   |
| ARM Cortex              | 6         | 1.3%    |
| AMD EPYC                | 6         | 1.3%    |
| Intel Core 2 Quad       | 5         | 1.08%   |
| AMD Athlon              | 4         | 0.86%   |
| Intel Xeon Silver       | 3         | 0.65%   |
| Intel Pentium Gold      | 3         | 0.65%   |
| AMD Ryzen Embedded      | 3         | 0.65%   |
| AMD Ryzen 5 PRO         | 3         | 0.65%   |
| AMD PRO A10             | 3         | 0.65%   |
| AMD E                   | 3         | 0.65%   |
| AMD A6                  | 3         | 0.65%   |
| Intel Pentium Silver    | 2         | 0.43%   |
| Intel Pentium Dual-Core | 2         | 0.43%   |
| Intel Genuine           | 2         | 0.43%   |
| Intel Core m3           | 2         | 0.43%   |
| AMD Ryzen Threadripper  | 2         | 0.43%   |
| AMD Ryzen 3             | 2         | 0.43%   |
| AMD G                   | 2         | 0.43%   |
| AMD E2                  | 2         | 0.43%   |
| AMD Athlon II X4        | 2         | 0.43%   |
| AMD A8                  | 2         | 0.43%   |
| Intel Xeon Gold         | 1         | 0.22%   |
| Intel Pentium 4         | 1         | 0.22%   |
| Intel Core 2            | 1         | 0.22%   |
| AMD Turion II Neo       | 1         | 0.22%   |
| AMD Ryzen 7 PRO         | 1         | 0.22%   |
| AMD PRO A8              | 1         | 0.22%   |
| AMD Opteron             | 1         | 0.22%   |
| AMD Embedded            | 1         | 0.22%   |
| AMD Athlon X4           | 1         | 0.22%   |
| AMD Athlon II X2        | 1         | 0.22%   |
| AMD Athlon Dual Core    | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)

![CPU Cores](./images/line_chart_bsd/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 225       | 48.6%   |
| 2       | 120       | 25.92%  |
| 8       | 32        | 6.91%   |
| Unknown | 20        | 4.32%   |
| 16      | 19        | 4.1%    |
| 6       | 17        | 3.67%   |
| 12      | 12        | 2.59%   |
| 32      | 5         | 1.08%   |
| 1       | 4         | 0.86%   |
| 24      | 3         | 0.65%   |
| 10      | 3         | 0.65%   |
| 64      | 1         | 0.22%   |
| 48      | 1         | 0.22%   |
| 28      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)

![CPU Sockets](./images/line_chart_bsd/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 439       | 94.82%  |
| 2       | 13        | 2.81%   |
| Unknown | 11        | 2.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)

![CPU Threads](./images/line_chart_bsd/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 289       | 62.42%  |
| 2       | 152       | 32.83%  |
| Unknown | 22        | 4.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)

![CPU Microarch](./images/line_chart_bsd/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 58        | 12.53%  |
| Haswell       | 44        | 9.5%    |
| Silvermont    | 35        | 7.56%   |
| Skylake       | 34        | 7.34%   |
| SandyBridge   | 31        | 6.7%    |
| IvyBridge     | 26        | 5.62%   |
| Puma          | 23        | 4.97%   |
| Goldmont plus | 22        | 4.75%   |
| Zen 2         | 20        | 4.32%   |
| Goldmont      | 16        | 3.46%   |
| Unknown       | 16        | 3.46%   |
| Penryn        | 15        | 3.24%   |
| Jaguar        | 15        | 3.24%   |
| Zen           | 13        | 2.81%   |
| Piledriver    | 12        | 2.59%   |
| Zen 3         | 10        | 2.16%   |
| Core          | 10        | 2.16%   |
| Broadwell     | 10        | 2.16%   |
| Westmere      | 7         | 1.51%   |
| Zen+          | 6         | 1.3%    |
| CometLake     | 6         | 1.3%    |
| Bobcat        | 6         | 1.3%    |
| Excavator     | 5         | 1.08%   |
| Bonnell       | 5         | 1.08%   |
| Steamroller   | 4         | 0.86%   |
| Nehalem       | 4         | 0.86%   |
| K10           | 4         | 0.86%   |
| TigerLake     | 3         | 0.65%   |
| P6            | 1         | 0.22%   |
| NetBurst      | 1         | 0.22%   |
| K8 Hammer     | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)

![GPU Vendor](./images/line_chart_bsd/gpu_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 243       | 56.25%  |
| AMD                        | 85        | 19.68%  |
| Nvidia                     | 59        | 13.66%  |
| Matrox Electronics Systems | 25        | 5.79%   |
| ASPEED Technology          | 20        | 4.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)

![GPU Model](./images/line_chart_bsd/gpu_model.svg)

| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 4.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 4.58%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 20        | 4.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 4.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 3.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 3.43%   |
| Intel HD Graphics 530                                                                    | 14        | 3.2%    |
| Intel HD Graphics 500                                                                    | 12        | 2.75%   |
| Intel HD Graphics 620                                                                    | 10        | 2.29%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 9         | 2.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 9         | 2.06%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.83%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 7         | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.37%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.37%   |
| AMD Renoir                                                                               | 6         | 1.37%   |
| Matrox Electronics Systems G200eR2                                                       | 5         | 1.14%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 5         | 1.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.14%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 1.14%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 5         | 1.14%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 4         | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.92%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 0.92%   |
| Intel HD Graphics 510                                                                    | 4         | 0.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 0.92%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.69%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 3         | 0.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.69%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 0.69%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 3         | 0.69%   |
| AMD Cezanne                                                                              | 3         | 0.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.69%   |
| Nvidia GT218 [NVS 300]                                                                   | 2         | 0.46%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.46%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.46%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.46%   |
| Matrox Electronics Systems MGA G200eH3                                                   | 2         | 0.46%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.46%   |
| Intel HD Graphics 630                                                                    | 2         | 0.46%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.46%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 0.46%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 2         | 0.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.46%   |
| AMD RS880 [Radeon HD 4250]                                                               | 2         | 0.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)

![GPU Combo](./images/line_chart_bsd/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 225       | 48.6%   |
| 1 x AMD        | 79        | 17.06%  |
| 1 x Nvidia     | 54        | 11.66%  |
| Other          | 41        | 8.86%   |
| 1 x Matrox     | 25        | 5.4%    |
| 1 x ASPEED     | 20        | 4.32%   |
| 2 x Intel      | 9         | 1.94%   |
| Intel + Nvidia | 5         | 1.08%   |
| Intel + AMD    | 4         | 0.86%   |
| 2 x AMD        | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)

![GPU Driver](./images/line_chart_bsd/gpu_driver.svg)

| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 393       | 84.88%  |
| Unknown     | 46        | 9.94%   |
| Proprietary | 24        | 5.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)

![GPU Memory](./images/line_chart_bsd/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 419       | 90.5%   |
| 0.01-0.5   | 12        | 2.59%   |
| 0.51-1.0   | 8         | 1.73%   |
| 1.01-2.0   | 7         | 1.51%   |
| 5.01-6.0   | 6         | 1.3%    |
| 3.01-4.0   | 5         | 1.08%   |
| 7.01-8.0   | 3         | 0.65%   |
| 8.01-16.0  | 2         | 0.43%   |
| 2.01-3.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)

![Monitor Vendor](./images/line_chart_bsd/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 15        | 12.61%  |
| Chimei Innolux          | 11        | 9.24%   |
| AU Optronics            | 11        | 9.24%   |
| Goldstar                | 10        | 8.4%    |
| BOE                     | 10        | 8.4%    |
| Dell                    | 9         | 7.56%   |
| LG Display              | 6         | 5.04%   |
| ViewSonic               | 5         | 4.2%    |
| Philips                 | 5         | 4.2%    |
| Lenovo                  | 5         | 4.2%    |
| Apple                   | 4         | 3.36%   |
| Acer                    | 4         | 3.36%   |
| Eizo                    | 3         | 2.52%   |
| Toshiba                 | 2         | 1.68%   |
| Iiyama                  | 2         | 1.68%   |
| Hewlett-Packard         | 2         | 1.68%   |
| AOC                     | 2         | 1.68%   |
| Unknown                 | 1         | 0.84%   |
| Sony                    | 1         | 0.84%   |
| Sharp                   | 1         | 0.84%   |
| PANDA                   | 1         | 0.84%   |
| Nvidia                  | 1         | 0.84%   |
| NEC Computers           | 1         | 0.84%   |
| LG Electronics          | 1         | 0.84%   |
| InfoVision              | 1         | 0.84%   |
| HannStar                | 1         | 0.84%   |
| Chi Mei Optoelectronics | 1         | 0.84%   |
| BenQ                    | 1         | 0.84%   |
| ASUSTek Computer        | 1         | 0.84%   |
| Ancor Communications    | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)

![Monitor Model](./images/line_chart_bsd/mon_model.svg)

| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2         | 1.57%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch               | 2         | 1.57%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch         | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 2         | 1.57%   |
| ViewSonic VX1940w VSC6A20 1680x1050 410x260mm 19.1-inch                | 1         | 0.79%   |
| ViewSonic VP3268-4K VSC8C34 3840x2160 700x390mm 31.5-inch              | 1         | 0.79%   |
| ViewSonic VP2768-4k VSC9636 3840x2160 600x340mm 27.2-inch              | 1         | 0.79%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1         | 0.79%   |
| ViewSonic LCD Monitor VSCBD2B 1920x1080 480x270mm 21.7-inch            | 1         | 0.79%   |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch            | 1         | 0.79%   |
| Unknown LCD Monitor KJT4K2K60DP 3840x2160                              | 1         | 0.79%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                      | 1         | 0.79%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 0.79%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                          | 1         | 0.79%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch   | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                        | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch   | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch    | 1         | 0.79%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SE790C 3440x1440                       | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC364D 1920x1080 310x170mm 13.9-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1020x570mm 46.0-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.79%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch     | 1         | 0.79%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch              | 1         | 0.79%   |
| Philips LCD Monitor PHL086D 1440x900 400x250mm 18.6-inch               | 1         | 0.79%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 1         | 0.79%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                | 1         | 0.79%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch               | 1         | 0.79%   |
| NEC Computers LCD24WMCX NEC6720 1920x1200 520x320mm 24.0-inch          | 1         | 0.79%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.79%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD05A7 2560x1440 310x170mm 13.9-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0499 2560x1440 310x170mm 13.9-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch            | 1         | 0.79%   |
| Lenovo Q24h-10 LEN66A8 2560x1440 530x300mm 24.0-inch                   | 1         | 0.79%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1         | 0.79%   |
| Lenovo LEN L193pC LEN114F 1280x1024 400x320mm 20.2-inch                | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch                | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                | 1         | 0.79%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1         | 0.79%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch                 | 1         | 0.79%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 0.79%   |
| Hewlett-Packard Z24nf HWP3209 1920x1080 530x300mm 24.0-inch            | 1         | 0.79%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch      | 1         | 0.79%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch              | 1         | 0.79%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                    | 1         | 0.79%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1         | 0.79%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch            | 1         | 0.79%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch             | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)

![Monitor Resolution](./images/line_chart_bsd/mon_resolution.svg)

| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 42.86%  |
| 1366x768 (WXGA)    | 19        | 15.97%  |
| 3840x2160 (4K)     | 11        | 9.24%   |
| 1600x900 (HD+)     | 6         | 5.04%   |
| 2560x1440 (QHD)    | 5         | 4.2%    |
| 1680x1050 (WSXGA+) | 5         | 4.2%    |
| 1280x800 (WXGA)    | 5         | 4.2%    |
| 1920x1200 (WUXGA)  | 4         | 3.36%   |
| 3440x1440          | 2         | 1.68%   |
| 5760x1200          | 1         | 0.84%   |
| 3360x1050          | 1         | 0.84%   |
| 2560x1080          | 1         | 0.84%   |
| 2256x1504          | 1         | 0.84%   |
| 1920x1920          | 1         | 0.84%   |
| 1600x1200          | 1         | 0.84%   |
| 1440x900 (WXGA+)   | 1         | 0.84%   |
| 1280x1024 (SXGA)   | 1         | 0.84%   |
| 1024x768 (XGA)     | 1         | 0.84%   |
| 1024x600           | 1         | 0.84%   |
| Unknown            | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart_bsd/mon_diagonal.svg)

| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 24        | 19.51%  |
| 15      | 14        | 11.38%  |
| 24      | 13        | 10.57%  |
| 27      | 8         | 6.5%    |
| 21      | 8         | 6.5%    |
| 12      | 8         | 6.5%    |
| Unknown | 8         | 6.5%    |
| 23      | 7         | 5.69%   |
| 20      | 5         | 4.07%   |
| 54      | 3         | 2.44%   |
| 31      | 3         | 2.44%   |
| 19      | 3         | 2.44%   |
| 18      | 3         | 2.44%   |
| 14      | 3         | 2.44%   |
| 11      | 3         | 2.44%   |
| 34      | 2         | 1.63%   |
| 22      | 2         | 1.63%   |
| 17      | 2         | 1.63%   |
| 50      | 1         | 0.81%   |
| 46      | 1         | 0.81%   |
| 26      | 1         | 0.81%   |
| 10      | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)

![Monitor Width](./images/line_chart_bsd/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 26.02%  |
| 501-600     | 28        | 22.76%  |
| 201-300     | 21        | 17.07%  |
| 401-500     | 19        | 15.45%  |
| Unknown     | 8         | 6.5%    |
| 351-400     | 5         | 4.07%   |
| 1001-1500   | 5         | 4.07%   |
| 601-700     | 3         | 2.44%   |
| 701-800     | 2         | 1.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)

![Aspect Ratio](./images/line_chart_bsd/mon_ratio.svg)

| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 85        | 74.56%  |
| 16/10   | 14        | 12.28%  |
| Unknown | 7         | 6.14%   |
| 4/3     | 2         | 1.75%   |
| 3/2     | 2         | 1.75%   |
| 21/9    | 2         | 1.75%   |
| 5/4     | 1         | 0.88%   |
| 1.00    | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)

![Monitor Area](./images/line_chart_bsd/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 27        | 21.95%  |
| 81-90          | 23        | 18.7%   |
| 91-100         | 12        | 9.76%   |
| 151-200        | 10        | 8.13%   |
| 61-70          | 8         | 6.5%    |
| 301-350        | 8         | 6.5%    |
| Unknown        | 8         | 6.5%    |
| 351-500        | 6         | 4.88%   |
| More than 1000 | 4         | 3.25%   |
| 71-80          | 3         | 2.44%   |
| 51-60          | 3         | 2.44%   |
| 251-300        | 3         | 2.44%   |
| 101-110        | 3         | 2.44%   |
| 41-50          | 1         | 0.81%   |
| 141-150        | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |
| 121-130        | 1         | 0.81%   |
| 501-1000       | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)

![Pixel Density](./images/line_chart_bsd/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 40        | 33.33%  |
| 121-160       | 30        | 25%     |
| 101-120       | 27        | 22.5%   |
| 161-240       | 12        | 10%     |
| Unknown       | 8         | 6.67%   |
| 1-50          | 2         | 1.67%   |
| More than 240 | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)

![Multiple Monitors](./images/line_chart_bsd/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 347       | 74.95%  |
| 1     | 99        | 21.38%  |
| 2     | 16        | 3.46%   |
| 3     | 1         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)

![Net Controller Vendor](./images/line_chart_bsd/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 364       | 54.17%  |
| Realtek Semiconductor             | 162       | 24.11%  |
| Broadcom                          | 40        | 5.95%   |
| Qualcomm Atheros                  | 34        | 5.06%   |
| Marvell Technology Group          | 6         | 0.89%   |
| AMD                               | 6         | 0.89%   |
| TP-Link                           | 4         | 0.6%    |
| Ralink                            | 4         | 0.6%    |
| Nvidia                            | 4         | 0.6%    |
| ASUSTek Computer                  | 3         | 0.45%   |
| VIA Technologies                  | 2         | 0.3%    |
| U-Blox                            | 2         | 0.3%    |
| Sierra Wireless                   | 2         | 0.3%    |
| Ralink Technology                 | 2         | 0.3%    |
| Novatel Wireless                  | 2         | 0.3%    |
| Mellanox Technologies             | 2         | 0.3%    |
| IMC Networks                      | 2         | 0.3%    |
| Hewlett-Packard                   | 2         | 0.3%    |
| Ericsson Business Mobile Networks | 2         | 0.3%    |
| Edimax Technology                 | 2         | 0.3%    |
| D-Link System                     | 2         | 0.3%    |
| Chelsio Communications            | 2         | 0.3%    |
| Xiaomi                            | 1         | 0.15%   |
| Solarflare Communications         | 1         | 0.15%   |
| Samsung Electronics               | 1         | 0.15%   |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Qcom                              | 1         | 0.15%   |
| OPPO Electronics                  | 1         | 0.15%   |
| NetXen Incorporated               | 1         | 0.15%   |
| Microchip Technology              | 1         | 0.15%   |
| MEDIATEK                          | 1         | 0.15%   |
| LG Electronics                    | 1         | 0.15%   |
| Lenovo                            | 1         | 0.15%   |
| Insyde Software                   | 1         | 0.15%   |
| ICS Advent                        | 1         | 0.15%   |
| Huawei Technologies               | 1         | 0.15%   |
| Fibocom                           | 1         | 0.15%   |
| Emulex                            | 1         | 0.15%   |
| Dell                              | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| Arduino SA                        | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)

![Net Controller Model](./images/line_chart_bsd/net_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 135       | 16.48%  |
| Intel I211 Gigabit Network Connection                                         | 69        | 8.42%   |
| Intel I210 Gigabit Network Connection                                         | 59        | 7.2%    |
| Intel I350 Gigabit Network Connection                                         | 27        | 3.3%    |
| Intel 82574L Gigabit Network Connection                                       | 24        | 2.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 22        | 2.69%   |
| Intel Ethernet Connection I217-LM                                             | 15        | 1.83%   |
| Intel 82583V Gigabit Network Connection                                       | 15        | 1.83%   |
| Intel 82576 Gigabit Network Connection                                        | 12        | 1.47%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 12        | 1.47%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 11        | 1.34%   |
| Intel Wi-Fi 6 AX200                                                           | 10        | 1.22%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 10        | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.1%    |
| Intel Wireless 7265                                                           | 9         | 1.1%    |
| Intel 82579V Gigabit Network Connection                                       | 9         | 1.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 0.85%   |
| Intel Wireless 8260                                                           | 7         | 0.85%   |
| Intel Wireless 3165                                                           | 7         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 0.73%   |
| Intel Wireless-AC 9260                                                        | 6         | 0.73%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 6         | 0.73%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 6         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 0.61%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.61%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 5         | 0.61%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 5         | 0.61%   |
| Intel Ethernet Controller 10G X550T                                           | 5         | 0.61%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 5         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 4         | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 4         | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 0.49%   |
| Intel Ethernet Connection X553 1GbE                                           | 4         | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                                         | 4         | 0.49%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 0.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 0.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.49%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.37%   |
| Nvidia MCP79 Ethernet                                                         | 3         | 0.37%   |
| Intel Wireless 3160                                                           | 3         | 0.37%   |
| Intel WiFi Link 5100                                                          | 3         | 0.37%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.37%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 3         | 0.37%   |
| Intel Ethernet Connection (14) I219-V                                         | 3         | 0.37%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 3         | 0.37%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.37%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 0.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 3         | 0.37%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 2         | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart_bsd/net_wireless_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 48.81%  |
| Qualcomm Atheros                | 28        | 16.67%  |
| Realtek Semiconductor           | 22        | 13.1%   |
| Broadcom                        | 12        | 7.14%   |
| TP-Link                         | 4         | 2.38%   |
| Ralink                          | 4         | 2.38%   |
| ASUSTek Computer                | 3         | 1.79%   |
| Sierra Wireless                 | 2         | 1.19%   |
| Ralink Technology               | 2         | 1.19%   |
| IMC Networks                    | 2         | 1.19%   |
| Edimax Technology               | 2         | 1.19%   |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Qcom                            | 1         | 0.6%    |
| MEDIATEK                        | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| D-Link                          | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)

![Wireless Model](./images/line_chart_bsd/net_wireless_model.svg)

| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.95%   |
| Intel Wireless 7265                                                     | 9         | 5.36%   |
| Intel Wireless 8260                                                     | 7         | 4.17%   |
| Intel Wireless 3165                                                     | 7         | 4.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.57%   |
| Intel Wireless-AC 9260                                                  | 6         | 3.57%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 2.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 4         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.79%   |
| Intel Wireless 3160                                                     | 3         | 1.79%   |
| Intel WiFi Link 5100                                                    | 3         | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2         | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.19%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.19%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.19%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 2         | 1.19%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 1.19%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.19%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.6%    |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.6%    |
| Sierra Wireless EM7455                                                  | 1         | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.6%    |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.6%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.6%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter         | 1         | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.6%    |
| Qualcomm Atheros AR922X Wireless Network Adapter                        | 1         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.6%    |
| Qcom RT73 USB Wireless LAN Card                                         | 1         | 0.6%    |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 1         | 0.6%    |
| Intel Wireless 7260                                                     | 1         | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart_bsd/net_ethernet_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 324       | 59.45%  |
| Realtek Semiconductor     | 151       | 27.71%  |
| Broadcom                  | 29        | 5.32%   |
| Qualcomm Atheros          | 9         | 1.65%   |
| Marvell Technology Group  | 6         | 1.1%    |
| AMD                       | 6         | 1.1%    |
| Nvidia                    | 4         | 0.73%   |
| VIA Technologies          | 2         | 0.37%   |
| Novatel Wireless          | 2         | 0.37%   |
| D-Link System             | 2         | 0.37%   |
| Xiaomi                    | 1         | 0.18%   |
| Solarflare Communications | 1         | 0.18%   |
| Samsung Electronics       | 1         | 0.18%   |
| OPPO Electronics          | 1         | 0.18%   |
| Lenovo                    | 1         | 0.18%   |
| Insyde Software           | 1         | 0.18%   |
| ICS Advent                | 1         | 0.18%   |
| Emulex                    | 1         | 0.18%   |
| Aquantia                  | 1         | 0.18%   |
| Apple                     | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart_bsd/net_ethernet_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 135       | 21.39%  |
| Intel I211 Gigabit Network Connection                                         | 69        | 10.94%  |
| Intel I210 Gigabit Network Connection                                         | 59        | 9.35%   |
| Intel I350 Gigabit Network Connection                                         | 27        | 4.28%   |
| Intel 82574L Gigabit Network Connection                                       | 24        | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 22        | 3.49%   |
| Intel Ethernet Connection I217-LM                                             | 15        | 2.38%   |
| Intel 82583V Gigabit Network Connection                                       | 15        | 2.38%   |
| Intel 82576 Gigabit Network Connection                                        | 12        | 1.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 12        | 1.9%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 11        | 1.74%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.58%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 10        | 1.58%   |
| Intel 82579V Gigabit Network Connection                                       | 9         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8         | 1.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 1.11%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 6         | 0.95%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 6         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 0.79%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 5         | 0.79%   |
| Intel Ethernet Controller 10G X550T                                           | 5         | 0.79%   |
| Intel Ethernet 10G 2P X520 Adapter                                            | 5         | 0.79%   |
| Intel Ethernet Connection X553 1GbE                                           | 4         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                         | 4         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 0.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4         | 0.63%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 4         | 0.63%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.48%   |
| Nvidia MCP79 Ethernet                                                         | 3         | 0.48%   |
| Intel Ethernet Controller I225-V                                              | 3         | 0.48%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 3         | 0.48%   |
| Intel Ethernet Connection (14) I219-V                                         | 3         | 0.48%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 3         | 0.48%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.48%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 2         | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.32%   |
| Novatel Wireless MiFi 8000 RNDIS Control RNDIS Ethernet Data                  | 2         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.32%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 2         | 0.32%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 2         | 0.32%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 2         | 0.32%   |
| Intel Ethernet Connection I354                                                | 2         | 0.32%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.32%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.32%   |
| Intel Ethernet Connection (6) I219-V                                          | 2         | 0.32%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 0.32%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.32%   |
| Intel 82575GB Gigabit Network Connection                                      | 2         | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2         | 0.32%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2         | 0.32%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 2         | 0.32%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 2         | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.16%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1         | 0.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)

![Net Controller Kind](./images/line_chart_bsd/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 446       | 71.82%  |
| WiFi     | 155       | 24.96%  |
| Unknown  | 13        | 2.09%   |
| Modem    | 7         | 1.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)

![Used Controller](./images/line_chart_bsd/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 393       | 89.12%  |
| WiFi     | 48        | 10.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)

![NICs](./images/line_chart_bsd/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 143       | 30.89%  |
| 3     | 85        | 18.36%  |
| 1     | 71        | 15.33%  |
| 4     | 57        | 12.31%  |
| 6     | 44        | 9.5%    |
| 5     | 30        | 6.48%   |
| 8     | 12        | 2.59%   |
| 0     | 6         | 1.3%    |
| 10    | 5         | 1.08%   |
| 12    | 4         | 0.86%   |
| 9     | 3         | 0.65%   |
| 16    | 1         | 0.22%   |
| 14    | 1         | 0.22%   |
| 11    | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)

![IPv6](./images/line_chart_bsd/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 386       | 83.37%  |
| Yes  | 77        | 16.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart_bsd/bt_vendor.svg)

| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 61.17%  |
| Realtek Semiconductor           | 7         | 6.8%    |
| IMC Networks                    | 7         | 6.8%    |
| Apple                           | 5         | 4.85%   |
| Qualcomm Atheros Communications | 4         | 3.88%   |
| Cambridge Silicon Radio         | 4         | 3.88%   |
| Broadcom                        | 3         | 2.91%   |
| Foxconn / Hon Hai               | 2         | 1.94%   |
| Alps Electric                   | 2         | 1.94%   |
| Toshiba                         | 1         | 0.97%   |
| Realtek                         | 1         | 0.97%   |
| Ralink                          | 1         | 0.97%   |
| Micro Star International        | 1         | 0.97%   |
| MediaTek                        | 1         | 0.97%   |
| Integrated System Solution      | 1         | 0.97%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)

![Bluetooth Model](./images/line_chart_bsd/bt_model.svg)

| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 27        | 26.21%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 9         | 8.74%   |
| Intel AX200 Bluetooth                                       | 9         | 8.74%   |
| Intel Wireless-AC 3168 Bluetooth                            | 7         | 6.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 5         | 4.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 3.88%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 3         | 2.91%   |
| Apple Bluetooth Host Controller                             | 3         | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.94%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.94%   |
| Intel AX210 Bluetooth                                       | 2         | 1.94%   |
| Intel AX201 Bluetooth                                       | 2         | 1.94%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 1.94%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 0.97%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.97%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.97%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 0.97%   |
| Realtek Bluetooth Radio                                     | 1         | 0.97%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.97%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.97%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.97%   |
| Micro Star International MS-6970 BToes Bluetooth adapter    | 1         | 0.97%   |
| MediaTek Wireless_Device                                    | 1         | 0.97%   |
| Integrated System Solution Bluetooth Device                 | 1         | 0.97%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 0.97%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 1         | 0.97%   |
| IMC Networks Bluetooth Radio                                | 1         | 0.97%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 0.97%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.97%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth Module                        | 1         | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 0.97%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.97%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.97%   |
| Alps Electric BCM2046 Bluetooth Device                      | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)

![Sound Vendor](./images/line_chart_bsd/snd_vendor.svg)

| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 250       | 58.96%  |
| AMD                                             | 106       | 25%     |
| Nvidia                                          | 49        | 11.56%  |
| Logitech                                        | 3         | 0.71%   |
| Lenovo                                          | 3         | 0.71%   |
| Creative Labs                                   | 3         | 0.71%   |
| Realtek Semiconductor                           | 2         | 0.47%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.24%   |
| Sennheiser Communications                       | 1         | 0.24%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.24%   |
| LG Electronics                                  | 1         | 0.24%   |
| JMTek                                           | 1         | 0.24%   |
| FiiO Electronics Technology                     | 1         | 0.24%   |
| Creative Technology                             | 1         | 0.24%   |
| C-Media Electronics                             | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)

![Sound Model](./images/line_chart_bsd/snd_model.svg)

| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 5.41%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 4.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 4.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22        | 4.41%   |
| AMD FCH Azalia Controller                                                                         | 21        | 4.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 19        | 3.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 3.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 3.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 3.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 3.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 2.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 2.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 2.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 2.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2%      |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.6%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.6%    |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.4%    |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1%      |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5         | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1%      |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1%      |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1%      |
| Unknown                                                                                           | 5         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.8%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4         | 0.8%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.8%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.6%    |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.6%    |
| Realtek Semiconductor Realtek USB Audio                                                           | 2         | 0.4%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.4%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.4%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 0.4%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 2         | 0.4%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.4%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.4%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)

![Memory Vendor](./images/line_chart_bsd/memory_vendor.svg)

| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 94        | 19.83%  |
| Kingston                     | 62        | 13.08%  |
| SK Hynix                     | 60        | 12.66%  |
| Unknown                      | 51        | 10.76%  |
| Crucial                      | 42        | 8.86%   |
| Micron Technology            | 25        | 5.27%   |
| Corsair                      | 23        | 4.85%   |
| G.Skill                      | 21        | 4.43%   |
| Unknown                      | 13        | 2.74%   |
| Unknown (ABCD)               | 11        | 2.32%   |
| Transcend                    | 9         | 1.9%    |
| A-DATA Technology            | 9         | 1.9%    |
| Nanya Technology             | 7         | 1.48%   |
| Kimtigo                      | 5         | 1.05%   |
| Ramaxel Technology           | 4         | 0.84%   |
| Elpida                       | 4         | 0.84%   |
| Super Talent                 | 3         | 0.63%   |
| Unifosa                      | 2         | 0.42%   |
| Team                         | 2         | 0.42%   |
| HPE                          | 2         | 0.42%   |
| Unknown (8A26)               | 1         | 0.21%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.21%   |
| Unknown (0x0C26)             | 1         | 0.21%   |
| Unknown (0x0191)             | 1         | 0.21%   |
| Unknown (000000000C01)       | 1         | 0.21%   |
| Undefined-00BA               | 1         | 0.21%   |
| TakeMS                       | 1         | 0.21%   |
| Smart                        | 1         | 0.21%   |
| Silicon Power                | 1         | 0.21%   |
| Patriot                      | 1         | 0.21%   |
| Neo Forza                    | 1         | 0.21%   |
| Kreton                       | 1         | 0.21%   |
| Kingmax                      | 1         | 0.21%   |
| Intel                        | 1         | 0.21%   |
| Hewlett-Packard              | 1         | 0.21%   |
| GOODRAM                      | 1         | 0.21%   |
| Goldkey                      | 1         | 0.21%   |
| Goldenmars                   | 1         | 0.21%   |
| CSX                          | 1         | 0.21%   |
| Cors                         | 1         | 0.21%   |
| Avant                        | 1         | 0.21%   |
| Atermiter                    | 1         | 0.21%   |
| ASint Technology             | 1         | 0.21%   |
| A-DA                         | 1         | 0.21%   |
| 06F100000C01                 | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)

![Memory Model](./images/line_chart_bsd/memory_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 13        | 2.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 11        | 2.19%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 11        | 2.19%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 4         | 0.8%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s          | 4         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 4         | 0.8%    |
| Unknown RAM Module 8GB 1600MT/s                                | 3         | 0.6%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 3         | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3         | 0.6%    |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1333MT/s          | 3         | 0.6%    |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK Hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s          | 3         | 0.6%    |
| SK Hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s           | 3         | 0.6%    |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s           | 3         | 0.6%    |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                      | 3         | 0.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 3         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.6%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 3         | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 3         | 0.6%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s           | 3         | 0.6%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 3         | 0.6%    |
| Kingston RAM 9905471-001.A01LF 2GB DIMM DDR3 1333MT/s          | 3         | 0.6%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 3         | 0.6%    |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s       | 3         | 0.6%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 3         | 0.6%    |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 3         | 0.6%    |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 2667MT/s          | 3         | 0.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 2         | 0.4%    |
| Unknown RAM Module 4GB DIMM SDRAM                              | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 0.4%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2         | 0.4%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2         | 0.4%    |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s              | 2         | 0.4%    |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 2         | 0.4%    |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 2         | 0.4%    |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 2         | 0.4%    |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.4%    |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s           | 2         | 0.4%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 2         | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.4%    |
| Samsung RAM M471B2873FHS-CH9 4GB DIMM DDR3 1600MT/s            | 2         | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 2         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 2         | 0.4%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.4%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 2         | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 2         | 0.4%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 2400MT/s           | 2         | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s              | 2         | 0.4%    |
| Kingston RAM HP497157-D88-ELFWG 2GB DIMM DDR3 1333MT/s         | 2         | 0.4%    |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 2         | 0.4%    |
| Kingston RAM 99U5458-005.A01LF 4GB DIMM DDR3 1333MT/s          | 2         | 0.4%    |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s          | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)

![Memory Kind](./images/line_chart_bsd/memory_kind.svg)

| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 199       | 47.27%  |
| DDR4            | 172       | 40.86%  |
| DDR2            | 17        | 4.04%   |
| LPDDR4          | 11        | 2.61%   |
| Unknown         | 9         | 2.14%   |
| LPDDR3          | 5         | 1.19%   |
| SDRAM           | 3         | 0.71%   |
| DRAM            | 2         | 0.48%   |
| DDR             | 2         | 0.48%   |
| Logical non-vol | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart_bsd/memory_formfactor.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 251       | 59.48%  |
| SODIMM       | 161       | 38.15%  |
| Row Of Chips | 4         | 0.95%   |
| Chip         | 3         | 0.71%   |
| Unknown      | 3         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)

![Memory Size](./images/line_chart_bsd/memory_size.svg)

| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 148       | 33.64%  |
| 4096   | 144       | 32.73%  |
| 16384  | 68        | 15.45%  |
| 2048   | 60        | 13.64%  |
| 32768  | 12        | 2.73%   |
| 1024   | 6         | 1.36%   |
| 129728 | 1         | 0.23%   |
| 65536  | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)

![Memory Speed](./images/line_chart_bsd/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 125       | 28.28%  |
| 1333    | 71        | 16.06%  |
| 2400    | 59        | 13.35%  |
| 2667    | 48        | 10.86%  |
| 3200    | 33        | 7.47%   |
| 2133    | 30        | 6.79%   |
| 800     | 16        | 3.62%   |
| 667     | 12        | 2.71%   |
| Unknown | 7         | 1.58%   |
| 2666    | 6         | 1.36%   |
| 1067    | 6         | 1.36%   |
| 3600    | 5         | 1.13%   |
| 1867    | 5         | 1.13%   |
| 3000    | 4         | 0.9%    |
| 1334    | 4         | 0.9%    |
| 65535   | 1         | 0.23%   |
| 3534    | 1         | 0.23%   |
| 3400    | 1         | 0.23%   |
| 3066    | 1         | 0.23%   |
| 2134    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 1400    | 1         | 0.23%   |
| 1066    | 1         | 0.23%   |
| 1033    | 1         | 0.23%   |
| 975     | 1         | 0.23%   |
| 400     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)

![Printer Vendor](./images/line_chart_bsd/printer_vendor.svg)

| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)

![Printer Model](./images/line_chart_bsd/printer_model.svg)

| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)

![Camera Vendor](./images/line_chart_bsd/camera_vendor.svg)

| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 36.21%  |
| Microdia                               | 7         | 12.07%  |
| Acer                                   | 7         | 12.07%  |
| Realtek Semiconductor                  | 3         | 5.17%   |
| Ricoh                                  | 2         | 3.45%   |
| Logitech                               | 2         | 3.45%   |
| Lenovo                                 | 2         | 3.45%   |
| IMC Networks                           | 2         | 3.45%   |
| Syntek                                 | 1         | 1.72%   |
| Suyin                                  | 1         | 1.72%   |
| Silicon Motion                         | 1         | 1.72%   |
| Quanta                                 | 1         | 1.72%   |
| Pixart Imaging                         | 1         | 1.72%   |
| OmniVision Technologies                | 1         | 1.72%   |
| Genesys Logic                          | 1         | 1.72%   |
| Denron                                 | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.72%   |
| ARC International                      | 1         | 1.72%   |
| Apple                                  | 1         | 1.72%   |
| Alcor Micro                            | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)

![Camera Model](./images/line_chart_bsd/camera_model.svg)

| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 7         | 12.07%  |
| Microdia Integrated Webcam                                    | 3         | 5.17%   |
| Chicony Chicony USB2.0 Camera                                 | 3         | 5.17%   |
| Acer HD Webcam                                                | 3         | 5.17%   |
| Ricoh USB2.0 Camera                                           | 2         | 3.45%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 3.45%   |
| Chicony HD Webcam                                             | 2         | 3.45%   |
| Acer Integrated Camera                                        | 2         | 3.45%   |
| Syntek Lenovo EasyCamera                                      | 1         | 1.72%   |
| Suyin Asus Integrated Webcam                                  | 1         | 1.72%   |
| Silicon Motion WebCam SC-10IRQ12340N                          | 1         | 1.72%   |
| Realtek USB Camera                                            | 1         | 1.72%   |
| Realtek Integrated_Webcam_HD                                  | 1         | 1.72%   |
| Realtek Integrated Webcam HD                                  | 1         | 1.72%   |
| Quanta ov9734_techfront_camera                                | 1         | 1.72%   |
| Pixart Imaging USB_2.0_Webcam                                 | 1         | 1.72%   |
| OmniVision OV2640 Webcam                                      | 1         | 1.72%   |
| Microdia Sonix USB 2.0 Camera                                 | 1         | 1.72%   |
| Microdia Dell Laptop Integrated Webcam HD                     | 1         | 1.72%   |
| Logitech Webcam C930e                                         | 1         | 1.72%   |
| Logitech C922 Pro Stream Webcam                               | 1         | 1.72%   |
| Lenovo Lenovo 500 RGB Camera                                  | 1         | 1.72%   |
| Lenovo Integrated Webcam                                      | 1         | 1.72%   |
| IMC Networks USB2.0 UVC VGA WebCam                            | 1         | 1.72%   |
| IMC Networks Integrated Camera                                | 1         | 1.72%   |
| Genesys Logic Digital Microscope                              | 1         | 1.72%   |
| Denron Corp., 2M Front Camera                                 | 1         | 1.72%   |
| Chicony XiaoMi USB 2.0 Webcam                                 | 1         | 1.72%   |
| Chicony USB2.0 HD UVC WebCam                                  | 1         | 1.72%   |
| Chicony Sonix ST50220 USB Video Camera                        | 1         | 1.72%   |
| Chicony Lenovo Integrated Camera UVC                          | 1         | 1.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)                      | 1         | 1.72%   |
| Chicony Integrated HP HD Webcam                               | 1         | 1.72%   |
| Chicony HP TrueVision HD Camera                               | 1         | 1.72%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 1.72%   |
| Chicony Chicony USB 2.0 Camera                                | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M WebCam | 1         | 1.72%   |
| ARC International Camera                                      | 1         | 1.72%   |
| Apple FaceTime HD Camera                                      | 1         | 1.72%   |
| Alcor Micro WebCam\S6000                                      | 1         | 1.72%   |
| Acer ThinkPad P50 Integrated Camera                           | 1         | 1.72%   |
| Acer Lenovo EasyCamera                                        | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart_bsd/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 45%     |
| Synaptics                  | 3         | 15%     |
| Upek                       | 2         | 10%     |
| LighTuning Technology      | 2         | 10%     |
| STMicroelectronics         | 1         | 5%      |
| Shenzhen Goodix Technology | 1         | 5%      |
| Broadcom                   | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart_bsd/fingerprint_model.svg)

| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 15%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 10%     |
| Validity Sensors Synaptics WBDI                                              | 2         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5%      |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5%      |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| AuthenTec AES1660 Fingerprint Sensor                                         | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)

![Unsupported Devices](./images/line_chart_bsd/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 179       | 38.66%  |
| 0     | 172       | 37.15%  |
| 2     | 73        | 15.77%  |
| 3     | 31        | 6.7%    |
| 4     | 7         | 1.51%   |
| 5     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart_bsd/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 244       | 60.7%   |
| Bluetooth                | 43        | 10.7%   |
| Net/wireless             | 38        | 9.45%   |
| Firewire controller      | 18        | 4.48%   |
| Fingerprint reader       | 18        | 4.48%   |
| Card reader              | 18        | 4.48%   |
| Net/ethernet             | 7         | 1.74%   |
| Network                  | 6         | 1.49%   |
| Storage                  | 4         | 1%      |
| Sound                    | 2         | 0.5%    |
| Graphics card            | 2         | 0.5%    |
| Storage/raid             | 1         | 0.25%   |
| Dvb card                 | 1         | 0.25%   |

