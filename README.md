# Engenharia de Software - 2024.1 | Universidade Federal do Tocantins
## PostMe
### Descrição

O PostMe é uma plataforma inovadora que permite aos usuários expressarem-se livremente, publicando fotos e textos em um feed dinâmico e interativo. Seja você um fotógrafo amador querendo compartilhar suas últimas capturas, um escritor aspirante buscando uma audiência para seus textos, ou simplesmente alguém que deseja compartilhar pedaços do seu dia-a-dia, o PostMe é o lugar perfeito para você.
### Definindo os requisitos e seus colaboradores.
---
#### Primeiro commit
- RF01 - Realizar Login do Usuário. Por [Cayke Daniel Pereira Veras](https://github.com/cayke1)

- RF02 - Realizar Cadastro do Usuário. Por [Caio Christhian Lopes Silva](https://github.com/CaioChristhian)

- RF03 - Realizar Publicações. Por [Henrique Noronha Fernandes](https://github.com/henrique-noronha)

- RF04 - Editar Perfil. Por [Ykaro Silva](https://github.com/ykarosilva)

- RF05 - Listagem de Publicações no feed. Por [Eduardo Henrique Coelho Ramos](https://github.com/KiwiProgamador)

## RF01 - Realizar Login do Usuário

### Atributos

|Item|Descrição|
| -- |    -    |
|Caso de Uso| Realizar Login do Usuário|
|Resumo| Permitir que um usuário cadastrado acesse as funcionalidades do site através de seu login e senha. O processo de login deve ser seguro e acessível para o usuário.|
|Ator principal| Usuário cadastrado no site.|
|Pré-condição|O ator principal deve estar cadastrado no sistema com um nome de usuário válido e uma senha válida.|
|Pós-condição|O ator principal deve estar autenticado no sistema.|

### Descrição sucinta 
Realizar o login do usuário na plataforma.

### Fluxo principal
1. O usuário acessa o blog do PostMe e é apresentada a tela inicial.
2. Na tela inicial, o usuário encontra um formulário de login com campos para preencher com seu nome de usuário e senha.
3. Após preencher o formulário, clica no botão "Login".
4. O sistema verifica os dados fornecidos pelo usuário.
   - Se correto, ele é redirecionado para a página inicial, autenticado no sistema.
   - Se estiver incorreto, irá retornar mensagens de erro no formulário de login.

### Campos do formulário de login:

| Campo            | Obrigatório? | Editável? | Formato      |
|------------------|--------------|-----------|--------------|
| Nome de Usuário  | Sim          | Sim       | Texto        |
| Senha            | Sim          | Sim       | Alfanumérico |

### Opções do usuário
| Opção                 | Descrição                                                      |
|-----------------------|----------------------------------------------------------------|
| Login no sistema      | Permite ao usuário acessar o sistema utilizando suas credenciais.|

### Relatório do usuário
| Campo                    | Descrição                                                                       | Formato |
|--------------------------|---------------------------------------------------------------------------------|---------|
| Autenticado com sucesso  | Assegura o usuário do resultado positivo da autenticação no sistema.            | Texto   |

### Fluxo alternativo
1. O ator não possui uma conta no sistema.
2. O ator clica no botão "Criar uma conta" e é redirecionado para tela de cadastro conforme o RF02.
