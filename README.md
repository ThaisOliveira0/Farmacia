# Loja Virtual de Farmácia

Este projeto é o protótipo de uma **Loja Virtual de Farmácia**, desenvolvido para atender ao segundo trabalho da disciplina de **Programação em Script**. A loja tem como objetivo proporcionar uma experiência de compra online de medicamentos e produtos farmacêuticos, com funcionalidades de navegação entre categorias, cadastro de clientes, carrinho de compras, e exibição de produtos de forma simples e intuitiva.

## Objetivos do Trabalho

O objetivo deste trabalho é desenvolver um protótipo funcional de uma loja virtual com as seguintes características:
- Escolha de um seguimento para a loja, neste caso, farmácia.
- Implementação de funcionalidades básicas de um comércio online, como navegação entre categorias, cadastro de usuários, e carrinho de compras.
- Disponibilização do projeto de forma online para visualização e testes.

## Funcionalidades

1. **Página Principal**:
   - Conta a história do surgimento das farmácias e contem cards com os membros da equipes.
   - Menu de navegação com as abas do site.
   - Rodapé com informações de identificação da loja.

2. **Página de Catálogo**:
   - Exibe os produtos, com informações de preço, quantidade e botão de compra.

3. **Página de Listagem de Produtos**:
   - Exibe um relatório dos produtos da loja, com as colunas: código, descrição, unidade, quantidade em estoque e preço de venda.

4. **Página de Cadastro de Usuário/Cliente**:
   - Formulário para cadastro de usuário, incluindo informações como nome, e-mail, CPF, senha, telefone e endereço (com preenchimento automático via API de CEP).

5. **Carrinho de Compras**:
   - Exibe os produtos selecionados, com a possibilidade de visualizar,alterar e finalizar a compra.

## Tecnologias Utilizadas

- **HTML5**: Estrutura básica das páginas.
- **CSS**: Estilos e layout para uma aparência agradável e funcional.
- **JavaScript**: Funcionalidades dinâmicas, como a interação com o carrinho de compras e navegação AJAX.
- **AJAX**: Utilizado para carregar páginas de conteúdo sem recarregar toda a página, proporcionando uma navegação fluida.
- **API de CEP**: Para preenchimento automático do endereço durante o cadastro de usuários.

## Como Usar

**Clone o Repositório:**
Para clonar o repositório, utilize o seguinte comando:

```bash
git clone https://github.com/ThaisOliveira0/Farmacia.git```

**Abra o Projeto:**Abra os arquivos no seu editor de código preferido.

**Visualize no Navegador:**Abra o arquivo index.html no seu navegador para visualizar a loja em funcionamento.

## Como Usar
## Estrutura do Projeto
A estrutura de arquivos do projeto é a seguinte:

index.html: Página principal da loja virtual.
catalogo.html: Exibe os produtos organizados por categoria.
listagem.html: Relatório com a listagem de todos os produtos.
cadastro.html: Formulário para o cadastro de novos clientes.
carrinho.html: Página de visualização e finalização da compra.
style.css: Arquivo de estilos para o design da loja.
script.js: Arquivo JavaScript que contém as funcionalidades dinâmicas, como a navegação e interações com o carrinho.
