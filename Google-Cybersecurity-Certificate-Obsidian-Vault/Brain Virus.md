Brain is the industry standard name for a computer virus that was released in its first form on 19 January 1986, and is considered to be the first computer virus for the IBM Personal Computer (IBM PC) and compatibles.

## Description

Brain affects the PC by replacing the boot sector of a floppy disk with a copy of the virus. The real boot sector is moved to another sector and marked as bad. Infected disks usually have five kilobytes of bad sectors. The disk label is usually changed to ©Brain, and the following text can be seen in infected boot sectors:

    Welcome to the Dungeon (c) 1986 Amjads (pvt) Ltd VIRUS_SHOE RECORD V9.0 Dedicated to the dynamic memories of millions of viruses who are no longer with us today - Thanks GOODNESS!!! BEWARE OF THE er..VIRUS : this program is catching program follows after these ....$#@%$@!!

There are many minor and major variations to that version of the text. The virus slows down the floppy disk drive and makes seven kilobytes of memory unavailable to DOS. Brain was written by Amjad Farooq Alvi, who at the time lived in Chah Miran, near Lahore Railway Station, in Lahore, Pakistan. The Alvi brothers told Time magazine they had written it to protect their medical software from illegal copying, and it was supposed to target copyright infringement only. The cryptic message "Welcome to the Dungeon", a safeguard and reference to an early programming forum on Dungeon BBS, appeared after a year because the brothers licensed a beta version of the code. The brothers could not be contacted to receive the final release of this version of the program.

Brain lacks code for dealing with hard disk partitioning, and avoids infecting hard disks by checking the most significant bit of the BIOS drive number being accessed. Brain does not infect the disk if the bit is set, unlike other viruses at the time, which paid no attention to disk partitioning and consequently destroyed data stored on hard disks by treating them in the same way as floppy disks. Brain often went undetected, partially due to this deliberate non-destructiveness, especially when the user paid little to no attention to the low speed of floppy disk access.

The virus came complete with address and three phone numbers, and a message that told the user that their machine was infected and to call them for inoculation:

    Welcome to the Dungeon © 1986 Amjads (pvt). BRAIN COMPUTER SERVICES 730 NIZAM
    BLOCK ALLAMA IQBAL TOWN LAHORE-PAKISTAN PHONE: 430791,443248,280530. Beware of this VIRUS.... Contact us for vaccination...

This program was originally used to track a heart monitoring program for the IBM PC, and people were distributing illicit copies of the disks. This tracking program was supposed to stop and track illegal copies of the disk, however the program also sometimes used the last five kilobytes on an Apple floppy, making additional saves to the disk by other programs impossible. 

Taken from https://en.wikipedia.org/wiki/Brain_(computer_virus)