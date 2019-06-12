# Termostato

**Conceito**  

Sistema de controle destinado a manter constante a temperatura de determinado sistema, através de regulação automática.  

**Função**  

Permite o usuário inserir uma temperatura desejada para o seu ambiente, sendo que quando a temperatura deste ambiente ultrapassada a desejada, o termostato fecha um relé e ativa um motor DC, que serve como o ar condicionado, resfriando o ambiente. Caso contrário, o relé abre e desliga o motor DC.  

**Motivação**  

Apresenta-se como um sistema barato e eficiente de automação residencial. Tem como vantagens a economia de energia, além de conforto para o usuário.

**Por que usar Labview?**

O Labview é um ambiente de programação gráfica que desenvolve software mais voltado para engenharia, como medições, testes, sistemas de controle, sistemas de monitoramento etc. Pode se comunicar com inúmeros Hadwares, é escalável através de targets e SO’s diferentes, além de fornecer bibliotecas de análise integradas. Por esses motivos, ele foi escolhido para desenvolver um termostato, que necessita de uma interface gráfica prática, da captura da temperatura do ambiente e de funções de análise da mesma.

# Esboço da interface gráfica

![Labview 5](https://user-images.githubusercontent.com/48916663/59390002-65ffc980-8d46-11e9-8a21-1768ff5002e1.PNG)


 
Comentários

1. O termômetro mede a temperatura do ambiente.
2. No "SET TEMP" o usuário irá colocar a temperatura desejada para o ambiente.
3. O botão ON/OFF é para ligar/desligar o termostato.
4. O botão STOP é para parar, caso haja algum erro na leitura da temperatura.
5. Os LEDs indicam se o sistema está resfriando ou esquentando.
