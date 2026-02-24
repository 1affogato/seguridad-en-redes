# Reto
# Descripcion
What was I last working on? I remember writing a note to help me remember...You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/163/challenge.zip)
# Solucion

```
affogato1-picoctf@webshell:~/drop-in$ ls -la
total 12
drwxr-xr-x 3 affogato1-picoctf affogato1-picoctf   49 Mar 12  2024 .
drwxr-xr-x 6 affogato1-picoctf affogato1-picoctf 4096 Feb 23 23:22 ..
drwxr-xr-x 8 affogato1-picoctf affogato1-picoctf 4096 Mar 12  2024 .git
-rw-r--r-- 1 affogato1-picoctf affogato1-picoctf   87 Mar 12  2024 message.txt
affogato1-picoctf@webshell:~/drop-in$ git log
commit e65fedb3a72a16c577f4b17023b63997134b307d (HEAD -> master)
Author: picoCTF <ops@picoctf.com>
Date:   Tue Mar 12 00:07:29 2024 +0000

    picoCTF{t1m3m@ch1n3_88c35e3b}
(END)
```
### Flag: picoCTF{t1m3m@ch1n3_88c35e3b}
# Notas
Al hacer cat en el txt no aparece nada relevante y al hacer ls -la para ver el interior de la carpeta parece que es un repositorio al ver el git log aparecio la bandera.
# Referencias
