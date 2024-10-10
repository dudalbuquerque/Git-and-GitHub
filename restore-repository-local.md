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
