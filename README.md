# Previsão de Preços de Ações com LSTM
📌 Sobre o Projeto

Este projeto tem como objetivo prever os preços de fechamento de ações utilizando Redes Neurais Recorrentes (RNNs) com a arquitetura LSTM (Long Short-Term Memory). Ele permite que o usuário insira um ticker de ação e obtenha previsões futuras baseadas em dados históricos.

🚀 Tecnologias Utilizadas
-Python 🐍
-Pandas (Manipulação de dados)
-NumPy (Cálculos matemáticos)
-Matplotlib & mplcyberpunk (Visualização)
-Yahoo Finance API (Obtenção de dados financeiros)
-Scikit-Learn (Escalonamento de dados)
-TensorFlow/Keras (Construção da rede LSTM)

📊 Como Funciona
1-O usuário insere o ticker de uma ação (ex: AAPL para Apple, PETR4.SA para Petrobras).
2-Os dados históricos de preço de fechamento são baixados do Yahoo Finance.
3-O conjunto de dados é transformado e normalizado.
4-O modelo LSTM é treinado para prever os preços futuros.
5-As previsões são comparadas aos valores reais e plotadas em um gráfico.

🛠️ Como Rodar o Projeto
1️⃣ Instale as dependências:
pip install -r requirements.txt
2️⃣ Execute o script:
python src/main.py
3️⃣ Insira o ticker desejado:
gite o ticker (ex.: AAPL, PETR4.SA, etc.):

📈 Exemplo de Saída
![Figure_1](https://github.com/user-attachments/assets/d1e1f240-c06f-4ec5-96ca-800bc54c7fa5)
