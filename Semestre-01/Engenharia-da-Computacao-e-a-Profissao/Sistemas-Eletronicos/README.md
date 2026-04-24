# Sistemas Eletrônicos - Práticas de Simulação

Repositório destinado ao registro das atividades práticas de eletrônica utilizando o simulador **Multisim Live**.

## Prática 01: Acionamento de LED com Chave SPST

### Descrição
O objetivo desta prática foi montar um circuito de malha simples para validar o fluxo de corrente contínua e o funcionamento de componentes básicos: fonte, interruptor, resistor e LED.

### Componentes Utilizados
* **Fonte de Tensão (V1):** 5V (DC Voltage Source)
* **Interruptor (S1):** Chave SPST (Single Pole Single Throw)
* **Resistor (R1):** 1kΩ
* **LED:** Diodo emissor de luz vermelho
* **Ground (Terra):** Referência de 0V indispensável para a simulação

### Resultados
Ao fechar a chave S1, o circuito é completado, permitindo que a corrente flua da fonte através do resistor e do LED até o terra.

| Circuito Aberto (OFF) | Circuito Fechado (ON) |
| :---: | :---: |
| ![Circuito Aberto](./exercicio-01-off.png) | ![Circuito Fechado](./exercicio-01-on.png) |

---
[Link para o projeto no Multisim Live (Prática 01)](https://www.multisim.com/content/RAH4vCgwjdgd74fX57FYQj/exercicio-01-acionamento-led/)

---

## Prática 02: Divisor de Tensão e Medição de Corrente

### Descrição
Análise técnica de um circuito em série composto por dois resistores para validar a **Lei de Ohm** e observar o fenômeno do **Divisor de Tensão**.

### Componentes Utilizados
* **Fonte de Tensão:** 5V DC
* **Resistores:** R1 (1kΩ) e R2 (Variável: 500Ω a 2kΩ)
* **Instrumentação:** Voltímetros e Amperímetro (Probes)

### Análise de Resultados (Variação de R2)
| Configuração Base (1kΩ) | Variação para 500Ω | Variação para 2kΩ |
| :---: | :---: | :---: |
| ![Base](./exercicio-02-base.png) | ![Low Res](./exercicio-02-variacao-baixo.png) | ![High Res](./exercicio-02-variacao-alto.png) |

---
[Link para o projeto no Multisim Live (Prática 02)](https://www.multisim.com/content/99KeK9YzxqVsrFAEBNecEH/pratica-02-divisor-de-tensao-e-medicoes-em-serie/)

---

## Prática 03: Sinal de Clock e Análise de Frequência

### Descrição
Introdução à eletrônica digital através da análise de um sinal de **Clock** (Onda Quadrada). O experimento foca na visualização do comportamento da tensão em função do tempo e no entendimento dos conceitos de frequência e período.

### Conceitos Matemáticos
A relação entre o tempo de um ciclo (Período - $T$) e a quantidade de ciclos por segundo (Frequência - $f$) é dada por:
$$f = \frac{1}{T}$$
Para o sinal de **1kHz** utilizado:
$$T = \frac{1}{1000} = 0,001s \text{ (ou 1ms)}$$

### Visualização no Grapher
Utilizando a ferramenta **Split/Grapher**, foi possível observar a transição instantânea entre os níveis lógicos **0** (0V) e **1** (5V), característica fundamental dos sistemas digitais.

| Esquemático do Circuito | Análise de Onda (Grapher) |
| :---: | :---: |
| ![Schematic](./exercicio-03-schematic.png) | ![Grapher](./exercicio-03-grapher.png) |

### Conclusão Técnica
Diferente da corrente contínua (DC), o sinal de clock permite a sincronização de tarefas em sistemas computacionais. A prática demonstrou como instrumentos de medição de tempo são essenciais para analisar sinais que variam periodicamente.

---
[Link para o projeto no Multisim Live (Prática 03)](https://www.multisim.com/content/QzyhmcM9BZfZv3ZYjWCuG7/pratica-03-analise-de-sinal-de-clock-e-ondas-quadradas/)
