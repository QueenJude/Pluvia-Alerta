# 🌧️ Sistema de Monitoramento de Alagamentos com Arduino

## Descrição do Problema
Enchentes urbanas são um problema recorrente em diversas cidades, especialmente durante períodos de chuvas intensas. Esses alagamentos podem causar danos materiais, transtornos à mobilidade urbana e colocar vidas em risco. A falta de sistemas de alerta preventivo acessíveis dificulta a ação rápida e eficaz da população e das autoridades.
----
## Visão Geral da Nossa Solução
Este projeto apresenta um sistema inteligente de monitoramento de nível de água, desenvolvido com Arduino e composto por um sensor ultrassônico, LEDs indicativos, buzzer e display LCD. O objetivo é fornecer uma solução prática, acessível e de resposta rápida para situações de risco de alagamento, por meio de alertas visuais e sonoros em tempo real. Ao detectar a aproximação da água, o sistema classifica o nível como seguro, alerta ou crítico (alagamento iminente), permitindo que moradores, comércios ou até agentes públicos tomem decisões com antecedência e evitem prejuízos.
----

### Componentes Utilizados:
- Arduino Uno
- Sensor Ultrassônico (HC-SR04)
- Display LCD 16x2 com interface I2C
- LEDs: Verde, Amarelo e Vermelho
- Buzzer piezoelétrico
- Resistores
- Protoboard e jumpers
----
### Como o sistema interpreta os níveis de água:
O sistema utiliza um sensor ultrassônico para medir a distância entre o solo e a superfície da água. Com base nessa medição, ele classifica a situação em três níveis:
🔹 Nível Seguro (acima de 100 cm):
A água está em um nível controlado e sem risco iminente. O LED verde acende para indicar normalidade e o buzzer permanece desligado.

🟡 Nível de Alerta (entre 50 cm e 100 cm):
A água começou a subir e representa um risco potencial de alagamento. O LED amarelo é ativado como sinal de atenção. O buzzer permanece desligado para evitar alarme prematuro.

🔴 Nível Crítico (abaixo de 50 cm):
A distância detectada é muito pequena, indicando que a água já está próxima do sensor, ou seja, há risco real de alagamento. O LED vermelho acende e o buzzer emite sinais sonoros intermitentes como alerta de emergência.
----
### Instrução para fazer a Simulação:
1. Acesse o link acima.
2. Clique em "Iniciar Simulação".
3. Use a barra deslizante do sensor ultrassônico para simular o nível da água (diminuindo a distância).
4. Observe as mudanças nos LEDs, no display LCD e no buzzer.
----
### Link do Projeto no Tinkcard:
(https://www.tinkercad.com/things/gc62KntR7AV/editel)
----
### Video Demonstrativo do nosso Projeto:

----
