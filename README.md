# bloader.py: python serial port loader and interactive tty

"bloader.py" is a command line tool that is useful to upload files containing
Bitlash script to an Arduino using the USB serial port.

## Requirements:

- python
- pyserial from http://pyserial.wiki.sourceforge.net/pySerial
- pexpect from http://pexpect.sourceforge.net/pexpect.html
 	see also http://www.noah.org/wiki/Pexpect

## 	Usage:

1. Send a file of commands to Bitlash, line by line

	python bloader.py elevator2.btl

2. Upload file memdump to "bitlashsd" as md:

	python bloader.py memdump md

3. Open a serial terminal session with Bitlash:

	python bloader.py

4. To exit: Control+] (just like telnet)
