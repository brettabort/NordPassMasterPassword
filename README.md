# NordPassMasterPassword
VBScript to Input Master Password into NordPass on Windows. This is assuming authentication via browswer has already occured with Nord.

## TO RUN ##
Edit NordPassMasterPassword in notepad and change <masterpassword> to your "MasterPassword".

Have assumed that the default path of NordPass.exe is located within AppData\Local\Programs\nordpass of C:\Users\Username. Have assigned a variable strUserName and called the %USERNAME% environment string to hopefully make the script run natively. If the NordPass window isn't populating, hardcode the location of the exe.

## TO ADD TO STARTUP 
Execute RunOnStartup.vbs 
  
## WARNING ##
I have added an automatic reboot command at the end to reset your machine and check to see if it works. If you don't want to execute this command, edit RunOnStartup in notepad and remove the last line.
  
## Uninstall ##
To uninstall access Startup menu via 'Run shell:startup' and delete NordPassMasterPassword.vbs
  
## Have a great day! ##
  
