# Comparativo Enem 21 X Enem 19 :bulb:

Para realizar a Análise e Comparativo de dados ENEM 2021 X ENEM 2019, optei pelos seguintes passos.
Construindo dois notebooks no Google Colab para utilizar comandos Python e manipular os dados nos seguintes endereços: SemantixENEM2019.ipynb - Colaboratory (google.com) e SemantixENEM2021.ipynb - Colaboratory (google.com)
Coletei os microdados do Enem dos anos de 2021 e 2019, que contém informações a respeito das provas, gabaritos, notas e questionário sócio-econôminco respondido pelos inscritos. Foram obtidos por meio da fonte: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem.
Após coleta e limpeza dos dados, resolvi realizar essa análise comparando os dados pós pandemia e pré-pandemia, pois os anos 2019 e 2021 foram marcantes para a análise de dados devido a ocorrência da pandemia COVID em 2020.

Por se tratar de um arquivo grande, um primeiro filtro de colunas foi feito diretamente na leitura dos dados, baseado na descrição dos dados obtida no arquivo de metadados "Dicionário_Microdados_Enem_2021".

Existem mais de 1 milhão de entradas nulas relacionadas às notas dos participantes. Observa-se que estes valores ausentes correspondem aos candidatos que não compareceram ou que foram eliminados em pelo menos um dos dias de prova. 

# Em 2021: 👀

Número total de inscritos: 3.389.832sendo sexo Feminino 61,67% Masculino 38,32% 🥇

 
Solteiro 88,37% Casado 5,79% Não Informado 4,11% Divorciado 1,59% Viúvo 0,11%
Parda 42,99% Branca 40,18% Preta 12,13% Não Declarado 2,09% Amarela 2,02% Indígena 0,56% 
 
Brasileiro 97,67% Brasileiro Naturalizado 1,93% Brasileiro nascido no exterior 0,19% Estrangeiro 0,13%
Observou-se que a maioria dos candidatos inscritos no ENEM 2021 são brasileiros e solteiros. Cerca de 62% declaram-se como gênero feminino e 38% como masculino. 43% dos participantes declararam raça/ cor parda, 40% raça branca e 12.% raça preta.
A maioria dos candidatos possui a idade de 18 anos, sendo a faixa etária de 17 a 20 anos correspondente a 58% dos inscritos. Após esta faixa,o número de participantes tende a diminuir conforme a idade aumenta.
Quanto a escolaridade: Concluido 52,78% Cursando - conclusão 2021 33,95% Cursando 12,89%
Dentre os candidatos que informaram o tipo de escola frequentada durante o ensino médio, há quase 5 vezes mais candidatos de escolas públicas do que escolas privadas.

Informações a respeito do local de prova

Distribuição por estado: :🇧🇷
 
 
Questionário Sócio-Econômico Os candidatos respodem a um questionário sócio-econômico que contém 25 questões. As respostas são classificadas com letras em ordem alfabética, onde a letra 'A' representa características equivalentes a um menor grau de instrução, renda familiar ou quantidade de equipamentos que possui.
 
 
A maior parte dos inscritos no ENEM possui pai / mãe com escolaridade: Ensino Médio completo porém sem Ensino Superior concluído. A renda familiar mais comum entre os inscritos está na faixa de Até R$ 1.100,00.
Observa-se que apenas 66% dos candidatos estiveram presentes nos dois dias prova.
As notas dos candidatos são divididas entre as quatro áreas de conhecimento: linguagens e códigos (LC), ciências humanas (CH), ciências da natureza (CN) e matemática (MT) e a nota de redação. 
Participantes com nota máxima: 22
Participantes com nota zero: 84582
 
Percebe-se que há correlação positiva entre as notas das quatro provas e a redação feitas por um candidato. Esta correlação é mais forte quando consideramos apenas as provas objetivas e não se considera a redação.
Para esta análise será considerado o desempenho apenas dos participantes presentes nos dois dias de prova. Deseja-se quais características dos candidatos podem estar relacionadas a um melhor desempenho, representado pela nota geral, gerada anteriormente.
 
Em geral, o desempenho de alunos que estudaram em escolas privadas mostra-se superior aos de escolas públicas. O desempenho dos candidatos parece ter influência de condições sócio-econômicas, sendo que é possível observar tendência de aumento da nota obtida com o aumento de escolaridade do pai e/ou da mãe e também com aumento da renda mensal familiar.
## Conclusão em 2021: 📊
3.389.832 pessoas se inscreveram no ENEM 2021, e apenas 66% estiveram presentes nos dois dias de prova.
62% dos candidatos inscritos são do sexo feminino e 38% do sexo masculino e 97,7% tem nacionalidade brasileira
Dentre as raças declaradas, há predominância de candidatos da raça branca e da raça parda.
A faixa etária entre 17-20 anos concentra cerca de 58% dos candidatos. Após esta faixa, o número de participantes tende a diminuir conforme a idade aumenta.
O ENEM foi aplicado em todos os estados brasileiros, e em 1747 municípios.
O estado de São Paulo teve o maior número de inscritos.
A região Nordeste teve o maior número de inscritos.
Observa-se uma tendência de aumento da nota obtida com o aumento de escolaridade dos pais e aumento da renda mensal familiar.

# Já em 2019: ⬅️

Dados dos inscritos
Número total de inscritos: 5.095.171 ⏫
Feminino 59,50% Masculino 40,49%
 
