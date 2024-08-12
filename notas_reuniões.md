https://github.com/kelvins/municipios-brasileiros/tree/main


NM_CIDADE_AULA quando estava na pandemia, as pessoas preenchiam com a cidade que moravam mesmo...
Desconsiderar esse campo para os anos letivos de 2020 (a partir de março) e 2021

No campo CD_ORIGEM_ALUNO, criar duas outras colunas para nascimento e durante a aula, usar essa coluna original apenas pra delimitar as cidades consideradas próximas a Maringá

Medidas a criar:

* Idade na matrícula (DH_MATRICULA, DT_NASC_ALUNO) - ok
* Ano da matrícula (DH_MATRICULA) - ok
* CD_ORIGEM_ALUNO para aula (NM_CIDADE_AULA, SG_UF_AULA) - 
* CD_ORIGEM_ALUNO para nascimento (NM_CIDADE_NASC, SG_UF_NASC_ALUNO) - 
* Estuda ou não no campus sede - ok
* Trancamento (ponto de atenção para a evasão) - ok

Informações para ML:

* Medidas acima
* Curso
* Centro
* Campus
* Habilitação
* Turno
* Estado civil
* Raça
* Forma de ingresso no curso
* Sexo
* Deficiência
* Tipo de escola do ensino médio
* Cotas

Booleano para trancamento

Quanto tempo cursado até a evasão

Recortes de modelos e análise
* Campus
* Centro
* Curso
* Turno

ML:

Análise de contribuição de uma característica para o problema

* seleção de característica -> métodos de filtro (ranquear características)
  * chi quadrado
  * modelos que fazem isso:
    * árvore
    * regressão

DBScan para clusterização, define a quantidade de grupos sozinho

Mendley

Mapeamento sistemático