---
layout: page
title: "PC-SIG Diskette Library (Disk #3133)"
permalink: /software/pcx86/sw/misc/pcsig/3000-3999/DISK3133/
machines:
  - id: ibm5170
    type: pcx86
    config: /machines/pcx86/ibm/5170/cga/1024kb/rev3/machine.xml
    diskettes: /machines/pcx86/diskettes.json,/disks/pcsigdisks/pcx86/diskettes.json
    autoGen: true
    autoMount:
      B: "PC-SIG Library Disk #3133"
    autoType: $date\r$time\rB:\rDIR\r
---

{% include machine.html id="ibm5170" %}
{% comment %}samples_begin{% endcomment %}

## INSTALL.DOC

{% raw %}
```

		    INSTALLING ASTRO SHAREWARE 2.71

This version of ASTRO is shipped with an install program. If you
recieved it from a BBS you may find a file with a name AST271-0.
Note I am not including the file extension. This will either be
.LZH for files compatible with LHA, and .ZIP for files compatible
with PKZIP/PKUNZIP.

To Use the Install program, Log onto the drive that you want to
install from and type INSTALL and press the Enter Key. Then follow
the instructions.

NOTE: If you must run ASTRO on two 360k floppies and want to print out
the graphics, make sure your path includes A:\;B:\; so it can find
the Printer Driver which is on the B: drive. For Example if you
type PATH at the DOS Command Line, and DOS Responds with PATH=C:\DOS;
you will need to type PATH=A:\;B:\;C:\DOS; before you start ASTRO
so you can print the graphics. TIP: Put this in a batch file which
sets the path and then starts ASTRO.

NOTE: If you have a Monochrome or Hercules Graphics Adapter, You must
start the Program MSHERC provided before starting ASTRO.

If you did not get an install program, this may be installed on
a hard disk by creating a single directory and unpacking each file
into that directory.

You can also install it on a single 5-1/4" 1.2MB floppy or a single
3-1/2" 1.44MB floppy using the same procedure. In That case I suggest
only including the Necessary Graphics Files. See The NOTES section
below for an explanation.

If You need to install ASTRO on 5-1/4" 360k or 3-1/2" 720k floppies,
the following table shows the way various disks need to be layed out in
order to use ASTRO on floppies. The Install program does this for you.
Follow this in case you can't find the install program and INSTALL.DAT
data file.

The Original Master File column shows the Master Archive file that you
will need to un archive using PKUNZIP or LHA. These file Should Not
Be on your Final Disks.

See the file FILELST.DOC for the Complete File Listing.

5-1/4" TWO 360k FLOPPY DRIVES.

ORIGINAL
MASTER      DISK
FILE        LABEL               DESCRIPTION
------------------------------------------------------------------------
AST271-1    MAIN PROGRAM        Main Program Files.
........................................................................
AST271-7    UTILITIES           Utilities.
........................................................................
AST271-4    HELP/DATABASE       Help Files.
AST271-5                        Basic 200 Location Database.
........................................................................
AST271-3    NATAL DATA/       + Graphics Fonts for Natal Charts.
AST271-2    USER/TEMP         ^ Graphics Printing Drivers for Natal.
AST271-6                        Natal Text Data.
........................................................................
AST271-2    COMPAT/TRANS      ^ Graphics Printing Drivers for Comp & Trans.
AST271-9    DATA/USER/          Compatibility & Transits Text Data.
AST271-3    TEMP             +  Graphics Fonts for Compatibility & Transits.
........................................................................
AST271-8    DOCS                Documentation.

NOTES:
^ One file from this archive is needed on both disks. Use only one to
  conserve disk space. EP9DRV.OVL--9-pin printers, EP24DRV.OVL 24-pin
  printers, HPLDRV.OVL--Laser/DeskJet printers.

* One file from this archive is needed on both disks. Use only one to
  conserve disk space. ASTROEP9.FON--9-pin printers, ASTROP24.FON--24-pin
  printers, ASTROHPL.FON--Laser/DeskJet printers

If you use 24-pin or HPL Laser Driver you will need to set up the program
using the Setup Graphic Modes & Printing Screenm, and possibly Setup
Printer Screen.

3-1/2" TWO 720k FLOPPY DRIVES.

ORIGINAL
MASTER      DISK
FILE        LABEL               DESCRIPTION
----------------------------------------------------------------------
AST271-1    MAIN PROGRAM        Main Program Files.
AST271-7    UTILITIES           Utilities.
AST271-8    DOCS                Documentation.
......................................................................
AST271-4    HELP/DATABASE       Help Files.
AST271-5                        Basic 200 Location Database.
......................................................................
AST271-3    DATA/USER         * Graphics Fonts for Natal Charts.
AST271-2    TEMP              ^ Graphics Printing Drivers for Natal.
AST271-6                        Natal Text Data.
AST271-9                        Compatibility & Transits Text Data.

NOTES:
^ One file from this archive is needed. Use only one to conserve disk
  space. EP9DRV.OVL--9-pin printers, EP24DRV.OVL 24-pin printers,
  HPLDRV.OVL--Laser/DeskJet printers.

* One file from this archive is needed. Use only one to conserve disk
  space. ASTROEP9.FON--9-pin printers, ASTROP24.FON--24-pin printers,
  ASTROHPL.FON--Laser/DeskJet printers

If you use 24-pin or HPL Laser Driver you will need to set up the program
using the Setup Graphic Modes & Printing Screenm, and possibly Setup
Printer Screen.

```
{% endraw %}

## README.DOC

{% raw %}
```





















































































































































































































































































































































































```
{% endraw %}

{% comment %}samples_end{% endcomment %}

### Directory of PC-SIG Library Disk #3133

     Volume in drive A has no label
     Directory of A:\

    AST271-1 LZH    182501   4-04-92   5:30p
    AST271-2 LZH      9298   4-04-92   5:30p
    AST271-5 LZH     15085   4-04-92   5:10p
    INSTALL  3         726   4-02-92   9:40p
    INSTALL  DAT       726   4-02-92   9:40p
    INSTALL  DOC      5133   4-03-92   1:45p
    INSTALL  EXE     38214   4-04-92   5:41p
    LHA      EXE     34283   7-20-91   2:13a
    LHA213   EXE     44381   8-09-91   4:44p
    README   DOC     16943   4-03-92   9:13p
    GO       BAT       955  12-21-92   2:13a
           11 file(s)     348245 bytes
                            8192 bytes free