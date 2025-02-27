# Diagrama de Entidade-Relacionamento para Ecommerce - DIO

Este repositório contém um diagrama de entidade-relacionamento (ER) que modela a estrutura de um sistema de e-commerce. O objetivo deste diagrama é representar as entidades principais, seus atributos e os relacionamentos entre elas.

## Sumário

- [Descrição do Diagrama](#descrição-do-diagrama)
- [Entidades e Atributos](#entidades-e-atributos)
- [Como Usar](#como-usar)
- [Licença](#licença)

## Descrição do Diagrama

O diagrama inclui entidades como:

- **Fornecedor**
- **Produto**
- **Estoque**
- **Vendedor**
- **Pedidos**

Os relacionamentos entre estas entidades são representados, ilustrando como os dados estarão interconectados no banco de dados.

## Entidades e Atributos

### Fornecedor
- `idFornecedor`: INT
- `Razão Social`: VARCHAR(45)
- `CNPJ`: VARCHAR(45)

### Produto
- `idProduto`: INT
- `Categoria`: VARCHAR(45)
- `Descrição`: VARCHAR(45)
- `Valor`: FLOAT

### Estoque
- `idEstoque`: INT
- `Local`: VARCHAR(45)

### Vendedor
- `idVendedor`: INT
- `Razão Social`: VARCHAR(45)
- `Local`: VARCHAR(45)

### Pedidos
- `idPedido`: INT
- `Produto_idProduto`: INT
- `Quantidade`: INT

## Como Usar

Para visualizar o diagrama, faça o download do arquivo [DiagramaEcommerce-DIO.png] e abra-o na ferramenta adequada (como MySQL Workbench ou Lucidchart). 

