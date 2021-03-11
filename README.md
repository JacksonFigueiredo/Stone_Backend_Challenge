# Stone_Backend_Challenge

O desafio que propomos é escrever uma API RESTful utilizando .Net Core 5 para gerenciar as vendas de uma loja delivery. Lembrando que você deve responder este e-mail com um prazo para recebermos o desafio solucionado.
Abaixo, algumas especificações:
- Utilizar SQL Server ou PostgreSQL como banco de dados;
- Necessário possuir endpoints para:
    - CRUD de produtos
    - CRUD de clientes
    - Calcular o valor do frete para entrega baseado na seguintes regras:
        - O endpoint deve receber o CEP que o pedido deve ser entregue, entregas na mesma cidade custam R$ 10,00 enquanto entregas para outras cidades custam R$ 20,00 e entregas para outros estados custam R$ 40,00.
        - A sede da loja fica no Rio de Janeiro   Lembre-se, um bom software é um software bem testado!