Solteiro 86,32% Casado 7,76% Não Informado 4,05% Divorciado 1,72% Viúvo 0,12%
Parda 46,39% Branca 35,95% Preta 12,72% Amarela 2,27% Não Declarado 2,02% Indígena 0,62%
Observou-se que a maioria dos candidatos inscritos no ENEM 2019 são brasileiros e solteiros. Cerca de 60% declaram-se como gênero feminino e 40% como masculino. 48% dos participantes declararam raça/ cor parda, 35% raça branca e 12% raça preta.
A maioria dos candidatos possui a idade de 18 anos, sendo a faixa etária de 17 a 20 anos correspondente a 53% dos inscritos. Após esta faixa, o número de participantes tende a diminuir conforme a idade aumenta.
Informações relacionadas ao ensino médio do candidato.
Concluido 58,73% Cursando - conclusão 2021 28,76% Cursando 12,10% Não concluido e não cursando 0,38%
 
Dentre os candidatos que informaram o tipo de escola frequentada durante o ensino médio, há quase 6 vezes mais candidatos de escolas públicas do que escolas privadas.
 
O ENEM foi aplicado em 1727 munícipios. :🇧🇷

O ENEM foi aplicado em 1727 munícipios.
Questionário Sócio-Econômico Os candidatos respondem a um questionário sócio-econômico que contém 25 questões. As respostas são classificadas com letras em ordem alfabética, onde a letra 'A' representa características equivalentes a um menor grau de instrução, renda familiar ou quantidade de equipamentos que possui.
 

A maior parte dos inscritos no ENEM possui pai / mãe com escolaridade: Ensino Médio completo porém sem Ensino Superior concluído. A renda familiar mais comum entre os inscritos está na faixa de Até R$ 1.100,00.
Observa-se que apenas 72% dos candidatos estiveram presentes nos dois dias prova.
As notas dos candidatos são divididas entre as quatro áreas de conhecimento: linguagens e códigos (LC), ciências humanas (CH), ciências da natureza (CN) e matemática (MT) e a nota de redação. 
Participantes com nota máxima: 53
Participantes com nota zero: 143689
Percebe-se que há correlação positiva entre as notas das quatro provas e a redação feitas por um candidato. Esta correlação é mais forte quando considera apenas as provas objetivas e não se considera a redação.
Análise Relação entre Desempenho e Perfil de Candidato:
Para esta análise será considerado o desempenho apenas dos participantes presentes nos dois dias de prova.
 
Em geral, o desempenho de alunos que estudaram em escolas privadas mostra-se superior aos de escolas públicas. O desempenho dos candidatos parece ter influência de condições sócio-econômicas, sendo que é possível observar tendência de aumento da nota obtida com o aumento de escolaridade do pai e/ou da mãe e também com aumento da renda mensal familiar.
## Conclusão de 2019: 🏁
5.095.171 pessoas se inscreveram no ENEM 2019, e apenas 72% estiveram presentes nos dois dias de prova.
60% dos candidatos inscritos são do sexo feminino e 40% do sexo masculino e 97,1% tem nacionalidade brasileira
Dentre as raças declaradas, há predominância de candidatos da raça branca com 36% e da raça parda com 46% além da preta com 13%.
A faixa etária entre 17-20 anos concentra cerca de 53% dos candidatos. Após esta faixa,o número de participantes tende a diminuir conforme a idade aumenta.
O ENEM foi aplicado em todos os estados brasileiros, e em 1727 municípios.

## Conclusão do comparativo: 📉
### 3.389.832 pessoas se inscreveram no ENEM 2021,X 5.095.171 pessoas se inscreveram no ENEM 2019 portanto uma redução superior a 33 % ou quase 2 milhoes de inscritos a menos após a pandemia. ⏬
### Se apenas 66% estiveram presentes nos dois dias de prova em 2021 e apenas 72% estiveram presentes nos dois dias de prova em 2019 demonstra uma redução na presença após pandemia. ⬇️
### 62% dos candidatos inscritos são do sexo feminino e 38% do sexo masculino e 97,7% tem nacionalidade brasileira em 2021 E 60% dos candidatos inscritos são do sexo feminino e 40% do sexo masculino e 97,1% tem nacionalidade brasileira indicando mínima variação nesse quesito. 🔄
### Dentre as raças declaradas, há predominância de candidatos da raça branca e da raça parda.x Dentre as raças declaradas, há predominância de candidatos da raça branca com 36% e da raça parda com 46% além da preta com 13%. Também com mínima variância. 🔄
### A faixa etária entre 17-20 anos concentra cerca de 53% dos candidatos em 2021. A faixa etária entre 17-20 anos concentra cerca de 58% dos candidatos em 2019. Apresentando assim uma redução significativa de quase 10% dos jovens talvez como reflexo da pandemia COVID19. ⤵️
### O ENEM foi aplicado em todos os estados brasileiros, e em 1747 municípios. em 2021 um acréscimo de 20 municípios em relação a 2019. ⏫
### O estado de São Paulo teve o maior número de inscritos nos dois períodos.
### Observa-se uma tendência de aumento da nota obtida com o aumento de escolaridade dos pais e aumento da renda mensal familiar nos dois períodos.

#### Satisfazendo assim a análise de dados requeridas pelo desafio Semantix, agradeço a chance de participação e aprendizado adquirido ao longo do processo. ☑️


## Ricardo Silva Cardoso
São Paulo
04 de Dezembro de 2022


##### ⚠️Referências Baseado na obra da autora : Jacqueline de Miranda Kian ⚠️
