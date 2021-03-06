# 4-Way-RF-Switch
Instructions for assembly and operation of a 4 Way RF Switch with WiFi control and Power-via-Coax.

For additional information on this project, see   https://team-xcr.com/

OTA uploading has 2 parts. The parts MUST be a matched set !

    The executable file. When loading this, select the FIRMWARE option.
    The accompanying data files in bin format (html, txt, png). When loading
    this, select the FILESYSTEM option.

Process

    Download BOTH files to your pc.
    Begin OTA.  From the Main Menu, select HELP
        Select Help - Software Update
    Select either Firmware or FileSystem as appropriate. You may need to do both. 
        See the specific instructions with the commit.
    In the File Explorer, navigate to the downloaded files.
        Double click on the file to be loaded. More details are available in the
        built-in HELP page. 
    Repeat steps 3-4 for the other file.

The CPU should reset. Watch the blue activity LED on the CPU PCB. It will be 
on steady in the CPU is in AP mode. In LAN mode, there will be a brief flash. 
If the unit does not return to LAN mode, cycle power.

DO NOT INTERRUPT THE PROCESS. It will likely leave the device in a state 
requiring a data-load via USB (which requires shipping the PCB to the factory).
