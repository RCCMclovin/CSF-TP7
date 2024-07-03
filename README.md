# CSF-TP7

Este trabalho usa o mesmo código das aulas anteriores.

Este trabalho deve ser realizado fora de sala de aula, e é necessário medir a distância entre o transmissor e o receptor. Para medir grandes distâncias com maior facilidade, podem usar o aplicativo "Medidor de áreas e distâncias"  (disponível em [Link para google play store](https://play.google.com/store/apps/details?id=lt.noframe.fieldsareameasure)).

## Medição de perda no espaço livre

Este teste consiste em calcular a perda em espaco livre usando as fórmulas vistas em sala e comparar esses resultados com medições feitas no CDC da UFAM.

### Procediemnto

+ Posicionar o transmissor e o receptor separados por, ao menos, 10m;

+ Calcular a perda em espaço livre e comparar com os resultados medidos;

  + Os resultados da fórmula bateram com os obtidos? Caso negativo discorrer sobre possíveis fatores que possam ter levado a essa diferença.

+ Calcular a área da primeira zona de Fresnel;

+ Repetir para, pelo menos, mais uma distância diferente;

+ Usar as escadas e o segundo andar do CDC para repetir o teste para alturas diferentes, explorar o efeito da diferença de altura entre o transmissor e o receptor;

  + Qual é melhor, o transmissor mais alto ou o receptor?

## Medição de perda com folhagem

Este teste consiste em calcular a perda em um caminho interrompido por vegetação e folhagem. Para este teste, consideraremos o modelo de perda exponencial de Weissberger (_Weissberger's exponential decay_). Alguns atrigos na internet sobre esse modelo:

+ [EVALUATION OF RADIO WAVE  PROPAGATION THROUGH FOLIAGE IN PARTS OF CALABAR, NIGERIA](https://www.ijser.org/researchpaper/EVALUATION-OF-RADIO-WAVE-PROPAGATION-THROUGH-FOLIAGE-IN-PARTS-OF-CALABAR-NIGERIA.pdf);

+ [Characterizing Foliage Influence on LoRaWAN Pathloss in a Tropical Vegetative Environment](https://www.researchgate.net/publication/341043296_Characterizing_Foliage_Influence_on_LoRaWAN_Pathloss_in_a_Tropical_Vegetative_Environment);

+ [Wikipédia](https://en.wikipedia.org/wiki/Weissberger%27s_model);

A fórmula para esta perda é:

![Weissberger's exponential decay](/img/formula.svg)

Onde:

+ L é a perda devido à folhagem
+ f é a frequência da transmissão;
+ d é a distância entre o transmissor e o receptor;

### Procedimento

Entre os blocos da UFAM há vários trechos curtos de vegetação densa, perfeitos para este teste. Escolha um desses trechos.

+ Posicionar o transmissor e o receptor a uma distância conhecida com um trecho de vegetação entre eles;

+ Calcular a perda esperada com o modelo de Weissberger;

+ Comparar com a perda real obtida;

  + Os resultados da fórmula bateram com os obtidos? Caso negativo discorrer sobre possíveis fatores que possam ter levado a essa diferença.
