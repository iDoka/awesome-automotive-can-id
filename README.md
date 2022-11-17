# Awesome CAN Bus Databases By Car Vendors [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![GitHub stars](https://badgen.net/github/stars/iDoka/awesome-automotive-can-id)](https://GitHub.com/iDoka/awesome-automotive-can-id/stargazers/)
[![GitHub forks](https://badgen.net/github/forks/iDoka/awesome-automotive-can-id)](https://GitHub.com/iDoka/awesome-automotive-can-id/network/)
[![GitHub watchers](https://badgen.net/github/watchers/iDoka/awesome-automotive-can-id/)](https://GitHub.com/iDoka/awesome-automotive-can-id/watchers/)
[![GitHub contributors](https://badgen.net/github/contributors/iDoka/awesome-automotive-can-id)](https://GitHub.com/iDoka/awesome-automotive-can-id/graphs/contributors/)
[![GitHub pull-requests merged](https://badgen.net/github/merged-prs/iDoka/awesome-automotive-can-id)](https://github.com/iDoka/awesome-automotive-can-id/pulls?q=is%3Amerged)
[![GitHub latest commit](https://badgen.net/github/last-commit/iDoka/awesome-automotive-can-id)](https://GitHub.com/iDoka/awesome-automotive-can-id/commit/)





An attempt to collect info about CAN IDs and payloads for various car brands/models in one place.

Also might be useful [this curated list](https://github.com/iDoka/awesome-canbus) of awesome tools and resources for CAN bus reverse engineering with lightly specializing in automotive embedded controller software and communication understanding.

URL: https://github.com/iDoka/awesome-automotive-can-id

## Contents

DB by Brands/Models:

* [Common](#common)

* [Acura](#acura)
* [BMW](#bmw)
  * [iDrive](#idrive)
* [General Motors (Buick, Cadillac, Chevrolet, GMC)](#general-motors-buick-cadillac-chevrolet-gmc)
* [Daimler-Chrysler (Chrysler, Dodge, Jeep, RAM)](#daimler-chrysler-chrysler-dodge-jeep-ram)
  * [Jeep](#jeep)
* [Fiat](#fiat)
* [Ford (Lincoln, Mercury)](#ford-lincoln-mercury)
* [Honda](#honda)
* [Hyundai](#hyundai)
* [Infiniti](#infiniti)
* [Jaguar](#jaguar)
* [Kia](#kia)
* [Land Rover](#land-rover)
* [Lexus](#lexus)
* [Lotus](#lotus)
* [Mazda](#mazda)
* [Mercedes-Benz](#mercedes-benz)
* [MINI](#mini)
* [Mitsubishi](#mitsubishi)
* [Nissan](#nissan)
* [Opel](#opel)
* [PSA (Peugeot, Citroen, DS)](#psa-peugeot-citroen-ds)
  * [Citroen](#citroen)
  * [Peugeot](#peugeot)
  * [DS](#ds)
* [Renault](#renault)
* [SAAB](#saab)
* [Subaru](#subaru)
* [Suzuki](#suzuki)
* [Tesla](#tesla)
* [Toyota](#toyota)
* [VAG (Audi, Porsche, Volkswagen, Seat, Skoda)](#vag-audi-porsche-volkswagen-seat-skoda)
  * [Audi](#audi)
  * [Porsche](#porsche)
  * [Seat](#seat)
  * [Skoda](#skoda)
  * [Volkswagen](#volkswagen)
* [Volvo](#volvo)

* [Motorcycles](#motorcycles)
  * [BMW motorcycle](#bmw-motorcycle)
  * [Ducati](#ducati)
  * [KTM motorcycle](#ktm)

<!--lint disable no-repeat-punctuation-->

## Common

Links for general DB and uther useful resources:

* [Democratize access to car decoder rings by CommaAI](https://github.com/commaai/opendbc).
* [Vehicle Reverse Engineering Wiki](https://vehicle-reverse-engineering.fandom.com/wiki/Vehicle_Reverse_Engineering_Wiki).
* [Opengarages Raw link references for CAN IDs](http://opengarages.org/index.php/Raw_link_references_for_CAN_IDs).
* [RACELOGIC Vehicle CAN Database](https://www.vboxautomotive.co.uk/index.php/en/customer-area/vehicle-can-database).

## Acura


## BMW

* [BMW E65 7 Series Powertrain CAN bus](https://github.com/damienmaguire/BMW-E65-CANBUS).
* [BMW DBUS/IBUS/KBUS information/reference/examples](https://github.com/kmalinich/node-bmw-ref).
* [BMW CANBUS information/reference](https://github.com/kmalinich/node-bmw-ref/tree/master/canbus).



### iDrive

* [Arduino library for devices compatible with either avr_can or due_can, to interface with a BMW iDrive controller](https://github.com/thatdamnranga/iDrive).
* [iDrive controller 500k CAN speed (2004y late model)](https://github.com/Autohome2/idrive-controller).
* [Arduino canbus reader for events on iDrive knob controller](https://github.com/jegb/iDrive_knob).


## General Motors (Buick, Cadillac, Chevrolet, GMC)

* [Opengarages GM LAN 29 Bit ID](http://opengarages.org/index.php/GM_LAN_29_Bit_ID).
* [GM LAN bible](https://docs.google.com/spreadsheets/d/1qEwOXSr3bWoc2VUhpuIam236OOZxPc2hxpLUsV0xkn0/edit).
* [GMLAN CAN ID](https://github.com/karlyamashita/common_libraries/blob/master/GMLAN_CAN_ID.h).
* [GMLAN CAN ID v2](https://github.com/karlyamashita/common_libraries/blob/master/GMLAN_CAN_ID_V2.h).

## Daimler-Chrysler (Chrysler, Dodge, Jeep, RAM)

* [Opengarages Dodge CAN ID](http://opengarages.org/index.php/Dodge_CAN_ID).
* [Several CHRYSLER models CAN ID](https://github.com/karlyamashita/common_libraries/blob/master/CHRYSLER_CAN_ID.h).

### Jeep

* [Projects around CAN BUS in Chrysler Jeep - VES enabler, other small features](https://github.com/latonita/jeep-canbus).


## Fiat

* [Fiat 500](https://github.com/P1kachu/talking-with-cars/blob/master/notes/fiat-500.txt).
* Fiat 500L: [ID](https://github.com/VeryBusyBee/FiatMon/blob/master/Core/Inc/main.h) & [payload](https://github.com/VeryBusyBee/FiatMon/blob/master/Core/Src/obd.cpp).


## Ford (Lincoln, Mercury)

* ~~[Ford extended PIDs](https://knowhow.windstar-club.de/index.php/PID-Codes)~~.
<!--lint disable double-link-->
* [Ford Escape 2010 LTD with Active Park Assist](https://github.com/andrewraharjo/CAN-Bus-Hack_Prius_Focus).
<!--lint enable double-link-->
* [DBC files for Lincoln MKZ and Ford Fusion](https://github.com/autti/abraham).
* [FORD Mustang 2005 CAN 125k](https://github.com/karlyamashita/common_libraries/blob/master/FORD_CAN_ID.h).
* [Ford Fusion and Lincoln MKZ](https://github.com/autti/abraham/blob/master/lincoln_mkz.dbc).

### Fiesta
* [Ford Fiesta MK5 >2006 (MK5 restyling, Bus speed 125K)](https://github.com/roncapat/Ford-Fiesta-MK5-MS-CAN-bus).
* [Ford Fiesta MK7](https://docs.google.com/spreadsheets/d/1oTembZpwUSb6LsxbFklwt7mOIdheLecYU2B6ZJ6AhQs/edit#gid=0).
* [Ford Fiesta MK7.5](https://github.com/fereste/tablero/wiki/Ford-Fiesta-CAN-bus-description).

### Ford FG Falcon
* [Ford FG Falcon](https://github.com/jakka351/FG-Falcon/blob/master/6FPA.xlsx)
* [CANBus decoded](https://github.com/jakka351/FG-Falcon/blob/master/fg_controller_area_network_latest.xlsx).
* [Orion](https://github.com/jakka351/FG-Falcon#orion-canbus).

### Ford Transit
* [Ford Transit 2020](https://github.com/slyt/van-hack).


## Honda

* [Honda Civic 8th Gen](https://github.com/Knio/carhack/blob/master/Cars/Honda.markdown).


## Hyundai

* [Hyundai Solaris 2013 (RU)](https://www.drive2.ru/b/522073135831319435/).
* [Hyundai Veloster 2016](https://github.com/tylerwatt12/VelosterCANBus).
* [Hyundai Genesis 5.0 2015](https://github.com/joshpatten/HyundaiCan).
* [Hyundai Ioniq 5](https://github.com/Esprit1st/Hyundai-Ioniq-5-Torque-Pro-PIDs).


## Infiniti

* [Infiniti G37 2011](https://github.com/icecube45/Dash_InfinitiG37/blob/master/InfinitiG37.dbc).


## Jaguar

## Kia

* [Kia Soul](https://github.com/PolySync/OSCC).
* [Kia Soul OBD](https://github.com/PolySync/oscc/wiki/Firmware-OBD).
* [Kia Soul Steering](https://github.com/PolySync/oscc/wiki/Firmware-Steering).
* [Kia Soul Throttle](https://github.com/PolySync/oscc/wiki/Firmware-Throttle).
* [Kia Soul Brake-Petrol](https://github.com/PolySync/oscc/wiki/Firmware-Brake-%28Petrol%29).
* [Kia Soul Brake-EV](https://github.com/PolySync/oscc/wiki/Firmware-Brake-%28EV%29).
* [Kia EV](https://github.com/JejuSoul/OBD-PIDs-for-HKMC-EVs).

**Note**: Kia Soul (2014-...) - All KIA (without Picanto) 2014+ have same systems




## Land Rover

## Lexus


* [Lexus RX 450h (RU)](https://habr.com/ru/post/450140/).
* [Lexus RX350 2011 (RU)](https://github.com/Paucpauc/lexus_canbus_id).


## Lotus

## Mazda

* [Database of known Mazda (SkyActiv and RX-8) CAN messages](https://github.com/majbthrd/MazdaCANbus).
* [Opengarages Mazda CAN ID](http://opengarages.org/index.php/Mazda_CAN_ID).

## Mercedes-Benz

* [Mercedes-Benz-CAN-BUS](https://github.com/dvjcodec/Mercedes-Benz-CAN-BUS) - Understand and run units via CAN-bus network.
* [controller for 722.6 automatic transmission](https://github.com/mkovero/7226ctrl).
* [W203-canbus](https://github.com/rnd-ash/W203-canbus) - Open source project for W211/W219 W203/W209 Mercs (bluetooth audio control and more).
* [W203 canbus](https://docs.google.com/spreadsheets/d/1krPDmjjwmlta4jAVcDMoWbseAokUYnBAHn67pOo00C0/edit#gid=2038710733).
* [W203 C200 CDI](https://github.com/rnd-ash/ultimate_nag52/tree/main/firmware/canframes) - Should theoretically work on W203/w209/w211/w219 vehicles.
* [Mercedes 2000-2007](https://github.com/rnd-ash/MBUX-Port) - See txt files with canbus desciption (tested on W203 C200 CDI, but in theory, any W203/211/219/209 should work).


## MINI

* [Mini Cooper 2002-2006](https://github.com/equinox311/open-can-db/raw/master/2002-2006_mini_cooper_all.xlsx).

## Mitsubishi

* [Mitsubishi Lancer 2008 (RU)](https://habr.com/ru/post/448658/).


## Nissan

* [Various Nissan models (Nissan LEAF and around)](https://docs.google.com/spreadsheets/d/1EHa4R85BttuY4JZ-EnssH4YZddpsDVu6rUFm0P7ouwg/edit#gid=1).

* [Nissan Sentra 2010](https://github.com/jackm/carhack/blob/master/nissan.md).
* [Nissan 370Z 2010](https://github.com/Knio/carhack/blob/master/Cars/Nissan.markdown).
* [LEAF CAN bus message decoding with proper database files](https://github.com/dalathegreat/leaf_can_bus_messages).
* [Some Logs from my Gen 1 Nissan Leaf](https://github.com/damienmaguire/LeafLogs).
* [Nissan LEAF](https://github.com/dalathegreat/EV-CANlogs/tree/main/Nissan%20LEAF).
* [Nissan LEAF #2](https://leaf-obd.readthedocs.io/en/latest/pid/index.html).


## Opel

* [Opel Astra H](https://github.com/alex161rus/Opel-Astra-H).
* [Opel Astra H climate](https://github.com/megadrifter/AstraH_climate/blob/master/AstraH_climate.ino).
* [Opel Astra H DB](https://github.com/Trueffelwurm/Car-CAN-Message-DB).
* [Opel Astra H (LS CAN, MS CAN)](https://github.com/megadrifter/Astra-H-Public).


## PSA (Peugeot, Citroen, DS)

### Citroen

### Peugeot

temporaly unsorted:

<!--

* https://github.com/ludwig-v
* https://github.com/ludwig-v/psa-seedkey-algorithm
* https://github.com/prototux/PSA-RE
* https://github.com/prototux/PSA-RE/blob/master/sandbox/uds_auth_algorithm.c
* https://github.com/prototux/PSA-RE/blob/master/sandbox/immobilizer_algorithm.c
* https://github.com/morcibacsi?tab=repositories

-->

### DS



## Renault

* [Renault Zoe CAN ID](https://github.com/ashtorak/CanSeeNoiseGen/blob/main/src/zoe.cpp).

## SAAB

## Subaru

* [Subaru Legacy 2005-2009](https://github.com/equinox311/open-can-db/raw/master/2005-2008_subaru_legacy_gt.xlsx).
* [Subaru BRZ 2013+](https://github.com/equinox311/open-can-db/raw/master/2013%2B_subaru_brz.xlsx).
* [Subaru Impreza WRX STi 2015+](https://github.com/equinox311/open-can-db/raw/master/2015%2B_subaru_impreza_sti.xlsx).


## Suzuki

* [Suzuki Swift IV AZG 1.3 DDiS 16V 75cv](https://github.com/P1kachu/talking-with-cars/blob/master/notes/suzuki-swift-IV.txt).



## Tesla

* [Tesla Model 3 CAN IDs and payload](https://docs.google.com/spreadsheets/d/1ijvNE4lU9Xoruvcg5AhUNLKr7xYyHcxa8YSkTxAERUw/edit#gid=0).
* [DBC file for Tesla Model 3 CAN messages](https://github.com/joshwardell/model3dbc).
* [Tesla Model S/X CAN IDs and payload](https://docs.google.com/spreadsheets/d/1UBHw2eY3QyJL3vUz0CnTZ7iLlLB-ao5s61hexT0GuHM/edit#gid=0).

## Toyota


* [TIS Document Ripper](https://github.com/threadproc/tis-rip) - Script allows you to rip electrical wiring diagrams, collision/body repair manuals, and repair manuals from Toyota's TIS.
* [Toyota Prius gen2](https://github.com/gerdbremer/Prius-gen2-torque-PIDs).
<!--lint disable double-link-->
* [Toyota Prius 2010 with Intelligent Parking Assist](https://github.com/andrewraharjo/CAN-Bus-Hack_Prius_Focus).
<!--lint enable double-link-->
* [Arduino emulating a CD Changer on a Toyota AVC LAN network](https://github.com/halleysfifthinc/Toyota-AVC-LAN).
* [Arduino emulating a CD Changer on a Toyota AVC LAN network (another project)](https://github.com/instalator/AVC-LAN-Toyota).
* [Toyota Prius CAN message translator](https://github.com/HbirdJ/CAN-Translator).
* [Opengarages Toyota CAN ID](http://opengarages.org/index.php/Toyota_CAN_ID).
* [Toyota Yaris](https://github.com/P1kachu/talking-with-cars/blob/master/notes/toyota-yaris.md).
* [Toyota 2018 Tacoma](https://github.com/karlyamashita/common_libraries/blob/master/TOYOTA_CAN_ID.h).

## VAG (Audi, Porsche, Volkswagen, Seat, Skoda)


### Audi

* [Audi Q8 2019](https://github.com/robbederks/q8_flexray_dumps) - RAW dumps + decoded frames of the EPS FlexRay bus.
* [Audi e-tron](https://github.com/bradarnold/e-tron_OBD2ABRP/blob/main/OBD/main.py).

### Porsche

### Seat

### Skoda

* [Skoda Octavia A5 2011 (RU)](https://habr.com/ru/post/442184/).


### Volkswagen

* [Volkswagen drivetrain CAN bus IDs](https://github.com/v-ivanyshyn/parse_can_logs/blob/master/VW%20CAN%20IDs%20Summary.md).
* [MQB platform (MK7 VW Golf R, GTI, 1.8, Audi S3/A3, etc)](https://github.com/bri3d/MQBSimosLogVariables/blob/master/exportedPIDs.csv).
* [VW Touran 2004](https://github.com/jsphuebner/stm32-car#can-configuration-vw).
* [Volkswagen Polo R6](https://github.com/P1kachu/talking-with-cars/blob/master/notes/vw-polo-r6.txt).
* [Volkswagen Polo R6](https://github.com/P1kachu/talking-with-cars/tree/master/docs).
* [VW_CAN_ID](https://github.com/karlyamashita/common_libraries/blob/master/VW_CAN_ID.h).
* [Volkswagen e-Golf](https://github.com/dalathegreat/EV-CANlogs/tree/main/Volkswagen%20e-Golf).
* [Volkswagen e-Golf #2](https://github.com/EVNotify/EVNotify/blob/master/app/www/components/cars/E_GOLF.vue).
* [Volkswagen Golf GTI MK5](https://docs.google.com/spreadsheets/d/1eirT8LbSRl4j06BpwgsiE4PM_2BGH9UStdWLXwKvHJw/edit).
* [Volkswagen MEB EV (like ID.3 ID.4, Enyaq) UDS PIDs](https://github.com/spot2000/Volkswagen-MEB-EV-CAN-parameters/blob/main/VW%20MEB%20UDS%20PIDs%20list.csv).
* [VW e-Up](https://www.goingelectric.de/wiki/Liste-der-OBD2-Codes/).


## Volvo

* [Volvo XC70 2.5T 2005 B5254T2+AW55](https://github.com/vtl/volvo-ddd/blob/master/data/2005_xc70_b5254t2_aw55_us.h).
* [Volvo C30 T5 2011 Codes](https://github.com/Alfaa123/Volvo-CAN-Gauge/blob/master/Codes.txt).
* [Volvo C30 T5 2011 LowSpeed CAN](https://github.com/Alfaa123/Volvo-CAN-Gauge/blob/master/Sniffing/Low%20Speed.cmt).
* [Volvo C30 T5 2011 HighSpeed CAN](https://github.com/Alfaa123/Volvo-CAN-Gauge/blob/master/Sniffing/High%20Speed.cmt).
* [Volvo V60 2015](https://github.com/commaai/opendbc/blob/master/volvo_v60_2015_pt.dbc).
* [Volvo C30 1.6d DRIVe](https://paul.sullivan.za.org/volvo-c30-1.6d/OBD-II_CAN-bus/).
* [Arduino CANBUS Volvo S60 DPF soot filter](https://github.com/waal70/S60CAN).
* [Volvo XC90 CAN bus adapter to restore wheel buttons and park assistant functionality](https://github.com/olegel/VolvoCan).
* [Volvo XC90 CAN bus: CCM, CEM, TCM, LSM, REM, SWM](https://github.com/olegel/VolvoCan/tree/master/doc/VolvoModules).
* [Volvo S60R 2007 DIM](https://github.com/andrewgabler/VolvoDIM/tree/master/Research) - Project to power a volvo DIM outside of the car.
* [Volvo S60R 2007 DIM](https://github.com/andrewgabler/VolvoDIM/blob/master/Research/Notes%20on%20CANBUS) - Notes on CANBUS.
* [Volvo S60 MY2009, aka P2 facelift model](https://github.com/waal70/VolvoCANBUS).
* [BUSMaster files for emulation of Climate Control Module used in Volvo P1 platform (C30,C70,S40,V50)](https://github.com/johnbutol/CCM-busmaster/tree/master/SimulatedSystems/ccm).
* [BUSMaster files for emulation of Central Electronics Module](https://github.com/johnbutol/CCM-busmaster/tree/master/SimulatedSystems/cem).
* [OBD-II CAN Data Extraction and Analysis from Volvo S60](https://github.com/ezkripke/volvo-CAN-exploration).
* [Volvo P3 PIDs (RU)](https://docs.google.com/spreadsheets/d/10vq5NIZu0Sd2SSoK2_YSrcsWrItZNC0X2rPcIWvLuS8/edit#gid=542587416).


---

## Motorcycles

### BMW motorcycle

* [BMW Motorrad CAN messages](https://docs.google.com/spreadsheets/d/1tUrOES5fQZa92Robr6uP8v2dzQDq9ohHjUiTU3isqdc/edit).

### Ducati

* [Collective decoding of Ducati CANBUS messages](https://docs.google.com/spreadsheets/d/1-NJ9OlGQYTGMzBzwDPYn-aI_7_ign9SCiscKZufx3Uw/edit?pli=1#gid=1950998351).
* [Ducati Panigale (899/959/1199/1199S/1199R/1299/1299S/R and Superleggera)](https://github.com/renatobo/DucatiPanigaleCanBus).

### KTM

* [Python library for decoding KTM motorcycle CAN-bus messages](https://github.com/blalor/ktm-can).


---
<!--lint enable no-repeat-punctuation-->

## etc

Please follow [this](https://github.com/iDoka/awesome-automotive-can-id) root-repo for lastest updates.


## Contributing

* Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.


## Tags

#awesome
#awesome-list
#can
#can-bus
#canbus
#logger
#sniffer
#socketcan
#car-hacking
#bus-monitoring
#lawicel
#elm327
#obd2
#canutils
#automotive
#embedded
#sae
#uds
#obd-ii
#usb2can
#dbc
#electric-vehicles
#vehicular-networks
#python
#automotive-security


