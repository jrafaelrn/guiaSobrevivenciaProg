## Seção 1  

### 1.1 - O `git merge` é usado para unir duas bases de código diferentes (cada uma em sua respectiva branch) e basicamente isso é feito criando automaticamente um novo commit que une os "ramos" destas branchs. Por outro, o `git rebase` altera o histórico dos commits no ramo, permitindo anexar de forma linear um série de commits de outra branch. Na prática, o resultado final no código será o mesmo, a diferença principal fica no histórico dos commits, alterando assim a forma de se interpretar como se deu o avanço no desenvolvimento do código.  
<br>

### 1.2 - Uma forma de resolver um conflito é criando outro commit após o arquivo em questão ser atualizado. Os arquivos que estão em conflito podem ser verificadoa com o `git status`, após isso é necessário abri-los e localizar os "marcadores de conflito", decidir qual parte do código deverá ser mantida, digitar o comando `git add .` e por fim fazer um `git commit` e `git push`.

<br>   

---

## Seção 2

### 2.1 - Comandos:
- `git commit -m 'Comentário Nova Branch'`
- `git push -u origin NovaBranch`

### 2.2 - `git fetch`


<br>

---

## Seção 3
Link: GitHub
