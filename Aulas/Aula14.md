# AULA 14: TABELAS
Para adicionar uma tabela, use três ou mais hifens ( ---) para criar o cabeçalho de cada coluna e use pipes ( |) para separar cada coluna. Para compatibilidade, você também deve adicionar um pipe em cada extremidade da linha.

## Exemplo
o código a baixo mostrará como é feito  

    |Nome|Idade|  
    |----|----|  
    |Su|40|  
    |Tiglecerinos|27|  
    |jurubeba|19|

| O resultado disso é:

|Nome|Idade|  
|----|----|  
|Su|40|  
|Tiglecerinos|27|  
|jurubeba|19|

### Alinhamento
Você pode alinhar o texto nas colunas à esquerda, à direita ou ao centro adicionando dois pontos ( :) à esquerda, à direita ou em ambos os lados dos hifens dentro da linha de cabeçalho.

| Os dois pontos a esquerda(: )

    |Nome|Idade|  
    |:----|:----|  
    |Su|40|  
    |Tiglecerinos|27|  
    |jurubeba|19|

| Saída esperada:

|Nome|Idade|  
|:----|:----|  
|Su|40|  
|Tiglecerinos|27|  
|jurubeba|19|

<br>

| Os dois pontos a direita( :)

    |Nome|Idade|  
    |----:|----:|  
    |Su|40|  
    |Tiglecerinos|27|  
    |jurubeba|19|

| Saída esperada:

|Nome|Idade|  
|----:|----:|  
|Su|40|  
|Tiglecerinos|27|  
|jurubeba|19|

<br>

| Os dois pontos em ambos lados(: :)

    |Nome|Idade|  
    |:----:|:----:|  
    |Su|40|  
    |Tiglecerinos|27|  
    |jurubeba|19|

| Saída esperada:

|Nome|Idade|  
|:----:|:----:|  
|Su|40|  
|Tiglecerinos|27|  
|jurubeba|19|

#### Observações
Você não pode usar títulos, citações, listas, regras horizontais, imagens ou a maioria das tags HTML.