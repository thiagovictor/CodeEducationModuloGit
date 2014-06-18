#Passos para primeiro push

Inicialize o git dentro do diret�rio definido como reposit�rio dos c�digos
```
git init
```
Ap�s criar o reposit�rio, crie o arquivo README.md
```
touch README.md
```
Escrevendo arquivo README utilizando linguagem Markdown.
```
vim README.md
```
Preparando os arquivo(s) para commit
```
git add README.md
```
Adicionando os arquivos ao controle de vers�o.
```
git commit -m "Meu primeiro commit"
```
Criando repositorio remoto
```
git remote add origin git@github.com:thiagovictor/CodeEducationModuloGit.git
```
Enviando para repositorio remoto
```
git push origin master
```

**Pronto, reposit�rio criado e enviado ao reposit�rio remoto**