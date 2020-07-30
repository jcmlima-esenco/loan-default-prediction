# Previsao de perdas por inadimplencia em emprestimo

Como trabalho final do curso.
Desafio. Prever a inadimplência de uma operação de emprestimo.

Este desafio foi pública inicialmente em 2013.

O desafio inicial pode ser visto em 
https://www.kaggle.com/c/loan-default-prediction/data
    

## Sobre o desafio

Essa competição solicita que você determine se um empréstimo será inadimplente, bem como a perda incorrida se não ocorrer. 
Diferentemente das abordagens tradicionais baseadas em finanças para esse problema, onde se distingue entre contrapartes boas ou ruins de uma maneira binária, procuramos antecipar e incorporar o padrão e a gravidade das perdas resultantes. Ao fazer isso, estamos construindo uma ponte entre o sistema bancário tradicional, em que buscamos reduzir o consumo de capital econômico, para uma perspectiva de gerenciamento de ativos, na qual otimizamos o risco para o investidor financeiro.

## Sobre o dataset

* Esses dados correspondem a um conjunto de transações financeiras associadas a indivíduos. 
* Os dados foram padronizados, descendentes e anonimizados. 
* Você recebe mais de duzentas mil observações e quase 800 recursos. 
* Cada observação é independente da anterior.
* Para cada observação, foi registrado se um padrão foi acionado.
* Em caso de inadimplência, a perda foi medida. 
* Essa quantidade está entre 0 e 100. 
* Foi normalizada, considerando que o ideal de cada transação no início é 100. 
* Por exemplo, uma perda de 60 significa que apenas 40 são reembolsados. 
* Se o empréstimo não for inadimplente, a perda será 0. 
* Você deverá prever as perdas para cada observação no conjunto de testes.
* Os valores dos recursos ausentes foram mantidos como estão, para que as equipes concorrentes possam realmente usar o máximo de dados disponíveis, implementando uma estratégia para preencher as lacunas, se desejado. 
* Observe que algumas variáveis podem ser categóricas (por exemplo, f776 e f777).
* O patrocinador da competição trabalhou para remover a dimensionalidade do tempo dos dados. No entanto, as observações ainda estão listadas na ordem do antigo para o novo no conjunto de treinamento. 
* No conjunto de teste, eles estão em ordem aleatória.
