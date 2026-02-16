# Reto
# Descripcion
Using a Secure Shell (SSH) is going to be pretty important.

Additional details will be available after launching your challenge instance.
# Solucion

```
affogato1-picoctf@webshell:~$ ssh ctf-player@titan.picoctf.net -p 58917 
ctf-player@titan.picoctf.net's password: 
Welcome ctf-player, here's your flag: picoCTF{s3cur3_c0nn3ct10n_3e293eea}
```
### Flag: picoCTF{s3cur3_c0nn3ct10n_3e293eea}
# Notas 
Challenge para conocer mejor ssh.
SSH utiliza criptografía para autenticar y encriptar las conexiones entre dispositivos. SSH también permite la tunelización, o redireccionamiento de puertos, que es cuando los paquetes pueden cruzar las redes que de otro modo no podrían cruzar.
# Referencias
https://www.cloudflare.com/es-es/learning/access-management/what-is-ssh/