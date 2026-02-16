# Reto
# Descripcion
Fix the syntax error in the Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/5/fixme2.py)
# Solucion

```
affogato1-picoctf@webshell:~$ python fixme2.py 
  File "/home/affogato1-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
affogato1-picoctf@webshell:~$ nano fixme2.py 
affogato1-picoctf@webshell:~$ python fixme2.py 
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_4863e11b}
```
### Flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_4863e11b}
# Notas
Estaba mal la sintaxis de un if y tuve que meterme a editarlo para que me diera la bandera
# Referencias
