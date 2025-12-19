# PERFORMANCE-DE-VENDAS
Análise de performance de vendas e metas comerciais através de indicadores dinâmicos de faturamento e volume de produtos no Power BI.
Você tem toda razão! Analisando a imagem agora com cuidado, vejo que este dashboard é focado em Análise de Metas e Planejamento (Target vs. Actual). As métricas que você calculou são muito mais avançadas do que uma simples soma de vendas.

Aqui está o texto do README corrigido e ajustado exatamente com as métricas que aparecem no seu dashboard (Objetivo, Planejado, Realizado e % de Meta):

# 📊 Dashboard de Performance de Vendas (Planejado vs. Realizado)
Este dashboard foi desenvolvido para o monitoramento de metas comerciais, permitindo uma análise profunda entre o planejamento estratégico e a execução real das vendas na ABC Corp.

# 📝 Contexto do Projeto
Diferente de uma análise de vendas comum, este projeto foca no Controle de Metas. Ele responde a perguntas críticas de negócio: "Quanto pretendíamos vender?" versus "Quanto realmente vendemos?", identificando desvios e oportunidades de melhoria por categoria e região.

# 📈 Indicadores Chave de Performance (KPIs)
O painel destaca quatro métricas principais de gestão:

Objetivo de Venda: A meta bruta total estabelecida pela organização.

Média Planejada: O valor médio que se esperava atingir por transação ou período conforme o planejamento.

Média Realizada: O valor médio que foi efetivamente alcançado, permitindo medir a eficiência da equipe.

Desempenho vs. Meta: Comparativo percentual que indica o quanto da meta foi atingido (Gap Analysis).

# 🎨 Apresentação Gráfica e Visualização
Velocímetros (Gauge Charts): Utilizados para mostrar de forma visual e rápida o quão próximo a empresa está do Objetivo de Venda (Meta).

Gráfico de Barras com Linha de Meta: Comparativo entre o realizado e o planejado por categoria de produto.

Tabela de Performance: Detalhamento granular por categoria, mostrando valores planejados e realizados lado a lado para facilitar a auditoria dos dados.

# 🛠️ Inteligência de Dados com DAX
Este projeto exigiu cálculos de comparação mais complexos:

Cálculo de Atingimento: Medidas DAX para calcular a variação percentual entre o Realizado e o Planejado.

Métricas Médias: Fórmulas para calcular a média realizada dinamicamente com base nos filtros aplicados.

Análise de Objetivo: Criação de medidas para consolidar o Objetivo de Venda total a partir de diferentes fontes ou tabelas de metas.

# ⚙️ Processo de ETL e Modelagem
Power Query: Tratamento de duas fontes distintas: os dados de Vendas Reais e a base de Planejamento/Metas, garantindo que ambas pudessem ser cruzadas na mesma granularidade.

Modelagem de Dados: Integração das tabelas Fato de Vendas e Fato de Metas através de dimensões comuns (Produtos e Calendário), seguindo as melhores práticas de BI.
![Performance de Vendas](performance.png)  
![Performance de Vendas](performance.png.2)  




# 💾 Origem e Fonte dos Dados
Projeto desenvolvido com base no curso "Business Intelligence Completo do ETL ao Power BI" do professor André Rosa (Udemy). A base é fictícia, mas estruturada para simular um cenário real de controle de metas corporativas. 
