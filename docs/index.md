## About me

My name is [Raghu](https://in.linkedin.com/in/raghunathkumar) ([/rʌgu:/](https://raghu-rana.gitlab.io/../supportFiles/0_Raghu.wav)), a.k.a. RaNa ([/rʌ:a-na/](https://raghu-rana.gitlab.io/../supportFiles/1_RaNa.wav)). I graduated from [IIT Madras](http://www.iitm.ac.in/) in 2007 with a [dual degree](https://www.iitm.ac.in/academic-programmes) (B.Tech. + M.Tech.) in [Electrical Engineering](http://www.ee.iitm.ac.in/). 

## Professional Experience
### [TVS Motor](https://www.tvsmotor.com/) [Sep15-On Going]

**Electric Machines &  Optimization**

This work is a combination of my long standing passions, electric motors and optimization. Part of this work resulted in a technical presentation at [SAE World Congress](https://www.sae.org/wcx) 2017 in Detroit (MI, USA), about the optimization methods for electric machines for engine starter application. Few patent applications about electric machine technology ([201641038223](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [201641038846](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [201641038845](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [201641038844](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [201741005098](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [201741012184](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [201741012185](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch)) are pending decision. 

I work on design automation & optimization for electric machine development with both the open-source and commercial electromagnetic FEA software. My personal interest is in using the open-source electromagnetic FEA software such as [FEMM](http://www.femm.info/wiki/HomePage), [Onelab(Gmsh/GetDP)](http://www.onelab.info/), and [Elmer](https://www.csc.fi/web/elmer) together with [Scilab](https://www.scilab.org/). I use Scilab as a base platform to implement design automation in other software which results in dramatic reduction in the model creation time. Using these models, and the optimization methods (I use the variant of gradient descent algo developed by myself to detect the global maximum), I arrive at a best possible design for a given set of specifications. More details about the tool's capabilities are [here](https://motorrlib.gitlab.io/).

**Machine Learning & Computer Vision**

I worked on understanding the basic principles of machine learning and implemented few projects and documented them in [this blog](https://saras152.github.io/). 

**Bootloader**

I worked on Bootloader specific to automotive systems with constrained memory resources and it resulted in a technical presentation at [SAE World Congress](https://www.sae.org/wcx) 2017 in Detroit (MI, USA).

### [MathWorks](https://in.mathworks.com/) [Jun14-Sep15]

**Code Generation with Bootloader**

I worked on [Embedded Coder Support Package](https://www.mathworks.com/help/supportpkg/armcortexm/index.html) for ST Microelectronics ([Nucleo](https://www.st.com/en/evaluation-tools/stm32-mcu-nucleo.html) and [Discovery](https://www.st.com/en/evaluation-tools/stm32-mcu-discovery-kits.html)) and Texas Instruments ([Piccolo F2869](http://www.ti.com/product/TMS320F28069)) processors. This effort resulted in successful implementation of a [modular two-stage bootloader](https://bitbucket.org/saras152/bootloader/wiki/blstages) ([help text](https://in.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ref/build-for-use-with-bootloader.html), [GUI](https://in.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ref/model-configuration-parameters-for-stmicroelectronics-stm32f4-discovery-board.html)) for ARM cortex-M based processors.  My contribution is hidden behind the checkbox "*[Build for use with bootloader](https://www.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ref/build-for-use-with-bootloader.html)*" below the *Build Actions* drop-down menu in the *Target Hardware Resources* pane. 


### [TVS Motor](https://www.tvsmotor.com/) [Aug07-Jun14]

**Anti-lock Braking System**

I worked on [Anti-Lock Braking System](https://en.wikipedia.org/wiki/Anti-lock_braking_system) for 2-wheeler systems resulting in my involvement for the India's first ABS equipped motorcycle [TVS Apache RTR 180 ABS](https://www.tvsapache.com/rtr-180.aspx). This work resulted in a technical presentation at [Eurobrake](https://www.eurobrake.net/) 2012 in Dresden, Germany. My work also resulted in the grant of the [*Indian patent* 280720](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch). Few more patent applications related to ABS technologies ([3098/CHE/2009](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [3449/CHE/2010](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [1002/CHE/2011](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch), [1001/CHE/2011](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch)) are pending decision.

**Other Projects**

* I worked on Fuel cell - Battery Hybrid system's control and it resulted in a technical presentation at [Fuel Cell Seminar and Energy Exposition](https://www.fuelcellseminar.com/) 2011 in Orlando, Florida, USA. 
* I worked on embedded software for [Battery Management System](https://en.wikipedia.org/wiki/Battery_management_system) for 2-wheeler (H)EV systems with cell monitoring and passive balancing of Li-ion cells.
* I worked on portable data acquisition system design including the embedded [FAT16](https://bitbucket.org/saras152/filesystem_fat/wiki/FAT%2016) & [FAT32](https://bitbucket.org/saras152/filesystem_fat/wiki/Home) drivers for writing the data on [SD card](https://bitbucket.org/saras152/filesystem_fat/wiki/SD%20CARD) and worked on embedded [USB Host drivers](https://bitbucket.org/saras152/usbhost_embedded/wiki/Home) for writing the data on USB flash memory using [Renesas Rx621](https://www.renesas.com/in/en/products/microcontrollers-microprocessors/rx/rx600/rx621-62n.html) platform.

### [Honeywell](https://www.honeywell.com/worldwide/en-in) [May06-May07]

**Motor Controller**

I supported the motor controller team in developing their in-house project titled Next Generation Low Cost Motor Controller (NGLCMC). Created Simulink models of Sine and Space-Vector PWM for MBD and simulations. Contributed to hardware development of gate driver circuits and PCB development. Participated in board bring-up and functional testing of the hardware to run the motor successfully.


## Computer Skills
### Languages
* Very comfortable with C for modular embedded applications to implement complex control algorithms and write device drivers in bare metal code.
    * Ported the complete BMS project code from old to new µC of new manufacturer in less than 5 days.
* Very comfortable with scripting in Scilab, MATLAB and Python
    * Developed my [design automation and optimization tool](https://motorrlib.gitlab.io/) from scratch in these environments.
* Comfortable with vb.net programming for implementing logic and creating GUI applications
    * Built applications for diagnostics during the ABS project development, and Data Acquisition tool development.
### Micro-controller platforms
* Worked with the following micro-controller platforms - using both [bare metal](https://en.wikipedia.org/wiki/Bare_machine) programming and [HAL](https://en.wikipedia.org/wiki/Hardware_abstraction)s. Exposure to [RTOS](https://en.wikipedia.org/wiki/Real-time_operating_system) is minimal.
    * Microchip ([8-bit](https://www.microchip.com/design-centers/8-bit) and [16-bit](https://www.microchip.com/design-centers/16-bit) PIC series)
    * Renesas ([RX](https://www.renesas.com/in/en/products/microcontrollers-microprocessors/rx.html), [M16C](https://www.renesas.com/in/en/products/microcontrollers-microprocessors/m16c.html), [R8C](https://www.renesas.com/in/en/products/microcontrollers-microprocessors/r8c.html) series)
    * Freescale (Now NXP: [S32](https://www.nxp.com/products/processors-and-microcontrollers/arm-based-processors-and-mcus/s32-automotive-platform:S32), [S12](https://www.nxp.com/products/processors-and-microcontrollers/additional-processors-and-mcus/8-16-bit-mcus/16-bit-s12-and-s12x-mcus:S12S12X) series)
    * Texas Instruments ([C2000](http://www.ti.com/microcontrollers/c2000-real-time-control-mcus/products.html) based [Piccolo](http://www.ti.com/microcontrollers/c2000-real-time-control-mcus/piccolo-entry-performance/overview.html), [Delfino](http://www.ti.com/microcontrollers/c2000-real-time-control-mcus/delfino-premium-performance/overview.html) series)
    * ST Microelectronics ([Nucleo](https://www.st.com/en/evaluation-tools/stm32-mcu-nucleo.html), [Discovery](https://www.st.com/en/evaluation-tools/stm32-mcu-discovery-kits.html?querycriteria=productId=LN1848) boards with [ARM Cortex-M](https://developer.arm.com/products/processors/cortex-m) based [STM32](https://www.st.com/en/microcontrollers/stm32-32-bit-arm-cortex-mcus.html) series)
* Comfortable working with the corresponding IDEs or [makefiles](https://www.gnu.org/software/make/manual/html_node/Introduction.html) and the required toolchains.
* Comfortable with MATLAB/Simulink based code generation tools and their workflows.
### Electric Machine Design Tools
* Worked extensively with [Flux](https://altairhyperworks.com/product/flux), [FEMM](http://www.femm.info/wiki/HomePage), [SPEED](https://ieeexplore.ieee.org/abstract/document/757901), [Onelab](http://www.onelab.info/) and [rlib](https://motorrlib.gitlab.io/)
* Worked reasonably with [MotorCAD](https://www.motor-design.com/motor-cad-software/)


## Professional Associations
* Licensed [Amateur (Ham) Radio](http://vigyanprasar.gov.in/science-communication-programs/ham-radio/) Operator ([VU3GML](http://www.wpc.dot.gov.in/exam_amatr.asp))
* Life member of [Magnetics Society of India](http://msi.org.in/)
* Life member of [Advanced Computing and Communications Society](http://accsindia.org/)
* Member of [IEEE](https://www.ieee.org/)
* Ex-member of [SAE](https://www.saeindia.org/)