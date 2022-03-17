# Challenge_BI_Alura_2
Repositório destinado a compartilhar os projetos propostos no Challenge de BI da Alura 2° Edição. 

<p><b>Documentação em construção...</b></p>

<h1>Desafios</h1>

  <li><a href="#week01"> Semana 1: Desafio mercado cinematográfico - Alura Films</a></li>
  <li><a href="#week02"> Semana 2: Desafio mercado de restaurantes - Alura Food</a></li>
  <li><a href="#week03"> Semanas 3 e 4: Desafio métricas de vendas - Alura Skimo </a></li>
  
 <!--Título da semana 1 -->
 <h2><a id="week01"</a>Semana 1: Desafio mercado cinematográfico - Alura Films</h2>
  <p>A empresa Alura Films necessitava fazer uma pesquisa de mercado, com a finalidade de identificar a seleção ideal de elenco e produção.</p>
  <img src="https://user-images.githubusercontent.com/73675930/158726637-255891f1-b4f8-4d06-8470-296e8d4f3808.png"/>
  <p><a href="https://github.com/CarolineOlive/Challenge_BI_Alura_2/blob/main/Semana%201/BI_alura_films.pdf">BI Alura Films Completo</a></strong></p>

  <h3><strong>Dados</strong></h3>
    <p>Foram disponibilizados dois conjuntos de dados.</p>
    <ul>
      <li> 1. Base de dados contendo informações sobre 1000 filmes, tais como, nome, ano de lançamento, diretor, atores, gênero, faturamento, número de votos recebidos, pontuação, classificação, tempo de execução e resumo
      <li> 2. Arquivo com informações sobre código e URL das imagens de cada filme.
    </ul>
    
  <h3><strong>Tratamento dos dados</strong></h3>
    <p>Base de dados original:</p>
    <ul>
      <li> dados da coluna 'gênero' divididos por delimitador resultando em 3 novas colunas com informações de gênero
      <li> linhas vazias filtradas
      <li> obtenção de nova coluna de data a partir do ano de lançamento
      <p>A base tratada foi utilizada para obter 3 <u>novas tabelas: atores, gênero e cachê médio por gênero</u></p>
    </ul>
      <p>Tabela gênero e cachê médio por gênero<p>
      <ul>
        <li>Agrupamento dos dados de gênero e média do valor de cache.
      </ul>
      <p>Tabela Atores</p>
      <ul>
        <li>colunas "Data", "Classificação", "Tempo filme", "Gênero.1", "Gênero.2", "Gênero.3", "Overview", "Pontuação do filme", "Director" removidas;
        <li>colunas referentes ao atores ("Star1", "Star2", "Star3", "Star4") transformadas em linha, resultando em duas novas colunas, "Atributo" - indica o "grau" do ator, "Ator" - contendo o nome dos atores.
      </ul>
      <p>Tabela Gênero:</P>
      <ul>
        <li> colunas "Ano lançamento", "Classificação", "Tempo filme", "Director", "Star1", "Star2", "Star3", "Star4", "Número de votos", "Data", "Overview" removidas.
      </ul>
   
   <h3><strong>Medidas</strong></h3>
    <ul>
  <li>Tabela calendário</li>
      <img src="https://user-images.githubusercontent.com/73675930/158724068-c4d8c86d-55a2-44ab-baa9-f66effb06dd3.png"/>
  <li>Tabela medidas</li>
    <img src="https://user-images.githubusercontent.com/73675930/158726296-2d354455-fc5a-433e-a346-eac7a6202ee1.png"/>
    <p>medidas criadas usando função de filtro.</p>
      <img src="https://user-images.githubusercontent.com/73675930/158726131-8859a72e-c3f4-478a-a7f3-a2e0975a4566.png"/>
    <p>Elas compõe a maior parte das informações na primeira página.</p>
    <p>📊 Ranking dos filmes por número de votos</p>
    <img src="https://user-images.githubusercontent.com/73675930/158901042-1d0971a9-6e27-4ea3-9898-62f67570ce0e.png"/>
   </ul>
  
  <h3><strong>Resultados</strong></h3>
  <ul>
    <p><strong>Filtro</strong></p>
    <img src="https://user-images.githubusercontent.com/73675930/158902103-f1e3c1c2-79dd-44b8-a7bf-ddb7b47639f8.png"/>
    <p>Ícone para ativação de filtros por gênero, Diretor e Ano de lançamento.</p>
    <li> Filmes mais votados e informações sobre ano, gênero, ator principal, nota
    <li> Descrição do filme e capa
    <li> Quantidade de filmes por gênero
    <li> 10 gênero com maior cache
    <li> Notas por gênero
    <li> 5 atores que mais fizeram filmes
    <li> Cache médio dos filmes por ator
    <li> Atores que fizeram filmes com maior cachê
    <li> Ranking dos filmes mais votados
  </ul>
  
  <h3><strong>Dashboard</strong></h3>
  <p><strong><a href="https://app.powerbi.com/view?r=eyJrIjoiZjkzNzk1NjktMWU3ZC00ZmFhLTlhYjQtYmIxYWI2ZTU1NDUxIiwidCI6ImMzZjM2NDZlLWRmY2ItNDlhNS04ZGUxLTc1ODA1Mjg4NTc1YyJ9&pageName=ReportSection847043c918bf1680df0d">Dashboard Alura Films</a></strong></p>
  
 <!--Título da semana 2 -->
 <h2><a id="week02"</a>Semana 2: Desafio mercado de restaurantes - Alura Food</h2>
 <p>A Alura Food tem interesse em expandir seu negócio entrando no mercado indiano. Para isso, ela precisa da criação de métricas e análise dos dados disponibilizados para tomar a melhor decisão.</p>
 <img src="https://user-images.githubusercontent.com/73675930/158727403-3134a691-44d8-4def-b397-c714479bc500.png"/>
  <p><a href="https://github.com/CarolineOlive/Challenge_BI_Alura_2/blob/main/Semana%202/Alura_food.pdf">BI Alura Food Completo</a></strong></p>
 
  <h3><strong>Dados</strong></h3>
    
  <h3><strong>Tratamento dos dados</strong></h3>
  
  <h3><strong>Dashboard</strong></h3>
 <p><strong><a href="https://app.powerbi.com/view?r=eyJrIjoiNzE2YWIyNmUtOTQ1Ny00YmNiLThiNTEtNDFjYzNmMDM4ZWU2IiwidCI6ImMzZjM2NDZlLWRmY2ItNDlhNS04ZGUxLTc1ODA1Mjg4NTc1YyJ9">Dashboard Alura Food</a></strong></p>
 
  <!--Título da semana 3 e 4-->
 <h2><a id="week03"</a>Semanas 3 e 4: Desafio métricas de vendas - Alura Skimo</h2>
  <p>A empresa Alura Skimo necessita acompanhar suas vendas através de um painel que comporte todas métricas necessárias.</p>
  <img src="https://user-images.githubusercontent.com/73675930/158727768-b4a6047e-9d2a-46f6-a69a-37122924b259.png"/>
  <p><a href= >BI Alura Skimo Completo</a></strong></p>
  <h3><strong>Dados</strong></h3>
    
    
  <h3><strong>Tratamento dos dados</strong></h3>
  
  <h3><strong>Dashboard</strong></h3>
  <p><strong><a href="https://app.powerbi.com/view?r=eyJrIjoiM2YzZTQwYzItMjdjYS00ZjkwLTlhYWMtMjY4YmU3ZDEyODQ2IiwidCI6ImMzZjM2NDZlLWRmY2ItNDlhNS04ZGUxLTc1ODA1Mjg4NTc1YyJ9">Dashboard Alura Skimo</a></strong></p>

