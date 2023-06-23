---
layout: page
title: "PC-SIG Diskette Library (Disk #1299)"
permalink: /software/pcx86/sw/misc/pcsig/1000-1999/DISK1299/
machines:
  - id: ibm5170
    type: pcx86
    config: /machines/pcx86/ibm/5170/cga/1024kb/rev3/machine.xml
    diskettes: /machines/pcx86/diskettes.json,/disks/pcsigdisks/pcx86/diskettes.json
    autoGen: true
    autoMount:
      B: "PC-SIG Library Disk #1299"
    autoType: $date\r$time\rB:\rDIR\r
---

{% include machine.html id="ibm5170" %}

{% comment %}info_begin{% endcomment %}

## Information about "UTILITIES GALORE"

    Make your printer serve you better with this collection of utilities.
    There's even a game thrown in for fun!
    
    DIRPRN prints a disk directory sorted in various ways to make it easy to
    find a file.  ENVPRN turns your computer into an electric typewriter for
    quickly dashing off addresses on an envelope in a variety of fonts.
    LABPRN works similarly but is specifically formatted to handle labels,
    such as for binders/drawers.  MERPRN merges several separate text files
    into one formatted printed text.  SETPRN sets the printer parameters
    prior to using a print spooler.  XTRPRN extracts and prints call
    declarations and comments from Turbo Pascal source files.
    
    All the programs let you select the print quality, text style, margin
    width, page numbering, printer port, and line spacing.  They can be
    added as batch files to run whenever needed.
    
    COLORE lets you choose the colors your monitor will display when
    your system first boots-up.  You can select from 16 different colors for
    the foreground, background, and border of your monitor.
    
    SURVIVAL is a game that requires quick reflexes.  With a boxing glove
    you must punch monsters before they descend to the bottom of the screen,
    sending them back to the top.
    
    LABEL computerizes your personal address/telephone directory for easy
    reference and printing of reports and labels.  Menu options let you
    print: address labels (using standard 15/16" x 3-1/2" wide labels),
    list of all records (done with two entries side-by-side on 8-1/2" x 11"
    paper), telephone list (only those records with a telephone number are
    printed), and individual records you select.  Handles both three and
    four line addresses, automatically suppressing blank lines.
    
    DOCFORM lets you add printing instructions to any text file to
    specify boldface print, underlined print, margins, double or triple
    spacing, headers, and footers -- which then print correctly on
    almost every printer.
{% comment %}info_end{% endcomment %}

{% comment %}samples_begin{% endcomment %}

## COMMENT.DOC

{% raw %}
```

















































































































```
{% endraw %}

## DIRPRN.TXT

{% raw %}
```

                              DirPRN by JJO

     PURPOSE

     DirPRN may be invoked from the DOS prompt or from within a batch
     file (see below) to secure disk or directory files listings, sort
     them (optional) and print them (always).

     If no printer options are selected, DirPRN defaults to Epson and
     should be compatible with most printers.

     USAGE

     Syntax: DIRPRN [?][pathspec] [options]

     Parameters: [] optional and <> required, where a parameter is a
     character or a string (no spaces). Parameter sets must be separated
     by one or more spaces where so shown above.

                              Parameter List

     ? means display this file (/? is also acceptable).

     Pathspec is the disk or directory to search; e. g: a:\ or c:\DOS.
        If pathspec is omitted, the current directory is used.

     Options, one or more of (any order and case);
        /B    forces black & white display.
        /C    centers header and date.
        /D    inserts date.
        /H:c  sets header style (c = (S)tandard, (H)igh or (W)ide).
        /L:n  sets line spacing (n = 6, 4 or 8 lpi).
        /M:n  sets margin (n = 0..10).
        /N    insert page numbers.
        /P:n  chooses printer port (n = 1..2).
        /Q:c  sets print quality (c = (D)raft, (E)mphasized or (L)etter).
        /S:c  sort criteria (c = (N)ame, (E)xtension, (D)ate or (S)ize).
        /S:pc p is optional prefix for c (p = (A)ll directory entries)
              where default (no prefix) is files, only.
        /T:c  sets text style (c = (P)ica, (E)lite or (C)ompressed).
        /U:c  selects printer (c = (E)pson, (D)ataproducts or (I)BM).
              The defaults are listed first.
              If H, L, Q or T are specified for other than an Epson (or
              clone), then enter a printer code.

     NOTES

     If there are command line errors or the specified printer is
     unavailable, DirPRN halts with an error message. Error messages are
     beeped and left on the screen when DirPRN terminates.

     If a header style is specified, it only affects printing of the
     directory name (header). If centering is specified, only the header
     and date are centered.

     This file may be printed via MerPRN or by typing at the DOS prompt
     TYPE DIRPRN.TXT > PRN.


     BATCH FILE USAGE

     DirPRN is designed for execution from within a batch file. When so
     used, test for an error code returned by DirPRN and, if found, stop
     batch execution until the problem is cleared. This can be done by
     inserting a line like this after each call to DirPRN:

                          IF ERRORLEVEL 1 GOTO Error

     where "Error" can be any line(s) which cause the batch process to
     terminate. See the sample batch file DirEx.Bat.

                                      ***


```
{% endraw %}

