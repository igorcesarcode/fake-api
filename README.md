## Fake API from my-json-server
DB de um pequeno servidor de teste usado para realizar teste de API e aplicação.
com ele você consegue simular um fake api em a necessidade de ter algo na sua maquina, simulando de forma mais real o funcionamento de uma api real.

## Como funciona?

Utilizando o serviço do site [my-json-server](https://my-json-server.typicode.com/) e com um repositório no GitHub você consegue manter uma pequena api.

1.  Crie um repositório no GitHub ( [**`<seu-username>/<nome-do-repositorio>`**](https://github.com/typicode/demo))
2.  Crie um **`db.json`**arquivo
3.  Visite `https://my-json-server.typicode.com/<seu-username>/<nome-do-repositorio>` para acessar seu servidor

**Sem registro.** Nada para instalar.

## Exemplo

Você pode verificar o seguinte servidor como exemplo:  
[https://my-json-server.typicode.com/igorcesarcode/fake-api](https://my-json-server.typicode.com/igorcesarcode/fake-api)

## Beta

No momento, o projeto está em **beta, o** que significa que muitas coisas podem mudar ou quebrar:

-   URLs podem mudar
-   O serviço pode estar fora do ar
-   A autenticação pode ser adicionada mais tarde
-   etc ...

Use-o por sua própria conta e risco. Se você precisar de uma solução **confiável** , **instale o** [servidor JSON](https://github.com/typicode/json-server) .

## Limites

Para poder fornecer um serviço gratuito ao maior número de pessoas possível durante esta fase, o projeto vem com alguns limites:

-   **As alterações são falsas e não são persistentes** (assim como [JSONPlaceholder](https://jsonplaceholder.typicode.com/) )
-   As solicitações são armazenadas em cache ( `1 minuto`)
-   `db.json` tem limites
-   Todos os servidores são `publico`
-   Repositórios GitHub privados (ainda) não são suportados