# O que você irá encontrar no: roteiro-PWM
Este projeto é um guia prático de como controlar a velocidade de motores via PWM. Desenvolvido no PlatformIO e validado via simulação no Proteus, o sistema foca no controle preciso em duty cycles e interface por botões. Aqui você encontra desde o código-fonte até os esquemáticos e a documentação técnica.

# 1. Introdução ao PWM -> O que é Modulação por
Largura de Pulso (PWM)

A modulação por largura de pulso (PWM, do inglês
Pulse Width Modulation) é uma técnica utilizada para
controlar a quantidade média de energia entregue a
um dispositivo eletrônico.
• O PWM possui dois parâmetros principais: frequência
e ciclo de trabalho (duty cycle).
• A frequência se refere ao número de vezes que o
sinal se repete em um segundo e é medida em hertz
(Hz).
• O ciclo de trabalho é a proporção do tempo em que o
sinal está em nível alto em relação ao tempo total do
período, geralmente expressa em porcentagem (%)

# 2. Componentes Necessários
Para esse projeto você precisará: 
- Button
- Cell
- L293D
- Motor
- Resistor 10K

# 3. Esquemático 
Abaixo segue a estrutura do projeto:
<img width="774" height="544" alt="esquematico" src="https://github.com/user-attachments/assets/29bdc0d6-e486-4b96-b919-a618ba271b1a" />

Agora, utilizando a Modulação por Largura de Pulso, podemos verificar os diferentes estágios de pulsos, sendo: 

- 25% Duty Cycle
<img width="1311" height="821" alt="25porc duty cycle" src="https://github.com/user-attachments/assets/48451ac5-e977-4805-8236-2def057afc41" />


- 50% Duty Cycle
<img width="1295" height="813" alt="50porc  duty cycle" src="https://github.com/user-attachments/assets/d9a95392-09c7-4d60-9d03-8b7ac8e92c53" />


- 75% Duty Cycle
<img width="1303" height="827" alt="75porc  duty cycle" src="https://github.com/user-attachments/assets/ef91fdbb-ace5-41b7-a122-9a446eb9f1e2" />


- 100% Duty Cycle
<img width="1360" height="836" alt="0porc  duty cycle" src="https://github.com/user-attachments/assets/db1539ec-2c15-492a-b723-a7bbd7155a00" />




