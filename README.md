# git-stuff

Para cambiar de ambiente localmente y dar un tracking es con este comando:
```shell
# git checkout <branch-en-servidor> i.e.
cmd> git checkout dev

```

### Requerimiento: 
Se necesita crear un nuevo archivo
Ejemplo: numero de ticket que es provisto por un sistema de gestion de requerimientos

```shell
# git checkout -b <tipo de item>/<item#> i.e.
cmd> git checkout -b feature/12345
```

Para poder subir mis cambios al servidor tengo que crear un pull request
Este pull request va a ser revisado por mi Tech Lead
* Avisa a tu tech lead cuando termines un feature y hayas creado el pull request

```shell
# para salvar tus cambios en tu branch actual
cmd> git add .
```