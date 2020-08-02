# MAB20
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

#### Requisitos
1.Ligar as bombas de Porão
    - Ligar por controle manual
    - Ligar por controle automatico
2.Manter as baterias isoladas galvanicamente
     - Usar isolamento otico
3.Proteções
     - Limitar a corrente de transiente do relé para não queimar  o transistor de acionamento 
     - Fusiveis
     - Filtrar ruidos que possam resultar em falsos acionamentos

           

#### Abordagens
1.Driver da bomba
 
 ![](https://github.com/ZeniteSolar/MAB20/blob/master/hardware/IMG/Pump_Driver.png?raw=true)









