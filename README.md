# **Planeta Azul**
## Descrição do Projeto:
Planeta azul é um projeto que visa monitorar a poluição nos oceanos, utilizando sensores para medir o pH da água e a turbidez. O pH da água é um indicador importante da saúde do ecossistema marinho, e alterações nesses níveis podem indicar poluição. Este sistema usa um ESP32, sensores de pH e turbidez, e um display OLED para apresentar as leituras em tempo real.
## Funcionalidade:
Medição de pH: O sistema mede o pH da água do mar para determinar o nível de poluição.
Medição de Turbidez: O sistema também mede a turbidez da água, que pode indicar a presença de partículas e poluentes.
Display OLED: As medições são exibidas em um display OLED, facilitando a visualização dos dados.
![tabela PH](https://github.com/EnzoTM1170/EDGE-_GS_2/assets/143804193/6ca2420b-10e3-4adf-acee-dc896fb47cfd)
## Componentes Utilizados:
### ESP32:
Microcontrolador que serve como cérebro do projeto, processando as leituras dos sensores e atualizando o display OLED.
Possui conectividade Wi-Fi e Bluetooth, permitindo futuras expansões para envio de dados para a nuvem ou integração com aplicativos móveis.

### Sensor de pH:
Mede o pH da água, fornecendo uma indicação direta da acidez ou alcalinidade.
Valores de pH são utilizados para inferir o nível de poluição da água. Por exemplo, um pH entre 7.5 e 8.5 é considerado normal para a água do mar, enquanto valores abaixo de 7 indicam poluição.

### Sensor de Turbidez (LDR):
Utilizado para medir a turbidez da água, indicando a quantidade de partículas suspensas.
A turbidez é mapeada em uma escala de 0 a 100, com valores mais altos indicando maior poluição.

### Display OLED (Adafruit SSD1306):
Display de 128x64 pixels utilizado para exibir os valores de pH e turbidez.
Permite uma visualização clara e fácil das medições em tempo real.

## Instruções de Uso:
### Montagem do Hardware:
Conecte o sensor de pH ao pino A1 (GPIO 35) do ESP32.
Conecte o sensor de turbidez ao pino A0 (GPIO 34) do ESP32.
Conecte o display OLED aos pinos I2C do ESP32 (SDA e SCL).
Certifique-se de que todos os componentes estão corretamente alimentados e conectados.

### Configuração do Software:
Baixe e instale o Arduino IDE.
Instale as bibliotecas necessárias:
Adafruit GFX Library
Adafruit SSD1306
OneWire
DallasTemperature
Carregue o código fonte para o ESP32 utilizando o Arduino IDE.

### Operação:
Ligue o ESP32.
O display OLED mostrará a mensagem "Monitoring Ocean Pollution" e, após alguns segundos, exibirá as leituras de pH e turbidez.
Monitore os valores para verificar o nível de poluição da água do mar.

## Requisitos:
ESP32
Sensor de pH
Sensor de Turbidez (LDR)
Display OLED (Adafruit SSD1306)
Conexões e cabos adequados
Arduino IDE
Bibliotecas Arduino:
Adafruit GFX Library
Adafruit SSD1306
OneWire
DallasTemperature

## Conclusão
O projeto PLANETA AZUL oferece uma solução eficaz para monitorar a poluição nos oceanos, utilizando um ESP32 e sensores de pH e turbidez. Este monitoramento é crucial para a preservação dos ecossistemas marinhos e para a conscientização sobre a poluição da água. Com uma estrutura de código clara e componentes acessíveis, o projeto pode ser expandido e adaptado para diversas aplicações em monitoramento ambiental.

## Membros:
##### RM Enzo Teles 553899 
##### RM Nicolas Ribeiro 553273



























