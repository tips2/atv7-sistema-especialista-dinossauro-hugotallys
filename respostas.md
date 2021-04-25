Coloque as suas respostas nesse arquivo e efetue um commit

> Q1-Este sistema especialista (sistema-especialista-dinossauro) faz as perguntas de forma dinâmica ou seja nem sempre as mesmas perguntas são exibidas ao usuário, ou sempre as mesmas perguntas são exibidas ao usuário, na mesma ordem? (sim, não)

Não. Sempre as mesmas perguntas são feitas e seguem o fluxograma descrito em `Rede Semântica.pdf`.

> Q2-Este sistema especialista (sistema-especialista-dinossauro) usa a técnica de encadeamento para frente e encademento para trás, ou nenhuma delas? (sim, não ou não sei)

Nenhuma delas.

> Q3-Este sistema especialista (sistema-especialista-dinossauro) utiliza uma base de conhecimento baseada em regras do tipo "SE (antecedente)-ENTÃO (consequente)"? (sim, não ou não sei)

Não. A base está estrutura no arquivo `db.txt` da seguinte maneira: `"nome dinossauro - atributo"`

> (opcional) Q4-Qual técnica esse "sistema especialista" utiliza?

A cada nova pergunta respondida o algoritmo vai eliminando dinossauros que não tenham o atributo especificado de uma lista de opções. A condição de parada é quando somente 1 único dinossauro permanece na lista de opções (probabilidade igual a 1.0).
