# Desafio 1: Formulário e Listagem de Fibonacci

## Objetivo

Criar uma aplicação front-end que permita ao usuário inserir seu nome e um número. A aplicação deve enviar esses dados para uma API, que calcula o número de Fibonacci correspondente e armazena o resultado no banco de dados. A aplicação deve exibir uma lista com o nome do usuário e o resultado de Fibonacci retornado pela API.

## Requisitos

1. **Formulário de Entrada:**
   - O usuário deve poder inserir seu nome e um número.
   - O formulário deve ter um botão para enviar os dados.

2. **Envio de Dados:**
   - Os dados do formulário devem ser enviados para a API.
   - A API retorna o nome do usuário e o resultado do cálculo de Fibonacci.

3. **Listagem de Resultados:**
   - A aplicação deve exibir uma lista com os nomes e os resultados de Fibonacci recebidos da API.

4. **Interface Responsiva:**
   - A aplicação deve ser responsiva e funcionar bem em dispositivos móveis.

## Ferramentas e Tecnologias

- **React**: Biblioteca principal para construir a UI.
- **Axios**: Biblioteca para fazer requisições HTTP.
- **CSS/Styled Components**: Para estilização.

## Passos para Implementação

1. **Configuração Inicial:**
   - Configure um novo projeto React usando `create-react-app`.

2. **Instalação do Axios:**
   - Instale a biblioteca `axios` com `npm install axios`.

3. **Componente de Formulário:**
   - Crie um componente `Form` para gerenciar a entrada de dados do usuário.

4. **Componente de Listagem:**
   - Crie um componente `ResultList` para exibir os resultados de Fibonacci recebidos da API.

5. **Gerenciamento de Estado:**
   - Utilize o `useState` e `useEffect` para gerenciar os dados dos formulários e os resultados da listagem.

6. **Estilização:**
   - Estilize a aplicação para torná-la visualmente agradável e responsiva.

