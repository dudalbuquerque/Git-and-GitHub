# Resumo Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub

## 📔documentação
- [Documentação GitHub](https://docs.github.com/pt)  
- [Documentação Git](https://git-scm.com/docs/git/pt_BR)


## 💻 Resumos
- **Criando um Repositório**
```
mkdir nomedorepositorio //cria repositório
cd nomedorepositorio  //entra no repositório
git init   //inicializa o repositório
cd .git   //verificação
```
- **Criando arquivo**
```
touch nomearquivo  //usado para criar um arquivo vazio ou para atualizar a data e hora de modificação de um arquivo existente
```

- **Clonando um Repositório**
```
git clone (https or ssh do repositório) 
git clone (https or ssh do repositório) --branch nomedabrach --single-branch //clona apenas a branch especificada, se não especificada será clonada a branch principal
```

- **Outros comandos**
```
cd pathdorepositorio  //entra no repositório
cd .git  //navega para a pasta .git, onde tem subpastas e arquivos que contreolam o estado do repositório.
```
```
cd .git
cat config  //exibe o que contém nas configurações do repositório
```
```
git status //Mostra o estado atual do repositório, incluindo arquivos modificados, adicionados, ou não rastreados
```


- **Repositório Remoto**
```
git remote add origin (https do repositório) //adiciona a um repositório remoto 
git remote -v  //verifica o path do repositório remoto
```


- **Desfazendo alterações no repositório local**
```
git restore   //descarta última mudança feita no arquivo
```
```
git comit --amend -m"nova mensagem"  //altera a mensagem do último commit
git commit --amend //abre o editor da mensagem 
esc + : + w //para escrever
esc + : + q //para sair
```
```
git reset (--soft or --mixed or --hard) (hashing do commit)
git reset nomedoarquivo  //remove o arquivo da área de preparação
git restore --staged  //remove também
```

- **Enviando alterações para Repositório Remoto**
```
git remote add origin (https or ssh)
git branch -M main   //se -> master
git push -u origin main   //envia o branch main para o repositório remoto origin
git pull  //atualizar o repositório local com as alterações mais recentes do repositório remoto
```


- Outros comandos 
```
git stash   //arquiva suas alterações não commitadas
git stash list  //lista a pilha de alterações arquivadas
git stash apply //recuperar suas alterações salvas
git stash pop  //aplicar e remover da pilha de alterações arquivadas 
git stash drop stash@{0}   //remove alterações específicas
git stash clear  //limpa a pilha
```

## 🔗 Links 
| Link | Descrição | 
|-------------|-------------|
| [GitFluence](https://gitfluence.com/) | IA para entender e aplicar conceitos relacionados ao Git e ao GitHub|
| [MyOctocat](https://myoctocat.com/) | Ferramenta interativa que permite aos usuários criar um avatar personalizado do Octocat, a mascote do GitHub |
| [ProGit](https://git-scm.com/book/en/v2) | Livro da documentação do Git |
| [Conventional commits](https://github.com/conventional-commits/conventionalcommits.org) | Convenções ultilizadas para mensagens nos commits |  



***
Made with 🤍 by evas(dudalbuquerque)

