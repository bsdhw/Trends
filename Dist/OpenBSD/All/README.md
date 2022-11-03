OpenBSD - Hardware Trends
-------------------------

A project to identify most popular hardware characteristics and track their change
over time based on data collected by BSD users at https://BSD-Hardware.info.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD/Desktop/README.md) and [notebooks](/Dist/OpenBSD/Notebook/README.md).

This report is for one last month. Overall report since the beginning of time: [TestCoverage](https://github.com/bsdhw/TestCoverage)

Period: Oct, 2022.

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

| Name        | Computers | Percent |
|-------------|-----------|---------|
| OpenBSD 7.2 | 21        | 72.41%  |
| OpenBSD 7.1 | 8         | 27.59%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)

![OS Family](./images/line_chart_bsd/os_family.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| OpenBSD | 29        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)

![Arch](./images/line_chart_bsd/os_arch.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 25        | 86.21%  |
| i386  | 4         | 13.79%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)

![DE](./images/line_chart_bsd/os_de.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 27        | 93.1%   |
| XFCE         | 1         | 3.45%   |
| GNOME        | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)

![Display Server](./images/line_chart_bsd/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 24        | 82.76%  |
| Console | 5         | 17.24%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)

![Display Manager](./images/line_chart_bsd/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 29        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)

![OS Lang](./images/line_chart_bsd/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 82.76%  |
| fr_FR   | 2         | 6.9%    |
| ru_RU   | 1         | 3.45%   |
| en_US   | 1         | 3.45%   |
| C       | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)

![Boot Mode](./images/line_chart_bsd/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 18        | 62.07%  |
| EFI  | 11        | 37.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)

![Filesystem](./images/line_chart_bsd/os_filesystem.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 29        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)

![Part. scheme](./images/line_chart_bsd/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 21        | 72.41%  |
| GPT  | 8         | 27.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)

![Vendor](./images/line_chart_bsd/node_vendor.svg)

| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 8         | 27.59%  |
| ASUSTek Computer               | 5         | 17.24%  |
| Panasonic                      | 2         | 6.9%    |
| Matsushita Electric Industrial | 2         | 6.9%    |
| Hewlett-Packard                | 2         | 6.9%    |
| Fujitsu                        | 2         | 6.9%    |
| Supermicro                     | 1         | 3.45%   |
| Soekris Engineering            | 1         | 3.45%   |
| PC Engines                     | 1         | 3.45%   |
| Dell                           | 1         | 3.45%   |
| Clevo                          | 1         | 3.45%   |
| ASRock                         | 1         | 3.45%   |
| Alienware                      | 1         | 3.45%   |
| Unknown                        | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)

![Model](./images/line_chart_bsd/node_model.svg)

| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Fujitsu LIFEBOOK E752                       | 2         | 6.9%    |
| Supermicro X8DTH-i/6/iF/6F                  | 1         | 3.45%   |
| Soekris Engineering net6501                 | 1         | 3.45%   |
| PC Engines APU2                             | 1         | 3.45%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.45%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.45%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.45%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.45%   |
| Lenovo ThinkPad X220 429043U                | 1         | 3.45%   |
| Lenovo ThinkPad T60 2613CTO                 | 1         | 3.45%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 3.45%   |
| Lenovo ThinkPad T420s 4174DL7               | 1         | 3.45%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 3.45%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 3.45%   |
| Lenovo ThinkPad T410 2518C3U                | 1         | 3.45%   |
| Lenovo IdeaPad 5 15ITL05 82FG               | 1         | 3.45%   |
| HP Compaq nw8440 (RND39ET)                  | 1         | 3.45%   |
| HP 260 G3 DM                                | 1         | 3.45%   |
| Dell Latitude E6420                         | 1         | 3.45%   |
| Clevo R130T                                 | 1         | 3.45%   |
| ASUS TUF Gaming B550-PLUS                   | 1         | 3.45%   |
| ASUS P8Z68-V GEN3                           | 1         | 3.45%   |
| ASUS P10S-I Series                          | 1         | 3.45%   |
| ASUS K53TA                                  | 1         | 3.45%   |
| ASUS 1000HE                                 | 1         | 3.45%   |
| ASRock Q1900M                               | 1         | 3.45%   |
| Alienware m15                               | 1         | 3.45%   |
| Unknown                                     | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)

![Model Family](./images/line_chart_bsd/node_model_family.svg)

| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 7         | 24.14%  |
| Fujitsu LIFEBOOK                            | 2         | 6.9%    |
| Supermicro X8DTH-i                          | 1         | 3.45%   |
| Soekris Engineering net6501                 | 1         | 3.45%   |
| PC Engines APU2                             | 1         | 3.45%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.45%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.45%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.45%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.45%   |
| Lenovo IdeaPad                              | 1         | 3.45%   |
| HP Compaq                                   | 1         | 3.45%   |
| HP 260                                      | 1         | 3.45%   |
| Dell Latitude                               | 1         | 3.45%   |
| Clevo R130T                                 | 1         | 3.45%   |
| ASUS TUF                                    | 1         | 3.45%   |
| ASUS P8Z68-V                                | 1         | 3.45%   |
| ASUS P10S-I                                 | 1         | 3.45%   |
| ASUS K53TA                                  | 1         | 3.45%   |
| ASUS 1000HE                                 | 1         | 3.45%   |
| ASRock Q1900M                               | 1         | 3.45%   |
| Alienware m15                               | 1         | 3.45%   |
| Unknown                                     | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)

![MFG Year](./images/line_chart_bsd/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 6         | 20.69%  |
| 2012    | 4         | 13.79%  |
| 2022    | 3         | 10.34%  |
| 2010    | 3         | 10.34%  |
| 2018    | 2         | 6.9%    |
| 2009    | 2         | 6.9%    |
| 2021    | 1         | 3.45%   |
| 2019    | 1         | 3.45%   |
| 2016    | 1         | 3.45%   |
| 2014    | 1         | 3.45%   |
| 2013    | 1         | 3.45%   |
| 2007    | 1         | 3.45%   |
| 2006    | 1         | 3.45%   |
| 2002    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)

![Form Factor](./images/line_chart_bsd/node_formfactor.svg)

| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 16        | 55.17%  |
| Desktop  | 13        | 44.83%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)

![Coreboot](./images/line_chart_bsd/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 93.1%   |
| Yes  | 2         | 6.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)

![RAM Size](./images/line_chart_bsd/node_ram_total.svg)

| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 9         | 31.03%  |
| 4.01-8.0    | 5         | 17.24%  |
| 3.01-4.0    | 5         | 17.24%  |
| 2.01-3.0    | 2         | 6.9%    |
| 16.01-24.0  | 2         | 6.9%    |
| 0.51-1.0    | 2         | 6.9%    |
| 32.01-64.0  | 1         | 3.45%   |
| 24.01-32.0  | 1         | 3.45%   |
| 64.01-256.0 | 1         | 3.45%   |
| 1.01-2.0    | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)

![RAM Used](./images/line_chart_bsd/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 23        | 79.31%  |
| 0        | 3         | 10.34%  |
| 0.51-1.0 | 2         | 6.9%    |
| 4.01-8.0 | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)

![Total Drives](./images/line_chart_bsd/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 72.41%  |
| 2      | 4         | 13.79%  |
| 14     | 1         | 3.45%   |
| 8      | 1         | 3.45%   |
| 6      | 1         | 3.45%   |
| 0      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart_bsd/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 29        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart_bsd/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 96.55%  |
| No        | 1         | 3.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)

![Has WiFi](./images/line_chart_bsd/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 65.52%  |
| No        | 10        | 34.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart_bsd/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 55.17%  |
| Yes       | 13        | 44.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)

![Country](./images/line_chart_bsd/node_location.svg)

| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Canada             | 10        | 34.48%  |
| Russia             | 4         | 13.79%  |
| France             | 4         | 13.79%  |
| USA                | 3         | 10.34%  |
| Germany            | 3         | 10.34%  |
| Ukraine            | 1         | 3.45%   |
| Netherlands        | 1         | 3.45%   |
| Italy              | 1         | 3.45%   |
| Dominican Republic | 1         | 3.45%   |
| Australia          | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)

![City](./images/line_chart_bsd/node_city.svg)

| City               | Computers | Percent |
|--------------------|-----------|---------|
| Montreal           | 10        | 34.48%  |
| Paris              | 2         | 6.9%    |
| Nuremberg          | 2         | 6.9%    |
| Moscow             | 2         | 6.9%    |
| Anglet             | 2         | 6.9%    |
| Vidnoye            | 1         | 3.45%   |
| Sydney             | 1         | 3.45%   |
| Sun Prairie        | 1         | 3.45%   |
| Santo Domingo Este | 1         | 3.45%   |
| Reutov             | 1         | 3.45%   |
| Odessa             | 1         | 3.45%   |
| Memphis            | 1         | 3.45%   |
| Lübeck            | 1         | 3.45%   |
| Lee's Summit       | 1         | 3.45%   |
| Gallarate          | 1         | 3.45%   |
| Amsterdam          | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)

