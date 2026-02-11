# Reto
## Descripcion
This file has a flag in plain sight (aka "in-the-clear").
## Solucion

```
affogato1-picoctf@webshell:~$ wget https://challenge-files.picoctf.net/c_wily_courier/eaf5dbd32acd6d3318c402247156552fc789474a5328dc436404e97932ab34c3/flag
--2026-02-10 05:30:02--  https://challenge-files.picoctf.net/c_wily_courier/eaf5dbd32acd6d3318c402247156552fc789474a5328dc436404e97932ab34c3/flag
Resolving challenge-files.picoctf.net (challenge-files.picoctf.net)... 3.160.5.18, 3.160.5.95, 3.160.5.64, ...
Connecting to challenge-files.picoctf.net (challenge-files.picoctf.net)|3.160.5.18|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 34 [application/octet-stream]
Saving to: 'flag'

flag                100%[==================>]      34  --.-KB/s    in 0s      

2026-02-10 05:30:02 (32.1 MB/s) - 'flag' saved [34/34]

affogato1-picoctf@webshell:~$ cat flag
picoCTF{s4n1ty_v3r1f13d_9b8fa0bc}
```
### Flag: picoCTF{s4n1ty_v3r1f13d_9b8fa0bc}
## Notas
## Referencias