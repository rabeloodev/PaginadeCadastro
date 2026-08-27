# Página de Cadastro e Login

Projeto de uma interface simples para criação de conta e acesso de usuários. A aplicação é feita com HTML e CSS, sem dependências externas ou integração com banco de dados.

## Páginas

### Criar conta (`index.html`)

É a página inicial do projeto. Nela, o usuário informa:

- Nome de usuário, com no mínimo 3 caracteres;
- E-mail, validado pelo navegador como endereço de e-mail;
- Senha, com no mínimo 8 caracteres.

O botão **Criar minha conta** envia o formulário. O link **Entrar** direciona para `login.html`.

### Login (`login.html`)

Permite que um usuário informe o nome de usuário, o e-mail e a senha para acessar a conta. Os campos possuem as mesmas validações básicas da página de cadastro.

O botão **Entrar na minha conta** envia o formulário. O link **Criar uma conta** retorna para `index.html`.

## Estilo

As duas páginas usam o arquivo `style.css`, que define:

- Tema escuro com detalhes em roxo;
- Formulário centralizado em um painel;
- Estados de foco e interação nos campos e botões;
- Layout responsivo para telas menores.

## Estrutura do projeto

```text
.
├── index.html    # Página de criação de conta
├── login.html    # Página de login
├── style.css     # Estilos compartilhados
└── README.md     # Documentação do projeto
```

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Navegue entre cadastro e login pelos links disponíveis nas páginas.

Também é possível usar uma extensão como o Live Server no VS Code para visualizar o projeto localmente.

## Observação

Este projeto contém apenas a interface. Os formulários usam `action="#"`, portanto não salvam usuários nem autenticam credenciais. Para colocar o fluxo em produção, será necessário conectar os formulários a um backend e implementar armazenamento seguro e autenticação.

## Link do Site
https://rabeloodev.github.io/PaginadeCadastro/index.html