![Drive Vendor](./images/line_chart_bsd/drive_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 11     | 20%     |
| NVMe                | 6         | 7      | 15%     |
| Samsung Electronics | 4         | 9      | 10%     |
| OPENBSD             | 3         | 3      | 7.5%    |
| Hitachi             | 3         | 3      | 7.5%    |
| Toshiba             | 2         | 2      | 5%      |
| Seagate             | 2         | 9      | 5%      |
| Kingston            | 2         | 2      | 5%      |
| HGST                | 2         | 2      | 5%      |
| SPCC                | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| LSI                 | 1         | 1      | 2.5%    |
| Intenso             | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| Corsair             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)

![Drive Model](./images/line_chart_bsd/drive_model.svg)

| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| OPENBSD SR RAID 1 2TB            | 2         | 4.08%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1         | 2.04%   |
| WDC WD7500BPKT-75PK4T0 752GB     | 1         | 2.04%   |
| WDC WD7500BPKT-00PK4T0 752GB     | 1         | 2.04%   |
| WDC WD7500AACS-00ZJB0 752GB      | 1         | 2.04%   |
| WDC WD5000LPLX-00ZNTT0 500GB     | 1         | 2.04%   |
| WDC WD3200BEVE-00A0HT0 320GB     | 1         | 2.04%   |
| WDC WD20PURX-64P6ZY0 2TB         | 1         | 2.04%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 2.04%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 2.04%   |
| WDC WD10JPLX-00MBPT0 1TB         | 1         | 2.04%   |
| WDC WD My Passport 25E7 2TB      | 1         | 2.04%   |
| Toshiba MQ01ACF032 320GB         | 1         | 2.04%   |
| Toshiba MK5065GSX 500GB          | 1         | 2.04%   |
| SPCC Solid State Disk 128GB      | 1         | 2.04%   |
| Seagate ST9160821A 160GB         | 1         | 2.04%   |
| Seagate ST3000DM001 137GB        | 1         | 2.04%   |
| Seagate OneTouch HDD 5TB         | 1         | 2.04%   |
| Seagate Expansion HDD 5TB        | 1         | 2.04%   |
| Seagate Expansion Desk 4TB       | 1         | 2.04%   |
| Seagate Expansion 4TB            | 1         | 2.04%   |
| Seagate BUP Slim BK 2TB          | 1         | 2.04%   |
| Seagate BUP Portable 5TB         | 1         | 2.04%   |
| Samsung SSD 870 QVO 2TB          | 1         | 2.04%   |
| Samsung MZ7PC128HAFU-000L1 128GB | 1         | 2.04%   |
| Samsung HM320II 320GB            | 1         | 2.04%   |
| Samsung Flash Drive FIT 32GB     | 1         | 2.04%   |
| OPENBSD SR RAID 5 9.9TB          | 1         | 2.04%   |
| OCZ VERTEX3 120GB                | 1         | 2.04%   |
| NVMe XPG GAMMIX S50 L 512GB      | 1         | 2.04%   |
| NVMe TOSHIBA-RC100 240GB         | 1         | 2.04%   |
| NVMe Samsung SSD 980 1TB         | 1         | 2.04%   |
| NVMe SAMSUNG MZALQ512 512GB      | 1         | 2.04%   |
| NVMe KXG50ZNV1T02 NVM 1TB        | 1         | 2.04%   |
| NVMe CT500P2SSD8 500GB           | 1         | 2.04%   |
| LSI MR9271-8i 438GB              | 1         | 2.04%   |
| Kingston SMS200S330G 32GB        | 1         | 2.04%   |
| Kingston SA400S37240G 240GB      | 1         | 2.04%   |
| Intenso SSD 128GB                | 1         | 2.04%   |
| Hitachi HUA723020ALA640 2TB      | 1         | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart_bsd/drive_hdd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 11     | 28.57%  |
| NVMe                | 4         | 5      | 14.29%  |
| OPENBSD             | 3         | 3      | 10.71%  |
| Hitachi             | 3         | 3      | 10.71%  |
| Toshiba             | 2         | 2      | 7.14%   |
| Seagate             | 2         | 9      | 7.14%   |
| Samsung Electronics | 2         | 2      | 7.14%   |
| HGST                | 2         | 2      | 7.14%   |
| LSI                 | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)

