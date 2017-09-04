# Calculando Estatisticas Simples

## Identificação

Objetivo: Sua tarefa é processar uma sequencia de numeros inteiros para determinar a seguintes estatisticas:

- Valor Minimo;

- Valor Maximo;

- Numero de Elementos da Sequencia;

- Valor Medio;



|Entrada|Condição|Classes Validas| Classes Invalidas|
|:-:|:----------------------------:|:------------------:|:--------------------:|
| sequencia | tipo(sequencia)== int[] | val_min=sequencia[0] foreach x in sequencia{  if(x<val_min)val_min=x  }    | foreach x in sequencia{x != (int)x} |
| |    | val_max=sequencia[0] foreach x in sequencia{if(x>val_max)val_max=x}|-|
| |    | quantidade=0  foreach x in sequencia{  quantidade++ |-|
| |    | val_medio=sequencia[0] foreach x in sequencia{if(x !=val_medio)val_medio=x}  val_medio/=quantidade|-|
