# banco-de-dados
# Tarefas, desafios e projetos relacionados a banco de dados <br />

Modelo Conceitual Desafio DIO <br />
Refinamento de Modelagem conceitual de um contexto reduzido de e-commerce. <br />
Objetivos do refinamento:
* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações; <br />
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento;<br />
* Entrega – Possui status e código de rastreio;<br />

| Entidades  | tabela de relaciomaneto
| ------------- | ------------- |
| pedido  | produto_estoque |
| produto  | produto_pedido |
| cliente  | produto_vendedor |
| fornecedor  | fornecedor_produto |
| estoque  | produto_vendedor |
| vendedor  |
| entrega  |
| forma_pagamento  |
<br />

![dioDer drawio](https://user-images.githubusercontent.com/105323660/190936725-275770b7-6b31-45f0-a5eb-a932a20b48e6.png)