## DOCFORM.DOC

{% raw %}
```


















































































































































































































































































































































































































```
{% endraw %}

## FILE1299.TXT

{% raw %}
```
Disk No: 1299
Program Title: UTILITIES GALORE
PC-SIG version: 1

Make your printer serve you better with this collection of utilities.
There's even a game thrown in for fun!

DIRPRN prints a disk directory sorted in various ways to make it easy to
find a file.  ENVPRN turns your computer into an electric typewriter for
quickly dashing off addresses on an envelope in a variety of fonts.
LABPRN works similarly but is specifically formatted to handle labels,
such as for binders/drawers.  MERPRN merges several separate text files
into one formatted printed text.  SETPRN sets the printer parameters
prior to using a print spooler.  XTRPRN extracts and prints call
declarations and comments from Turbo Pascal source files.

All the programs let you select the print quality, text style, margin
width, page numbering, printer port, and line spacing.  They can be
added as batch files to run whenever needed.

COLORE lets you choose the colors your monitor will display when
your system first boots-up.  You can select from 16 different colors for
the foreground, background, and border of your monitor.

SURVIVAL is a game that requires quick reflexes.  With a boxing glove
you must punch monsters before they descend to the bottom of the screen,
sending them back to the top.

LABEL computerizes your personal address/telephone directory for easy
reference and printing of reports and labels.  Menu options let you
print: address labels (using standard 15/16" by 3-1/2" wide labels),
list of all records (done with two entries side-by-side on 8-1/2" by 11"
paper), telephone list (only those records with a telephone number are
printed), and individual records you select.  Handles both three and
four line addresses, automatically suppressing blank lines.

DOCFORM lets you add printing instructions to any text file to
specify boldface print, underlined print, margins, double or triple
spacing, headers, and footers--which then print correctly on
almost every printer.

Usage:  DOS Utilities/Entertainment.

Special Requirements:  DataProducts DP8070, Epson MX/FX, IBM Proprinter
or compatible printer, a color monitor (except DOCFORM), and a second
printer connected to the first printer port (PRN).

How to Start:  Type GO (press enter).

Suggested Registration: $20.00 for LABEL

File Descriptions:

DIREX    BAT  Sample batch file for DIRPRN.
DIRPRN   EXE  DIRPRN, main program.
DIRPRN   TXT  Documentation for DIRPRN.
ENVPRN   EXE  ENVPRN, main program.
LABPRN   EXE  LABPRN, main program.
PRNSUITE DOC  File descriptions.
MEREX    BAT  Sample batch file for MERPRN.
MERPRN   EXE  MERPRN, main program.
MERPRN   TXT  Documentation for MERPRN.
PRNSUITE BAT  Displays PRNSUITE.DOC.
SETEX    BAT  Sample batch file for SETPRN.
SETPRN   EXE  SETPRN, main program.
SETPRN   TXT  Documentation for SETPRN.
XTREX    BAT  Sample batch file for XTRPRN.
XTRPRN   EXE  XTRPRN, main program.
XTRPRN   TXT  Documentation for XTRPRN.
COLOR    BAT  Batch file to start up colors.
COLOR    DOS  Sample color file.
COLORE   EXE  Color menu.
CONFIG   SYS  Sample configuration file.
PCGREF   EXE  Run-time routines.
SURVIVAL EXE  The game SURVIVAL.
READ     ME   Documentation.
LABEL    EXE  Program file.
LABEL    FLE  Data File.
READ     ME2  Manual.
READ     ME3  Short description.
DOCFORM  DOC  Documentation, formatted by DOCFORM.
COMMENT  DOC  User comment form.
DOCFORM  COM  Main program.
DOCFORM  ASC  Documentation, unformatted.

PC-SIG
1030D E Duane Avenue
Sunnyvale CA 94086
(408) 730-9291
(c) Copyright 1989 PC-SIG, Inc.

```
{% endraw %}

