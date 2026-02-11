# Reto
# Descripcion
Can you look at the data in this binary? The bash script might help![static](https://challenge-files.picoctf.net/c_wily_courier/418e2775a501eaabeb99a96c5c467a83539369fe9649e8234644250cfb72d717/static), [ltdis.sh](https://challenge-files.picoctf.net/c_wily_courier/418e2775a501eaabeb99a96c5c467a83539369fe9649e8234644250cfb72d717/ltdis.sh)
# Solucion 1

```
affogato1-picoctf@webshell:~$ file *
README.txt: ASCII text, with escape sequences
ltdis.sh:   Bourne-Again shell script, ASCII text executable
static:     ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, BuildID[sha1]=9a00d4dca6b92d22aa0cd1fceffa4ed7495b8534, for GNU/Linux 3.2.0, not stripped
affogato1-picoctf@webshell:~$ chmod +x ltdis.sh 
affogato1-picoctf@webshell:~$ ./ltdis.sh static
Attempting disassembly of static ...
Disassembly successful! Available at: static.ltdis.x86_64.txt
Ripping strings from binary with file offsets...
Any strings found in static have been written to static.ltdis.strings.txt with file offset
affogato1-picoctf@webshell:~$ cat static.ltdis.strings.txt | grep pico
   3020 picoCTF{d15a5m_t34s3r_20335e41}
```

# Solucion 2

```
affogato1-picoctf@webshell:~$ strings static | grep pico
picoCTF{d15a5m_t34s3r_20335e41}
```
### Flag: picoCTF{d15a5m_t34s3r_20335e41}
# Notas

# Referencias
