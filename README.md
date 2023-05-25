# DIP Project 
O link em anexo contém 77 imagens de garrafas. Cada garrafa (no centro da imagem) pode possuir um ou mais dos seguintes 8 defeitos:
CONTENT_HIGH,
CONTENT_LOW,
COVER_NONE,
BOTTLE_SMASHED,
LABEL_WHITE,
LABEL_MISPLACED,
LABEL_NONE,
BOTTLE_NONE.
Cada indivíduo/grupo deverá submeter 1 arquivo de notebook (<nome do indivíduo/grupo>.ipynb) contendo uma função que receba uma imagem (numpy) e entregue um array (numpy) contendo 8 valores. Cada valor deve ser:
0 (para ausência do defeito correspondente), ou;
1 (para presença do defeito correspondente).
Requisitos:
1. Utilizar o Opencv 4.5.5.
2. Em cada imagem, considerar somente a garrafa do meio.
3. Trabalho individual ou em dupla. No caso de dupla, o grupo vai decidir a divisão dos pontos que será no mín. 0 e no máx. 20.
4. Utilizar somente técnicas referentes à disciplina de processamento de imagens, excetuando redes neurais.
