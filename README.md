# testbranch
Para teste de varias branch

# comandos utilizados

* Para criar uma branch
```sh
$ git checkout -b 'develop'
```

* Para deletar uma branch
```sh
$ git checkout -d 'develop'
```

* Para voltar sua branch
```sh
$ git checkout develop
```
* ou
```sh
$ git checkout master
```

* Para fazer merge com sua versão
```sh
$ git merge --no-ff myfeature
``` 

> A flag no-ff faz com que o merge sempre crie um novo objeto commit,
> mesmo se esse merge pudesse ser realizado com um fast-forward.
> Isso evita perda de informações sobre a existência histórica de um 
> ramo e agrupa todas os commits juntos.
