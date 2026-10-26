# Sistema de Login

Interface estática em HTML contendo páginas de login e de cadastro de usuários.

## Funcionalidades

- **Página de Login (`Index.html`)**:
  - Formulário com campo de e-mail (`type="email"`, placeholder `"E-mail"`), campo de senha (`type="password"`, placeholder `"Senha"`) e botão `"Entrar"`.
  - Link `"Criar conta"` que redireciona para `cadastro.html`.
- **Página de Cadastro (`cadastro.html`)**:
  - Formulário com campo de nome (`type="text"`, placeholder `"Nome"`), campo de e-mail (`type="email"`, placeholder `"E-mail"`), campo de data de nascimento (`type="date"`, placeholder `"Data de Nascimento"`), campo de senha (`type="password"`, placeholder `"Senha"`) e botão `"Cadastrar"` (`type="submit"`).
- **Validações e Mensagens**:
  - Apenas validação nativa do HTML5 nos campos `type="email"` e seletor nativo no campo `type="date"`. Não possui validações customizadas, mensagens de feedback ou processamento de dados em JavaScript.

## Tecnologias

- HTML5

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/mths-machado/sistema-login.git
   ```
2. Acesse a pasta do projeto e abra o arquivo `Index.html` diretamente no navegador.

## Autor

Matheus Machado Oliveira, [LinkedIn](https://www.linkedin.com/in/mths-dev)
