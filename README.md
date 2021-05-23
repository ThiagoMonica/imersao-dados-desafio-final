
![imagem início](https://github.com/ThiagoMonica/imersao-dados-desafio-final/blob/main/img_readme.jpg?raw=true)

# Desafio Final Imersão Dados

Esse projeto é resultado de 5 aulas da Imersão Dados 3 da Alura. Nele, podemos ver algumas análises com base em um conjunto de dados oferecidos pelo [Kaggle](https://www.kaggle.com/c/lish-moa/overview/description). Essas análises levaram à construção de modelos de machine learning que nos auxiliriaram a atingir nossos objetivos.

## Objetivos
Através de modelos de machine learning, temos dois objetivos:

- Prever se uma configuração de experimento pode ativar 2 ou mais MOA's.
- Prever se no experimento foi ou não utilizado o composto com mais aplicações em todo o conjunto.

Assim, podemos cada vez mais automatizar alguns processos na extensa e delicada função que é a descoberta de novas drogas.

### Conhecendo os Dados

Os dados dizem respeito à 23.814 experimentos em diferentes **culturas de células** que foram submetias à algum algum composto.

Abaixo temos o que significa cada coluna dos nossos dados:

*   id: identificador do experimento. Esse valor é único, portanto ele não se repete na base de dados.

*   tratamento: diz qual o tratamento utilizado nos experimentos. Pode assumir dois valores:

  * com_droga: a cultura celular foi submitida à um determinado **composto** (explicitado na coluna *composto*).

  * com_controle: a cultura celular foi submitida à um tipo **placebo**. Esse tipo de experimento não altera nenhuma característica do experimento e existe para ser utilizado como parâmetro de comparação para outros experimentos.

Tratamento   | Quantidade
-------------|------------
com_droga    | 21948
com_controle | 1866


*   tempo: representa o tempo em horas que a cultura celular ficou exposta ao composto. Pode assumir 24, 48 ou 72.
 
Tempo | Quantidade
------|------------
24    | 7772
48    | 8250
72    | 7792


*   dose: representa a dose do composto que o experimento foi observado. Pode assumir D1 (1ª dose) ou D2 (2ª dose).

Dose | Quantidade
-----|------------
D1   | 12147
D2   | 11667


*  composto: representa o composto em que a cultura celular foi exposto. Pode-se observar que não trabalhamos com os nomes reais dos compostos, mas sim nomes fictícios.

*   g-x: representa a expressão genética do gene x. Isso significa que, dada a exposição de um composto em uma cultura celular, um a expressão genética de uma célula pode aumentar, aumentando também a produção de determinada proteína, ou pode diminuir, causando o efeito contrário na produção de proteínas da célula. Nesta base, temos 0 a 771 genes.

*   c-x: representa a viabilidade genética, ou seja, quantas células sobreviveram ou não à aplicação do composto. Temos 0 a 99 viabilidades celular na base de dados.

## Links
* [Imersão Dados Alura](https://www.alura.com.br/imersao-dados).
* [Aulas Imersão Dados](https://github.com/ThiagoMonica/Imersao_Dados_Alura).

