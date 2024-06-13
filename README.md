# RC4-Encryption-Decryption-
Rivest Cipher 4 Algorithm 

# Implementation
This program is written for Windows Based application , has it uses "SystemFunction033" which is defined in NTDLL.DLL

# Usage 
Generate an payload with msfvenom ,
-like for example = "msfvenom --platform windows -p windows/exec cmd=calc.exe -f c --var-name encrypted_payload"

Just Replace the payload you generated inside the encrypted.cpp file and vice versa for decryption just paste it in the decrypted.cpp file

Note : The Payload should not be in string format it should be in hex format
