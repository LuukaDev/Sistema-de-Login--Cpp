# Sistema-de-Login---C++

Sistema de Autenticação de Usuários em C++
Este projeto implementa um sistema simples de autenticação de usuários em C++ com três funcionalidades principais: Registro, Login e Recuperação de Senha.

Funcionalidades

1. **Registro**
   - Usuários podem se registrar com um nome de usuário, email e senha.
   - Os dados são armazenados em um arquivo `Login.data.txt`.

2. **Login**
   - Usuários podem fazer login fornecendo nome de usuário e senha.
   - As credenciais são verificadas com os dados armazenados.

3. **Recuperação de Senha**
   - Usuários podem recuperar a senha fornecendo nome de usuário e email.
   - Caso as credenciais coincidam, a senha é exibida.

## Estrutura do Arquivo
- **`Login.data.txt`**: Armazena os dados dos usuários no formato:
  ```
  nome_de_usuario*email*senha
  ```

## Visão Geral do Código

- **`SignUp()`**: Coleta os detalhes do usuário e os adiciona ao arquivo de dados.
- **`Login()`**: Verifica as credenciais do usuário com os dados armazenados.
- **`Forgot()`**: Recupera a senha do usuário se o nome de usuário e o email coincidirem.

## Exemplo de Interação
```
1. Entrar na conta
2. Registrar conta
3. Esqueci a senha
4. Sair

Qual será a opção escolhida :: 2

Registre seu nome :: João
Registre seu Email :: joao@exemplo.com
Registre sua Senha :: minha_senha
```




