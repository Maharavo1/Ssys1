# Ssys1@@ -0,0 +1,48 @@
 SOLUTION LEVEL ROOT ME : 


A)----------FTP Authentication------------- :
     1)Download the subject
     2)Open the ch1 file with wireshark
     3)Right click on the FTP protocol and follow it in TCP stream


B) -----------TIWTER Authentication----------: 
     1)Download the subject .
     2 ) Decode the Hex in the file and convert to String.
     3 ) Decode the password which has base 64 .

C)  ---------TELNET Authentication----------- : 
      1 ) Download the subject .
      2 ) Open the file on Wirashark (Name of the folder : ch2.pcap) .
      3 ) Search on the search bar --> telnet .
      4 ) Right click on the TCP stream --> follow --> TCP stream --> solution of our challenge .



D)----------- BLUETOOTH - Unknown file------------:
     1)Download the subject
     2)Open the ch18 file with wireshark
     3)Click on wireless and go to "Bluetooth devices" to identify the mac address of the pc and the name of the phone
     4)Concatenate the mac address with the phone name and convert all lowercase letters to uppercase
     5)Encode in SHA1 and we get the password


E)-------------- ETHERNET Frame----------------:
     1 )Download the subject .
     2) new tab containing hexadecimal codes will open
     3)Decode these characters using ASCII converter
     4)We find a string of characters encoded in base 64 then we decode and the password is displayed.


