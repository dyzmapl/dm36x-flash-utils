/****************************************************************
 *  TI CCS-based NOR Flashing utility for C672x                 *
 *  (C) 2008, Texas Instruments, Inc.                           *
 *                                                              *
 * History: 18-Aug-2008 - v1.00 release                         *
 *                                                              *
 ****************************************************************/

Usage
=====
1.  Set your device in emulation boot mode.
2.  Open CCS with the appropriate GEL file loaded.
3.  Connect to the DM6437 EVM in CCS (Alt+C).
4.  Load the DM643x_NORWriter.out file (located in \build\debug).
5.  Run the program.
6.  When prompted for the AIS binary, supply the AIS file generated by the 
    DM6437_AISGen utility, or by the genAIS.pl perl script.
7.  Downloading the application can take some time...be patient.
8.  When complete, you will see various status messages indicating erasure
    and writes are complete.
9.  Disconnect the board from CCS (Alt+C).
10. Remove power, change bootmode switches to NOR Fastboot.
11. Restore power and application will boot and execute.
