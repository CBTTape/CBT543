# CBT543
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 543 is from David Barnard-Brown, and contains REXX        *   FILE 543
//*           execs and an Assembler program, to display system     *   FILE 543
//*           information.                                          *   FILE 543
//*                                                                 *   FILE 543
//*      email:    ext.b_m.barnard-brown@sncf.fr                    *   FILE 543
//*                                                                 *   FILE 543
//*      phone:    03 28 55 62 19    (SNCF : 22 52 19)              *   FILE 543
//*                03 28 55 63 09    (SNCF : 22 53 09)              *   FILE 543
//*                                                                 *   FILE 543
//*      SNCF - DSIV - GL-XL                                        *   FILE 543
//*      Centre Informatique de Lille                               *   FILE 543
//*      Pont de Tournai - 59041 LILLE CEDEX                        *   FILE 543
//*                                                                 *   FILE 543
//*   Short Description:                                            *   FILE 543
//*                                                                 *   FILE 543
//*      I have written some REXX code to display System            *   FILE 543
//*      Information.                                               *   FILE 543
//*                                                                 *   FILE 543
//*      I wrote it initially to verify a system after an IPL,      *   FILE 543
//*      and it grew from there.                                    *   FILE 543
//*                                                                 *   FILE 543
//*      The utility is called 'CHECKSYS'.                          *   FILE 543
//*                                                                 *   FILE 543
//*      It now uses pop-up ISPF panels, an assembler program       *   FILE 543
//*      ('cause I could not do it in REXX) and REXX.               *   FILE 543
//*                                                                 *   FILE 543
//*      I also continued to develop it as a means of               *   FILE 543
//*      understanding how OS/390 holds together and to utilize     *   FILE 543
//*      some of the 'fancier' statements of REXX.                  *   FILE 543
//*                                                                 *   FILE 543
//*      'CHECKSYS' has been verified on OS/390 2.6 and OS/390      *   FILE 543
//*      2.8.  Because I am contracting here in France, some of     *   FILE 543
//*      the characters used to define screen attributes, and       *   FILE 543
//*      used by REXX (! instead of |), may not operate             *   FILE 543
//*      correctly when used elsewhere.                             *   FILE 543
//*                                                                 *   FILE 543
//*      There is one part of this package written in Assembler.    *   FILE 543
//*      It is the member called GETUADDR, to return a UCB          *   FILE 543
//*      address, given a volume name.                              *   FILE 543
//*                                                                 *   FILE 543
//*     - - - - - - - - - - - - - - - - - - - - - - - - - - - - -   *   FILE 543
//*                                                                 *   FILE 543
//*      I have broken CHECKSYS up into it's individual             *   FILE 543
//*      compmnents.                                                *   FILE 543
//*                                                                 *   FILE 543
//*      This way, you can call the component directly, or you      *   FILE 543
//*      can still use CHECKSYS.                                    *   FILE 543
//*                                                                 *   FILE 543
//*      The components are:                                        *   FILE 543
//*                                                                 *   FILE 543
//*      APF - list out the current APF.                            *   FILE 543
//*      ASL - simple Address Space monitoring utility.             *   FILE 543
//*      LNK - list out the current Linklist.                       *   FILE 543
//*      LPA - list out the current LPA list                        *   FILE 543
//*      MAP - display Storage Map.                                 *   FILE 543
//*      STR - Display the Storage Usage.                           *   FILE 543
//*      SYS - display the System paramaters.                       *   FILE 543
//*      VER - display the Software Versions.                       *   FILE 543
//*                                                                 *   FILE 543
//*      For example:                                               *   FILE 543
//*                                                                 *   FILE 543
//*      You can call 'TSO LPA' directly, or still use the          *   FILE 543
//*      original CHECKSYS,                                         *   FILE 543
//*                                                                 *   FILE 543
//*      'TSO CHECKSYS LPA' or 'TSO CHECKSYS 5' or just 'TSO        *   FILE 543
//*      CHECKSYS' and select option 5.                             *   FILE 543
//*                                                                 *   FILE 543
```
