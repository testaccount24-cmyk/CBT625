# CBT625
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 625 is contributed semi-anonymously and contains a REXX   *   FILE 625
//*           exec that will recatalog datasets, based on a LISTCAT *   FILE 625
//*           from their old catalog.  This REXX was developed      *   FILE 625
//*           when moving from one datacenter to the other, where   *   FILE 625
//*           the packs in the old datacenter were 3380's, and the  *   FILE 625
//*           packs in the new datacenter were 3390's having the    *   FILE 625
//*           same names as the old packs.                          *   FILE 625
//*                                                                 *   FILE 625
//*           email for questions:  sbgolob@cbttape.org             *   FILE 625
//*                                                                 *   FILE 625
//*   More detailed description:                                    *   FILE 625
//*                                                                 *   FILE 625
//*         This REXX will attempt to read the output file from     *   FILE 625
//*    a LISTCAT command and then uncatalog and recatalog all       *   FILE 625
//*    the files listed.  The files will be recataloged to the      *   FILE 625
//*    same pack name as they were originally cataloged on.         *   FILE 625
//*    The purpose of this was to change the cataloging of all      *   FILE 625
//*    files on a list of 3380 packs to 3390 packs when moving      *   FILE 625
//*    to a new data center.  The LISTCAT was for just the 3380     *   FILE 625
//*    packs and it did what was expected of it.  The program       *   FILE 625
//*    may not handle all possible file types, but it should be     *   FILE 625
//*    fairly easy to make the changes needed for them.             *   FILE 625
//*                                                                 *   FILE 625
//*         Under ISPF the input and output file names may          *   FILE 625
//*    either be requested by the program or entered as             *   FILE 625
//*    arguments on the command line.  Otherwise, it expects the    *   FILE 625
//*    input to be in the DDNAME INPUT and the output will go to    *   FILE 625
//*    the DDNAME OUTPUT so that it can easily be run in batch      *   FILE 625
//*    mode.                                                        *   FILE 625
//*                                                                 *   FILE 625
```
