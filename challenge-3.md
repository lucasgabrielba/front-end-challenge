# Desafio de Front-End: Formulário de Criação de Perfil

## Objetivo

Criar uma aplicação front-end que permita ao usuário criar um perfil preenchendo um formulário com seu nome, telefone, email, endereço e foto. A foto deve ser enviada utilizando um componente Dropzone.

## Requisitos

1. **Formulário de Criação de Perfil:**
   - O formulário deve ter campos para nome, telefone, email, endereço e foto.
   - O campo de foto deve utilizar um componente Dropzone para permitir o upload arrastando e soltando a imagem.

2. **Envio de Dados:**
   - Os dados do formulário devem ser enviados para uma API para serem salvos.

3. **Validação de Formulário:**
   - Todos os campos devem ser validados (e.g., campos obrigatórios, formato de email válido).

4. **Feedback Visual:**
   - O formulário deve exibir mensagens de erro em caso de validação falha.
   - Exibir uma mensagem de sucesso após o envio bem-sucedido.

5. **Interface Responsiva:**
   - A aplicação deve ser responsiva e funcionar bem em dispositivos móveis.

## Ferramentas e Tecnologias

- **React**: Biblioteca principal para construir a UI.
- **react-dropzone**: Biblioteca para implementar a funcionalidade de dropzone para o upload de fotos.
- **Axios**: Biblioteca para fazer requisições HTTP.
- **CSS/Styled Components**: Para estilização.


## Passos para Implementação

1. **Configuração Inicial:**
   - Configure um novo projeto React usando `create-react-app`.

2. **Instalação de Bibliotecas:**
   - Instale as bibliotecas `axios` e `react-dropzone` com `npm install axios react-dropzone`.

3. **Componente de Formulário:**
   - Crie um componente `ProfileForm` para gerenciar a entrada de dados do usuário.

4. **Componente Dropzone:**
   - Crie um componente `Dropzone` para gerenciar o upload de fotos.

5. **Gerenciamento de Estado:**
   - Utilize o `useState` e `useEffect` para gerenciar os dados do formulário e o estado da aplicação.

6. **Validação de Formulário:**
   - Implemente a validação para todos os campos do formulário.

7. **Envio de Dados:**
   - Configure o envio de dados para a API utilizando `axios`.

8. **Estilização:**
   - Estilize a aplicação para torná-la visualmente agradável e responsiva.