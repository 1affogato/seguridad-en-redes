# Reto
# Descripcion
My team has been working very hard on new features for our flag printing program! I wonder how they'll work together?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/177/challenge.zip)
# Solucion

```
affogato1-picoctf@webshell:~/drop-in$ git branch -a
 feature/part-1
  feature/part-2
  feature/part-3
* main
(END)

affogato1-picoctf@webshell:~/drop-in$ git checkout feature/part-1
Switched to branch 'feature/part-1'
affogato1-picoctf@webshell:~/drop-in$ python flag.py 
Printing the flag...
picoCTF{t3@mw0rk_

affogato1-picoctf@webshell:~/drop-in$ git checkout feature/part-2
Switched to branch 'feature/part-2'
affogato1-picoctf@webshell:~/drop-in$ python flag.py 
Printing the flag...
m@k3s_th3_dr3@m_

affogato1-picoctf@webshell:~/drop-in$ git checkout feature/part-3
Switched to branch 'feature/part-3'
affogato1-picoctf@webshell:~/drop-in$ python flag.py 
Printing the flag...
w0rk_7ae8dd33}
```
### Flag: picoCTF{t3@mw0rk_m@k3s_th3_dr3@m_w0rk_7ae8dd33}
# Notas
Al ver el branch hice checkout a las versiones anteriores del repositorio, cada version me dio una parte de la contraseña para al final armarla
# Referencias
