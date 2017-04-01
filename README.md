# aix1.3i386
aix1.3i386 : virtualbox 5.1.16 test image 


[host os ] 

           linux centos6.8     ok

           windows-xp ~ 10     ok
           
           macos-10.12.3       ok


#step1  virtualbox install  https://www.virtualbox.org/wiki/Downloads

#step2  aix.ovf import


#step3  booting
        
        
        1. floppy diskette insert     :01atboot1.img
        
        2. start virtual box guest os :AIX1.3i386 start
        
        3. boot form Diskette choice
        
        4. Module to be loaded : unix.gen   enter
        
        5. System mode         : Single User enter
        
        6. Run system from hard disk : No --> Yes(space bar) enter
       
        7. floppy diskette insert     :02atboot2.img  enter 
        
        8. Do you want to enter system maintenance (single user) mode ? <n> n
        
        9. su -
        
        10. have a nice day~~~^^
        
        
        
        
        
        
        
        

