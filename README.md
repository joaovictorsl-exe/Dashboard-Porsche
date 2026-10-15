Dashboard de Vendas Porsche
Criei esta dashboard para analisar as vendas de carros Porsche de forma visual e interativa. O design foi inspirado no site da Porsche Brasil, buscando um estilo simples, elegante e refinado.
Quais perguntas de negócio escolhi e por quê?
- Quais modelos são mais vendidos por cidade? Para entender as preferências dos clientes em cada local.
- Qual ano de modelo teve mais vendas no período? Para identificar quais safras de veículos tiveram maior saída.
- Quais foram os melhores vendedores de cada ano? Para comparar o desempenho por quantidade de vendas, usando o valor negociado como desempate.
- Quantos carros foram entregues, ficaram pendentes ou foram cancelados? Para acompanhar a situação dos pedidos, incluindo os veículos em transporte.
Qual foi o prompt e o que mudou?
Meu pedido inicial foi:
Crie uma dashboard em HTML usando Canvas, com filtros por modelo Porsche, ano do modelo, cidade e forma de pagamento. Mostre os principais modelos vendidos por cidade, os anos de modelo mais vendidos em um período e insights sobre os carros mais populares em cada cidade. Use o site da Porsche Brasil como referência visual, com um estilo elegante e refinado.

Depois da primeira versão, pedi algumas mudanças: troquei o filtro de cidade por estado, substituí o insight de popularidade pelo ranking anual de vendedores e acrescentei uma análise das entregas. Também refinei o visual e incluí uma foto de um Porsche no topo.
Que tratamento a base precisou?
A planilha enviada já tinha uma aba tratada, chamada Sanitized. Durante a preparação do dashboard, foram identificadas 24 datas inválidas. Esses registros foram mantidos nos totais gerais, mas ficaram fora das análises por ano ou período.
Também foram padronizados os nomes dos vendedores e agrupados os status em quatro categorias: entregues, em transporte, pendentes e cancelados.
As vendas canceladas foram retiradas dos indicadores comerciais. Como a base não informa a moeda nem as datas de entrega, não foi possível definir a moeda dos valores ou calcular atrasos.
Usei Canvas, agente com skill ou os dois?
Usei os dois. Comecei com o ChatGPT e a prévia em HTML solicitada no Canvas. Depois, utilizei o agente Codex com a skill Sites para refinar o visual e implementar as mudanças até chegar à versão final.
GitHub Pages: https://joaovictorsl-exe.github.io/Dashboard-Porsche/
