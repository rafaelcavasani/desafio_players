# desafio_players
Desafio data science para clusterização de jogadores de um game.

# Arquivos
* tratamento_dados: Foi realizado a busca dos dados das tabelas matches e goals e exportado para 2 arquivos csv. Escolhi fazer dessa maneira para tratar os dados com o pandas, pois a execução da união das 2 tabelas ocorreu mais rápidamente no pandas do que na consulta SLQ.
* clusterin: Nesse arquivo é realizado a clusterização e a separação dos grupos dos jogadores com os dados já tratados pelo arquivo tratamento_dados.
* classificacao: De acordo com os grupos criados no arquivo clustering, foi aplicado um modelo de ML para classificação de novos jogadores.
