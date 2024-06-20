# GoForest.co
This is a project for the public API GoForest.co.in


1. Escolher uma ferramenta para automatizar testes à seguinte Api REST, explica o porquê
dessa escolha. https://gorest.co.in/  - Escolhi o Cypress baseado em JS

2. Explica os use case de teste;

a.	TC: Validate API JSON Schema
Given access the go forest API 
When I get schema from GET Todos
Then the schema is validated

b.	TC: Validate Completed Status
 Given access the go forest API 
 When I get JSON Response from GET Todos
Then the status of JSON response are ‘completed'
 
c.	TC: Validate JSON parameter due_on
Given access the go forest API 
When I get JSON Response from GET Todos
Then parameter due_on should be validated

   
5. Em automação, com resposta desta API gorest.co.in/public/v2/todos
3.1. Aplica uma validação de schema ao resultado;
3.2. Valida se todos os resultados têm status completed;
3.3. Interpreta e valida o valor “due_on”

Comenta e publica o código num repositório público de GitHub - Repositorio é este aqui
6. DevOps, CI/CD.
4.1. Explica e justifica uma implementação de testes de carga a esta API;
Criar com Jmeter um grande volume de solicitacoes para ver como a API se comporta sob diferentes cargas e volumes de tráfego
4.2. Como implementarias uma solução de Continuous Testing, justifica;
 Implementaria no github actions uma vez que o codigo ja esta versionado no git 
