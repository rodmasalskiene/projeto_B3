<h1>🏛️ Projeto de Análise da Bolsa de Valores - Ações</h1>
<h2>Visão Geral</h2>
<p>No projeto foi feita a coleta de dados das ações da bolsa de valores por meio de duas APIs - Yfinance e Brapi, por meio destas foram criados datasets no formato .csv para a subsequente análise desses dados. O período de dados coletados foi de três anos 12/20 ~ 12/23. Ações que não possuiam registros dentro desse período foram excluídas.</p>

<h3>🗃️ Datasets criados:</h3>
<ul>
  <li>df_close: Valor de fechamento da ação no dia.</li>
  <li>df_dividends: Valor dos dividendos que foram pagos pela empresa.</li>
  <li>df_high: Maior valor que a ação alcançou no dia.</li>
  <li>df_low: Menor valor que a ação alcançou no dia.</li>
  <li>df_open: Preço de abertura da ação.</li>
  <li>df_volume: Atividade de negociação da ação no dia - Compra e Venda.</li>
</ul>
<h3>⚒️ Ferramentas utilizadas:</h3>
<ul>
  <li>Jupyter Notebook: IDE utilizada.</li>
  <li>Python: Linguagem de programação utilizada.</li>
  <li>Pandas: Biblioteca do Python usada para manipular os dados - Converter para DataFrame e respectivamente para csv.</li>
  <li>APIs:
    <ul>
      <li>Brapi: Utilizada para coletar o nome de todas as ações do mercado.</li>
      <li>Yfinance: Utilizada para coletar o histórico de preço de cada ação.</li>
    </ul>
  </li>
</ul>

<h3>A seguir...</h3>
<p>🚧 O projeto está em desenvolvimento! 🚧</p>
  <p>No próximo passo eu pretendo fazer uma análise de mercado, tais como ações que mais pagaram dividendos, ações que mais se valorizaram, etc. E com isso elaborar dashboards no Power BI para exibição dos resultados.</p>
  <p>Também busco implementar um modelo de Machine Learning para predizer o preço das ações. Por que não afinal? Desde o começo é o que mais estou ansioso para realizar! 👻</p>
