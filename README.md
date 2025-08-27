# Sensor-de-Movimento-para-ligar-o-LED

### Materiais Necessários:

ESP32 ou ESP8266 (microcontrolador)

Servo Motor (com fio de controle, alimentação e terra)

LED (para indicar o funcionamento do projeto)

Resistor de 220Ω (para o LED)

Protoboard (Breadboard) e fios de conexão

Cabo USB (para conectar o microcontrolador ao computador)

Software: Arduino IDE ou PlatformIO (para programar o microcontrolador)

### Passo 1: Conectar os Componentes

ESP32/ESP8266:

Conecte o pino 5V do ESP32/ESP8266 ao trilho de + da protoboard (para alimentação).

Conecte o pino GND do ESP32/ESP8266 ao trilho de - da protoboard (terra).

LED:

Conecte o pino positivo (anodo) do LED ao pino de controle do ESP32/ESP8266 (digamos, o pino 23, por exemplo).

Conecte o pino negativo (catodo) do LED a um resistor de 220Ω e depois ao trilho de - (terra) da protoboard.

Servo Motor:

Conecte o fio VCC do servo motor ao pino 5V da protoboard (alimentação).

Conecte o fio GND do servo motor ao pino GND da protoboard (terra).

Conecte o fio de controle (geralmente de cor amarela ou laranja) ao pino D12 do ESP32/ESP8266 (pode ser outro pino digital, dependendo da sua escolha).

Fios de Conexão:

Utilize fios jumper para conectar todos os pinos corretamente entre a protoboard e o microcontrolador.

### Passo 2: Programação

Abra o Arduino IDE e selecione a placa correta (ESP32 ou ESP8266).

Se ainda não tiver a biblioteca do servo motor instalada, vá até Sketch > Incluir Biblioteca > Gerenciar Bibliotecas... e procure por Servo e instale.

### Passo 3: Carregar o Código

Conecte o seu ESP32/ESP8266 ao computador via cabo USB.

Selecione a porta correta em Ferramentas > Porta.

Clique em Carregar para enviar o código para o microcontrolador.

### Passo 4: Testando

Após o upload do código, o servo motor deve começar a se mover de 0 a 180 graus e vice-versa.

O LED acenderá assim que o circuito for energizado e o código começar a rodar.

![Um exemplo Pronto]()
