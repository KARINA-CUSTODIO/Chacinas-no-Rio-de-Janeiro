# Chacinas-no-Rio-de-Janeiro
Análise de dados do Fogo Cruzado avaliando o impacto da decisão do STF nas chacinas no estado do Rio de Janeiro.
**Onde ocorrem as chacinas? Em qual horário? Recorte temporal: janeiro de 2018 até setembro de 2022**
Primeiro passo: eliminei todos os resultados antes de janeiro de 2018 da planilha. 
Segundo passo: filtro na coluna “mortes civis” e exclusão de resultados "0", "1", "2"
Na coluna "Local" eu manipulei ela para tirar rua, cidade e estado e deixar apenas o bairro. 
Tirei a estatística das colunas "Local" e de "Horário"
**Resultado Local**: Salgueiro: 12; Bangu: 11; Maré: 8; Fonseca: 7; Penha: 7
**Resultado horário**: 08h00 (12 chacinas); 06h00 (11 chacinas). 05h00 (10 chacinas), 00h00 (10 chacinas), 20h00 (8 chacinas)- (*o número 00h00 pode ser um missing data, mas ainda não tivemos oportunidade de checar com os criadores da base de dados
