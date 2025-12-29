<h3>Projeto Mega-Sena: Web Scraping e Análise de Dados</h3>

<p>
  Este projeto Python demonstra um pipeline completo de <b>web scraping</b> e <b>análise de dados</b> focado nos resultados da Mega-Sena.
  A implementação utiliza as bibliotecas <code>requests</code> para requisições HTTP e <code>BeautifulSoup</code> para parsing HTML, com o objetivo de extrair informações históricas de sorteios da plataforma <a href="https://asloterias.com.br">asloterias.com.br</a>.
</p>

<p>
  A escolha deste site específico não foi arbitrária; ele serviu como um cenário ideal para refinar e validar a robustez dos métodos de extração de dados.
  Dada a estrutura do conteúdo, a necessidade de identificação precisa dos padrões dos sorteios via <b>expressões regulares</b> (<code>re</code>) foi um ponto chave no desenvolvimento.
</p>

<p>
  Após a coleta, os dados são processados para determinar a frequência de cada número sorteado, utilizando a classe <code>Counter</code> da biblioteca padrão <code>collections</code> para otimizar essa contagem.
  O resultado é a apresentação dos 60 números mais recorrentes na história da Mega-Sena.
</p>

<p>
  Este trabalho destaca a aplicação prática de técnicas de coleta e processamento de dados para obtenção de <b>insights relevantes</b>.
</p>
