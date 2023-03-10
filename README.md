# DashboardVendas:zap:

### Dashboard de Vendas em Power BI

O Dashboard abaixo refere-se a uma base de Vendas. Nele contém informações sobre o Faturamento Total por diversos escopos, Quantidades, Faturamento Líquido e Custos.

No primeiro momento foi necessário realizar algumas alterações no Power Query, sendo essas o tipo de cada coluna, limpeza de dados desnecessários, desmembramento da base para criação de tabelas de dimensão afim de diminuir a quantidade de dados/informações repetitivas e melhorar o desempenho do Dashboard. Automaticamente, com o desmembramento da base foi necessário realizar o gerenciamento das relações entre a tabela fato e suas dimensões:

<img width="425" alt="Relacionamentos" src="https://user-images.githubusercontent.com/98985401/224327257-0a7c0b3c-90ff-4845-a094-4ccb1f0e973f.png">

Em seguida, foram criadas as medidas para Custo Total, Faturamento Total, Quantidade Vendida e Resultado Líquido:

<img width="131" alt="Medidas" src="https://user-images.githubusercontent.com/98985401/224327355-d65d9de3-3f27-4dfa-8c86-3c26f626a73a.png">

No layout, foi usado Segmentação de Dados para filtragem do ano, cartões para visualização do Faturamento Total, Custo Total, Resultado Líquido e Produto Mais Vendido. Gráfico de Colunas Empilhadas e Linha para Faturamento Total e Quantidade Vendida por Mês e por Marca. Gráfico de Mapa para Faturamento Total por País:

<img width="425" alt="Dashboard" src="https://user-images.githubusercontent.com/98985401/224327511-c741918e-a1b3-4c4c-954d-d85012ed534c.png">

Diante das informações apresentadas podemos gerar os seguintes Insights:

  :heavy_check_mark: O Faturamento Total foi de $64,17 milhões;
  
  :heavy_check_mark: O Custo Total de $13,55 milhões;
  
  :heavy_check_mark: O Resultado Líquido de $50,63 milhões;
  
  :heavy_check_mark: A informação do Produto Mais Vendido, que alterna com base no filtro de ano e de acordo com a marca selecionada;
  
  :heavy_check_mark: O País que possuí o melhor faturamento.
  
  Esses Insights são de grande valia, pois por meio deles podemos nos aprofundar nas informações identificando pontos que precisam de atenção, como por exemplo:
  
  :heavy_check_mark: Elaborar um estudo de caso e plano de meta para aumentar o faturamento e consequentemente a quantidade vendida de determinados produtos;
  
  :heavy_check_mark: Verificar se é viável a continuidade de determinado produto/marca no catálogo de vendas, devido ao baixo retorno financeiro;

