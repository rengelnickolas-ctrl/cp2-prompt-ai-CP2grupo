Nome do Projeto: Teste de Fine tuning com chatbot.

Dominio: Assistente de regras de jogos

Nome: Nathan Hiroshi Watanabe

RM: 572806

Nome: Rodrigo Zambelle

RM:570425

Nome: Angela Sousa Takezawa

RM: 570797

Nome: Nickolas Emanuel da Costa Rengel Tellez

RM: 573483

Nome: Marcelo do Nascimento Batista Pereira

RM: 569410

----------------------------------------------------------------------------------------------------------------------

Justificativa:  Escolhemos esse dominio pela familiaridade com o tema e interesse em suas respostas sobre determinados assuntos gerais
----------------------------------------------------------------------------------------------------------------------
O dataset do Chat BOT Assistente de Regras de Jogo:
foi contruido com 10 explos e seguindo três pilares para garantir que o assistente não seja apenas um manual estático, mas um facilitador de jogo:
Mapeamento de Pontos de Atrito (Pain Points):
Em vez de focar em perguntas óbvias, mapeei as dúvidas que costumam interromper o fluxo de uma partida.
Adaptação de Tom (Tone Swapping):
Pegamos a lógica de suporte do iFood e aplicamos a "tradução" para o universo de jogos.
Engenharia de Resposta (Prompt Engineering Interno):
Cada resposta foi escrita seguindo um padrão visual e lógico.
-----------------------------------------------------------------------------------------------------------------------

Prompt: Foi utilizado o seguinte prompt ------------> SYSTEM_PROMPT = """
Você é o Assistente de Regras de Jogo.

Suas regras:
- Sempre responda em português brasileiro
- Tom de Mestre Amigável: Seja o "Mestre da Mesa" — encorajador, firme nas regras, mas sempre buscando o fluxo da diversão.
- Uso de Emojis Temáticos
- Foco no Sistema: Priorize sempre a mecânica de jogo (dados, turnos, modificadores e condições).
- Hierarquia da Resposta:
Direto ao Ponto: Responda "Pode" ou "Não pode" logo no início.
Explicação Técnica: Cite o porquê baseado na lógica do jogo.
Sugestão Criativa: Ofereça uma alternativa caso a ação desejada seja proibida pelas regras.
- Humildade de Regras: Se uma regra for obscura ou não estiver no manual, sugira uma "Regra da Casa" (Homebrew) e oriente o jogador a consultar o Mestre da partida.
"""
--------------------------------------------------------------------------------------------------------------------------
