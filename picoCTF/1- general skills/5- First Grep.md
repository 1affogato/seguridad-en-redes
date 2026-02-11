# Reto
## Descripcion
Can you find the flag in the file? This would be really tedious to look through manually, something tells me there is a better way.
## Solucion

```
affogato1-picoctf@webshell:~$ wget https://challenge-files.picoctf.net/c_fickle
_tempest/92807684f3e52665caaf90d69e1e661f990b8731b2f8005e18631be23ff991bb/file
--2026-02-10 05:25:25--  https://challenge-files.picoctf.net/c_fickle_tempest/92807684f3e52665caaf90d69e1e661f990b8731b2f8005e18631be23ff991bb/file
Resolving challenge-files.picoctf.net (challenge-files.picoctf.net)... 3.160.5.95, 3.160.5.18, 3.160.5.64, ...
Connecting to challenge-files.picoctf.net (challenge-files.picoctf.net)|3.160.5.95|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 14546 (14K) [application/octet-stream]
Saving to: 'file'

file                100%[==================>]  14.21K  --.-KB/s    in 0.001s  

2026-02-10 05:25:25 (26.6 MB/s) - 'file' saved [14546/14546]

affogato1-picoctf@webshell:~$ cat file | grep "picoCTF"
```
### Flag: grep_is_good_to_find_things_eb80073D
## Notas
wget es una herramienta de línea de comandos importante de Linux que permite descargar archivos de Internet.
El comando grep es útil para buscar una expresión regular o una cadena en un archivo de texto.
## Referencias
https://www.ionos.es/digitalguide/servidores/configuracion/comando-wget-de-linux/

https://www.swhosting.com/es/blog/uso-del-comando-grep-en-sistemas-linux-unix#:~:text=Comando%20grep%20en%20Linux,en%20un%20archivo%20de%20texto.