# 🤖 Assistente de IA de Vendas — Ótica

> Projeto desenvolvido como parte do bootcamp da [DIO (Digital Innovation One)](https://www.dio.me), adaptando a metodologia de prompt engineering para o contexto de uma ótica.

---

## 📌 Sobre o Projeto

Este projeto consiste em um **assistente de vendas especializado**, construído com engenharia de prompt, capaz de:

- Identificar o perfil e as necessidades do cliente a partir de uma frase simples
- Classificar o lead (high-ticket, misto ou low-ticket)
- Gerar perguntas qualificadoras para aumentar a chance de fechamento
- Sugerir oferta principal, cross-sell inteligente e estratégia de ancoragem
- Produzir mensagens prontas para WhatsApp ou abordagem presencial

O assistente foi adaptado para o nicho de **ótica**, com produtos, gatilhos e regras de comportamento específicos para esse mercado.

---

## 💡 Motivação

A maioria dos vendedores perde oportunidades não por falta de vontade, mas por não ter um método claro na hora do atendimento. A IA, configurada com o prompt certo, age como um **mentor de vendas sempre disponível** — pensa mais rápido, considera mais variáveis e nunca esquece as regras.

---

## 🧠 Tecnologias e Ferramentas

| Ferramenta | Uso |
|---|---|
| ChatGPT (ou qualquer IA generativa) | Motor do assistente |
| Prompt Engineering | Estrutura e regras de comportamento |
| Metodologia de vendas | Base conceitual (Joe Girard) |

---

## 🗂️ Estrutura do Repositório

```
📁 assistente-ia-vendas-otica/
│
├── README.md               # Este arquivo
├── prompt-otica.md         # Prompt completo pronto para uso
└── exemplos-de-uso.md      # Casos de atendimento simulados
```

---

## 🚀 Como Usar

1. Abra o arquivo [`prompt-otica.md`](./prompt-otica.md)
2. Copie o bloco de prompt completo
3. Abra uma **aba nova** no ChatGPT (ou Gemini, Claude, DeepSeek)
4. Cole o prompt e pressione Enter
5. Envie o interesse do cliente neste formato:

```
Interesse: [descreva o que o cliente disse ou quer ao entrar na loja]
```

**Exemplo real:**

```
Interesse: cliente de 45 anos, passa o dia no escritório na frente do computador, 
reclama de cansaço nos olhos no final do dia. Tem grau, mas não sabe quanto.
```

A IA responderá automaticamente com:

- **A** — Leitura de Interesse
- **B** — Diagnóstico de Oportunidade (perfil do lead)
- **C** — Perguntas Qualificadoras (até 5, estilo WhatsApp)
- **D** — Oferta Principal Recomendada
- **E** — Cross-sell Inteligente
- **F** — Estratégia de Ancoragem

---

## 🔍 Estrutura do Prompt

O prompt é dividido em 6 seções:

| Seção | Conteúdo |
|---|---|
| 1 — Papel e Objetivo | Define quem é a IA e sua missão na ótica |
| 2 — Input | Como enviar o interesse do cliente |
| 3 — Como Responder (A–F) | Formato fixo e ordenado de resposta |
| 4 — Regras de Ouro | Guardrails: o que fazer e o que nunca fazer |
| 5 — Gatilhos de Oportunidade | Perfis comuns de clientes e o que indicam |
| 6 — Primeira Ação Sempre | Comportamento padrão ao receber o primeiro input |

---

## 🎯 Gatilhos de Oportunidade Mapeados

| Situação / fala do cliente | Indicativo |
|---|---|
| "Passo o dia no computador e tenho dor de cabeça" | Lente anti-luz azul |
| "Meu grau é alto e o óculos fica pesado" | Lente de alto índice (fina e leve) |
| "Preciso enxergar perto e longe" | Lentes progressivas |
| "Quero um óculos de sol" | Investigar se tem grau; upsell com grau solar |
| "É para meu filho" | Armação resistente + proteção UV + segundo par |
| "Meu óculos quebrou" | Urgência; abertura para upgrade |
| Motorista / viaja muito | Lente fotossensível (Transitions) |
| "É de presente" | Low-ticket: estojo premium, kit de limpeza |

---

## 📊 Diferenças em Relação ao Projeto Original (Loja Gamer)

| Elemento | Original (gamer) | Este projeto (ótica) |
|---|---|---|
| High-ticket | PC gamer, notebook | Armações premium, lentes progressivas/especiais |
| Low-ticket | Teclado, mouse | Estojos, panos, kits de limpeza |
| Gatilho principal | Jogo travando | Dor de cabeça, cansaço visual, grau alto |
| Cross-sell inteligente | Mouse para o teclado escolhido | Óculos de sol para quem fez grau |
| Argumento emocional | Performance nos jogos | Conforto visual e aparência |
| Urgência | Lançamento de jogo | Óculos quebrado / viagem marcada |

---

## 📚 Referências

- Bootcamp DIO — Projeto original: [Assistente de IA de Vendas (Loja Gamer)](https://www.dio.me)
- Livro: **Como Vender Qualquer Coisa a Qualquer Um** — Joe Girard
- Plataforma: [dio.me](https://www.dio.me/?utm_source=github)

---

## 👤 Autor

Feito por **Sindivaldo** como parte do desafio de portfólio da DIO.  
Conecte-se: [LinkedIn](https://linkedin.com) · [GitHub](https://github.com)

---

> *"As pessoas que ficarão para trás no mercado de trabalho não são as que lutam contra a IA, mas as que não aprenderam a usá-la de forma inteligente."* — Felipão, DIO
