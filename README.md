Conque-Shell
============

Run interactive commands inside a Vim buffer 

This is a mirror of https://code.google.com/p/conque/

Conque is a Vim plugin which allows you to run interactive programs, such as bash on linux or powershell.exe on Windows, inside a Vim buffer. In other words it is a terminal emulator which uses a Vim buffer to display the program output.

== WEBSITE ==

For more information http://code.google.com/p/conque/

== SCREENSHOTS ==

http://Conque.googlecode.com/svn/wiki/screenshot/unix.jpg
http://Conque.googlecode.com/svn/wiki/screenshot/windows.jpg

== USAGE ==

Type :ConqueTerm <command> to run your command in vim, for example:

:ConqueTerm bash
:ConqueTerm mysql -h localhost -u joe -p sock_collection
:ConqueTerm Powershell.exe
:ConqueTerm C:\Python27\python.exe

To open ConqueTerm in a new horizontal or vertical buffer use:

:ConqueTermSplit <command>
:ConqueTermVSplit <command>
:ConqueTermTab <command>

All text typed in insert mode will be sent to your shell. Use the <F9> key to send a visual selection from any buffer to the shell.

For more help type :help ConqueTerm
