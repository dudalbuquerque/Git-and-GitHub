- **Branch**
```
git checkout -b nomep/branch //Para criar uma nova branch e alternar para ela ao mesmo tempo
git checkout nomedabranch //Muda seu diretório de trabalho para a branch especificada
git merge nomedabranchramificada //Combinar mudanças de duas branches em uma única branch
git branch -d nomedabranch  //Deleta a branch especificada

```
```
git branch  //lista todas as branchs que existem no repositório
git branch -v //lista o commit de cada branch
```
```
git fetch origin nomedabranch //Ele baixa as alterações (commits, branches, etc.) do repositório remoto para o seu repositório local, mas não aplica essas mudanças ao seu diretório de trabalho imediatamente
```
#### OBS: git pull = git fetch + git merge
```
git diff main origin/main  //Mostra as diferenças entre a branch local main e a branch main no repositório remoto
git merge origin/main   //Mescla as alterações da branch main do repositório remoto (origin) na sua branch atual
```
