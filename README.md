# NutriVisionAI App

NutriVisionAI é um aplicativo inovador que utiliza inteligência artificial para identificar e descrever pratos a partir de imagens, fornecendo informações nutricionais detalhadas. Ele também permite que os usuários façam perguntas sobre os alimentos identificados, oferecendo respostas claras e precisas.

---

## ✨ Funcionalidades

1. **Identificação de Pratos:**
   - A partir de uma imagem de um prato, o app utiliza um modelo de IA para descrever os alimentos presentes.

2. **Informações Nutricionais:**
   - Com base na descrição gerada, o app oferece dados nutricionais aproximados, incluindo calorias, macronutrientes e outras informações importantes.

3. **Interação com o Usuário:**
   - Os usuários podem fazer perguntas relacionadas aos alimentos detectados, como:
     - *"Quantas calorias tem esse prato?"*
     - *"Esse prato é saudável para uma dieta low-carb?"*

---

## 🛠️ Tecnologias Utilizadas

### 1. **Modelos de IA**
   - **BLIP-Image-Captioning-Large**:
     - Utilizado para a tarefa de *image-to-text*, gerando descrições precisas do prato a partir da imagem fornecida.
   - **LLama3.2-Vision**:
     - Um modelo avançado de LLM (Large Language Model) que cria o texto explicativo e responde às perguntas do usuário sobre os alimentos detectados.

### 2. **Arquitetura**
   - Integração entre modelos para processar imagens, gerar descrições e fornecer respostas em linguagem natural.
   - Utiliza APIs de consulta de dados nutricionais para garantir precisão nas informações.

---

## 🖼️ Como Funciona

1. **Upload de Imagem:**
   - O usuário faz o upload de uma foto do prato.

2. **Processamento da Imagem:**
   - O modelo BLIP analisa a imagem e gera uma descrição textual do prato.

3. **Consulta de Dados Nutricionais:**
   - Baseado na descrição, o sistema consulta informações nutricionais relevantes.

4. **Interação com o Usuário:**
   - O modelo LLama3.2-Vision responde perguntas sobre os dados nutricionais ou fornece informações adicionais sobre o prato.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Python 3.8 ou superior
- Bibliotecas necessárias (instale com o comando abaixo):
  ```bash
  pip install -r requirements.txt
  ```
### Executando o App
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/nutrivision.git
```
2. Navegue até a pasta do projeto:
```bash
cd nutrivisionai
```
3. Inicie o aplicativo:
```bash
python app.py
```

## 📚 Referências
- BLIP-Image-Captioning-Large: [Hugging Face](https://huggingface.co/Salesforce/blip-image-captioning-large)
- LLama3.2-Vision: [Modelo LLama Vision](https://github.com/meta-llama/llama-models)

## 📧 Contato
- Criador: Lucas Lopes
- Email: lucasfalopes66@gmail.com
- LinkedIn: Lucas Lopes

## 🌟 Agradecimentos
Obrigado por conferir o NutriVision! Estamos ansiosos para ajudar você a entender melhor seus pratos e fazer escolhas mais saudáveis. 🍎
