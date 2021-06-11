# Anonimização k

Implementação de método para anonimização k em python para Dataset de informações de COVID.

## Métodos de anonimização
- Métodos de anonimização tem a função de tornar registros individuais indistinguiveis dentro de um grupo de registros para isso se pode usar técnicas de generalização e supressão.

### K-Anonymity
- Tornar um conjunto de dados k anônimo é um problema complexo e encontrar a anonimização ótima é um problema de NP-difícil. Mas existem heurísticas que produzem resultados "bons o bastante" e nesse trabalho iremos mostrar uma forma de realizar essa anonimização.

## Dependências:

- Python 3
- pandas
- matplotlib

## Implementação
O arquivo kAnomSupress.ipynb tem uma solução detalhada para a anonimização k para os valores de k = 2,4,8 e 16 e a posterior geração de um arquivo csv para cada uma desses valores de k.

## Referências e créditos:

Esse trabalho é parte da disciplina de banco de dados ministrada pelo professor Javam Machado no programa de Pós-graduação da UFC. Essa implementação foi inspirada no artigo [1] da Latanya Sweeney que defini o que é anonimização k e tambem no artigo [2] Preservação de Privacidade de Dados: Fundamentos, Técnicas e Aplicações do Felipe Timbó e Javam Machado.

[1] SWEENEY, Latanya. k-anonymity: A model for protecting privacy. International Journal of Uncertainty, Fuzziness and Knowledge-Based Systems, v. 10, n. 05, p. 557-570, 2002.

[2] Timbó, Felipe. Machado Javan: Preservação de Privacidade de Dados: Fundamentos, Técnicas e Aplicações, Jornadas de Atualização em Informática 2017 (pp.40) Chapter: 3
