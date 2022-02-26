# webserver_privesc
Compromise and Priv Esc of webserver (Linux)

(For ctf purposes only)

Find a way to upload file to webserver.
Use php-reverse-shell.php and change IP
rename php-reverse-shell.php > php-reverse-shell.phtml (if needed)

set up netcat listener  nc -lnvp 1234
Navigate to website/php-reverse-shell.phtml

To priv esc to root
Use PrivEsc markup.zip > unzip
Create file root.service and change kaliip > your ip
follow instructions