![SSD Vendor](./images/line_chart_bsd/drive_ssd_vendor.svg)

| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 7      | 16.67%  |
| NVMe                | 2         | 2      | 16.67%  |
| Kingston            | 2         | 2      | 16.67%  |
| SPCC                | 1         | 1      | 8.33%   |
| OCZ                 | 1         | 1      | 8.33%   |
| Intenso             | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| Corsair             | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)

![Drive Kind](./images/line_chart_bsd/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 39     | 67.74%  |
| SSD  | 10        | 17     | 32.26%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)

![Drive Connector](./images/line_chart_bsd/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 56     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)

![Drive Size](./images/line_chart_bsd/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 21     | 51.35%  |
| 0.51-1.0   | 11        | 11     | 29.73%  |
| 1.01-2.0   | 4         | 17     | 10.81%  |
| 4.01-10.0  | 2         | 4      | 5.41%   |
| 3.01-4.0   | 1         | 3      | 2.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)

![Space Total](./images/line_chart_bsd/drive_space_total.svg)

| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 10        | 34.48%  |
| 251-500        | 6         | 20.69%  |
| 101-250        | 5         | 17.24%  |
| More than 3000 | 3         | 10.34%  |
| 501-1000       | 2         | 6.9%    |
| 51-100         | 2         | 6.9%    |
| 1-20           | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)

![Space Used](./images/line_chart_bsd/drive_space_used.svg)

| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 22        | 75.86%  |
| 101-250        | 3         | 10.34%  |
| 21-50          | 2         | 6.9%    |
| More than 3000 | 1         | 3.45%   |
| 2001-3000      | 1         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)

![Malfunc. Drives](./images/line_chart_bsd/drive_malfunc.svg)

| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD7500AACS-00ZJB0 752GB   | 1         | 1      | 11.11%  |
| WDC WD15EARS-00Z5B1 1.5TB     | 1         | 1      | 11.11%  |
| Toshiba MQ01ACF032 320GB      | 1         | 1      | 11.11%  |
| Toshiba MK5065GSX 500GB       | 1         | 1      | 11.11%  |
| OCZ VERTEX3 120GB             | 1         | 1      | 11.11%  |
| Kingston SMS200S330G 32GB     | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB      | 1         | 1      | 11.11%  |
| Corsair Force LS SSD 120GB    | 1         | 1      | 11.11%  |
| A-DATA Technology SP550 480GB | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)

![Malfunc. Drive Vendor](./images/line_chart_bsd/drive_malfunc_vendor.svg)

| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 25%     |
| WDC               | 1         | 2      | 12.5%   |
| OCZ               | 1         | 1      | 12.5%   |
| Kingston          | 1         | 1      | 12.5%   |
| HGST              | 1         | 1      | 12.5%   |
| Corsair           | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)

![Malfunc. HDD Vendor](./images/line_chart_bsd/drive_malfunc_hdd_vendor.svg)

| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| WDC     | 1         | 2      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)

![Malfunc. Drive Kind](./images/line_chart_bsd/drive_malfunc_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 50%     |
| HDD  | 4         | 5      | 50%     |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)

![Drive Status](./images/line_chart_bsd/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 16        | 29     | 48.48%  |
| Detected | 9         | 18     | 27.27%  |
| Malfunc  | 8         | 9      | 24.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)

![Storage Vendor](./images/line_chart_bsd/storage_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 25        | 71.43%  |
| AMD                       | 3         | 8.57%   |
| Toshiba                   | 2         | 5.71%   |
| Samsung Electronics       | 2         | 5.71%   |
| Micron/Crucial Technology | 1         | 2.86%   |
| Broadcom / LSI            | 1         | 2.86%   |
| ADATA Technology          | 1         | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)

![Storage Model](./images/line_chart_bsd/storage_model.svg)

| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 3         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 7.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 7.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 5.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 2         | 5.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 5.13%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 5.13%   |
| Toshiba unknown                                                                        | 1         | 2.56%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 2.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 2.56%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 2.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 2.56%   |
| Intel Platform Controller Hub EG20T SATA AHCI Controller                               | 1         | 2.56%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 2.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 1         | 2.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 2.56%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 2.56%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                         | 1         | 2.56%   |
| AMD 500 Series Chipset SATA Controller                                                 | 1         | 2.56%   |
| ADATA Technology unknown                                                               | 1         | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)

