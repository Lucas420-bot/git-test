# Git Test

Este repositório serve como exemplo para criar e configurar um projeto Node.js com `npm init`, configurar um servidor de desenvolvimento com `lite-server`, e iniciar o servidor localmente.

## Requisitos

- **PowerShell** (Versão mais recente recomendada)  
  Baixe a versão mais recente para obter novos recursos e aprimoramentos: [PowerShell](https://aka.ms/PSWindows)
- **Node.js** e **npm**  
  Verifique se o Node.js e o npm estão instalados corretamente. Em um terminal, use o comando `node -v` para verificar a versão do Node.js.

## Inicialização do Projeto

1. No PowerShell, navegue até o diretório do projeto e inicie o `npm init` para configurar o arquivo `package.json`:

   ```powershell
   PS C:\LUCAS FRANÇA\workspace\package.json\git-test> npm init
{
  "name": "git-test",
  "version": "1.0.0",
  "description": "descricao",
  "main": "index.js",
  "scripts": {
    "test": "echo \\\"Error: no teste specified\\\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Lucas420-bot/-git-test.git"
  },
  "keywords": [],
  "author": "José Lucas",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/Lucas420-bot/-git-test/issues"
  },
  "homepage": "https://github.com/Lucas420-bot/-git-test#readme"
}