## GO.TXT

{% raw %}
```
╔═════════════════════════════════════════════════════════════════════════╗
║                <<<<  Disk No 1299 Utilties Galore  >>>>                 ║
╠═════════════════════════════════════════════════════════════════════════╣
║ To print the documentation for the programs, type:                      ║
║                                                                         ║
║             MANUAL (press enter)                                        ║
║                                                                         ║
║   To run any of the programs on this disk, simply type in the name      ║
║   of the program you wish to run then press the ENTER key. For          ║
║   example, to run LABEL you would type:                                 ║
║                                                                         ║
║             LABEL (press enter)                                         ║
║                                                                         ║
╚═════════════════════════════════════════════════════════════════════════╝
```
{% endraw %}

## MERPRN.TXT

{% raw %}
```

                              MerPRN by JJO

     PURPOSE

     MerPRN may be invoked from the DOS prompt or from within a batch
     file (see below) to merge and print an unformatted text file pair: a
     base (target) file and its associated header. The header file
     typically contains descriptive text which complements the base and
     must have the same filename, with .Hdr as its extension.

     If no printer options are selected, MerPRN defaults to Epson and
     should be compatible with most printers.

     USAGE

     Syntax: MERPRN [?] <filespec> [options]

     Parameters: [] optional and <> required, where a parameter is a
     character or a string (no spaces). Parameter sets must be separated
     by one or more spaces where so shown above.

                              Parameter List

     ? means display this file (/? is also acceptable).

     Filespec is the target file (and its path); e. g: c:\Any\File.Ext.
        If a file with the same name and extension of .Hdr exists, it
        will be printed first as the header for the target file. If not
        present, the target file title is used as the header.

     Options, one or more of (any order and case);
        /B    forces black & white display.
        /C    centers header and date.
        /D    inserts date after the header.
        /H:c  sets header style (c = (S)tandard, (H)igh or (W)ide).
        /L:n  sets line spacing (n = 6, 4 or 8 lpi).
        /M:n  sets margin (n = 0..10).
        /N    causes pages to be numbered.
        /P:n  chooses printer port (n = 1..2).
        /Q:c  sets print quality (c = (D)raft, (E)mphasized or (L)etter).
        /T:c  sets type style (c = (P)ica, (E)lite or (C)ompressed).
        /U:c  selects printer (c = (E)pson, (D)ataproducts or (I)BM).
              The defaults are listed first.
              If H, L, Q or T are specified for other than an Epson (or
                 clone), then enter a printer code.

     NOTES

     If there are command line errors or the specified target file and/or
     printer is/are unavailable, MerPRN halts with an error message.
     Error messages are beeped and left on the screen when MerPRN
     terminates.

     If a header style is specified, it only affects printing of the
     header file or default header. If centering is specified, only the
     header and date are centered.

     This file may be printed with MerPRN or by typing at the DOS prompt
     TYPE MERPRN.TXT > PRN.


     BATCH FILE USAGE

     MerPRN is designed for execution from within a batch file. When so
     used, test for an error code returned by MerPRN and, if found, stop
     batch execution until the problem is cleared. This can be done by
     inserting a line like this after each call to MerPRN:

                          IF ERRORLEVEL 1 GOTO Error

     where "Error" can be any line(s) which cause the batch process to
     terminate. See the sample batch file MerEx.Bat.

                                      ***


```
{% endraw %}

## PRNSUITE.DOC

