# Chatbot Inteligente com LangChain

Um chatbot versátil que utiliza a API do Groq e LangChain para interagir com diferentes tipos de conteúdo, incluindo sites, PDFs e vídeos do YouTube.

## 🚀 Funcionalidades

- Conversação com conteúdo de sites
- Interação com documentos PDF
- Análise de vídeos do YouTube
- Respostas inteligentes e personalizadas
- Interface de linha de comando amigável

## 📋 Pré-requisitos

- Python 3.12.9 ou superior
- Conta na Groq para obter a API key
- Bibliotecas Python necessárias (listadas em requirements.txt)

## 🔧 Instalação

1. Clone este repositório:
```bash
git clone [URL_DO_REPOSITÓRIO]
cd [NOME_DO_DIRETÓRIO]
```

2. Crie um ambiente virtual:
```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Configure sua API key do Groq:
```python
api_key = 'SUA_API_KEY_AQUI'
os.environ['GROQ_API_KEY'] = api_key
```

## 💻 Como Usar

1. Execute o notebook `Chatbot-Final.ipynb`
2. Escolha uma das opções:
   - (1) Conversar com Site
   - (2) Conversar com PDF
   - (3) Conversar com Vídeo do YouTube
3. Digite o link do conteúdo desejado
4. Comece a conversar com o bot
5. Digite 'x' para encerrar a conversa

## 🤖 Sobre o Bot

O bot, chamado James, é um assistente virtual com:
- Personalidade humorística e criativa
- Capacidade de processar diferentes tipos de conteúdo
- Respostas contextualizadas baseadas no material fornecido

## 📚 Tecnologias Utilizadas

- LangChain
- Groq API
- Python
- Jupyter Notebook

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.
