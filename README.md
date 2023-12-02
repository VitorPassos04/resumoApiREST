# resumoApiREST

## Api REST e RESTFul

Uma API REST (Interface de Programação de Aplicações baseada em Transferência de Estado Representacional) é uma abordagem arquitetônica para comunicação entre sistemas distribuídos, 
utilizando o protocolo HTTP (Hypertext Transfer Protocol). As APIs REST são projetadas para serem simples, escaláveis e flexíveis, seguindo princípios fundamentais que promovem a eficiência e a interoperabilidade.

De acordo com a Red Hat 1, a RESTful API é uma implementação específica de uma API REST, seguindo os princípios e práticas recomendadas definidas pela arquitetura REST. 
Ela enfatiza a representação dos recursos de maneira hierárquica e frequentemente utiliza formatos de dados como JSON (JavaScript Object Notation) para a transmissão de informações.

Os princípios REST definem como uma API RESTful deve ser implementada, incluindo:

* Recursos: Todo o conteúdo da API é modelado como recursos, identificados por URIs.
* Representação: Os recursos são representados em um formato de dados padronizado, como JSON ou XML.
* URIs: As URIs devem ser significativas e descritivas do recurso que representam.
* Verbos HTTP: Os verbos HTTP são usados para indicar a operação que o cliente deseja realizar no recurso.
* Status Codes: Os status codes HTTP são usados para indicar o resultado da operação.

## Diferenças entre REST e RESTFul

A diferença fundamental entre uma API REST e uma API RESTful reside na adesão aos princípios e práticas definidos pela arquitetura REST. Enquanto uma API REST segue a abordagem geral, 
uma API RESTful implementa esses princípios de maneira mais estrita, garantindo a conformidade com diretrizes fundamentais, como a identificação de recursos, manipulação de recursos 
por meio de representações e o uso apropriado dos métodos HTTP.

## HTTP verbs

Os métodos HTTP, também conhecidos como HTTP verbs, são a base para a interação entre clientes e servidores em uma API RESTful. De acordo com a Mozilla Developer Network 2, 
esses métodos descrevem a ação que deve ser realizada em um recurso específico. Alguns dos principais métodos incluem:

* GET: Solicita a representação de um recurso.
* POST: Submete dados para serem processados por um recurso identificado.
* PUT: Atualiza ou cria um recurso.
* DELETE: Remove um recurso específico.
  
Esses métodos proporcionam uma interface uniforme para interação, facilitando o desenvolvimento e a compreensão da API.

## HTTP Status Code

Os códigos de status HTTP indicam o resultado de uma solicitação feita pelo cliente ao servidor. Eles são divididos em diferentes categorias, 
cada uma representando um grupo de respostas. A Mozilla Developer Network 3 fornece uma lista abrangente desses códigos. Alguns exemplos notáveis incluem:

Código de Status   | 	Descrição
--------- | ------
200 OK | Indica que a solicitação foi bem-sucedida.
201 Created	| Informa que a solicitação resultou na criação de um novo recurso.
204 No Content |	Indica que a solicitação foi bem-sucedida, mas não há conteúdo para ser enviado.
400 Bad Request |	Sinaliza que a solicitação do cliente é inválida ou malformada.
401 Unauthorized |	Indica que a solicitação não foi autorizada, geralmente devido a credenciais ausentes ou inválidas.
403 Forbidden |	O servidor entende a solicitação, mas o acesso é proibido.
404 Not Found |	Indica que o recurso solicitado não foi encontrado.
405 Method Not Allowed |	O método especificado na solicitação não é permitido para o recurso identificado.
500 Internal Server Error |	Indica um erro interno no servidor que impediu a conclusão bem-sucedida da solicitação.
503 Service Unavailable |	Indica que o servidor não está pronto para lidar com a solicitação. Pode ser temporário ou permanente.

O entendimento dos códigos de status é crucial para os desenvolvedores e usuários da API, pois eles comunicam eficientemente o resultado de uma operação.

Neste contexto, as APIs RESTful, ao seguir os princípios da arquitetura REST, utilizam esses códigos de status para fornecer informações sobre o estado da solicitação e do recurso associado.

---

  Autor do resumo: Vítor Passos do Rego - 01538874