![Storage Kind](./images/line_chart_bsd/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 22        | 59.46%  |
| IDE  | 8         | 21.62%  |
| NVMe | 6         | 16.22%  |
| RAID | 1         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)

![CPU Vendor](./images/line_chart_bsd/cpu_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 26        | 89.66%  |
| AMD    | 3         | 10.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)

![CPU Model](./images/line_chart_bsd/cpu_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                      | 4         | 13.79%  |
| Intel Core i5-3320M CPU @ 2.60GHz                      | 2         | 6.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz                      | 2         | 6.9%    |
| Intel Xeon CPU X5675 @ 3.07GHz                         | 1         | 3.45%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                    | 1         | 3.45%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                     | 1         | 3.45%   |
| Intel Genuine CPU T2300 @ 1.66GHz                      | 1         | 3.45%   |
| Intel Genuine CPU @ 1.00GHz ("GenuineIntel" 686-class) | 1         | 3.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz                      | 1         | 3.45%   |
| Intel Core i7-3520M CPU @ 2.90GHz                      | 1         | 3.45%   |
| Intel Core i5-3570K CPU @ 3.40GHz                      | 1         | 3.45%   |
| Intel Core i5-2540M CPU @ 2.60GHz                      | 1         | 3.45%   |
| Intel Core i5 CPU M 540 @ 2.53GHz                      | 1         | 3.45%   |
| Intel Core i3-7130U CPU @ 2.70GHz                      | 1         | 3.45%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz                   | 1         | 3.45%   |
| Intel Core 2 CPU T7400 @ 2.16GHz                       | 1         | 3.45%   |
| Intel Core 2 CPU T5600 @ 1.83GHz                       | 1         | 3.45%   |
| Intel Celeron N5105 @ 2.00GHz                          | 1         | 3.45%   |
| Intel Celeron CPU J1900 @ 1.99GHz                      | 1         | 3.45%   |
| Intel Atom CPU N280 @ 1.66GHz                          | 1         | 3.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz                | 1         | 3.45%   |
| AMD Ryzen 9 5950X 16-Core Processor                    | 1         | 3.45%   |
| AMD GX-412TC SOC                                       | 1         | 3.45%   |
| AMD A6-3400M APU with Radeon HD Graphics               | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)

![CPU Model Family](./images/line_chart_bsd/cpu_family.svg)

| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 11        | 37.93%  |
| Intel Xeon       | 2         | 6.9%    |
| Intel Genuine    | 2         | 6.9%    |
| Intel Core i7    | 2         | 6.9%    |
| Intel Core 2     | 2         | 6.9%    |
| Intel Celeron    | 2         | 6.9%    |
| Other            | 1         | 3.45%   |
| Intel Pentium 4  | 1         | 3.45%   |
| Intel Core i3    | 1         | 3.45%   |
| Intel Core 2 Duo | 1         | 3.45%   |
| Intel Atom       | 1         | 3.45%   |
| AMD Ryzen 9      | 1         | 3.45%   |
| AMD GX           | 1         | 3.45%   |
| AMD A6           | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)

![CPU Cores](./images/line_chart_bsd/cpu_cores.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 12        | 41.38%  |
| 4       | 7         | 24.14%  |
| Unknown | 7         | 24.14%  |
| 6       | 2         | 6.9%    |
| 32      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)

![CPU Sockets](./images/line_chart_bsd/cpu_sockets.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 25        | 86.21%  |
| Unknown | 4         | 13.79%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)

![CPU Threads](./images/line_chart_bsd/cpu_threads.svg)

| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 15        | 51.72%  |
| 1       | 7         | 24.14%  |
| Unknown | 7         | 24.14%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)

![CPU Microarch](./images/line_chart_bsd/cpu_microarch.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| SandyBridge | 5         | 17.24%  |
| Westmere    | 4         | 13.79%  |
| IvyBridge   | 4         | 13.79%  |
| KabyLake    | 2         | 6.9%    |
| Core        | 2         | 6.9%    |
| Bonnell     | 2         | 6.9%    |
| Zen 3       | 1         | 3.45%   |
| TigerLake   | 1         | 3.45%   |
| Skylake     | 1         | 3.45%   |
| Silvermont  | 1         | 3.45%   |
| Puma        | 1         | 3.45%   |
| Penryn      | 1         | 3.45%   |
| P6          | 1         | 3.45%   |
| NetBurst    | 1         | 3.45%   |
| K10 Llano   | 1         | 3.45%   |
| Unknown     | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)

