# SSH server
## @edt ASIX M06-ASO Curs 2021-2022

### SSH Images:

 * **edtasixm06/ssh21:base**


``` 
docker run --rm --name ldap.edt.org -h ldap.edt.org --net 2hisix -d edtasixm06/ldap21:grup
docker run --rm --name ssh.edt.org -h ssh.edt.prg --net 2hisix -d edtasixm06/ssh21:base
```
