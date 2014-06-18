#Passos para primeiro push

Inicialize o git dentro do diretório definido como repositório dos códigos
```
git init
```
Após criar o repositório, crie o arquivo README.md
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
Adicionando os arquivos ao controle de versão.
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

**Pronto, repositório criado e enviado ao repositório remoto**