# git-test-2

# Projeto Node.js com lite-server

Este repositório contém um projeto básico usando **Node.js** e **lite-server** para configuração de um ambiente de desenvolvimento web simples. O projeto utiliza o **NPM** para gerenciamento de dependências e o **Git** para controle de versão.

## O que foi feito

1. **Configuração do Ambiente**:
   - Foi criado um projeto em Node.js com o arquivo `package.json` para gerenciar as dependências.
   - O **lite-server** foi instalado para servir os arquivos estáticos e garantir a atualização automática do navegador durante o desenvolvimento.
   - O script `npm start` foi configurado para iniciar o servidor local.

2. **Execução do Servidor**:
   - Ao rodar o comando `npm start`, o servidor **lite-server** inicia e serve os arquivos do projeto na URL `http://localhost:3000`.

3. **Git para Controle de Versão**:
   - O código foi versionado com **Git** e o repositório foi inicializado no GitHub para acompanhamento do progresso do projeto.
   - O diretório `node_modules` foi adicionado ao `.gitignore` para evitar o versionamento de dependências.

## Como rodar o projeto

1. Clone o repositório para o seu ambiente local:
## Como rodar o projeto

1. Clone o repositório para o seu ambiente local:
git clone <URL do repositório>

arduino
Copiar código

2. Navegue até o diretório do projeto:
cd <diretório do projeto>

csharp
Copiar código

3. Instale as dependências com o NPM:
npm install

markdown
Copiar código

4. Inicie o servidor com:
npm start

markdown
Copiar código

5. Abra o navegador e acesse:
http://localhost:3000

markdown
Copiar código

## O que foi testado

- **Configuração do servidor**: O servidor deve iniciar corretamente e exibir os arquivos estáticos no navegador.
- **Execução do script**: O comando `npm start` deve iniciar o **lite-server** sem erros.
- **Versionamento com Git**: O repositório Git está funcionando corretamente com o código versionado.

## Tecnologias usadas

- **Node.js**: Ambiente de execução de JavaScript no servidor.
- **NPM**: Gerenciamento de pacotes e dependências.
- **lite-server**: Servidor de desenvolvimento simples com recarga automática do navegador.
- **Git**: Controle de versão do código.