{% raw %}
```


                           PRNSuite by JJO Software

                                   Release 1

     PROGRAMS

     PRNSuite is a set of related print utilities with a common user
     interface. It consists of the following programs (.Exe), related
     information (.Txt) and sample batch files (.Bat):

     DirPRN (v1.2) - prints directory contents sorted (optional) in
     various ways. See DirPRN.Txt and DirEx.Bat. Type DIRPRN ? for syntax.

     EnvPRN (v1.5) - prints various type styles for addressing envelopes.
     Interactive, type ENVPRN to run.

     LabPRN (v1.3) - prints various type styles for binder/drawer labels.
     Interactive, type LABPRN to run.

     MerPRN (v1.3) - prints a merged set of related text files. See
     MerPRN.Txt and MerEx.Bat. Type MERPRN ? for syntax.

     SetPRN (v1.3) - sets a printer for print spooling. See SetPRN.Txt and
     SetEx.Bat. Type SETPRN ? for syntax.

     XtrPRN (v1.7) - extracts and prints call declarations and comments
     (optional) from Turbo Pascal source files. See XtrPRN.Txt and
     XtrEx.Bat. Type XTRPRN ? for syntax.

     The information (.Txt) files must be in the current directory or a
     \Print directory to be viewed (via ?) from within the programs. The
     interactive programs are self-contained; i.e., have no information
     files. The information files may be printed via MerPRN or by typing
     at the DOS prompt TYPE Filename.Ext > PRN.

     For best results on CGA systems with monochrome monitors, use the /B
     parameter with all of the programs to force black and white operation.


     SYSTEM REQUIREMENTS

     System: Any member of the IBM PC or PS/2 family, or compatible.

     Memory: 64 kb over and above DOS and any resident programs should be
     adequate.

     Video: XWord does not require graphics and has been run in both color
     and monochrome on IBM and Tandy VGA, EGA, CGA and MDA systems.

     Printer: DataProducts DP8070, Epson MX/FX and IBM Pro, or equivalents,
     are supported in all respects. The printer defaults are compatible
     with most Epson-like printers so no parameters need be supplied.


     UPGRADES

     Refer to documentation for the individual programs. What is to be
     implemented, if anything, will be determined via feedback from
     registered users.



     REGISTRATION

     Written communications from all users will be accepted and answered.
     However, registered users will be given a daytime phone number which
     may be used for discussing upgrades and for technical support.
     Registered users are to receive at least one upgrade, not including
     bug fixes (if needed). To register, send a $20 check or money order
     to:

                                  JJO Software
                               174 Westover Court
                                Delran, NJ 08075

                                      ***



```
{% endraw %}

## SETPRN.TXT

{% raw %}
```

                              SetPRN by JJO

     PURPOSE

     SetPRN is intended to be called from a batch file (see below) to
     set printer parameters prior to calling a print spooler. SetPRN
     always sets the printer's perforation skip function to 5 lines.

     If no printer options are selected, SetPRN defaults to Epson and
     should be compatible with most printers.

     USAGE

     Syntax: SETPRN [?][options]

     Parameters: [] optional and <> required, where a parameter is a
     character or a string (no spaces). Parameters must be separated
     by one or more spaces where so shown above.

                              Parameter List

     ? means display this file (/? is also acceptable).

     Options, one or more of (any order and case);
        /B    forces black & white display.
        /L:n  sets line spacing (n = 6, 4 or 8 lpi).
        /M:n  sets margin (n = 0..10).
        /P:n  chooses printer port (n = 1..2).
        /Q:c  sets print quality (c = (D)raft, (E)mphasized or (L)etter).
        /T:c  sets type style (c = (P)ica, (E)lite or (C)ompressed).
        /U:c  selects printer (c = (E)pson, (D)ataproducts or (I)BM.
              The defaults are listed first.
              If M, Q or T are used for other than an Epson (or clone)
                 then enter printer code.

     NOTES

     If there are command line errors or the specified printer is
     unavailable, SetPRN will halt with an error message. Error messages
     are beeped and left on the screen when SetPRN terminates.

     Planned upgrades include automatic generation of the print spooler
     command line from file and option parameters supplied to SetPRN.

     This file amy be printed via MerPRN or by typing at the DOS prompt
     TYPE SETPRN.TXT > PRN.

     BATCH FILE USAGE

     SetPRN is designed for execution from within a batch file; hence,
     test for an error code returned by SetPRN and, if found, stop batch
     execution until the problem is cleared. This can be done by
     inserting a line like this after each call to SetPRN:

                          IF ERRORLEVEL 1 GOTO Error

     where "Error" can be any line(s) which cause the batch process to
     terminate. See the sample batch file SetEx.Bat.

                                      ***


```
{% endraw %}

## XTRPRN.TXT

