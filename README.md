# Contrato
Consumir uma API Json-Server, efetuando um GET na API e usando o Mocha com Joi-Assert e Joi-Validate sendo validado por um esquema de contrato.

## Pré-requisito

É necessário a instalação do node e npm, para instalar digite em seu terminal:

```
brew install node
```

É necessário também a instalação do Json-Server:

```
npm install -g json-server
```

## Clonando o repositório

Clone o Repositório:

```
git clone https://github.com/andreluaz/contrato.git
```

## Instalação das dependências:

Após a clonagem do repositório digite:

```
npm install
```

Isto fará a instalação das dependências necessárias para a execução dos testes.

## Iniciando o json-server

Iniciar o Json-Server:

```
json-server --watch info.json
```

## Execução dos Testes

Para executar os testes, abra uma nova aba no terminal e digite:

```
mocha contrato.js
```

## Arquitetura do Projeto

```
├── README.md
├── contrato.js           - Testes de GET e POST
├── info.json             - Arquivo usado pelo Json-server
├── node_modules          - Dependências instaladas
├── package-lock.json     - Versões das dependências instaladas
└── package.json          - Dependências usada no projeto
└── schema                - Schemas usados para os testes de contrato
    └── info.js
```

## Referências

Link para maiores informações sobre o joi-assert: https://www.npmjs.com/package/joi-assert

