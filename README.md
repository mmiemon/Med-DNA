# Med-DNA
Installation: 

A.Windows

    1. Download the windows directory.
  
    2. If you dont have any DICOM viewer and GDCM installed on your pc, you need to install them first.
    You can do it just by double clicking "installer.bat" file. 
    
    3. Then you can run the software by double clicking the "software.jar" file.
    
B.Linux
  
    1. Download the Linux_Mac directory. 
    2. Run the following commands to install GDCM. 
       sudo apt-get update
       sudo apt-get install python-gdcm
       sudo apt install libgdcm-tools
    3. Give executive permission to the file "software.jar".
       chmod +x software.jar
       Then you can run the software by double clicking the "software.jar" file.
 
 C.MAC
 
     1.You need to have brew installed on your mac. 
     2.The run the following command. 
       brew update
       brew install python-gdcm
       brew install libgdcm-tools
     3.Then you can run the software by double clicking the "software.jar" file.
       
  

Cromosome file:

You can download Chromosome files from following link.

https://drive.google.com/open?id=1wSoMo0tgrqCKAH21L2vvTv72PTE9SmyV

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

