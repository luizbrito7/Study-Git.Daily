## Day 2 

### Objetivos 

- deletar branch 
- criar branch 
- renomear branch 
- entender o merge das branchs 

comando para renomeara uma branch: 

```
git branch -m old-branch new-branch
```

Comando para deletar uma branch, porém tem que ficar atento a um detalhe:

- se o merge da branch que está tentando ser deletada não foi feito o merge ainda com o parametro -d vai retornar um erro, para forçar a exclusão utilize o parametro -D

```
git branch -d <nome-da-branch>
```


