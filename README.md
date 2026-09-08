# consumo-energia
# ⚡ Sistema de Cálculo de Consumo de Energia

![Python](https://shields.io)
![GitHub](https://shields.io)
![Status](https://shields.io)

## 📝 Sobre o Projeto

Este é um script interativo em **Python** desenvolvido para calcular o **consumo mensal estimado** (baseado em 30 dias) de qualquer eletrodoméstico. O sistema interage com o usuário via terminal para coletar as especificações técnicas do aparelho e exibir o resultado em kWh/mês.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.14 (executado no console)

## 🧮 Fórmula Utilizada

O cálculo realiza a projeção para um período padrão de 30 dias utilizando a seguinte lógica:

\[Consumo\ Mensal\ (kWh) = \frac{Pot\hat{e}ncia\ (W) \times Horas\ de\ Uso\ Di\text{á}rio \times 30}{1000}\]

## 🚀 Como Executar o Programa

### Pré-requisitos
Certifique-se de ter o **Python** instalado em seu sistema operacional.

### Passo a Passo

1. **Clonar o repositório:**
   ```bash
   git clone [app.py](https://github.com/user-attachments/files/31935218/app.py)
   ```

2. **Navegar até o diretório:**
   ```bash
   cd consumo-de-energia
   ```

3. **Executar o script:**
   ```bash
   python app.py
   ```

4. **Exemplo de Uso no Terminal:**
   ```text
   Digite o nome do aparelho: geladeira
   A potência da geladeira em watts (W): 110
   Digite o tempo médio de uso diário de(a) geladeira em horas: 24
   
   Aparelho: geladeira
   Consumo estimado: 79.2 kWh/mês
   ```

---
Desenvolvido com ❤️ por [Bethania](https://github.com)


