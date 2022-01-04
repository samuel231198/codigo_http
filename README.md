# Códigos HTTP
Lista de alguns códigos HTTP mais comuns.

## Success

| Código | Nome | Descrição |
| ------------- | ------------- | ------------- |
| 200 | OK | Resposta a um bem-sucedido GET, PUT, PATCH ou DELETE. Também pode ser usado para um POST que não resulte em uma criação. |
| 201 | Created | Em requisições POST quando um recurso é criado. |
| 204 | No Content | Resposta a uma requisição bem-sucedida que não retorna um corpo (requisição DELETE). |

## Redirecionamento

| Código | Nome | Descrição |
| ------------- | ------------- | ------------- |
| 301 | Moved Permanently | Base para criação de encurtadores de URL. |
| 304 | Not Modified | Usado ao lidar com cabeçalhos de cache HTTP. |

## Erros do cliente da API

| Código | Nome | Descrição |
| ------------- | ------------- | ------------- |
| 400 | Bad Request | O pedido é malformado; não foi possível fazer o parse do corpo. |
| 401 | Unauthorized | Cliente não está autenticado ou os dados de autenticação são inválidos. |
| 403 | Forbidden | A autenticação foi bem-sucedida, mas o usuário autenticado não tem acesso ao recurso. |
| 404 | Not Found | Recurso solicitado não existe. |
| 405 | Method Not Allowed | Método HTTP que não é permitido para o usuário autenticado. |
| 415 | Unsupported Media Type | Se o content type incorreto foi fornecido como parte do pedido. |
| 422 | Unprocessable Entity | Usado para validação de erros. |

## Erros do servidor

| Código | Nome | Descrição |
| ------------- | ------------- | ------------- |
| 500 | Erros do servidor | Erro genérico indicando um problema de execução no servidor (cliente pode fazer chamar novamente se faz sentido) |
