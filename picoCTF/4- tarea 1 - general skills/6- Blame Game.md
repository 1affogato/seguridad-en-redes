# Reto
# Descripcion
Someone's commits seems to be preventing the program from working. Who is it?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/157/challenge.zip)
# Solucion

```
affogato1-picoctf@webshell:~/drop-in$ python message.py 
  File "/home/affogato1-picoctf/drop-in/message.py", line 1
    print("Hello, World!"
         ^
SyntaxError: '(' was never closed
affogato1-picoctf@webshell:~/drop-in$ nano message.py 
affogato1-picoctf@webshell:~/drop-in$ python message.py 
Hello, World!
affogato1-picoctf@webshell:~/drop-in$ git log
commit 2466febd40004b9ca644ce924181d07e23dcfaeb
Author: picoCTF{@sk_th3_1nt3rn_cfca95b2} <ops@picoctf.com>
Date:   Tue Mar 12 00:07:06 2024 +0000

    optimize file size of prod code
```
### Flag: picoCTF{@sk_th3_1nt3rn_cfca95b2}
# Notas
Al correr el python me dio error, lo arregle y no me dio nada mas. Revise el git log y hasta abajo en la lista de commits aparecio la bandera
# Referencias
