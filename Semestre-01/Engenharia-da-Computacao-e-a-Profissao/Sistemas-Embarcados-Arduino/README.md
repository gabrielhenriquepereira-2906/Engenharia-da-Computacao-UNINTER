# Automação com Arduino

Este projeto explora a integração entre software (firmware) e hardware através da plataforma Arduino, focando em controle de periféricos e leitura de dados ambientais.

## Atividades Realizadas
1. **Blink Control:** Controle de temporização de um LED.
2. **Sensor Crepuscular:** Sistema automático que liga o LED conforme a ausência de luz (usando LDR).

## Componentes Utilizados
* Arduino (Uno ou Simulação)
* LED e Resistor (220Ω)
* Sensor LDR e Resistor (10kΩ)
* Protoboard e Jumpers

## Lógica de Funcionamento
O sistema utiliza um divisor de tensão para converter a variação de resistência do LDR em um sinal de tensão legível pelo conversor AD do Arduino.
