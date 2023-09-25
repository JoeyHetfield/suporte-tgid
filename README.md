# suporte-tgid

## Cenário:
Uma empresa solicitou um sistema simples de compra. Nesse sistema o cliente pode fazer
compras em algumas empresas de acordo com os produtos que as mesmas têm disponível
em estoque, além disso ele também pode ver as suas compras. Por sua vez, a empresa pode
ver as suas vendas e os seus produtos.

Algumas das regras de negócios são:

● Cada empresa tem sua taxa (comissão do sistema) para as transações

● Além do administrador e a própria empresa, nenhum outro usuário poderá ver informações da empresa (além do nome)

● Ao finalizar uma compra o cliente deve ver um resumo da mesma

● O saldo da empresa deve ser alterado já refletindo as taxas

● A empresa deve vender apenas produtos que ela esteja relacionada

● A empresa poderá ver a taxa de comissão de sistema em cada venda (ao listar suas vendas)


# Mudanças feitas:

- Adicionando alguns comentários para facilitar legibilidade
- O código não funcionava da forma correta quando o usuario era o admin, então adicionei as funções especificas pra ele(de empresa e cliente já estavam feitas)
- O cliente podia comprar um produto que não venda na empresa escolhida, alterei o codigo para que só seja possivel escolher produtos que são da empresa
- Coloquei os arquivos de classes dentro de uma pasta model para organizar melhor

  
