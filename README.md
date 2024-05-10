# O Caso da Vinheiria Agnello - Edge Computing Checkpoint 2

Esse é um projeto desenvolvido para poder gerenciar os fatores de que podem influenciar na qualidade do vinho como: Luminosidade, Temperatura e Umidade. O projeto utiliza um DHT22 para medir esses fatores, e um sistema de leds compostos de 3 leds e um display LCD para mostrar a qualidade do ambiente. Além disso, há um buzzer para saor um alerme quando as condiçôes do ambiente estiverem impropriar 


## integrantes :

RM:554952 - André flores

RM: 558537 - Luan Ramos

RM: 555189 - Matheus Bortolotto

RM: 556930 - Matheus Ricciotti

RM:556892 - Guilherme Lunghini

 
## Principais Requisitos

1. Enquanto o ambiente estiver escuro, o LED Verde deve ficar aceso; 

2. Enquanto o ambiente estiver a meia luz, o LED amarelo deve ficar aceso e mensagem de “Ambiente a meia luz” deve ser mostrado no Display;

3. Enquanto o ambiente estiver totalmente iluminado, o LED vermelho deve ficar aceso e a mensagem “Ambiente muito claro” deve ser mostrado no display;

4. Enquanto o ambiente estiver totalmente iluminado, o Buzzer deve ficar ligado continuamente;

5. Enquanto o ambiente estiver com uma temperatura entre 10°C e 15°C, o Display deve informar “Temperatura OK” e também mostrar o valor da temperatura;

6. Enquanto o ambiente estiver com uma umidade entre 50% e 70%, o Display deve informar “Umidade OK”, e também mostrar o valor da umidade;

7. Os valores apresentados no display devem ser a média de pelo menos 5 leituras dos sensores, e os valores devem ser apresentados a cada 5 segundos;

8. Enquanto a temperatura estiver fora da faixa ideal, o LED Amarelo deve ficar aceso e o Buzzer deve ligar continuamente;

9. Enquanto a temperatura estiver fora da faixa ideal, o Display deve informar “Temp. Alta”, para valores acima de 15°C e também mostrar a temperatura;

10. Enquanto a temperatura estiver fora da faixa ideal, o Display deve informar “Temp. Baixa”, para valores abaixo de 10°C e também mostrar a temperatura;

11. Enquanto a umidade estiver fora da faixa ideal, o LED Vermelho deve ficar aceso e o Buzzer deve ligar continuamente;

12. Enquanto a umidade estiver fora da faixa ideal, o Display deve informar “Umidade. Alta”, para valores acima de 70% e também mostrar a umidade;

13. Enquanto a umidade estiver fora da faixa ideal, o Display deve informar “Umidade. Baixa”, para valores abaixo de 50% e também mostrar a umidade;





## Como reproduzir :

### Componentes:

1 Arduino

1 Placa de ensaio

3 Leds (verde, amarelo,vermelho)

4 Resistores

1 DHT22 

1 LCD1602 

1 Buzzer 

1 Módulo sensor fotoresistor

### Passos:

1 - Montar os componentes de acordo com imagem 

![image](https://github.com/Luansramos/Edge-Cp2/assets/161903762/2c9d7f34-b318-4f4e-8585-c8acce54d464)


2 - Rodar o codigo 

3 -  Rodar e ver se o codigo está funcoinando


## dependencias:

Pesquisas na internete

Videos no youtube

Arduino.css
