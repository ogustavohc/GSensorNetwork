### GSensorNetwork
<img width="813" height="458" alt="image" src="https://github.com/user-attachments/assets/c1edc8bf-e86a-4b43-b22a-d688010b4817" />

#### O que é?

O GSensorNetwork é um projeto que visa a criação de uma rede de sensores a fim de monitorar ambientes e proporcionar alertas de segurança em caso de emergência em casas, prédios e outros edifícios.

#### Como funciona e que tecnologias utiliza

<p>Utilizei para meu projeto o Visual Studio Code com a extensão Plataform IO, com o framework Arduino para o ESP8266. Havia planos para utilizar a versão para ESP-IDF, mas diante de problemas com a configuração e versões desatualizadas, foi preferida a mais bem mantida versão do Plataform IO, que embora mais amigável para iniciantes, não é menos útil. </p>

<p>As unidades de monitoramento utilizam MQTT para enviar e receber os alertas, assim como a desativação dos mesmos. Também é utiliza a biblioteca da Adafruit para DHT22 a fim de ler temperatura e humidade na unidade que possuí o sensor, com essas opções no código podendo ser ativadas ou desativadas de acordo com os sensores presentes.</p>

https://www.youtube.com/watch?v=0hu5iRDC58g

#### Lista de componentes

Uma unidade mínima do sistema utiliza: <br>
- Uma placa ESP8266 NodeMCU v3; <br>
- Um LED; <br>
- Um resistor de 1K Ohm <br>
- Um Buzzer de 3.3-5V; <br>
- Fios ou Jumpers para as ligações.

##### Um sistema de monitoramento residencial e comercial, baseado no protocolo wireless MQTT e utilizando o ESP8266-12E, NodeMCU v3.
