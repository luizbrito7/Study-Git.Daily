## Day 01 

```
# desfaz as alterações no arquivo 
git restore
```

```
# retira o arquivo da staged area 
git restore --staged
```

O comando ```git remote``` é responsável por adicionar a conexão entre o repositório local e o remoto, sendo possível ter um ou mais repositórios remotos conectados ao repositório local. 

Para enviar as alrerações para um o repo remoto específico é necessário no push informar o nome do remote. 

ex: git push <origem> <branch>

Para listar os repos remotos é possível atráves do comando ```git remove -v```

Para remover um repo remoto segue o comando ```git remote rm <nome-repo-remoto>```
