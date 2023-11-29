# API REST e RESTful
REST é a sigla em inglês para "Representational State Transfer", que em português significa tansferência de estado representacional.

REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas.
Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando geralmente o formato Javascript Object Notation (JSON), pois é independente de qualquer outra linguagem e pode ser lido por máquinas e humanos.

## Diferenças entre REST e RESTful
Enquanto **REST** é um conceito teórico que define princípios para sistemas distribuídos, **RESTful** é a implementação prática desses princípios em APIs específicas. Uma API pode ser considerada RESTful se ela adere às diretrizes do REST, utilizando os recursos e métodos HTTP de acordo com esses princípios, permitindo assim uma comunicação eficiente e padronizada entre diferentes sistemas.

## HTTP verbs
O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso.

- **GET**: solicita a representação de um recurso.
- **POST**: cria um novo recurso.
- **PUT**: atualiza um recurso existente.
- **DELETE**: remove um recurso.
- **PATCH**: realiza modificações parciais em um recurso.
- **HEAD**: retorna apenas os cabeçalhos de uma resposta HTTP.
- **OPTIONS**: é usado para descrever as opções de comunicação com o recurso de destino.
- **TRACE**: executa um teste de chamada loop-back junto com o caminho para o recurso de destino.
- **CONNECT**: estabelece uma conexão com um recurso identificado pelo URI.

## HTTP Status Code
Os códigos de status HTTP são retornados como parte da resposta a uma requisição feita a um servidor. Eles indicam o resultado da solicitação e podem ser divididos em 5 categorias:

| Categoria                | Faixa de Códigos |
|--------------------------|------------------|
| Respostas informacionais  | (100 – 199)      |
| Respostas de sucesso      | (200 – 299)      |
| Mensagens de redirecionamento | (300 – 399)  |
| Respostas de erro do cliente | (400 – 499)   |
| Respostas de erro do servidor | (500 – 599)  |

---

Autor do resumo: Lucas Araújo de Sá Ribeiro - 01556186
