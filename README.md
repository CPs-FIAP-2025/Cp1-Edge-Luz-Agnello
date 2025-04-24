
# 🔅 Sistema de Monitoramento de Luminosidade para Vinheria Agnello

## ♦ Descrição do Projeto
O sistema desenvolvido para a Vinheria Agnello tem como objetivo monitorar as condições de luminosidade do ambiente onde os vinhos são armazenados. A qualidade do vinho pode ser impactada diretamente por fatores como temperatura, umidade e luminosidade, e este sistema visa garantir que a luminosidade esteja sempre dentro dos limites recomendados para preservar a qualidade do vinho. O primeiro desafio consiste na implementação de um sistema de monitoramento utilizando Arduino e sensores de luminosidade LDR (Light Dependent Resistor).

## ♦ Funcionalidade
- O sistema utiliza um sensor LDR para capturar os dados de luminosidade do ambiente.
- Dependendo da intensidade da luz medida, um sistema de alarme visual é acionado:
  - LED verde: luminosidade dentro dos parâmetros ideais (OK).
  - LED amarelo: luminosidade em níveis de alerta.
  - LED vermelho: luminosidade fora dos limites estipulados (problema).
- Caso a luminosidade atinja níveis de alerta, um buzzer será ativado por 3 segundos. O buzzer continuará soando enquanto os níveis de luminosidade permanecerem fora da faixa ideal.

## ♦ Dependências
Este projeto utiliza os seguintes componentes e bibliotecas:
- **Arduino Uno** ou qualquer outro modelo de Arduino compatível.
- **Sensor LDR** (Light Dependent Resistor) para medição da luminosidade.
- **LEDs** (verde, amarelo e vermelho) para sinalização do status do ambiente.
- **Buzzer** para alerta sonoro em caso de luminosidade em nível de alerta.
- **Resistor de 10kΩ** para configurar o divisor de tensão com o LDR.
- **Biblioteca Arduino IDE** para programação e upload do código no Arduino.

## ♦ Como Reproduzir o Projeto

### 1. Materiais Necessários:
- 1x Arduino Uno
- 1x LDR (Light Dependent Resistor)
- 1x Resistor de 10kΩ
- 3x LEDs (verde, amarelo e vermelho)
- 1x Buzzer
- Fios de conexão
- Protoboard 

### 2. Montagem do Circuito:
1. Conecte o LDR no pino analógico do Arduino (A0).
2. Conecte os LEDs aos pinos digitais do Arduino (D2 para verde, D3 para amarelo, D4 para vermelho).
3. Adicione resistores em série com os LEDs (220Ω).
4. Conecte o buzzer ao pino digital D5.
5. O resistor de 10kΩ deve ser utilizado para fazer o divisor de tensão com o LDR.

### 3. Como Rodar o Código:
1. Conecte o Arduino ao computador e abra a IDE do Arduino.
2. Selecione o modelo correto do Arduino na IDE e a porta COM.
3. Copie o código acima para a IDE e faça o upload para o seu Arduino.
4. Observe o comportamento dos LEDs e do buzzer conforme a luminosidade medida pelo LDR.

### Nome Integrantes e RM

Leonardo Da Silva Pinto 564929 <br>
Samuel Enzo D. Monteiro 564391 <br>
Lucas Toledo Cortonezi 563271 <br>

### 💻 Linguagens utilizadas

<img 
    align="left" 
    alt="C"
    title="C" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" 
/>
<img 
    align="left" 
    alt="GIT" 
    title="GIT"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
/>


