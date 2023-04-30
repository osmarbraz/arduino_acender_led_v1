# Projeto Arduíno mais simples

## Contextualização

Neste experimento faremos com que o LED embutido vinculado ao pino digital 13 (pino digital incorporado LED_BUILTIN = 13) pisque. Este é o experimento  mais simples que se poder fazer com o Arduíno.

## Lista de componentes:

- 1 – Arduíno UNO R3
- 1 – Um cabo de conexão USB

## Esquema do projeto

![Esquema do projeto](esquema_projeto.jpg)

## Experimentar e pesquisar:

- Use o comando "Serial.println(<NOME_IDENTIFICADOR>);"  no código fonte para exibir o valor de constantes no monitor serial.
	- Para visualizar o monitor serial na IDE Arduíno acesse o menu Ferramentas (Ctrl+Shift+M).
	- Exemplo, coloque o comando depois da última linha de comando: "Serial.println(LED_BUILTIN);".
- Qual o valor das constantes LOW e HIGH?
- Qual o valor das constantes OUTPUT e INPUT?
- Qual o resultado de apagar a linha 9 ("delay(1000);")?
- Qual o resultado de mover a linha 9 ("delay(1000);") para o final no bloco de loop()entre as linhas 12 ("digitalWrite(LED_BUILTIN, HIGH);") e 13 ("}")?

## Projeto no Tinkercad

https://www.tinkercad.com/things/bqfWWQWUI0B