File: Readme.txt Date: 2000-01-31

Installation
------------
When installing from the Cd just run Setup.exe.

When no Cd player is available on the system you are about
to make the installation on, you can run the installation
from diskettes by copying the files setup.exe, setup.lst
and awp11.cab to disk 11, and awp12.cab to disk 12.
Start the installation by running setup.exe from disk 11.
(Yes, the two disks are numbered 11 and 12)

Configuration
-------------
Logos: The default logo is the one of Roper Whitney,
if you want another logo you can find them in the
"\Logos" subdirectories. Just copy the appropriate
mainlogo.bmp to your Awp directory.

Setup.ini: The default Setup.ini is the one for the
Roper Whitney Autobrake machine, different setup.ini
files can be found in the "\Ini files" subdirectories.
Copy the appropriate setup.ini to your Awp directory,
then you MUST remove the read-only attribute from the
file! Otherwise the file will be READ-ONLY. 
If the machine is an Automax you also need an angcorr.tab
file!

Setup tuning
------------
All entries in the setup.ini file are changeable from
within the Awp program, see "\document\awp setup.xls"
for information. WARNING! THESE SETTINGS ARE CRITICAL
FOR THE FUNCTION OF THE MACHINE AND IF NOT SET TO CORRECT
VALUES THE MACHINE CAN BE LEFT USELESS OR WITH AN UNPREDICTABLE
BEHAVIOR!! 

The following entries CB04,CB05,CB06,CB07 for the clamping 
beam height sensor MUST be tuned on every machine!

If backgauge depth control is installed, BG20, BG21,
BG22,BG23 MUST also be tuned.

If The Awp program is installed on a desktop computer
with no Ics connected, S05 should be set to 0 to disable
the communication.

Ics
---
The latest versions of the Ics control programs
available at this time is include on the Cd and
can be found in the "\Ics" subdirectories.
You can download the appropriate control program
to the Ics using the Awp program.