{% raw %}
```

                              XtrPRN by JJO

     PURPOSE

     XtrPRN may be invoked from the DOS prompt or from within a batch
     file (see below) to extract and print subroutine calls and comments
     (optional) from Turbo Pascal source files.

     If no printer options are selected, XtrPRN defaults to Epson and
     should be compatible with most printers.

     USAGE

     Syntax: XTRPRN [?] <filespec> [options]

     Parameters: [] optional and <> required, where a parameter is a
     character or a string (no spaces). Parameter sets must be separated
     by one or more spaces where so shown above.

                              Parameter List

     ? means display this file (/? is also acceptable).

     Filespec is the target file (and its path); e. g: c:\Pascal\Test.Pas.

     Options, one or more of (any order and case);
        /B    forces black & white display.
        /C    centers header and date.
        /D    inserts date after header.
        /H:c  sets header style (c = (S)tandard, (H)igh or (W)ide).
        /L:n  sets line spacing (n = 6, 4 or 8 lpi).
        /M:n  sets margin (n = 0..10).
        /N    insert page numbers.
        /P:n  chooses printer port (n = 1..2).
        /Q:c  sets print quality (c = (D)raft, (E)mphasized or (L)etter).
        /T:c  sets type style (c = (P)ica, (E)lite or (C)ompressed).
        /U:c  selects printer (c = (E)pson, (D)ataproducts or (I)BM).
        /V    include compiler directives and comments.
              The defaults are listed first.
              If H, L, Q or T are specified for other than an Epson (or
                 clone), then enter a printer code.

     NOTES

     If there are command line errors or the specified target file and/or
     printer is/are unavailable, XtrPRN halts with an error message.
     Error messages are beeped and left on the screen when XtrPRN
     terminates.

     If a header style is specified, it only affects printing of the
     file name (header). If centering is specified, only the header and
     date are centered.

     This file may be printed via MerPRN or by typing at the DOS prompt
     TYPE XTRPRN.TXT > PRN.


     BATCH FILE USAGE

     XtrPRN is designed for execution from within a batch file. When so
     used, test for an error code returned by XtrPRN and, if found, stop
     batch execution until the problem is cleared. This can be done by
     inserting a line like this after each call to XtrPRN:

                          IF ERRORLEVEL 1 GOTO Error

     where "Error" can be any line(s) which cause the batch process to
     terminate. See the sample batch file XtrEx.Bat.

                                      ***


```
{% endraw %}

{% comment %}samples_end{% endcomment %}

### Directory of PC-SIG Library Disk #1299

     Volume in drive A has no label
     Directory of A:\

    COLOR    BAT        44   2-02-88   8:15a
    COLOR    DOS       128   2-02-88   4:00p
    COLORE   EXE      3869   2-02-88   3:57p
    COMMENT  DOC      3534  12-12-87   4:36p
    CONFIG   SYS        17   2-02-88   8:10a
    DIREX    BAT       520   2-13-88   7:07p
    DIRPRN   EXE     25072   2-13-88   7:07p
    DIRPRN   TXT      2921   2-13-88   7:07p
    DOCFORM  ASC     14309  12-29-87   8:29p
    DOCFORM  COM     21419  12-12-87   4:10p
    DOCFORM  DOC     20489  12-12-87   4:12p
    ENVPRN   EXE     14768   2-13-88   7:07p
    FILE1299 TXT      3620   2-23-89  12:55p
    GO       BAT        38  10-19-87   3:56p
    GO       TXT      1079   2-21-89   9:54a
    LABEL    EXE     32296   1-14-88  10:34p
    LABEL    FLE       528   1-14-88  10:34p
    LABPRN   EXE     13248   2-13-88   7:07p
    MANUAL   BAT       179   1-12-89  10:03a
    MEREX    BAT       505   2-13-88   7:07p
    MERPRN   EXE     19488   2-13-88   7:07p
    MERPRN   TXT      3087   2-13-88   7:07p
    PCGREF   EXE     31744   5-07-82  12:00p
    PRNSUITE BAT       198   2-13-88   7:07p
    PRNSUITE DOC      2994   2-13-88   7:07p
    READ     ME       1846   2-02-88   4:34p
    READ     ME2     12285   1-14-88  10:35p
    READ     ME3       971  12-12-87   5:02p
    SETEX    BAT      1015   2-13-88   7:07p
    SETPRN   EXE     18160   2-13-88   7:07p
    SETPRN   TXT      2368   2-13-88   7:07p
    SURVIVAL EXE      3629  12-05-87   4:46p
    XTREX    BAT       509   2-13-88   7:07p
    XTRPRN   EXE     20896   2-13-88   7:07p
    XTRPRN   TXT      2760   2-13-88   7:07p
           35 file(s)     280533 bytes
                           24576 bytes free