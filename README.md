# Viacep - Estudo e Treinamento

## Sobre o Projeto

Este é um projeto de formulário de cadastro simples, desenvolvido com HTML, CSS e JavaScript. **Este projeto foi copiado de uma fonte externa** como parte do meu processo de **estudo e treinamento** em desenvolvimento web. O objetivo principal foi praticar a manipulação de formulários, input de dados e estilização de componentes em HTML e CSS.

O projeto original não foi criado por mim, mas o processo de replicação me permitiu ganhar familiaridade com a estrutura de formulários web e a lógica básica para coleta e validação de dados do usuário.

## Funcionalidades

- **Formulário de Cadastro**: O formulário coleta dados como nome, email, CEP, endereço, número da casa, bairro, cidade e estado.
- **Validação Básica**: Os campos são validados como "requeridos" para garantir que o usuário preencha todas as informações necessárias antes de submeter o formulário.
- **Estilização Responsiva**: O formulário foi estilizado com CSS, e a disposição dos campos foi feita para ser amigável em diferentes tamanhos de tela.
  
## Tecnologias Utilizadas

Este projeto foi replicado utilizando as seguintes tecnologias:

- **HTML5**: Estruturação do formulário e elementos de input.
- **CSS3**: Estilização do layout e das interações visuais.
- **JavaScript (ES6+)**: Manipulação de dados no frontend e validação simples de campos.

## Código de Destaque

O código abaixo representa a manipulação do evento de clique no botão de salvar:

```javascript
document.getElementById('btn').addEventListener('click', function() {
    const nome = document.getElementById('nome').value;
    const email = document.getElementById('email').value;
    const cep = document.getElementById('cep').value;
    // Validação de outros campos
    console.log(`Nome: ${nome}, Email: ${email}, CEP: ${cep}`);
});
