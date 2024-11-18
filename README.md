# get-windows-password-hashes-google-colab
Allows for getting the hashes of windows passwords by uploading 2 files, and then will return the hashes of the passwords. DISCLAIMER: ONLY USE THIS FOR GOOD PURPOSES!!! TESTING SECURITY, AND INFORMATION ONLY!!! DO NOT USE THIS FOR EVIL OR DESTRUCTIVE PURPOSES!!!

# secretsdump.py

https://colab.research.google.com/github/Samuel-Brzozowski/get-windows-password-hashes-google-colab/blob/main/secretsdump_py_return_windows_password_hashes.ipynb

# samdump2

https://colab.research.google.com/github/Samuel-Brzozowski/get-windows-password-hashes-google-colab/blob/main/samdump2_return_windows_password_hashes.ipynb

To get Windows SAM and SYSTEM files, (Located in: C:\windows\system32\config\SAM and C:\windows\system32\config\SYSTEM) enter these commands:

del "c:\sam"

del "%HOMEPATH%\Desktop\SAM"

reg save hklm\sam c:\sam

copy "c:\sam" "%HOMEPATH%\Desktop\SAM"

del "c:\system"

del "%HOMEPATH%\Desktop\SYSTEM"

reg save hklm\system c:\system

copy "c:\system" "%HOMEPATH%\Desktop\SYSTEM"

