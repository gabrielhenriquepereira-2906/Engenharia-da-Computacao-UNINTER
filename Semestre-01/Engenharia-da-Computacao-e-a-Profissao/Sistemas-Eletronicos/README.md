# Sistemas Eletrônicos - Práticas de Simulação

Repositório destinado ao registro das atividades práticas de eletrônica utilizando o simulador **Multisim Live**.

## Prática 01: Acionamento de LED com Chave SPST

### Descrição
O objetivo desta prática foi montar um circuito de malha simples para validar o fluxo de corrente contínua e o funcionamento de componentes básicos: fonte, interruptor, resistor e LED.

### Componentes Utilizados
* **Fonte de Tensão (V1):** 5V (DC Voltage Source)
* **Interruptor (S1):** Chave SPST (Single Pole Single Throw)
* **Resistor (R1):** 1kΩ (Utilizado para limitar a corrente e proteger o LED)
* **LED:** Diodo emissor de luz vermelho
* **Ground (Terra):** Referência de 0V indispensável para a simulação

### Resultados
Ao fechar a chave S1, o circuito é completado, permitindo que a corrente flua da fonte através do resistor e do LED até o terra, resultando no acionamento luminoso.

| Circuito Aberto (OFF) | Circuito Fechado (ON) |
| :---: | :---: |
| ![Circuito Aberto](./exercicio-01-off.png) | ![Circuito Fechado](./exercicio-01-on.png) |

---
[Link para o projeto no Multisim Live](https://www.multisim.com/content/RAH4vCgwjdgd74fX57FYQj/exercicio-01-acionamento-led/)
