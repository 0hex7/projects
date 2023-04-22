# projects

contains the projects that i have worked upon till now.



1.Ransomware

    - I created a ransomware in python language. This ransomware is just a smal version of the actual Ransomwares.
    - We need to give the following command in the terminal in the directory in which the Ransomware is present.
    
          $ python ransomware.py -e test-folder -s 32
               - e stands for encryption
               - 32 is the length alloted for the salt(to make the password more stronger)
               - test-folder is the dummy folder on which we are running the Ransomware to encrypt it. You can create a dummy folder with some documents.
               - give a simple password for the encryption process and dont forget it as it is needed for decryption process.
         
         
          $ python ransomware.py -d test-folder
               - the above command decrypts the test-folder.
               - to decrypt we need to enter the password that was entered while encrypting.
               
               
               
               
      

2.Password generator

    - No special modules needed for this project.
    - we can use the below command to get all the available options 
    
          $ python password_generator.py --help
               - the above command lists out all the possible commands and methods to run the program
               
               
3.Keylogger

   - Uses mail or the local directory to store the key strokes that are captured.
   
4.Portscanner

   - Scans for any open ports in a host.
   - We must give the ip address of the target for scanning the ports.
