# Blog Drey 👍

## Post 1 (20260818)

### O que eu achava que veria na disciplina?

Imaginei que ia ser uma matéria de "Front End", voltada para a interface dos computadores e coisas do tipo

### O que eu entendi que estudaremos?

Na verdade, a gente vai estudar como a imagem digital funciona por dentro. Como a luz vira número, como o olho humano enxerga, por que usamos RGB, como uma foto vira uma matriz de pixels... É bem mais sobre a ciência por trás da imagem do que sobre ferramentas práticas.

## Post 2 (20260825)

### Toda imagem digital começa com luz e reflexo
Uma imagem nada mais é que a combinação de duas coisas: a luz que incide sobre uma cena e o que os objetos dessa cena refletem de volta. A fórmula é simples:

imagem = iluminação × refletância

A iluminação pode ser um sol forte (90.000 lux) ou uma lua cheia (0,1 lux). A refletância vai de 0,01 (veludo preto, quase absorve tudo) até 0,93 (neve, quase devolve tudo). É essa dança entre luz e superfície que forma o que a gente vê.

### Sensores: o olho de metal
Pra capturar essa luz e transformar em imagem digital, usamos sensores. Tem três tipos principais:

Sensor único: varre um ponto por vez (tipo aqueles leitores de código de barras).

Sensores de linha: varrem uma fileira de cada vez (scanners, satélites).

Sensores de área: capturam a cena inteira de uma vez (câmeras digitais).

É como se a tecnologia tivesse inventado três jeitos diferentes de copiar o olho.

### Amostragem e quantização: o mundo real vira número
A luz é contínua, mas o computador só entende números. Então a gente precisa:

Amostrar: decidir quantos pontos (pixels) vão representar a imagem — é a resolução.

Quantizar: decidir quantos níveis de cinza cada pixel vai ter — é a profundidade de cor.

Uma imagem de 8 bits tem 256 tons de cinza. Uma de 1 bit tem só preto e branco. Quanto mais bits, mais suave a transição entre os tons.

### Resolução espacial: o DPI que todo mundo ouve falar
Resolução é basicamente quantos pixels cabem numa determinada área. Quanto mais, mais detalhe.

DPI (dots per inch): usado pra impressão.

PPI (pixels per inch): usado pra telas.

Sabe quando alguém fala "essa foto tem 300 DPI"? É isso — é a densidade de pontinhos que formam a imagem. Mais pontinhos = mais qualidade (e mais peso no arquivo).

No fim das contas: uma imagem digital é uma tradução. A luz vira sinal, o sinal vira número, o número vira pixel. E no meio do caminho, a gente decide quantos pixels usar e quantos tons de cinza são suficientes. A arte da imagem digital é saber onde vale a pena gastar bit.
