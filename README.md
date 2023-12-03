# Api REST e RESTFul
Uma API REST (Representational State Transfer) é uma Interface de Programação de Aplicações que segue os princípios do estilo arquitetural REST, já uma API Restful é uma implementação especifica de uma API Rest que segue rigorosamente os príncipios do REST. Ambas utilizam os métodos HTTP (GET, POST, PUT, DELETE) para fazer requisições e manipular dados em geralmente em formatos JSON ou XML.

## Diferenças entre REST e RESTFul
As diferenças são poucas e geralmente associadas ao nível que API segue os príncipios REST, alguns exemplos são: Uma API Rest pode ou não ser Statelessness(Sem estado), enquanto uma API RESTful por seguir rigorosamente o REST ela sempre vai ser statelessness. Outro exemplo está na representação de seus dados, enquanto a api Restful usa formatos padronizados como JSON ou XML, uma api rest usa diversos formatos.
Para finalizar com um ultimo exemplo uma api restful deve seguir uma interface uniforme, usar nomenclaturas e convenções padronizados, enquanto uma api rest não tem essa necessidade.

## HTTP verbs
Os verbos http mais conhecidos são os GET(Usado para pegar dados da api), POST(Usado para enviar algum dado para api e o mesmo ser usar para criar um novo recurso ou para validar um token por exemplo), PUT(Usado para atualizar algum recurso), PATCH(Usado para atualizar partes de um recurso, e não o todo como no PUT), DELETE(Apaga algum recurso da api). Além de outros um pouco menos famosos como HEAD(Usado para pegar os headers de uma requisição), OPTIONS, TRACE E CONNECT.

## HTTP Status Code
Os servidores retornam códigos de status HTTP para indicar o resultado de uma solicitação feita por um cliente. Cada código de status pertence a uma categoria geral, indicando o tipo de resposta que está sendo enviada.
100 até 199(Informacional), exemplo: Status code: 100 -> Indica que a solicitação foi recebida pelo servidor e o cliente pode continuar com a solicitação.
200 até 299(Sucesso), exemplo: Status code: 200 -> Indica que a solicitação foi bem-sucedida. O servidor entendeu, aceitou e processou a solicitação com sucesso.
300 até 399(Redirecionamento), exemplo: Status code: 301 ->  Indica que o recurso solicitado foi movido permanentemente para uma nova localização.
400 até 499(Erro do lado do cliente), exemplo: 404 -> Indica que a solicitação do cliente não pôde ser atendida porque o recurso solicitado não foi encontrado no servidor.
500 até 599(Erro do lado do servidor), exemplo: Status code: 500 -> Indica um erro interno no servidor que impediu que a solicitação do cliente fosse atendida.

Autor do resumo: Charles Alves Sales Junior - 01370813
