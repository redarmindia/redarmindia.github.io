# About me

My name is [Raghu](https://in.linkedin.com/in/raghunathkumar) ([/rʌgu:/](https://bitbucket.org/saras152/phdtopic/downloads/0_Raghu.wav)), a.k.a. RaNa ([/rʌ:a-na/](https://bitbucket.org/saras152/phdtopic/downloads/1_RaNa.wav)). I graduated from [IIT Madras](http://www.iitm.ac.in/) in 2007 with a [dual degree](https://www.iitm.ac.in/academic-programmes) (B.Tech. + M.Tech.) in [Electrical Engineering](http://www.ee.iitm.ac.in/). 

# Professional Experience
## [TVS Motor](https://www.tvsmotor.com/) [Sept 2015 - Present]
### Electric Machines &  Optimization
This work is a combination of my long standing passions, electric motors and optimization. Part of this work resulted in a technical presentation at [SAE World Congress](https://www.sae.org/wcx) 2017 in Detroit (MI, USA), about the optimization methods for electric machines for engine starter application. Few patent applications about electric machine technology ([201641038223](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [201641038846](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [201641038845](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [201641038844](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [201741005098](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [201741012184](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [201741012185](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search)) are pending decision. 

I work on design automation & optimization for electric machine development with both the open-source and commercial electromagnetic FEA software. My personal interest is in using the open-source electromagnetic FEA software such as [FEMM](http://www.femm.info/wiki/HomePage), [Onelab(Gmsh/GetDP)](http://www.onelab.info/), and [Elmer](https://www.csc.fi/web/elmer) together with [Scilab](https://www.scilab.org/). I use Scilab as a base platform to implement design automation in other software which results in dramatic reduction in the model creation time. Using these models, and the optimization methods (I use the variant of gradient descent algo developed by myself to detect the global maximum), I arrive at a best possible design for a given set of specifications. More details about the tool's capabilities are [here](https://motorrlib.gitlab.io/).
### Machine Learning & Computer Vision
I worked on understanding the basic principles of machine learning and implemented few projects and documented them in [this blog](https://saras152.github.io/). 
### Bootloader
I worked on Bootloader and it resulted in a technical presentation at [SAE World Congress](https://www.sae.org/wcx) 2017 in Detroit (MI, USA).

## [MathWorks](https://in.mathworks.com/) [June 2014 - Sept 2015]
### Code Generation with Bootloader
I worked on [Embedded Coder Support Package](https://www.mathworks.com/help/supportpkg/armcortexm/index.html) for ST Microelectronics ([Nucleo](https://www.st.com/en/evaluation-tools/stm32-mcu-nucleo.html) and [Discovery](https://www.st.com/en/evaluation-tools/stm32-mcu-discovery-kits.html)) and Texas Instruments ([Piccolo F2869](http://www.ti.com/product/TMS320F28069)) processors. This effort resulted in successful implementation of a [modular two-stage bootloader](https://bitbucket.org/saras152/bootloader/wiki/blstages) ([help text](https://in.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ref/build-for-use-with-bootloader.html), [GUI](https://in.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ref/model-configuration-parameters-for-stmicroelectronics-stm32f4-discovery-board.html)) for ARM cortex-M based processors.  My contribution is the checkbox "*[Build for use with bootloader](https://www.mathworks.com/help/supportpkg/stmicroelectronicsstm32f4discovery/ref/build-for-use-with-bootloader.html)*" below the Build actions drop down menu in the Target Hardware Resources pane. 


## [TVS Motor](https://www.tvsmotor.com/) [Aug 2007 - June 2014]
### Anti-lock Braking System
I worked on [Anti-Lock Braking System](https://en.wikipedia.org/wiki/Anti-lock_braking_system) for 2-wheeler systems resulting in my involvement for the India's first ABS equipped motorcycle [TVS Apache RTR 180 ABS](https://www.tvsapache.com/rtr-180.aspx). This work resulted in a technical presentation at [Eurobrake](https://www.eurobrake.net/) 2012 in Dresden, Germany. My work also resulted in the grant of the [*Indian patent* 280720](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search). Few more patent applications related to ABS technologies ([3098/CHE/2009](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [3449/CHE/2010](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [1002/CHE/2011](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search), [1001/CHE/2011](http://ipindiaservices.gov.in/PublicSearch/PublicationSearch/Search)) are pending decision.
### Other Projects
* I worked on Fuel cell - Battery Hybrid system's control and it resulted in a technical presentation at [Fuel Cell Seminar and Energy Exposition](https://www.fuelcellseminar.com/) 2011 in Orlando, Florida, USA. 
* I worked on embedded software for [Battery Management System](https://en.wikipedia.org/wiki/Battery_management_system) for 2-wheeler (H)EV systems. 
* I worked on data acquisition system design including the embedded [FAT16](https://bitbucket.org/saras152/filesystem_fat/wiki/FAT%2016) & [FAT32](https://bitbucket.org/saras152/filesystem_fat/wiki/Home) drivers for writing data on [SD card](https://bitbucket.org/saras152/filesystem_fat/wiki/SD%20CARD) and on embedded [USB Host drivers](https://bitbucket.org/saras152/usbhost_embedded/wiki/Home) using [Renesas Rx621](https://www.renesas.com/in/en/products/microcontrollers-microprocessors/rx/rx600/rx621-62n.html) platform.

## [Honeywell](https://www.honeywell.com/worldwide/en-in) [May 2006 - May 2007]
### Motor Controller
I supported the motor controller team in developing their Next Generation Low Cost Motor Controller (NGLCMC). Created Matlab models of Sine and Space Vector PWM for MBD and simulations. Contributed to hardware development of gate driver circuits and PCB development. Participated in board bring-up and functional testing of the hardware.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
