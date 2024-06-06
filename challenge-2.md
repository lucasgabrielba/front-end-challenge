# Desafio 2: Dropzone Upload Application

## Objetivo

Criar uma aplicação que permita ao usuário arrastar e soltar arquivos em uma área específica para fazer upload. A aplicação deve listar os arquivos enviados e permitir a remoção de arquivos individuais.

## Requisitos

1. **Área de Dropzone:**
   - O usuário deve poder arrastar e soltar arquivos em uma área destacada na interface.
   - Alternativamente, o usuário deve poder clicar na área para selecionar arquivos através do explorador de arquivos.

2. **Listar Arquivos Enviados:**
   - Após o upload, os arquivos devem ser listados abaixo da área de dropzone com detalhes como nome e tamanho do arquivo.

3. **Remover Arquivos:**
   - O usuário deve ser capaz de remover arquivos individuais da lista de uploads.

4. **Feedback Visual:**
   - A área de dropzone deve mudar visualmente quando um arquivo é arrastado sobre ela para indicar que o usuário pode soltar o arquivo ali.

5. **Interface Responsiva:**
   - A aplicação deve ser responsiva e funcionar bem em dispositivos móveis.

## Ferramentas e Tecnologias

- **React**: Biblioteca principal para construir a UI.
- **react-dropzone**: Biblioteca para implementar a funcionalidade de dropzone.
- **CSS/Styled Components**: Para estilização.

## Passos para Implementação

1. **Configuração Inicial:**
   - Configure um novo projeto React usando `create-react-app`.

2. **Instalação do react-dropzone:**
   - Instale a biblioteca `react-dropzone` com `npm install react-dropzone`.

3. **Componente Dropzone:**
   - Crie um componente `Dropzone` para gerenciar a área de upload de arquivos.

4. **Componente de Lista de Arquivos:**
   - Crie um componente `FileList` para exibir os arquivos enviados.

5. **Gerenciamento de Estado:**
   - Utilize o `useState` para gerenciar os arquivos enviados.

6. **Estilização:**
   - Estilize a aplicação para torná-la visualmente agradável e responsiva.
