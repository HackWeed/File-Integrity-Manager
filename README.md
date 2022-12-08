# File-Integrity-Manager
Hello Everyone This is a Project of CyberSecurity which is an integrity based project which is one of the most important term of Cyber Security i.e. CIA(Confidentiality, Integrity &amp; Authenticity) Triad

This Project is coded in Powershell Scripting which can be 
Implemented over a folder and it just look at all the files and 
captures the hashes of the files and then monitors them by continously 
checking the hashes of all the files contained by that particular folder/directory

as soon as any of the file gets any changes according to calculation made using hashes it will be giving alerts to the user 
alerts could be as follows:

<FILE_NAME> IS CHANGED  

<FILE_NAME> IS DELETED  

<FILE_NAME> HAS BEEN REMOvED  

to run the project just open fim,ps1 with powershell because it is a bash scriptand you will be looking at 2 options named as collect baseline and start monitoring. 

here if you select collect baseline the software will be collecting the hashes of all the files which would be there in the target folder ( can be modified in the source code ) which is Files by default and after collecting the baseline he window would be closed so you will be needing to open the same file with powershell again and then start monitoring it after selecting then it will be looking at all the activities of the files like mentioned above..



