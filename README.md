# MAB19
  **M**odulo de **A**cionamento das **B**ombas de porão

Embarcação Guarapuvu II

Equipe Zênite Solar

### Sobre

O módulo de acionamento das bombas encarrega-se de receber os dados que o piloto envia por meio
do Módulo de Interface de Controle (MIC), ou pelo sensor de altura da água, usando uma interface CAN, rede
que diminui o número de cabos no sistema e diminui seu peso.
Pela regra, o circuito das baterias auxiliares deve ser isolado da bateria principal, a rede CAN está
conectada no circuito da principal, para isolar os dados da rede são recebidos por um microcontrolador e
isolados com opto-acopladores.


![](https://github.com/ZeniteSolar/MAB20/blob/master/hardware/IMG/3DUP.png?raw=true)
![](https://github.com/ZeniteSolar/MAB20/blob/master/hardware/IMG/3DDOWN.png?raw=true)










O módulo exibido na Figura 18 divide-se em vários blocos: canbus, atmega, power supply, canbus-
connector, filter, pump_driver. Os circuitos que recebem, processam e alimentam o CAN, usam um layout
padrão utilizado no barco para otimizar o processo de montagem.
