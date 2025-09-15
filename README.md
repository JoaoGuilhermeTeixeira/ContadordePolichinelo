🤸‍♂️ Contador de Polichinelos em Tempo Real
Este projeto utiliza visão computacional com Python, OpenCV e MediaPipe para detectar e contar automaticamente polichinelos (jumping jacks) em tempo real através da webcam. Ideal para quem quer monitorar exercícios físicos sem precisar de sensores externos!

📸 Demonstração
<img width="1306" height="770" alt="{3FA3E9DA-A59D-4DCF-AE2B-456DD11830F8}" src="https://github.com/user-attachments/assets/cfdcf5d1-2618-452d-ba0a-e404cbf0ae1d" />



🧠 Tecnologias Utilizadas
Python 3.8+

OpenCV – para captura e manipulação de vídeo

MediaPipe – para detecção de pose corporal

NumPy – para cálculos matemáticos

⚙️ Instalação
Clone o repositório:

bash
git clone https://github.com/JoaoGuilhermeTeixeira/contador-polichinelos.git
cd contador-polichinelos
Crie um ambiente virtual (opcional, mas recomendado):

bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
Instale as dependências:

bash
pip install -r requirements.txt
▶️ Como Usar
Execute o script principal:

bash
python contador_polichinelos.py
A webcam será ativada e o sistema começará a detectar seus movimentos. Cada polichinelo completo será contado e exibido na tela.

📐 Lógica de Detecção
O algoritmo utiliza os pontos de pose do MediaPipe para identificar os movimentos dos braços e pernas. Um polichinelo é contado quando o corpo passa por uma sequência de posições que representam o início e fim do movimento.

🏋️‍♂️ Aplicações
Monitoramento de treinos em casa

Sistemas de gamificação para exercícios

Ferramentas de fisioterapia

Projetos educacionais de IA e visão computacional


