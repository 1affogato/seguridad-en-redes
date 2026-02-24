# Reto
# Descripcion
I accidentally wrote the flag down. Good thing I deleted it!You download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/137/challenge.zip)
# Solucion

```
affogato1-picoctf@webshell:~/drop-in$ git init
Reinitialized existing Git repository in /home/affogato1-picoctf/drop-in/.git/

affogato1-picoctf@webshell:~/drop-in$ git log
commit ef0b7cc6b98367fa168573c931e0f7098ef59182 (HEAD -> master)
Author: picoCTF <ops@picoctf.com>
Date:   Tue Mar 12 00:06:20 2024 +0000

    remove sensitive info

commit ea859bf3b5d94ee74ce5ee1afa3edd7d4d6b35f0
Author: picoCTF <ops@picoctf.com>
Date:   Tue Mar 12 00:06:20 2024 +0000

    create flag
	(END)

affogato1-picoctf@webshell:~/drop-in$ git checkout ea859bf3b5d94ee74ce5ee1afa3edd7d4d6b35f0
HEAD is now at ea859bf create flag

affogato1-picoctf@webshell:~/drop-in$ cat message.txt 
picoCTF{s@n1t1z3_cf09a485}
```
### Flag: picoCTF{s@n1t1z3_cf09a485}
# Notas
Al hacer ls -la aparece una carpeta de git y al ver los hints me di cuenta que trata sobre control de versiones, inicie git mire el log y cambie de version con checkout para volver a imprimir el message con la bandera
# Referencias