![GPU Vendor](./images/line_chart_bsd/gpu_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 20        | 68.97%  |
| AMD                        | 5         | 17.24%  |
| Nvidia                     | 2         | 6.9%    |
| Matrox Electronics Systems | 1         | 3.45%   |
| ASPEED Technology          | 1         | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)

![GPU Model](./images/line_chart_bsd/gpu_model.svg)

| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 15.63%  |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 9.38%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 9.38%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 6.25%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                       | 1         | 3.13%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 3.13%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 1         | 3.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 3.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 3.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 3.13%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 3.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1         | 3.13%   |
| Intel HD Graphics 620                                                         | 1         | 3.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 3.13%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 3.13%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 1         | 3.13%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 3.13%   |
| AMD RV530/M56-P [Mobility Radeon X1600]                                       | 1         | 3.13%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                         | 1         | 3.13%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 3.13%   |
| AMD Caicos PRO [Radeon HD 7450]                                               | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)

![GPU Combo](./images/line_chart_bsd/gpu_combo.svg)

| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 55.17%  |
| 2 x Intel      | 3         | 10.34%  |
| 1 x AMD        | 3         | 10.34%  |
| Other          | 2         | 6.9%    |
| 2 x AMD        | 1         | 3.45%   |
| 1 x Nvidia     | 1         | 3.45%   |
| Intel + Nvidia | 1         | 3.45%   |
| 1 x ASPEED     | 1         | 3.45%   |
| AMD + Matrox   | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)

![GPU Driver](./images/line_chart_bsd/gpu_driver.svg)

| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 23        | 79.31%  |
| Unknown | 6         | 20.69%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)

![GPU Memory](./images/line_chart_bsd/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)

![Monitor Vendor](./images/line_chart_bsd/mon_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 4         | 23.53%  |
| Samsung Electronics     | 3         | 17.65%  |
| LG Display              | 2         | 11.76%  |
| Lenovo                  | 2         | 11.76%  |
| Acer                    | 2         | 11.76%  |
| Philips                 | 1         | 5.88%   |
| Chi Mei Optoelectronics | 1         | 5.88%   |
| Apple                   | 1         | 5.88%   |
| Ancor Communications    | 1         | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)

![Monitor Model](./images/line_chart_bsd/mon_model.svg)

| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                        | 2         | 11.76%  |
| Samsung Electronics S24E650 SAM0CC3 1920x1200 520x320mm 24.0-inch        | 1         | 5.88%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 5.88%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 5.88%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 1         | 5.88%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch              | 1         | 5.88%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 5.88%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 5.88%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 1         | 5.88%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 5.88%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch           | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO34EB 3840x2160 340x190mm 15.3-inch           | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 5.88%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 5.88%   |
| Apple LCD Monitor APP9C73 1280x800 290x180mm 13.4-inch                   | 1         | 5.88%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch    | 1         | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)

![Monitor Resolution](./images/line_chart_bsd/mon_resolution.svg)

| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 6         | 35.29%  |
| 1366x768 (WXGA)   | 4         | 23.53%  |
| 1600x900 (HD+)    | 3         | 17.65%  |
| 3840x2160 (4K)    | 1         | 5.88%   |
| 1920x1200 (WUXGA) | 1         | 5.88%   |
| 1400x1050         | 1         | 5.88%   |
| 1280x800 (WXGA)   | 1         | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart_bsd/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 35.29%  |
| 13     | 4         | 23.53%  |
| 21     | 3         | 17.65%  |
| 24     | 1         | 5.88%   |
| 23     | 1         | 5.88%   |
| 14     | 1         | 5.88%   |
| 12     | 1         | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)

![Monitor Width](./images/line_chart_bsd/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 52.94%  |
| 401-500     | 3         | 17.65%  |
| 201-300     | 3         | 17.65%  |
| 501-600     | 2         | 11.76%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)

![Aspect Ratio](./images/line_chart_bsd/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 82.35%  |
| 16/10 | 2         | 11.76%  |
| 4/3   | 1         | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)

