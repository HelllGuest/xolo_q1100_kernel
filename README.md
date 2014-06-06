Building Kernel and kernel modules 

Environment setup Getting ready
      a. Getting the prebuilt tool chain in your machine.  
             git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.6
      b. Ensure the tool chain is in your path 
             export PATH=$(pwd)/prebuilts/gcc/linux-x86/arm/arm-eabi-4.6/bin:$PATH
      c. export ARCH=arm 
         export SUBARCH=arm
         export CROSS_COMPILE=arm-eabi-   
  
   Building 
      a. cd kernel 
      b. make -f Android.mk bootimage