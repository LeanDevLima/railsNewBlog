# 📚 Blog de Livros

Este é um projeto de blog de livros criado com Ruby on Rails. O blog registra os livros que você leu este ano, incluindo informações como o título do livro, o autor, a nota que você atribuiu ao livro e uma descrição.

## 🔧 Configuração do Projeto

Para executar este projeto em sua máquina local, siga as etapas abaixo:

1. Clone o repositório para sua máquina, você pode usar o comando `git clone https://github.com/LeanDevLima/railsNewBlog.git`.

2. Navegue até o diretório do projeto e instale as dependências usando o Bundler, o comando `bundle install` resolve.

3. Execute as migrações do banco de dados usando o comando `rails db:migrate`.

4. Inicie o servidor local usando o comando `rails server`.

5. Em seguida, abra um navegador da web e acesse [http://localhost:3000](http://localhost:3000) para acessar o blog de livros.

## 📖 Funcionalidades do Blog

O blog permite que você:

- Adicione informações sobre os livros que você leu, incluindo título, autor, nota e descrição.
- Liste todos os livros que você registrou.
- Edite as informações de um livro existente.
- Exclua um livro da lista.

## 📊 Modelagem de Dados

O projeto utiliza um único modelo de dados: `Book`. O arquivo de modelo está localizado em `app/models/book.rb`. Foram adicionadas validações para garantir que o título e o autor de um livro sejam fornecidos.

## 🚀 Rotas

As rotas do projeto estão definidas em `config/routes.rb`. A rota raiz (`root 'books#index'`) direciona a página inicial para listar todos os livros.

## 👥 Contribuições

Fique à vontade para contribuir com melhorias para este projeto. Se você deseja adicionar recursos adicionais, correções de bugs ou melhorias no estilo, sinta-se à vontade para enviar uma solicitação de pull.
