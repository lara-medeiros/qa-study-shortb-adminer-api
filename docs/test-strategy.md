# Cenários de testes para login e cadastro ShortBeyond:

## Cenários de testes para Login:

- Login do usuário com sucesso
- Login de um usuário com senha inválida
- Login com email inválido
- Login sem preencher email
- Login sem preencher a senha
- Login de usuário sem cadastro
- Login sem payload
- Login com senha contendo espaços ou caracteres especiais
- Login após múltiplas tentativas falhas
- Login com conta inativa ou excluída
- Login usando método HTTP inválido
- Login com email excedendo limite de caracteres (255)


## Cenários de testes para Cadastro:

- Cadastro de um novo usuário
- Cadastro com uma senha inválida
- Cadastro com um email inválido
- Cadastro sem inserir 'nome' do usuário
- Cadastro sem o 'email' ser informado
- Cadastro com um 'email' já cadastrado (existente)
- Cadastro com 'email' que já foi cadastrado porém 'excluído'
- Cadastro com um 'email' que utilize um 'alias'
- Cadastro com email excedendo o limite de caracteres (255)
- Cadastro com senha excedendo o limite de caracteres (255)
- Cadastro utilizando um email temporário
- Cadastro sem payload


