# Macro Runner
 A gpc script made to run custom macros. This is a script used to run macros to complete repetitive tasks. You can create your own macro.gmk file and this script will run it. An sd card will be needed to store your gmk file. To activate the macro, switch to the profile containing this script. A custom gmk file can be made by using gtuner. There are now two versions of this script. The "light_k.gph" file is required for this program to change the light colors on the TitanTwo.

**Version 1.0.5 (For older controllers)**
----------------------------------------------------------------------------------------------------------------------------
Press R3 twice quickly to activate your macro. Repeat to deactivate.

**Version 2.0.0 (For newer controllers)**
----------------------------------------------------------------------------------------------------------------------------
Press the share button once to activate the macro. Press it quickly twice to switch between macro files. I have rewritten the code to make it easier to change macro file names or add more macro files by editing the code. Currently the TitanTwo can show the status of the script as follows:  

Blue = Deactivated  
Red = Activated, macro.gmk file  
White = Activated, macro2.gmk file  


**Macro Recording**
----------------------------------------------------------------------------------------------------------------------------
To record a macro, go to the device monitor tab. Then hit record when you are ready to start recording. There will be a 3 second countdown until the recording starts. After you are done recording, hit stop and then save the file as macro.gmk or anything else that is supported in the switch cases. When recording a macro, I suggest you consider making it so the scene is as consistent as possible. If it is not, then it is possible for the macro to not have the results you want because of different character or camera positions.

![alt text](https://github.com/Kttra/MacroRunner/blob/sub/macro%20recorder.png)

**Macro Editting**
----------------------------------------------------------------------------------------------------------------------------
To edit your macro file, switch to the macro editor tab. You can highlight an area in the macro file by first clicking on a section in the waveform. Then hold shift and click on another area. The edit tools are on top of the waveform.

![alt text](https://github.com/Kttra/MacroRunner/blob/sub/macro%20editor.png)
