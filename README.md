# Projeto de Reconhecimento de Imagens com Webcam


## 🏷️ Webcam Object Recognition
Classificação de objetos em tempo real usando webcam e machine learning

## 📝 Descrição
Projeto que utiliza a webcam do usuário para capturar imagens e classificar objetos, pessoas ou animais em tempo real usando um modelo de deep learning (MobileNetV2). Ideal para iniciantes em visão computacional e aplicações web com machine learning.

✨ Funcionalidades Principais
Captura de imagens direto da webcam do navegador

Classificação em tempo real usando modelo pré-treinado

Exibição das probabilidades de classificação

Modos de operação: captura única ou contínua

Interface simples e intuitiva

## 🛠️ Tecnologias Utilizadas
Frontend: HTML5, JavaScript (Webcam API)

Backend: Python, Flask

ML Framework: TensorFlow/Keras

Modelo: MobileNetV2 (pré-treinado no ImageNet)

## 📦 Como Executar o Projeto
Pré-requisitos
Python 3.8+

Navegador moderno (Chrome, Firefox, Edge)

Webcam funcionando

Instalação
bash
```
# Clone o repositório
git clone https://github.com/seu-usuario/webcam-object-recognition.git
cd webcam-object-recognition
```
# Crie um ambiente virtual (recomendado)
```
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```
# Instale as dependências
```
pip install -r requirements.txt
```
Execução
```
bash
python app.py
Acesse no navegador: http://localhost:5000
```
## 🎯 Demonstração
GIF demonstrativo (Incluir GIF mostrando a funcionalidade)

## 🚀 Roadmap
Adicionar detecção de múltiplos objetos

Implementar bounding boxes

Adicionar suporte para modelos customizados

Criar versão PWA (Progressive Web App)

## 🤝 Como Contribuir
Faça um fork do projeto

Crie uma branch (git checkout -b feature/nova-feature)

Commit suas mudanças (git commit -m 'Adiciona nova feature')

Push para a branch (git push origin feature/nova-feature)

Abra um Pull Request

📄 Licença
Distribuído sob licença MIT. Veja LICENSE para mais informações.

📧 Contato
Edison Alves - eddy.terabyte@gmail.com

Link do Projeto: https://github.com/eddygordonn/reconhecimento-de-imagens

Estrutura Recomendada de Arquivos
```
/reconhecimento-de-imagens
│
├── static/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
└── assets/
    ├── demo.gif
    └── screenshot.png
```
