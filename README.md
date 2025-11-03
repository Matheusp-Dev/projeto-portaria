# projeto-portaria
Projeto portaria para faculdade, data de entrega 18/11


- Iluminação da portaria
   - 5 leds
      > Esses leds devem acender com sensor de luminosidade.
      > Todos são ligados em paralelo
      > Sensor de luminosidade a capitação for <X Todos os leds acendem

- Sensor de estacionamento
  - 3 modulos infravermelhos
      > 6 leds (3 verdes e 3 vermelhos)
      > Toda vez que tiver algo em cima do sensor(For tampado)
      > O sensor emite sinal pro led de High or Low
  - Leds
      > Leds em paralelos
      > Se o sensor estiver coberto o led vermelho acende
      > Se o sensor estiver descoberto o led verde acende
      > Os sinal vem da mesma porta
      > Led verde com a porta not que inverte a porta

- Cerca eletrica
  - 1 interruptor
      > Tem que estar em Pull Up
  - modulo rele
      > Vai estar integrado ao interruptor
  > Quando o interruptor for High ele liga o rele

- Entrada para os moradores
  - Modulo RFID
      > Cartão e uma tag
      > Sempre que aproximar o cartão ou tag do modulo a porta abre
  - Servo motor
      > Porta
      > A porta abre espera 2s e fecha
  - Display LCD
      > Toda vez que a porta abrir o display diz:"Bem vindo!"
      
- Entrada para os carros
  - Modulo de radio
      > Vai receber o sinal do controle
      > Controle tem o botão de A e B
      > A representa a entrada(Servo 1)
      > B representa a saida(Servo 2)
  - 2 servo motores
      > Abre e fecha num periodo de 2s
