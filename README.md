# Calculando Estatisticas Simples

## Identificação

Objetivo: Sua tarefa é processar uma sequencia de numeros inteiros para determinar a seguintes estatisticas:

- Valor Minimo;

- Valor Maximo;

- Numero de Elementos da Sequencia;

- Valor Medio;



|Entrada|Condição|Classes Validas| Classes Invalidas|
|:-:|:----------------------------:|:------------------:|:--------------------:|
| seq | tipo(seq)== int[] | size(seq)>1 | size(seq)< 2|
|-| - | Min(seq)<=Max(seq) and Min(seq)<=Media(seq)| Min(seq)>Max(seq) or Min(seq)>Media(seq)|
|-| - | Media(seq)>=Min(seq) and Media(seq)<=Max(seq)| Media(seq)<Min(seq) or Media(seq)>Max(seq)|
|-| - | Max(seq)>=Min(seq) and Max(seq)>=Media(seq)| Max(seq)<Min(seq) or Max(seq)<Media(seq)| 

public int size(int[] seq){return quantidade;}

public double Media(int[] seq){ return ValMedio;}

public double Min(int[] seq){ return ValMin;}

public double Max(int[] seq){ return ValMax;}

public boolean seqValida(int[] seq){ return true;}
