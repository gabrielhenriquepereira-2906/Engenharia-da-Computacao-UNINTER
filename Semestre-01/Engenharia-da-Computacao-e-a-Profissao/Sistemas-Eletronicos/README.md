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
[Link para o projeto no Multisim Live (Prática 01)](https://www.multisim.com/content/RAH4vCgwjdgd74fX57FYQj/exercicio-01-acionamento-led/)

---

## Prática 02: Divisor de Tensão e Medição de Corrente

### Descrição
Análise técnica de um circuito em série composto por dois resistores. O foco desta prática foi validar a **Lei de Ohm** e observar o fenômeno do **Divisor de Tensão**, monitorando como a variação da resistência impacta a corrente total e a queda de potencial nos componentes.

### Componentes Utilizados
* **Fonte de Tensão:** 5V DC
* **Interruptor:** Chave SPST
* **Resistores:** R1 (1kΩ) e R2 (Variável entre 500Ω e 2kΩ)
* **Instrumentação:** Voltímetros (Ponteiras de Tensão) e Amperímetro (Ponteira de Corrente)

### Análise e Resultados
Durante a simulação, foram realizados testes alterando o valor de R2 para observar a dinâmica do circuito:

1. **Configuração Base (R1=1kΩ, R2=1kΩ):** A tensão foi dividida igualmente (2.5V em cada) e a corrente estabilizou em 2.5mA.
2. **Redução de Resistência (R2=500Ω):** Observou-se um aumento na corrente total, conforme a Lei de Ohm ($I = V/R$).
3. **Aumento de Resistência (R2=2kΩ):** A corrente diminuiu e a queda de tensão sobre R2 aumentou proporcionalmente.

| Configuração Base (1kΩ) | Variação para 500Ω | Variação para 2kΩ |
| :---: | :---: | :---: |
| ![Base](./exercicio-02-base.png) | ![Baixa Resistência](./exercicio-02-variacao-baixo.png) | ![Alta Resistência](./exercicio-02-variacao-alto.png) |

### Conclusão Técnica
A prática comprovou que em um circuito série, a corrente é inversamente proporcional à resistência total. Além disso, validou-se que a soma das quedas de tensão nos componentes passivos é igual à tensão total da fonte.

---
[Link para o projeto no Multisim Live (Prática 02)](COLE_O_NOVO_LINK_AQUI)
