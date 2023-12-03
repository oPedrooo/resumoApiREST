# Api REST e RESTFul

Uma API REST (Representational State Transfer) é um conjunto de princípios arquiteturais que definem como os sistemas de software podem se comunicar pela internet. Ela utiliza os métodos padrão do protocolo HTTP (como GET, POST, PUT, DELETE) para realizar operações em recursos (dados) de um sistema.

Uma API RESTful é uma implementação de uma API seguindo os princípios REST, utilizando a estrutura e os padrões da arquitetura REST para criar serviços web que são flexíveis, escaláveis e fáceis de entender e utilizar. Ela é caracterizada por ser stateless (sem estado), ter uma interface uniforme, ser orientada a recursos e usar o protocolo HTTP de forma consistente para operações CRUD (Create, Read, Update, Delete) em dados.

## Diferenças entre REST e RESTFul

- REST: É um conjunto de princípios arquiteturais que define como sistemas podem se comunicar na web. Ele especifica diretrizes sobre como os serviços web devem ser projetados, enfatizando conceitos como estado uniforme, comunicação stateless, manipulação de recursos através de métodos HTTP (GET, POST, PUT, DELETE) e utilização de hypermedia (HATEOAS).

- RESTful: Refere-se à implementação desses princípios em uma API específica. Uma API é considerada RESTful quando segue os princípios e práticas estabelecidos pelo REST. Isso significa que a API é orientada a recursos, utiliza os métodos HTTP de forma adequada para operações CRUD e mantém a comunicação stateless entre cliente e servidor, além de respeitar outras diretrizes da arquitetura REST.

Em resumo, REST é um conjunto de diretrizes e princípios, enquanto RESTful se refere à aplicação prática desses princípios na construção de APIs web. Uma API que segue os princípios REST é chamada de RESTful.

## HTTP verbs

HTTP verbs, são ações que definem as operações que podem ser realizadas em um recurso na web. São utilizados para indicar a ação desejada a ser executada em um recurso específico. Os principais HTTP verbs são:

- GET: Solicita e recupera dados de um recurso específico no servidor.
- POST: Cria novos dados enviando informações para o servidor.
- PUT: Atualiza ou substitui completamente um recurso no servidor.
- DELETE: Remove um recurso específico no servidor.
- PATCH: Atualiza parcialmente um recurso, modificando apenas as informações específicas fornecidas.
- OPTIONS: Retorna os métodos HTTP permitidos para um recurso ou as opções de comunicação disponíveis.
- HEAD: Solicita apenas os cabeçalhos de resposta, sem os dados do recurso, sendo útil para verificar informações de cabeçalho, como status e tamanho do recurso, sem baixar seu conteúdo completo.

## HTTP Status Code

Os códigos de status HTTP são números enviados pelo servidor em resposta a uma solicitação feita por um cliente (navegador, aplicativo, etc.). Eles indicam o resultado da solicitação e se ela foi processada com sucesso ou se ocorreu algum problema. Os códigos de status mais comuns incluem:

- 2xx (ex: 200 OK): Indica sucesso na requisição.
- 3xx (ex: 301 Moved Permanently): Indica redirecionamento para outro recurso.
- 4xx (ex: 404 Not Found): Indica erro do cliente, como recurso não encontrado.
- 5xx (ex: 500 Internal Server Error): Indica erro do servidor ao processar a requisição.

---

Autor do resumo: Pedro Alves Barbosa de Lira da Silva - 01530523
