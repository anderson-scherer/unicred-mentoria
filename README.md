
# unicred-mentoria

# Desafio: Projeto inicial
Desenvolver o [projeto](https://github.com/anderson-scherer/unicred-mentoria) entreque no figma, com apenas uma preocupação, ficar parecido com o protótipo.

**Objetivo?**: a cada encontro, aprimorar o projeto, aplicando boas práticas de desenvolvimento.

**O que posso Utilizar?** apenas HTML e CSS sem uso de pré-processadores, bibliotecas, frameworks

# Comandos Úteis
## GIT
Recomendação de leitura: [Controlando versões com Git e GitHub](https://www.casadocodigo.com.br/pages/sumario-git-github)
### Configurando a conta local
```bash
$ git config --global user.email [email_cadastro_git]
$ git config --global user.name [nome]
```
### Clonando um projeto
Acessar o repositório onde está presente o código de trabalho, validar a url que será utilzada através do método escolhido, HTTPS ou SSH.
Seguir os passos solicitados, no caso de uso de HTTPS, será solicitado usuário e senha.
```bash
$ git clone https://github.com/user/projeto.git
```
### Adicionado arquivos
Adicionar todos os arquivos modificados de uma única vez.
```bash
$ git add .
```
Adicionando arquivo único ou em lote.
```bash
$ git add [path]/[nome_do_arquivo]
```
```bash
$ git add [path]/[nome_do_arquivo]  [path]/[nome_do_outro_arquivo]
```
### Adicionando mensagem de commit
```bash
$ git commit -m "Aqui uma mensagem do que foi feita, máximo 50 caracteres"
```
### Enviado para o repositório
```bash
$ git push origin [branch]
```
