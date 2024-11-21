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


## Como usar?  
1. **Clone o repositório**: Baixe o repositório para o seu computador usando o comando:  
   ```bash
   git clone https://github.com/ThaisOliveira0/Farmacia.git
   
2. **Abra o arquivo index.html:** Use um navegador de sua escolha para visualizar a aplicação.
3. **Navegue pelas páginas:** Utilize os links de navegação para visualizar a loja em funcionamento.

## Estrutura do Projeto
A estrutura de arquivos do projeto é a seguinte:

- `index.html`: Página principal da loja virtual.
- `produtos.html`: Exibe os produtos organizados contindos no banco de dados.
- `lista.html`: Relatório com a listagem de todos os produtos.
- `sobre.html`:Contém as informações da loja, como o endereço e informações de contato.
- `formulario.html`: Formulário para o cadastro de novos clientes.
- `login.html`:Formulário para clientes que ja possuem contas.
- `carrinho.html`: Página de visualização e finalização da compra.
- `styles.css`: Arquivo de estilos para o design da loja.
- `app.js`: Arquivo JavaScript que contém o consumo da API e outras funcionalidades.

  Este projeto segue o modelo **MVC** (Model-View-Controller), que é uma arquitetura comum para separar as responsabilidades e tornar o código mais organizado e fácil de manter.

### O que é o MVC?

- **Model**: Representa os dados da aplicação e a lógica de negócios. No nosso caso, é a parte responsável pela interação com o banco de dados, como o gerenciamento de produtos e usuários.
  
- **View**: É a interface com o usuário, ou seja, o que o usuário vê e interage. No nosso projeto, são as páginas HTML e os arquivos de estilo CSS que definem a aparência da loja virtual.
  
- **Controller**: Faz a intermediação entre o Model e a View, processando as entradas do usuário e manipulando os dados. Em nosso projeto, a lógica de navegação e interações dinâmicas, como a manipulação do carrinho de compras, é feita pelo arquivo JavaScript.

### Como o MVC é aplicado no Projeto?

- **Model**: Os dados dos produtos e dos usuários são gerenciados no banco de dados, e as interações com esses dados são realizadas no backend. (Exemplo: `script.js` e arquivos de conexão com o banco de dados).
  
- **View**: As páginas HTML (`index.html`, `catalogo.html`, etc.) são responsáveis por exibir as informações de forma organizada e agradável para o usuário.

- **Controller**: A lógica de interações e manipulação de dados, como adicionar produtos ao carrinho e buscar informações de usuários, é gerida no arquivo `script.js`.

Este padrão MVC ajuda a manter o código organizado e facilita futuras manutenções e expansões do sistema.

### Acessando pela Web:

O projeto está disponível online, onde você pode acessar a loja diretamente por meio do seguinte link:

[**Acesse a Loja Virtual**](http://projetoprogscript.great-site.net/farmacia/Trabalho2/index.html)

Basta clicar no link acima para visualizar a loja em funcionamento.

## Conexão com o Banco de Dados

Este projeto está integrado a um banco de dados para armazenar e gerenciar os dados dos produtos e dos usuários. Para utilizá-lo localmente, siga as instruções abaixo.

### Usando o XAMPP:

1. **Baixe e instale o XAMPP**: Caso não tenha o XAMPP instalado, baixe e instale a partir de [aqui](https://www.apachefriends.org/index.html).
2. **Inicie o XAMPP**: Abra o painel de controle do XAMPP e inicie os módulos Apache e MySQL.
3. **Acesse o phpMyAdmin**: Vá para `http://localhost/phpmyadmin/` em seu navegador.
4. **Crie o banco de dados**: Importe o arquivo SQL fornecido.
5. **Configure a conexão com o banco de dados**: Certifique-se de que os detalhes de conexão com o banco de dados no código estão configurados corretamente (como host, nome de usuário, senha, etc.).
6. **Acesse o site localmente**: Depois de iniciar o Apache e o MySQL, você pode acessar a loja em `http://localhost/farmacia/views`.

## Quer contribuir?
Se você tem sugestões ou melhorias para o projeto, fique à vontade para abrir um pull request ou relatar problemas na seção de issues!
