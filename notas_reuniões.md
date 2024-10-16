https://github.com/kelvins/municipios-brasileiros/tree/main

NM_CIDADE_AULA quando estava na pandemia, as pessoas preenchiam com a cidade que moravam mesmo, porém está com muitas cidades em todos os anos, e não só nos dois anos de pandemia.

No campo CD_ORIGEM_ALUNO, criar duas outras colunas para nascimento e durante a aula, usar essa coluna original apenas pra delimitar as cidades consideradas próximas a Maringá

Medidas a criar:

* Idade na matrícula (DH_MATRICULA, DT_NASC_ALUNO) - ok
* Ano da matrícula (DH_MATRICULA) - ok
* CD_ORIGEM_ALUNO para ferias (NM_CIDADE_FERIAS, SG_UF_FERIAS) - ok
* CD_ORIGEM_ALUNO para nascimento (NM_CIDADE_NASC, SG_UF_NASC_ALUNO) - ok
* Estuda ou não no campus sede - ok
* Trancamento (ponto de atenção para a evasão) - ok
* Tempo cursado até a última situação - ok

Informações para ML:

* Medidas acima
* Curso
* Centro
* Campus
* Habilitação
* Tempo máximo para conclusão do curso
* Turno
* Estado civil
* Raça
* Forma de ingresso no curso
* Sexo
* Deficiência
* Tipo de escola do ensino médio
* Cotas


Recortes de modelos e análise

* Campus
* Centro
* Curso
* Turno
* Gerações

ML:

Análise de contribuição de uma característica para o problema

* seleção de característica -> métodos de filtro (ranquear características)
  * chi quadrado
  * modelos que fazem isso:
    * árvore
    * regressão

DBScan para clusterização, define a quantidade de grupos sozinho

Mendley

Mapeamento sistemático dos artigos que ler

- Mostrar números dos cursos, quantos alunos ficaram depois da limpeza

## Reunião 03/10

deixar matriculados na geração completas ok
pegar ids dos jubilados de gerações incompletas ok 

deixar casos estranhos (matriculados e jubilados) nos gráficos ok

deixar vagas remanescentes juntas ok
se ainda ficar maior, fazer gráfico separado mostrando / ficou quase nada menor

investigar transferências

ver quais são os cursos vespertinos ok

quando tiver os 3 gráficos, deixar as colunas mais finas para os 3 gráficos ficarem na mesma linha, deixar gráficos na mesma escala ok

fazer todos os gráficos das gerações, total, completa e incompleta ok

## 17/10
MEC considera jubilados evadidos também