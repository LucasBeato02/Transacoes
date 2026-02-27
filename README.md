# Análise de Transações
Este projeto consiste em um dashboard interativo desenvolvido no Power BI para analisar o desempenho de vendas e o perfil de clientes de grandes redes de varejo e serviços (como Renner, Carrefour e Uber). Os dados utilizados são fictícios e provenientes de um dataset de treinamento.

# Funcionalidades
- Visão Geral de Receita: Exibição do faturamento total (Renda) e volume de transações.

- Análise por Estabelecimento: Comparação de performance entre diferentes lojas.

- Filtros Temporais e Geográficos: Gráficos que mostram a evolução mensal das transações e a distribuição por estado (SP, RJ, MG, etc.).

- Perfil do Consumidor: Segmentação de dados por gênero (Masculino/Feminino) e status de aprovação de pagamentos.

- Dicas de Ferramenta (Tooltips): Página de detalhes integrada que aparece ao passar o mouse sobre os gráficos para visualização profunda.

# Tecnologias Utilizadas
- Power BI: Criação de visualizações, medidas DAX e modelagem de dados.

- DAX: Para cálculos de soma de valores e contagens distintas de estabelecimentos.

# Estrutura dos Dados
A tabela principal contém as seguintes colunas essenciais:

- renda: Valor financeiro associado ao cliente.

- estado: UF onde a transação ocorreu.

- estabelecimento: Nome da rede varejista.

- valor: Montante da transação individual.

- status: Indicador de transação aprovada ou negada.
