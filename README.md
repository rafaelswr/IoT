# IoT
Projeto Académico de Domótica para Internet Das coisas.

 A domótica envolve a integração de tecnologia e sistemas para controlar e automatizar diversos aspectos de uma residência, como iluminação, temperatura, segurança, áudio, vídeo, eletrodomésticos e outras funcionalidades.

Através da domótica, é possível criar um ambiente inteligente e interconectado, onde os dispositivos eletrônicos e sistemas de uma casa podem ser controlados de forma centralizada e programada, proporcionando conforto, eficiência energética e segurança.

Os sistemas domóticos podem ser controlados por meio de painéis de controle, computadores, smartphones ou tablets, permitindo que os usuários gerenciem e monitorem os dispositivos e sistemas remotamente, mesmo estando fora de casa. Além disso, a domótica também pode ser integrada a assistentes de voz, como a Amazon Alexa ou o Google Assistant, permitindo o controle por comandos de voz.

Entre os benefícios da domótica estão o aumento do conforto e conveniência, economia de energia, segurança aprimorada e acessibilidade. Por exemplo, é possível programar o sistema de iluminação para ligar e desligar em horários específicos, controlar a temperatura ambiente de forma automática, monitorar câmeras de segurança remotamente e até mesmo simular a presença de pessoas quando a casa está vazia.

Em resumo, a domótica representa a integração de tecnologia e automação para transformar uma residência em um ambiente inteligente, oferecendo maior controle, eficiência e segurança para os moradores.

Neste projeto, é proposto fazer a automação e monitoramento de um espaço, ambiente interno, de um divisão de uma casa.
O sistema, simulado no wokwi, permite ter um conjunto de sensores para coletar dados e enviá-los através de MQTT, publish-subscribe,
para o ambiente do Node-red. Uma vez que os dados são recolhidos e enviados, o node-red trata do processamento deles, mostrando em uma dashboard,
publicando em determinado tópico para os atuadores (simulados no wokwi) receberem instruções.


Tecnologias utilizadas:
Microntrolador ESP32, Node-Red, InfluxDB, Simulador Wokwi com sensores(dht22,PhotoResistor) e atuadores(servo Motor para janela, LED)

Linguaguens:
HTML,CSS,JS,C++
