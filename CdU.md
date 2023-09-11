# Casos de uso (CdU)

## Abrir venda

Autor: vendedor

1. Vendedor informa número do cliente
2. Vendedor registra produto (sublinhado)
3. Vendedor informa forma de pagamento
4. Vendedor informa forma de entrega
5. Vendedor cadastra preço final do produto

Extensões:

1a. O número do cliente deve ser precedido de operadora e prefixo

3a. As formas de pagamento válidas são via débito, fatura, pix ou dinheiro

## Baixar venda

Autor: vendedor

1. Vendedor atualiza venda como paga
2. Vendedor informa data da baixa
3. Sistema emite nota fiscal
4. Sistema envia nota fiscal para o cliente (extends - Whatsapp, Email)

Extensões:

1a. Valor do preço final da venda tem que ser maior ou igual ao preço do produto

## Adicionar produto

Autor: vendedor

1. Vendedor informa nome
2. Vendedor informa descrição
3. Vendedor informa categoria
4. Vendedor informa preço
5. Vendedor informa desconto
6. Vendedor informa fornecedor 

Extensões:

4a. Se nome do produto conter caracteres não alfanuméricos, solicitar novo nome

5a. O desconto do produto é um valor percentual

6a. Se o produto não tem fornecedor, o vendedor pode deixar em branco

## Avaliar lucro mensal

1. Vendedor informa mês
2. Vendedor informa ano
3. Sistema lista produtos comprados no mês
4. Sistema lista produtos vendidos no mês
5. Sistema apresenta lucro no mês

Extensões:

1a. Se o mês for menor que a sua venda mais antiga, solicitar novo mês

2a. Se o ano for menor que a sua venda mais antiga, solicitar novo ano

# Diagrama de CdU

Abaixo o diagrama de CdU do sistema em questão