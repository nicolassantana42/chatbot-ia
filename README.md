# Chatbot-IA-OpenAI

## Nome do Projeto
Chatbot-IA-OpenAI: Miniaplicação colaborativa que consome a OpenAI API para criar um chatbot simples de respostas inteligentes.

## Integrantes
- Integrante 1: Seu Nome
- Integrante 2: Nome2
- Integrante 3: Nome3
- Integrante 4: Nome4
- Integrante 5: Nome5
- Integrante 6: Nome6
- Integrante 7: Nome7

## API de IA Utilizada
OpenAI API (modelo gpt-3.5-turbo) para geração de texto e respostas inteligentes.

## Explicação de Como Rodar/Testar o Projeto
1. Clone o repositório: `git clone https://github.com/seu-usuario/chatbot-ia-openai.git`
2. Instale dependências: `pip install -r requirements.txt`
3. Copie config/.env.example para config/.env e adicione sua chave: `OPENAI_API_KEY=sua-chave-aqui` (obtenha em https://platform.openai.com/api-keys)
4. Rode a aplicação: `python main.py`
5. No console, digite mensagens (ex: "Olá, qual é o sentido da vida?"). O chatbot responde usando a OpenAI. Digite "sair" para encerrar.
6. Interações são logadas em chatbot.db (use `sqlite3 chatbot.db "SELECT * FROM interactions;"` para visualizar logs).

Teste exemplo: Envie um prompt e veja a resposta exibida. Verifique os logs no banco de dados.

## Contribuições
Cada integrante trabalhou em branch própria (ex: nome-aluno) e integrou via Pull Request. Veja histórico no GitHub.