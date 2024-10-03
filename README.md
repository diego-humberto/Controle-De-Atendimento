Controle de Atendimento

Este projeto é um aplicativo móvel desenvolvido em Ionic, que gerencia senhas de atendimento. O aplicativo possui funcionalidades para criar e chamar senhas, além de gerar relatórios sobre as senhas emitidas.

Estrutura do Projeto:
O projeto é dividido em três abas principais:

1. Clientes: 
   - Permite criar senhas priorizadas, gerais e de exame.
   - Exibe a senha criada em um campo de entrada.

2. Atendente:
   - Permite chamar a próxima senha da fila.
   - Exibe informações sobre a senha chamada, incluindo data e hora de atendimento.

3. Relatórios:
   - Exibe relatórios sobre o total de senhas emitidas, senhas gerais, priorizadas e de exame.
   - Lista todas as senhas emitidas com data e hora.

## Tecnologias Utilizadas:

- **Ionic Framework**: Para construção do aplicativo móvel.
- **Angular**: Para gerenciamento de componentes e estrutura do projeto.

## Instruções para Execução

### Pré-requisitos

- Node.js
- Ionic CLI

### Passos para Execução

1. Clone o repositório:

   ```bash
   git clone https://github.com/diego-humberto/Controle-de-Atendimento
   cd controle-atendimento

2. Instale as dependências:

   ```bash
   npm install

3. Inicie o servidor de desenvolvimento:

  ```bash
  ionic serve
