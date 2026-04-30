# Sistemas Embarcados com Arduino | Arduino Embedded Systems

[Português](#português) | [English](#english)

---

<h2 id="português">Versão em Português</h2>

Integração entre firmware (C++) e hardware utilizando a plataforma Arduino. Foco em controle de temporização, leitura analógica e automação baseada em sensores.

### 1. Controle de Temporização (Blink LED)
Acionamento de saída digital para alternância de estado em intervalos de 1s.
* **Hardware:** Arduino Uno, Resistor 220Ω, LED.
* **Firmware:** Configuração de Pin Mode (Output) e manipulação de ciclos de delay.

<div align="center">
  <img src="./blink-led.png" width="500px">
  <p><b>Figura 1:</b> Simulação do circuito Blink (Pino Digital 2).</p>
  <a href="https://www.tinkercad.com/things/kmfK5OYC6PL-exercise-01-blink-led-exercicio-01-blink-led">🔗 Simulação Interativa (Tinkercad)</a>
</div>

### 2. Sensor Crepuscular (LDR)
Sistema de automação para acionamento de carga baseado em luminosidade ambiente.
* **Hardware:** Divisor de Tensão (LDR + Resistor Fixo), Entrada Analógica A0.
* **Lógica:** Implementação de Threshold (< 200) para controle condicional de saída.
* **Diagnóstico:** Monitoramento Serial em tempo real para calibração do sensor.

<div align="center">
  <img src="./sensor-ldr.png" width="500px">
  <p><b>Figura 2:</b> Automação via LDR (Entrada A0 / Saída D8).</p>
  <a href="https://www.tinkercad.com/things/2RSLdo5xVcm-exercise-02-ldr-light-sensor-exercicio-02-sensor-de-luz-ldr">🔗 Simulação Interativa (Tinkercad)</a>
</div>

> **Nota Técnica:** Com baixa luminosidade, o divisor de tensão fornece **13.9mV** ao pino A0, convertido para o valor **3** no Monitor Serial, acionando o LED.

---

<h2 id="english">English Version</h2>

Integration between firmware (C++) and hardware using the Arduino platform. Focused on timing control, analog readings, and sensor-based automation.

### 1. Timing Control (Blink LED)
Digital output activation for state toggling at 1s intervals.
* **Hardware:** Arduino Uno, 220Ω Resistor, LED.
* **Firmware:** Pin Mode configuration and delay cycle management.

### 2. Twilight Sensor (LDR)
Automation system for load activation based on ambient light levels.
* **Hardware:** Voltage Divider (LDR + Fixed Resistor), Analog Input A0.
* **Logic:** Threshold implementation (< 200) for conditional output control.
* **Diagnostics:** Real-time Serial Monitoring for sensor calibration.

> **Technical Note:** At low light levels, the voltage divider provides **13.9mV** to pin A0, converted to value **3** in the Serial Monitor, triggering the LED.

---
**Status:** Concluído / Completed.
