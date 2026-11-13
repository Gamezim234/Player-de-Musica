Reprodutor de Música com Arduino

Sobre o projeto

Esse projeto é um reprodutor de músicas feito com Arduino Uno. Ele usa um display LCD 16x2 para mostrar as informações, um buzzer para tocar as músicas e alguns botões para controlar tudo.

É possível escolher entre cinco músicas, avançar, voltar e reproduzir a que foi selecionada.

Componentes utilizados

- Arduino Uno
- Display LCD 16x2
- Buzzer
- 4 botões
- LED vermelho e verde
- Resistores
- Potenciômetro
- Protoboard e jumpers

Conexões

Display LCD 16x2:
- RS: pino 2
- E: pino 3
- D4: pino 4
- D5: pino 5
- D6: pino 6
- D7: pino 7

LEDs:
- LED vermelho: pino 8
- LED verde: pino 9

Botões:
- Reproduzir: pino 10
- Avançar: pino 11
- Voltar: pino 12
- Menu: pino 13

Buzzer:
- Positivo: A0
- Negativo: GND

Músicas disponíveis

1. Super Mario Bros.
2. Pallet Town - Pokémon
3. Megalovania - Undertale
4. Song of Storms - Zelda
5. Sweden - Minecraft

Como funciona

Quando o Arduino é ligado, aparece o menu principal no LCD. Nele, dá para escolher qual música tocar usando os botões.

O botão de avançar vai para a próxima música e o de voltar retorna para a anterior. Quando a música desejada estiver selecionada, é só apertar o botão de reproduzir.

O buzzer é responsável por tocar as melodias, enquanto o LCD mostra qual música está selecionada. Os LEDs servem para indicar o funcionamento do reprodutor.

Programação

O código foi feito em C/C++ para Arduino. Para controlar o LCD, foi utilizada a biblioteca LiquidCrystal.h. O restante do código cuida dos botões, da seleção das músicas e da reprodução das melodias pelo buzzer.
