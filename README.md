1. TrackIR 2 Virtual Joystick Converter (vJoy)  
2. TrackIR 2 Virtual Xbox Controller Converter (XInput)  
3. TrackIR 2 Virtual Mouse Converter  

Note: Currently, only the executable file and Readme are distributed.

# tir2vjoy (c) silkysky  
 TrackIR 2 Virtual Joystick Converter (vJoy) https://github.com/silkyskyj/tir2vjoy 

 Sample video of operation: https://youtu.be/Erhs9UkKw3E  

 Require:  
		1. TrackIR 5 https://www.trackir.com/trackir5/  
		2. vJoy https://github.com/BrunnerInnovation/vJoy/releases  
https://github.com/shauleiz/vJoy/releases  
https://github.com/jshafer817/vJoy/releases  
https://github.com/njz3/vJoy/releases/  
https://sourceforge.net/projects/vjoystick/  

Note: Some of the vJoy installation processes listed above may enable the OS's test mode. Please refer to the following page to disable this setting.  

How to disable test mode in Windows 10 when it is protected by secure boot policy?  
https://learn.microsoft.com/en-us/answers/questions/4233514/how-to-disable-test-mode-in-windows-10-when-it-is  
Removing the Test Mode Watermark From the Windows 10 Desktop  
https://www.dell.com/support/kbdoc/en-al/000190354/removing-the-test-mode-watermark-from-the-windows-10-desktop  

 Usage: tir2vjoy.exe \[ID\] \[Timer\]  
  ID ... vJoy Device ID 1 - 16 (Default 1)  
  Timer ... Processing interval \[ms\] (Default 20)  

 Download: Latest v2.0.1.0 https://1drv.ms/u/c/538de3d97d257b91/EUADIEQsnYNIjTfkKSzqZLEBTbdwbI0gkTqK2XA1fVfWoA?e=dlnWXV  

# tir2vx360 (c) silkysky  
 TrackIR 2 Virtual Xbox Controller Converter (XInput) https://github.com/silkyskyj/tir2vjoy   
 
 Sample video of operation: https://youtu.be/NUd6JMkqy4o  
 
 Require:   
 		1. TrackIR 5 https://www.trackir.com/trackir5/  
		2. ViGEmBus https://github.com/nefarius/ViGEmBus/releases  

 Usage: tir2vx360.exe \[ID\] \[Timer\]  
  ID ... Xbox Controller Device ID 0 - 3 (Default 0)  
  Timer ... Processing interval \[ms\] (Default 20)  
 
 Download: Latest v2.0.1.0 https://1drv.ms/u/c/538de3d97d257b91/EU2Kfx6EdUFEsA6_vsYTBDUBBLQtp_tsKZUnV-3gQHelvA?e=UX4hFq  

# tir2vmouse (c) silkysky  
 TrackIR 2 Virtual Mouse Converter https://github.com/silkyskyj/tir2vjoy   
 
 Sample video of operation: https://youtu.be/suzJyNXR_2I  
 
 Require:   
 		1. TrackIR 5 https://www.trackir.com/trackir5/  

 Usage: tir2vmouse \[Timer\]  
  Timer ... Processing interval \[ms\] (Default 20)  

 Note: Unlike the TIRMouse that comes with TrackIR5, it can be used in an inactive window. To avoid mouse control conflicts, use the F9 key to enable/disable TrackIR data transmission and reception on a case-by-case basis.   
 
 Download: Latest v2.0.1.0 https://1drv.ms/u/c/538de3d97d257b91/EWWxyUFyorBEtI1dBYAS67YB57OkSgmHEJnFoNsXFe8wtw?e=hKvmf0

# tir2joy

This is an old project of mine which I understand is still being used here and there. 
As I no longer support the project, I have been asked to release the source code.

This repository includes all original project files. The original [readme.html](readme.html) is included.

The referenced PPJoy project can also be found on [Github](https://github.com/elitak/PPJoy).

## What is it?

vJoy is a tool that can map [TrackIR](https://www.trackir.eu) head movements to movements of a virtual joystick.
It can be used to control games via head movements that don't work directly with a TrackIR device.

## Where can I get support?

I'm afraid you can't get support from me. If you have any problems with the code or binary, you are on your own.

If someone is willing to take over this project, please feel free to do so.

## License

Original project [tir2joy] is licensed under the MIT Software License - see the [LICENSE](LICENSE) file for details.
