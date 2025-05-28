## Build

## Pré-requisitos

Node.js: versão 16 ou superior

npm: versão 7 ou superior

Python: versão 3.8 ou superior

MongoDB: instância local ou URI do MongoDB Atlas


## Configuração do Ambiente

Clonar o repositório:

git clone https://github.com/araujoithalo/unihub.git
cd unihub

Configurar o Backend:

cd backend
npm install

Configurar o Frontend:

cd ../frontend
npm install

Configurar o Chatbot:

cd ../chatbot
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
pip install -r requirements.txt


## Executando o Projeto

Iniciar o Backend:

cd backend
node server.js

Iniciar o Frontend:

cd ../frontend
npm start

Iniciar o Chatbot:

cd ../chatbot
python app.py
