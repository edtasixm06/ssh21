# SSH server
## @edt ASIX M06-ASO Curs 2021-2022

Podeu trobar les imatges docker al Dockehub de [edtasixm06](https://hub.docker.com/u/edtasixm06/)

Podeu trobar la documentació del mòdul a [ASIX-M06](https://sites.google.com/site/asixm06edt/)

ASIX M06-ASO Escola del treball de barcelona


### SSH Images:

 * **edtasixm06/ssh21:base**


``` 
docker run --rm --name ldap.edt.org -h ldap.edt.org --net 2hisix -d edtasixm06/ldap21:latest
docker run --rm --name ssh.edt.org -h ssh.edt.prg --net 2hisix -d edtasixm06/ssh21:base
```
