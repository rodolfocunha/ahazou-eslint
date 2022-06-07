# Ahazou Eslint Config

Configuração global de eslint para projetos web da Ahazou.

## 1. Instalação

### 1.1. Repository
Certifique-se de ter o arquivo `.npmrc` no root do projeto com a configuração do reposity e _authToken

```txt
//npm.pkg.github.com/:_authToken=${github_auth_token}
registry=https://npm.pkg.github.com/ahazou

```

Para saber mais [clique aqui](https://help.github.com/pt/github/managing-packages-with-github-packages/configuring-npm-for-use-with-github-packages)

### 1.2. Rodar o comando

```shell
npm install @ahazou/stylelint-config
```

## 2. Observações

A publicação do pacote já está automatizada com Github Actions, após a criação de um release automaticamente uma nova versão será gerada.