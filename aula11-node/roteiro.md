# Roteiro para executar programa Javascript usando Node (backend)

1. Crie uma pasta para seu projeto. Neste repositório o nome da pasta será `aula11-node`, mas você tem a liberdade de usar o nome de pasta que faça sentido para seu projeto. No terminal, digite o comando abaixo:
```
mkdir projeto
```
2. Entre nessa pasta. 
```
cd projeto
```
3. Inicialize um projeto Node nesssa pasta com o comando. Observe que será criado o arquivo `package.json`:
```
npm init -y
```
4. Instale as bibliotecas que irá necessitar. Neste exemplo, vamos precisar da `prompt-sync`, para poder usar a função `prompt` para ler dados informados pelo usuário. Observe que será criada a pasta `node_modules` e o arquivo `package-lock.json`. Na pasta `node_modules` são instalados os programas que fazem parte da(s) biblioteca(s) desejada(s).
```
npm install prompt-sync
```
5. Neste ponto, devemos criar o arquivo `.gitignore` cujo objetivo é informar ao git para ignorar algumas pastas e arquivos de modo que não sejam versionados nem armazenados no Github. Fazemos isso para economizar espaço no repositório no Github e também para evitar versionar arquivos com informações sensíveis como senhas e chaves criptográficas. Criamos o arquivo `.gitignore` e colocamos o nome da pasta `node_modules` como conteúdo.
6. Para executar o seu programa:
```
node index.js
``` 