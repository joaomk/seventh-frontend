# Formulário de Validação

Este projeto foi desenvolvido como parte do teste para desenvolvedor fullstack na Seventh. Ele consiste em um formulário simples com validação de campos utilizando HTML, CSS e JavaScript.

## Descrição

O formulário possui os seguintes campos:

- **Nome**: Campo de texto para o nome do usuário.
- **Email**: Campo de texto para o email do usuário.
- **Botão de envio**: Botão para submeter o formulário.

### Funcionalidades

1. **Validação de Campos**:

   - Ao clicar no botão de envio, o JavaScript verifica se os campos "Nome" e "Email" estão preenchidos.
   - Caso algum campo esteja vazio, uma mensagem de erro será exibida: **"Por favor, preencha todos os campos."** e o campo vazio será destacado com uma borda vermelha.
   - Se todos os campos estiverem preenchidos, uma mensagem de sucesso será exibida: **"Formulário enviado com sucesso!"**.

2. **Estilização**:
   - O formulário possui uma estilização simples e responsiva, com destaque para mensagens de erro e sucesso.

## Estrutura do Projeto

O projeto contém apenas um arquivo HTML que inclui o código HTML, CSS e JavaScript necessários para o funcionamento do formulário.

### Arquivo: `index.html`

- **HTML**: Estrutura do formulário com campos de entrada e botão de envio.
- **CSS**: Estilos para o layout do formulário, mensagens de erro e sucesso.
- **JavaScript**: Lógica de validação dos campos e exibição das mensagens.

## Como Executar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. Preencha os campos do formulário e clique no botão "Enviar" para testar a validação.

## Exemplo de Uso

1. **Caso de erro**:

   - Deixe um ou ambos os campos vazios e clique em "Enviar".
   - A mensagem **"Por favor, preencha todos os campos."** será exibida, e os campos vazios serão destacados.

2. **Caso de sucesso**:
   - Preencha ambos os campos e clique em "Enviar".
   - A mensagem **"Formulário enviado com sucesso!"** será exibida.

## Tecnologias Utilizadas

- **HTML5**: Estrutura do formulário.
- **CSS3**: Estilização do formulário e mensagens.
- **JavaScript**: Validação dos campos e manipulação do DOM.

## Autor

Este projeto foi desenvolvido por João Vitor da Silva como parte do teste prático para a Seventh.
