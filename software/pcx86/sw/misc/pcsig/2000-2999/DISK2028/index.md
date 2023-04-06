---
layout: page
title: "PC-SIG Diskette Library (Disk #2028)"
permalink: /software/pcx86/sw/misc/pcsig/2000-2999/DISK2028/
machines:
  - id: ibm5170
    type: pcx86
    config: /machines/pcx86/ibm/5170/cga/1024kb/rev3/machine.xml
    diskettes: /machines/pcx86/diskettes.json,/disks/pcsigdisks/pcx86/diskettes.json
    autoGen: true
    autoMount:
      B: "PC-SIG Library Disk #2028"
    autoType: $date\r$time\rB:\rDIR\r
---

{% include machine.html id="ibm5170" %}

{% comment %}info_begin{% endcomment %}

## Information about "LASER UTILITIES"

    TILES is a soft font for the HP LaserJet II printer.  It is not an
    "Alpha-Numeric" font, instead it replaces the normal character set with
    a series of random graphic symbols.  The font is used in the "Portrait"
    orientation.  Installing the font is very simple; just copy the file
    TILES.LOD to your laser printer and you are ready to go.  Also on the
    disk are all of the programs used to create the font or modify it.
    Using these programs to modify the font or to create your own requires
    some 'C' programming knowledge.
    
    LASER ENVELOPE PRINTER is a very simple utility to print address
    information on envelopes using an HP LaserJet II printer.  This program
    is extremely easy to use; the user is allowed 3 lines of text for the
    return address and 5 lines for the destination.  The program will save
    your return address on disk, and will import an ASCII mailing list file
    when named on the command line. There is no documentation with this
    program and none is needed; simply run the program and follow the
    instructions on the screen.  LASER ENVELOPE PRINTER uses whatever font
    you have selected from your printer keypad - internal, soft, or
    cartidge.
    
    SEND2LJ is a printer utility program used to send commands, fonts, and
    text files to your HP LaserJet II printer.  The operation of the program
    is simple, just enter your commands into a text file (using your
    favorite text editor) following the documented format, and the program
    will add the needed escape character wherever you have indicated when
    sending the command file to the printer.  The documentation is fairly
    simple, and the disk contains a sample command file for you to try
    (provided you have the softfont specified in the command file handy).
    The program, as designed, is set up to work on printers hooked up to the
    LPT1 port; to change this requires some programming knowledge.
    
    LASER LABEL is a simple utility for printing diskette labels on an HP
    LASERJET II printer. The program reads the directory of files on
    a
    floppy disk and then sorts and prints them (along with a user-defined
    title and description) on AVERY #5161 laser printer diskette labels.
    LASERLBL allows the user to download different fonts for both the title
    and file name areas of the label. There are no documentation files on
    this disk. All of the information you need to use this program is on
{% comment %}info_end{% endcomment %}


### Directory of PC-SIG Library Disk #2028

     Volume in drive A has no label
     Directory of A:\

    LL       EXE     25563   2-19-90  10:26a
    LE       EXE     45389   2-19-90  10:39a
    RETURN              87   2-19-90  10:44a
    LASERENV UPG      2071   2-19-90  12:19p
    LASERLBL UPG      2702   2-19-90  12:20p
    GO       BAT        38   1-01-80   1:37a
    GO       TXT       540   1-01-80   2:28a
    FILE2028 TXT      5329   3-21-90  11:23a
    CL_TIL2C BAT        60   6-07-89   9:32a
    CL_TIL2L BAT        63   6-07-89   9:32a
    CL_TIL2S BAT        60   6-07-89   9:33a
    HV18B#US SLJ       697  11-02-88  11:34a
    READ     ME       7132   6-07-89   9:31a
    README            5521  11-02-88   1:43p
    SEND2LJ  C        7907  11-02-88   1:18p
    SEND2LJ  EXE     10125  11-02-88  11:45a
    TEST     TXT       215   1-21-89   8:05p
    TIL2LOAD C        9746   1-23-89   8:33a
    TIL2LOAD EXE     20707   3-28-89   7:59p
    TIL2LOAD LNK        50   1-21-89   5:52p
    TIL2SFP  C        9058   1-23-89   9:42a
    TIL2SFP  EXE     20577   3-28-89   8:00p
    TIL2SFP  LNK        48   1-23-89   9:45a
    TILES    BAT        33   1-21-89   5:55p
    TILES    C       28001   3-28-89   7:58p
    TILES    LOD     34236   3-28-89   8:00p
    TILES    SFP     34212   3-28-89   8:01p
    TILES    TXT     36409   3-28-89   7:54p
    TILES2C  C        5224   1-21-89   9:25a
    TILES2C  EXE     10485   1-21-89   9:31a
    TILES2C  LNK        48   1-21-89   9:28a
           31 file(s)     322333 bytes
                           19456 bytes free