# Resumo Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub

## 📔documentação
[Documentação GitHub](https://docs.github.com/pt)
[Documentação Git](https://git-scm.com/docs/git/pt_BR)

## 💻 Resumos
- Criando um Repositório
```
mkdir nomedorepositorio //cria repositório
cd nomedorepositorio  //entra no repositório
git init   //inicializa o repositório
cd .git   //verificação
```

- Clonando um Repositório
```
git clone (https or ssh do repositório)
```

- Outros comandos
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
```
git add  nomerepositorio  //adiciona o arquivo
git add .   //adiciona todos os arquivos
```

- Repositório Remoto
```
git remote add origin (https do repositório) //adiciona a um repositório remoto 
git remote -v  //verifica o path do repositório remoto
```

- Commit 
```
git commit -m "Mensagem explicativa do commit"  //salva as alterações ou mudanças (nos arquivos versionados) no histórico de um repositório Git
```
```
git log  //exibe o histórico de commits
git reflog  //histórico detalhado
```
```
touch nomearquivo  //usado para criar um arquivo vazio ou para atualizar a data e hora de modificação de um arquivo existente
```

- Desfazendo alterações no repositório local
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
git reset (--soft or --mixed or --hard) hashing do commit 
git reset nomedoarquivo  //remove o arquivo da área de preparação
git restore --staged  //remove também
```


