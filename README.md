# Time to Answer

## Sobre
O projeto **Time to Answer** é um site de perguntas e respostas desenvolvido durante o curso [**Ruby on Rails 5.x - Do início ao fim!**](https://www.udemy.com/course/rubyonrails-5x/) do Jackson Pires com o intuito de colocarmos em prática todo conteúdo estudado durante o curso.

## Algumas tecnologias utilizadas
- [Ruby](https://www.ruby-lang.org/pt/) (2.7.8)
- [Rails](https://rubyonrails.org/) (6.1.7.6)
- HTML
- CSS
- JavaScript

## Algumas ferramentas utilizadas
- [Devise](https://github.com/heartcombo/devise) para autenticação
- [Rails-I18n](https://github.com/svenfuchs/rails-i18n) para internacionalização
- [Kaminari](https://github.com/kaminari/kaminari) para paginação

## Instruções para uso
Clone o projeto em sua máquina e instale as dependências do projeto com os comandos:
```bash
bundle
yarn
```

Logo após, crie o banco de dados com:
```bash
rails db:create
rails db:migrate
```

Para inicializar o banco de dados com dados, rode:
```bash
rails dev:setup
```

Levante e rode a aplicação com:
```bash
rails s
```
E, finalmente, acesse ```http://localhost:3000``` no seu navegador.

---

## Telas do Projeto

### Página inicial
![index](images/index.png)

### Busca por área
![Busca](images/busca_area.png)

### Busca por termo
![Busca termo](images/busca_termo.png)

### Login
![Login](images/login.png)

### Esqueceu a senha
![Esqueceu a senha](images/esqueceu_senha.png)

### Cadastro de usuário
![Cadastrar](images/cadastrar.png)

---

## Área do Usuário

### Página inicial do usuário
![User index](images/user_index.png)

### Perfil do usuário
![User perfil](images/user_perfil.png)

### Editar perfil
![User perfil editar](images/user_perfil_editar.png)

### Editar foto do perfil
![User perfil editar foto](images/user_perfil_editar_foto.png)

### Editar nome do usuário
![User perfil nome](images/user_perfil_nome.png)

### Página inicial do usuário - Respondendo perguntas
![User index resposta errada](images/user_index_resposta_errada.png)

![User index resposta certa](images/user_index_resposta_certa.png)

### Perfil do usuário - Respostas
![User perfil respostas](images/user_perfil_respostas.png)