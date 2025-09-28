# Display-de-7-Seg-mentos-Sequ-ncia-de-0-a-9
# 🔢 Display de 7 Seg­mentos – Sequência de 0 a 9

Este projeto em **MicroPython** controla um display de 7 segmentos (common anode) conectado ao **Raspberry Pi Pico** e exibe os dígitos de **0 a 9** em sequência.

🔗 [Abrir no Wokwi](https://wokwi.com/projects/440482234493945857)

---

## 📖 Descrição

O sistema mapeia cada dígito de 0 a 9 para os segmentos que devem ser acesos ou apagados e faz um “loop” que exibe cada número por meio da ativação dos pinos correspondentes.

---

## 🧠 Funcionalidades

- Define **7 GPIOs** como saídas correspondentes aos segmentos A, B, C, D, E, F e G do display.  
- Mapeia cada número (0 a 9) a um padrão de segmentos (ligados/desligados).  
- Loop contínuo: exibe 0, depois 1, 2, … até 9, com intervalo de **0,5 s** entre cada número.

---

## 🛠️ Tecnologias

- Linguagem: **MicroPython**  
- Placa: **Raspberry Pi Pico**  
- Simulação: **Wokwi**

---

## ▶️ Como executar

1. Acesse o link da simulação no Wokwi.  
2. Inicie a simulação.  
3. O display de 7 segmentos começará a mostrar os números de 0 a 9 repetidamente, com meio segundo entre cada número.

---

Desenvolvido como parte de estudos de **eletrônica digital** e **microcontroladores**.