![Monitor Area](./images/line_chart_bsd/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 4         | 23.53%  |
| 101-110        | 4         | 23.53%  |
| 91-100         | 3         | 17.65%  |
| 201-250        | 2         | 11.76%  |
| 151-200        | 2         | 11.76%  |
| 61-70          | 1         | 5.88%   |
| 251-300        | 1         | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)

![Pixel Density](./images/line_chart_bsd/mon_density.svg)

| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 6         | 35.29%  |
| 101-120       | 6         | 35.29%  |
| 51-100        | 4         | 23.53%  |
| More than 240 | 1         | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)

![Multiple Monitors](./images/line_chart_bsd/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23        | 79.31%  |
| 0     | 6         | 20.69%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)

![Net Controller Vendor](./images/line_chart_bsd/net_vendor.svg)

| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 22        | 62.86%  |
| Realtek Semiconductor             | 7         | 20%     |
| Qualcomm Atheros                  | 3         | 8.57%   |
| Marvell Technology Group          | 1         | 2.86%   |
| Ericsson Business Mobile Networks | 1         | 2.86%   |
| Broadcom                          | 1         | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)

![Net Controller Model](./images/line_chart_bsd/net_model.svg)

| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 8         | 15.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 7         | 13.73%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 4         | 7.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 5.88%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 5.88%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 2         | 3.92%   |
| Intel I210 Gigabit Network Connection                                       | 2         | 3.92%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 3.92%   |
| Intel 82579V Gigabit Network Connection                                     | 2         | 3.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1         | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                           | 1         | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.96%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.96%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.96%   |
| Intel Wireless-AC 9260                                                      | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.96%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller             | 1         | 1.96%   |
| Intel I350 Gigabit Network Connection                                       | 1         | 1.96%   |
| Intel I226-V                                                                | 1         | 1.96%   |
| Intel 82576 Gigabit Network Connection                                      | 1         | 1.96%   |
| Intel 82574L Gigabit Network Connection                                     | 1         | 1.96%   |
| Intel 82573L Gigabit Ethernet Controller                                    | 1         | 1.96%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.96%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                    | 1         | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart_bsd/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 78.95%  |
| Realtek Semiconductor | 2         | 10.53%  |
| Qualcomm Atheros      | 2         | 10.53%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)

![Wireless Model](./images/line_chart_bsd/net_wireless_model.svg)

| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 40%     |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 15%     |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 2         | 10%     |
| Intel Centrino Advanced-N 6200                                 | 2         | 10%     |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 5%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 5%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 5%      |
| Intel Wireless-AC 9260                                         | 1         | 5%      |
| Intel Wi-Fi 6 AX201                                            | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart_bsd/net_ethernet_vendor.svg)

| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 64.29%  |
| Realtek Semiconductor    | 6         | 21.43%  |
| Qualcomm Atheros         | 2         | 7.14%   |
| Marvell Technology Group | 1         | 3.57%   |
| Broadcom                 | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart_bsd/net_ethernet_model.svg)

| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 23.33%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 13.33%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 10%     |
| Intel I210 Gigabit Network Connection                             | 2         | 6.67%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 3.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.33%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.33%   |
| Intel Platform Controller Hub EG20T Gigabit Ethernet Controller   | 1         | 3.33%   |
| Intel I350 Gigabit Network Connection                             | 1         | 3.33%   |
| Intel I226-V                                                      | 1         | 3.33%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 3.33%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.33%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 3.33%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)

![Net Controller Kind](./images/line_chart_bsd/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 58.33%  |
| WiFi     | 19        | 39.58%  |
| Unknown  | 1         | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)

![Used Controller](./images/line_chart_bsd/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 58.62%  |
| Ethernet | 12        | 41.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)

![NICs](./images/line_chart_bsd/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 19        | 65.52%  |
| 1     | 6         | 20.69%  |
| 4     | 2         | 6.9%    |
| 5     | 1         | 3.45%   |
| 3     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)

![IPv6](./images/line_chart_bsd/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart_bsd/bt_vendor.svg)

| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Broadcom                | 4         | 30.77%  |
| Intel                   | 2         | 15.38%  |
| Foxconn / Hon Hai       | 2         | 15.38%  |
| Alps Electric           | 2         | 15.38%  |
| Hewlett-Packard         | 1         | 7.69%   |
| Cambridge Silicon Radio | 1         | 7.69%   |
| ASUSTek Computer        | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)

