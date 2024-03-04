AVR2.dll library description:

Now regarding AVR simulation. As I could notice (and maybe I am not the only one),
starting from version 8.12.SP0+ - the emulation of some AVR's, including Arduino, is slowed down!
It looks like the simulation time countdown with a delay in real time.
As I understood it is not a problem of the crack or something else....
Maybe there are other reasons for this, such as the presence of certain instructions in the
processor on your computer, maybe support for deeper virtualization or something else...
For myself, I solved this problem by replacing the AVR2.DLL file (in the models)
with the version 8.11.SP1 file.
So far it works without problems even on 8.15.SP1 - in real time.
Standard replacement path:
c:\ProgramData\Labcenter Electronics\Proteus 8 Professional\MODELS\
(of course something probably doesn't work as it should, it's not for nothing that the new
original file size +1MB, so make a backup of the original file before replacing)