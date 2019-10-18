# Gerenciamento remoto de Temperatura

[Projeto Gerenciamento de temperatura](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/projects/1)

[Blog de Acompanhamento - será substituído por outro site - em construção](https://gerenciamento-remoto-de-temperatura.webnode.com) :microphone: :loudspeaker:

## Cronograma do Projeto - data de atualização: 18/10/2019

![Cronograma do Projeto - Gerenciamento Remoto de Temperatura](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/cronograma%20projeto%20-%20rev%2001%20-%202019-10-18.PNG)

:sparkles: **Cronograma de atividades** :sparkles:

- [x] **27/09/2019** - Apresentação da disciplina
- [x] **04/10/2019** - Acompanhamento dos projetos: Apresentação das **Propostas de Projeto** (Plano do Projeto)
- [x] **11/10/2019** - Acompanhamento dos projetos: Apresentação das **Especificações do Projeto** (Requisitos de Sistema, Casos de Uso)
- [ ] **18/10/2019** - Acompanhamento dos projetos: Apresentação do **Entregável 01** (implementação parcial, 30% dos requisitos)
- [ ] **25/10/2019** - Acompanhamento dos projeto: Apresentação do **Entregável 02** (implementação parcial, 60% dos requisitos)
- [ ] **01/11/2019** - Acompanhamento dos projetos: Apresentação Final do Projeto (implementação final, 100% dos requisitos)
- [ ] **3/11/2019 (domingo) - Entrega do trabalho (via Moodle)**

:sparkles: **Resumo de entregáveis** :sparkles:

- [x] Plano do Projeto
- [x] Especificação do Projeto
- [ ] Blog público de acompanhamento da execução do projeto
- [ ] Repositório público contendo o sofware e demais artefatos produzidos durante a execução do projeto (deve ser atualizado frequentenente para evidenciar o andamento das atividades de implementação)
- [ ] Relatório técnico (final)

**Pessoal!** :wave: Segue relação de providências imediatas.

## Providências IMEDIATAS para 18/10/2019
- [x] **Todos** - levantar as atividades futuras que culminaram em 30% dos requisitos a serem entregues e constar no cronograma. Entregar ao Pablo para postar no Blog.
- [x] **Todos** - levantar as dificuldades encontradas no projeto até o momento.
- [ ] **Marcelo** - Levantamento dos equipamentos, custos, materiais a serem utilizados e suas especificações técnicas.
- [x] **Marcelo** - realizar a leitura de temperatura utilizando o ESP32 e o DHT11 para ser apresentado no dia 18/10/2019.
                    Importante fazer um vídeo para incluirmos no blog de acompanhamento.
- [ ] **Marcelo** - pesquisar e testar a abertura e fechamento de janelas, bem como, acionamento de ventiladores utilizando relés.
                    Ainda, coletar base teórica e especificações técnicas para postar no blog e incluir no relatório técnico.
- [ ] **Pablo** - análise de riscos em função dos riscos apresentados no plano de projeto (04/10/2019). Utilizar modelo disponível [Modelo de análise de riscos-doc](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Modelo%20de%20an%C3%A1lise%20de%20riscos-doc.docx) 
- [ ] **Pablo** - base teórica sobre Firebase e AWS.
- [ ] **Pablo** - postar a base teórica do projeto no blog de acompanhamento.
- [ ] **Pablo** - ajustar Blog conforme apresentado no plano de projeto
- [x] **Rafael e Johnatan** - testar a utilização do firebase para disponibilizar aos ESP32 as temperaturas mínima e máxima.
- [x] **Rafael** - montar o caso de uso RF002 - Definir limites de temperatura para incluir no documento requisitos do sistema
- [x] **Sérgio** - ajustar/complementar as informações do cronogramas das etapas.
- [x] **Sérgio** - registrar as dificuldades (conforme documento [Dificuldades.doc](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Dificuldades.docx) encontradas até o momento conforme reunião com a equipe e passar para Pablo postar no blog.
- [ ] **Sérgio** - base teórica sobre ESP32, DHT11, Bluetooth, Wi-fi, MQTT
- [x] **Sérgio** - estruturar e redigir o Relatório Técnico


## Entrega 01 - 18/10/2019
 
- Bases teóricas (obrigatório) 

   - constar fonte de referência bibliográfica que informe como será realizado a leitura de temperatura de um ambiente residencial.
   - quais equipamentos serão utilizados para realização destas leituras, qual a especificação técnica dos materiais e equipamentos?
   - qual a diferenciação de um material/equipamento de um em relação ao outro?
   - quais são os custos e diferença de preços de um para o outro?
   - como se realizará o processo de comunicação entre os vários equipamentos? Qual o pré-requisito necessário para que ocorra tal comunicação?
   - qual o protocolo será adotado?
   - o que é necessário para que o projeto se concretize levando-se em consideração os aspectos técnicos, operacionais e financeiros?

- Re-avaliação de riscos (obrigatório) 
   
   - re-avaliar os riscos possíveis existentes e apresentar novamente conforme modelo de riscos (inclusive os apresentados no plano de projeto).

- Acompanhamento do cronograma (obrigatório) 

   - atualizar o cronograma de atividades do projeto.
   
- Dificuldades (obrigatório) 
  
   - apontar as dificuldades encontradas no projeto - entrega 01.
   
- Atividades futuras (obrigatório) 
 
   - informar as atividades futuras do projeto a serem apresentadas na entrega 02.

## Entrega 02 - 25/10/2019

- [ ] **Johnatan** - Levar maquete
- [ ] **Pablo** - Montar o Perfil da equipe necessária para realizar o projeto - vide pág.1 das [instruçoes do blog](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Modelo-Estrutura%20do%20Blog%20de%20Acompanhamento.pdf) - e entregar ao Pablo para postar no Blog.

### Dificuldades encontradas

**18/10/2019**
- diminuir o consumo de memória para gravação do código no EPROM/FLASH do ESP32

**16/10/2019**
- informar aos ESP32 da casa a rede e senha para permitir o acesso a internet.
- gravar na memória flash dos ESP32, a rede e senha de acesso a internet.
- como realizar a conexão com o firebase - ESP32 e este acessar as temperaturas mínimas e máximas.
- definir as telas do aplicativo Android e qual software de projeto a ser utilizado.

**11/10/2019**
- reaquadação dos casos de uso e diagramas
- desenvolver solução de conexão bluetooth para o aplicativo Android a ser utilizado
- desenvolver solução de conexão webservice, clientservice e cloud MQTT

**09/10/2019**

- indefinição dos casos de uso dada a diversidade de fatores envolvidos
- indefinição do protocolo a ser adotado
- indefinição processo de comunicação com a nuvem
- falta de conhecimento de como utilizar a comunicação do aplicativo com os sensores por bluetooth
- prazo restrito haja visto que todos apresentam outras atividades durante o dia
- escolha de site para postar o blog que seja mais flexível e com mais recursos de apresentação.

### Possíveis soluções para processo de comunicação com a nuvem e protocolo a ser adotado

**11/10/2019**

Trabalho do Aroldo - Nível a laser (protocolo MQTT)

**09/10/2019**

[ AWS IoT - Serviços de IoT para soluções industriais, comerciais e de consumo ](https://aws.amazon.com/pt/iot/)

[Mosquitto . Um cliente/servidor MQTT](https://cadernodelaboratorio.com.br/2018/12/05/mosquitto-um-cliente-servidor-mqtt/)

[MQTT – Um protocolo para IoT](https://cadernodelaboratorio.com.br/2018/11/30/mqtt-um-protocolo-para-iot/)

[MQTT-Hosted message broker for the Internet of Things ](https://www.cloudmqtt.com/)

[Temperature Data record on AWS IoT Core with NodeMCU-ESP32 using Arduino IDE and MQTT Protocol](https://www.youtube.com/watch?v=2y0w977q_yk)

[ESP32 | FLUTTER | FIREBASE - Temperature & Humidity Check App](https://www.youtube.com/watch?v=nVrACWPXi8g)
[Connected Home IoT Use Cases](https://aws.amazon.com/pt/iot/solutions/connected-home/)

[ESP8266 talking to AWS IoT using MQTT](https://www.youtube.com/watch?v=AiCa6E_DBL8)

[Wix.com - Crie um Site Incrível Grátis](https://pt.wix.com/criarsitegratis/pt900?utm_source=bing&utm_campaign=MS_Wix_NEW%5EWix_PR&experiment_id=wix%5Ebp%5E8519664405%5Ewix+login&msclkid=c9063d85d1e51754412c601baf358216&utm_medium=cpc)

[Programar ESP32 com a IDE Arduino – Tutorial Completo](https://www.usinainfo.com.br/blog/programar-esp32-com-a-ide-arduino-tutorial-completo/)

[Tutorial: Intro to Grove Connectors for Arduino/Raspberry Pi Projects](https://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/)

[What is the Grove System?](http://wiki.seeedstudio.com/Grove_System/)

[Projeto ESP32 com Display 16×2](https://www.usinainfo.com.br/blog/esp32-projeto-com-display/)

[ESP32 WiFi: Comunicação com a Internet](https://www.usinainfo.com.br/blog/esp32-wifi-comunicacao-com-a-internet/)

[Projeto ESP32 com Display OLED e Sensor AM2302 DHT22 Medindo Temperatura e Umidade](https://www.usinainfo.com.br/blog/projeto-esp32-com-display-oled-e-sensor-am2302-dht22-medindo-temperatura-e-umidade/)

[ESP32 Tutorial com Primeiros Passos](https://www.usinainfo.com.br/blog/esp32-tutorial-com-primeiros-passos/)

[ESP32 Display Oled: Programando o Display do NodeMCU ESP32](https://www.usinainfo.com.br/blog/programando-o-display-do-nodemcu-esp32-oled/)


## Providências realizadas

```
11/10/2019
```
- [x] **Todos** - apresentação das especificações do Projeto (será alterado)
- [x] **Rafael** - completar o cronograma e passar para Sérgio para que inserir ao plano de projeto e Esse postar no Moodle. Obs. Deveria ser postado dia 04/10/2019.	  
- [x] **Sérgio** - ajustar a apresentação o plano de projeto entregue em 04/10/2019 e postar no Moodle.

```
04/10/2019
```
- [x] definição de quem será o gerente de equipe
- [x] levantamento e definição do que iremos projetar (gerenciamento remoto de uma casa ou empresa)
- [x] quais dispositivos iremos utilizar e acionar
- [x] título e nome do projeto
- [x] especificação do objetivo
- [x] definição da meta
- [x] definição das premissas
- [x] definição das restrições
- [x] definir quem fará o blog / gitHub de acompanhamento do projeto
- [x] definir quem fará o vídeo (possibilidade de postar no youtube). Deverá ser espelho da apresentação à Banca.
- [x] estruturar e  redigir o Plano de Projeto (Project Charter)


## Exemplo de Projetos realizados

[Projeto TheBitBox - Vending Machine com compras por CriptoMoedas](https://thebitboxproject.wordpress.com)

[Projeto STEVE-Sistema de TElemetria VEicular](https://projetosteve.wordpress.com/)

[Projeto Trayker, robô de coleta de bandejas em shoppings](http://everson.dev)

## Elaboração do blog de acompanhamento do projeto

[Modelo-Estrutura do Blog de Acompanhamento](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Modelo-Estrutura%20do%20Blog%20de%20Acompanhamento.pdf)

## Relatório técnico

[Estrutura do Relatório Técnico](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Estrutura%20do%20Relat%C3%B3rio%20T%C3%A9cnico.pdf)

[Relatório Técnico - versão 01 - incompleta](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Relat%C3%B3rio%20t%C3%A9cnico%20-%20Gerenciamento%20Remoto%20de%20Temperatura%20-%20rev%2001.docx)

### Estrutura Base do **nosso** relatório técnico

[Estrutura Base adotada](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/ESTRUTURA%20BASE%20do%20nosso%20Relat%C3%B3rio%20t%C3%A9cnico%20-%20Gerenciamento%20Remoto%20de%20Temperatura.docx)

```
	1. Introdução
	    1.1	Requisitos
	2. Tecnologias
	    2.1 ESP32
	    2.2	DHT11
	    2.3	Bluetooth
	    2.4	Wi-fi
	    2.5	MQTT
	    2.6	Firebase
	    2.7	AWS
	3. Desenvolvimento
	4. Testes
	5. Dificuldades
	6. Conclusão
```
### Exemplo de Relatório Técnicos

[Relatório Técnico - BitBox-uma Cripto-Vending Machine operada via celular](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Relat%C3%B3rio%20T%C3%A9cnico%20-%20BitBox-uma%20Cripto-Vending%20Machine%20operada%20via%20celular.pdf)

[Relatório Técnico - Steve-Sistema de Telemetria Veicular](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Relat%C3%B3rio%20T%C3%A9cnico%20-%20Steve-Sistema%20de%20Telemetria%20Veicular.pdf)

[Relatório Técnico - Trayker - Um sistema automatizado de coleta de bandejas](https://github.com/turma2019-iot/Gerenciamento-remoto-de-temperatura/blob/master/Relat%C3%B3rio%20T%C3%A9cnico%20-%20Trayker%20-%20Um%20sistema%20automatizado%20de%20coleta%20de%20bandejas.pdf)