![Bluetooth Model](./images/line_chart_bsd/bt_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Broadcom BCM2045B (BDC-2.1)                              | 3         | 23.08%  |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 2         | 15.38%  |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 15.38%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 7.69%   |
| Intel AX201 Bluetooth                                    | 1         | 7.69%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1         | 7.69%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 1         | 7.69%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)

![Sound Vendor](./images/line_chart_bsd/snd_vendor.svg)

| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 22        | 78.57%  |
| AMD              | 3         | 10.71%  |
| VIA Technologies | 1         | 3.57%   |
| Nvidia           | 1         | 3.57%   |
| JMTek            | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)

![Sound Model](./images/line_chart_bsd/snd_model.svg)

| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 17.24%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 13.79%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3         | 10.34%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 10.34%  |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 1         | 3.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1         | 3.45%   |
| JMTek USB PnP Audio Device                                                        | 1         | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 3.45%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1         | 3.45%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 3.45%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1         | 3.45%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                          | 1         | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 3.45%   |
| AMD FCH Azalia Controller                                                         | 1         | 3.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 3.45%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)

![Memory Vendor](./images/line_chart_bsd/memory_vendor.svg)

| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 4         | 30.77%  |
| Samsung Electronics | 4         | 30.77%  |
| SK hynix            | 2         | 15.38%  |
| Micron Technology   | 1         | 7.69%   |
| Kingston            | 1         | 7.69%   |
| Unknown             | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)

![Memory Model](./images/line_chart_bsd/memory_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 14.29%  |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 7.14%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 7.14%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 7.14%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 7.14%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 7.14%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 7.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 7.14%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 7.14%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s | 1         | 7.14%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s  | 1         | 7.14%   |
| Unknown                                                | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)

![Memory Kind](./images/line_chart_bsd/memory_kind.svg)

| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR3  | 7         | 58.33%  |
| SDRAM | 2         | 16.67%  |
| DDR4  | 2         | 16.67%  |
| DDR2  | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart_bsd/memory_formfactor.svg)

| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 91.67%  |
| DIMM   | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)

![Memory Size](./images/line_chart_bsd/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 4         | 33.33%  |
| 2048  | 4         | 33.33%  |
| 32768 | 1         | 8.33%   |
| 16384 | 1         | 8.33%   |
| 1024  | 1         | 8.33%   |
| 512   | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)

![Memory Speed](./images/line_chart_bsd/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3         | 25%     |
| 1334    | 2         | 16.67%  |
| 1333    | 2         | 16.67%  |
| 1067    | 2         | 16.67%  |
| 2667    | 1         | 8.33%   |
| 2400    | 1         | 8.33%   |
| 1600    | 1         | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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

| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 5         | 50%     |
| Sunplus Innovation Technology | 1         | 10%     |
| Ricoh                         | 1         | 10%     |
| Lenovo                        | 1         | 10%     |
| Alcor Micro                   | 1         | 10%     |
| Acer                          | 1         | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)

![Camera Model](./images/line_chart_bsd/camera_model.svg)

| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony integrated camera                | 2         | 20%     |
| Sunplus Integrated_Webcam_FHD            | 1         | 10%     |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 10%     |
| Lenovo Integrated Webcam [R5U877]        | 1         | 10%     |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 10%     |
| Chicony FJ Camera                        | 1         | 10%     |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 10%     |
| Alcor Micro ASUS USB2.0 WebCam           | 1         | 10%     |
| Acer Integrated Camera                   | 1         | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)

![Fingerprint Vendor](./images/line_chart_bsd/fingerprint_vendor.svg)

| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Upek                       | 3         | 42.86%  |
| AuthenTec                  | 2         | 28.57%  |
| STMicroelectronics         | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)

![Fingerprint Model](./images/line_chart_bsd/fingerprint_model.svg)

| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 42.86%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 14.29%  |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 14.29%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 14.29%  |

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
| 1     | 16        | 55.17%  |
| 2     | 5         | 17.24%  |
| 0     | 4         | 13.79%  |
| 5     | 2         | 6.9%    |
| 4     | 1         | 3.45%   |
| 3     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart_bsd/device_unsupported_type.svg)

| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 18        | 45%     |
| Graphics card            | 7         | 17.5%   |
| Firewire controller      | 4         | 10%     |
| Storage/ata              | 2         | 5%      |
| Storage                  | 2         | 5%      |
| Sound                    | 2         | 5%      |
| Network                  | 2         | 5%      |
| Net/wireless             | 2         | 5%      |
| Net/ethernet             | 1         | 2.5%    |

