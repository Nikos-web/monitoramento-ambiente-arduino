# monitoramento-ambiente-arduino
LINK PARA PROJETO-->https://www.tinkercad.com/things/7kD6szAevbl-monitoramento-ambiente-arduino
Descrição:
Este projeto busca monitorar a temperatura, umidade e luminosidade de um ambiente usando sensores conectados ao Arduino. O sistema exibe os dados em um display LCD e ativa LEDs e buzzer conforme condições críticas de ambiente, com alertas visuais e sonoros.
Funcionamento:
Luminosidade-->
Baixa: LED verde aceso.
Média: LED amarelo aceso + mensagem no LCD.
Alta: LED vermelho aceso + mensagem no LCD + buzzer ativado.
Temperatura-->
Dentro da faixa: “Temperatura OK”.
Alta (> 15°C): “Temp. Alta” + LED amarelo + buzzer.
Baixa (< 10°C): “Temp. Baixa” + LED amarelo + buzzer.
Umidade-->
Dentro da faixa: “Umidade OK”.
Alta: “Umidade Alta” + LED vermelho + buzzer.
Baixa: “Umidade Baixa” + LED vermelho + buzzer.
