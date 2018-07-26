# Med-DNA
Installation: 

A.Windows:

    1. Download the windows directory.
  
    2. If you dont have any DICOM viewer and GDCM installed on your pc, you need to install them first.
    You can do it just by double clicking "installer.bat" file. 
    
    3. Then you can run the software by double
    clicking the "software.jar" file.
    
B.Linux


About Sofrware:

This software takes in the whole genome sequence of a person, lengths of all chromosomes, start
and end positions of coding regions as inputs before we can use it for archiving DICOM and
other files.The whole genome sequence has to be uploaded to the software as a folder which has seperate
files in FASTA format corresponding to each chromosome.  Moreover, the lengths of all chro-
mosomes are in a .txt file; start and end positions of coding regions are in a separate .txt file.
If all inputs are valid, the software displays a list of files already stored in the input genome
sequence.  User can add one or multiple new file provided that genome has enough capacity
left. There are two options for retrieving a stored file - user can select file(s) from displayed list
to view; the software reconstructs original file(s) and opens with default viewer in system, or
save a file to any location of system. Finally user can remove one or multiple files, then the files
will be removed from displayed filelist too.

sudo apt-get update
sudo apt-get install python-gdcm
sudo apt install libgdcm-tools
