# Dashboard Eletrodoméstico

Desenvolvi um dashboard que ajuda a entender o controle financeiro de uma loja "EletroMais", todos os dados são fictícios que se encontram na pasta "DADOS". Além disso, disponibilizei outros dois arquivos:
- fundo.png: template utilizado
- dashboard_eletrodomestico.pbix: o dashboard já pronto

## Colunas adicionadas
- Total_Vendas -> Quantidade x Preco_Unitario
- Lucro -> Quantidade x (Preco_Unitario - Custo_Unitario)
- Gasto -> Quantidade x Custo_Unitario

## Medidas criadas
- Receita Total -> SUM(vendas[Total_Venda])
- Lucro Total -> SUM(vendas[Lucro])
- Gasto Total -> SUM(vendas[Gasto])

  ## Gráficos
Vou listar os tipos de gráficos que adicionei no meu dashboard:
- 3 cartões: Receita Total, Lucro Total, Gasto Total;
- Gráfico de linha: mostra a evolução mensal das vendas;
- Gráfico de rosca: mostra o percentual de vendas por região;
- Gráfico de pizza: mostra a quantidade de vendas por categoria;
- Gráfico de barras empilhadas: mostra a quantidade vendida por produto.

![Image](https://github.com/user-attachments/assets/1b678818-d38b-43db-a105-547af7c8c0f7)
