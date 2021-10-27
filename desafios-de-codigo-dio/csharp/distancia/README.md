# Distância

#### Nível: básico

### Desafio

Duas motos (X e Y) partem em uma mesma direção. A moto X sai com velocidade constante de 60 Km/h e a moto Y sai com velocidade constante de 90 Km/h.

Em uma hora (60 minutos) a moto Y consegue se distanciar 30 quilômetros da moto X, ou seja, consegue se afastar um quilômetro a cada 2 minutos.

O seu desafio é ler a distância (em Km) e calcular quanto tempo leva (em minutos) para a moto Y tomar essa distância da outra moto.

### Entrada

O arquivo de entrada contém um número inteiro **K** que representa a quantidade de quilômetro que que a moto Y deve estar da moto X.

### Saída

Imprima o tempo necessário para a moto Y ficar com a quantidade **K** de quilômetro da moto X, seguido da mensagem " minutos".

| Exemplo de entrada | Exemplo de saída |
| :----------------: | :--------------: |
|         30         |    60 minutos    |
|        110         |   220 minutos    |

### Comentário

Esse desafio é bem simples. Já temos a informação de que a moto Y se desloca 1 km a cada 2 minutos. Ou seja, é uma relação de 1 para 2, bastando multiplicar o valor da distância por 2 para encontrar o tempo. O que precisamos fazer é escrever essa equação na sintaxe da linguagem.