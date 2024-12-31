# Users-Reg

Uma API onde cadastramos um usuário pelo nome e email. Seu id é gerado automaticamente e as informações são salvas em um arquivo .json local para a persistencia de dados.

Query Parameters
  http://localhost:3333/users?name=Lucas -> URL Stateful -> Filtros, paginação, não-obrigatório
Route Parameters
  GET or DELETE http://localhost:3333/users/1 -> Identificação de rescurso
Request Body
  POST http://localhost:3333/users -> Envio de informações de um formulário (HTTPs)

Exemplo de body para o POST:
{
	"name": "Jhon Doe",
	"email": "jhondoe@email.com"
}

## Funcionalidades
- Cadastro, listagem, exclusão e filtragem de usuários.

## Pré-requisitos
- Node.js

## Instalação
1. Clone o repositório: 
  ```
  https://github.com/daniellichotti/users-reg.git
  ```
2. Instale as dependências:
   ```
   npm install
   ```
3. Instale as dependências:
   ```
   npm run dev
   ```

Se tudo foi feito corretamente ja sera possivel ver a aplicacao rodando no emulador.

## Tecnologias
Node.js

## Contribuição
Contribuições são bem-vindas! Abra uma issue ou envie um pull request.

## Licença
- 
