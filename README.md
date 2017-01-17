# ansible-addloginuser

## vars

- username

## prepare

```bash
$ ssh-keygen -t rsa -b 4096 -C {{ mail }} -f ~/.ssh/{{ username }}-id_rsa
```
