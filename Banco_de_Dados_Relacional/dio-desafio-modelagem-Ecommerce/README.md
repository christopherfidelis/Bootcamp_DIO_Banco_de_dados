# DIO: Desafio de Projeto E-commerce

#### Repositório criado para refinar o Projeto Conceitual de Banco de Dados para E-COMMERCE.

## Descrição do projeto conceitual:

### Narrativa - Produto
* Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros);
* Cada produto possui um fornecedor;
* Um ou mais produtos podem compor um pedido.

### Narrativa - Cliente
* O cliente pode se cadastrar no site com seu CPF ou CNPJ;
* O Endereço do cliente irá determinar o valor do frete;
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

### Narrativa – Pedido
* O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega;
* Um produto ou mais compoem o pedido;
* O pedido pode ser cancelado.

### Considerações Finais:
* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
* Entrega – Possuistatus e código de rastreio.