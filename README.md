#EZ-FLASH  Omega Definitive Edition Kernel

### How to build 

    1.We use devkitARM_r53, you can use the current version or newer.
    2.Set the following environment variables in system, or modify the value in build.bat, based on your installation path
 
        PATH,DEVKITARM,DEVKITPRO,LIBGBA

    3.Double click on build.bat under winodws. If it goes well, you will get ezkernelnew.gba
    4.Double click on  Link_kernel_image.exe link the ezkernelnew.gba and image.bin to ezkernelnew.bin, that is the omegaDE kernel upgrade file
    4a. Or from a cmd prompts Link_kernel_image.exe omega-de-kernel-main.gba image.bin
    4b. Or just drag and drop the omega-de-kernel-main.gba on to the Link_kernel_image.exe
