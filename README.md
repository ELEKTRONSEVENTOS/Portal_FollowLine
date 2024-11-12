# Portal_FollowLine
Esse é um portal de tomada de tempo para competições de robótica para a categoria FollowLine

Foi utilizado dois sensores E18-D80NK para detectar a passagem do robô no portal, o potenciomentro fica de fácil acesso.

Os cabos utilizados form do tipo manga de 4 vias + GND (Malha)
Um cabo com 1,20m com ambos os lados com conector MIC FEMEA de 4 vias em ambos os lados, conectando 1 com 1, 2 com 2, 3 com 3 e 4 com 4.
O outro cabo com comprimento de 3 m também com conector MIC FEMEA de 5 vias em ambos os lados e conectados como o anterior.

No suporte do sensor (Parede_Sensor.stl) foram instalados dois conectores MIC, um MIC Femea de 5 vias e outro MIC Femea de 4 vias e estes 
foram conectados entre si seguindo a orientação do arquivo (Diagrama dos Conectores.png).
Como cada suporte pega apenas um sensor, escolha um suporte para ser o sensor 1 e outro será o sensor 2. Observe que no Diagrama do Portal os conectores MIC de 4 vias ficam em posições opostas, 
assim, o cabo manga de 4 vias conecta um portal ao outro e sem cruzamento de cabos. O cabo de MIC de 5 vias conectará apenas um dos lados do portal ao sistema que cronometrará os tempos.

Os arquivos Parede_Sensor.stl e Parede_Simples.stl foram impressos sem suporte e em PLA. Os pés tem entrada para ventosas para ajudar a fixar na pista.

A parte superior do portal (Chegada e Largada) tem a opção de impressão bi-partida ou não. No caso da bi-partida, esta foi impressa em pé em relação a base e foi colocado suporte com "roof top" para que as
letras podessem ter uma boa definição. Para cada parte superior imprimir uma emenda_inferior e duas emenda_superior.

Caso queira colocar LED's luminosos, os arquivos AcrilicoX.dxf já possui as dimensões necessárias. O acrilico de 10mm de espessura deve ser contado a laser e na parte das letras usar a opção scan na máquina
de corte a laser.
