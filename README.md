# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Chatgpt** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## 📝 PRD refinado pelo Chatgpt

```txt
(Provisório): Agente Financeiro Conversacional
================================================

🌍 VISÃO DO PRODUTO
------------------------------------------------
Aplicativo de organização financeira pessoal baseado em conversação em linguagem natural, permitindo que qualquer pessoa organize sua vida financeira sem formulários, planilhas ou conhecimento técnico.

O app atua como um assistente financeiro pessoal, com simplicidade, empatia e inteligência contextual.

❗ PROBLEMA
------------------------------------------------
Apps financeiros tradicionais:

- Exigem alto esforço cognitivo
- Entrada manual estruturada
- Conhecimento prévio de finanças
- Interfaces complexas
- Baixa retenção e alto abandono

👥 PÚBLICO-ALVO
------------------------------------------------
- Jovens adultos
- Pessoas endividadas
- Usuários com baixa alfabetização digital
- Pessoas que nunca usaram apps financeiros
- Usuários sobrecarregados por apps complexos

🎯 OBJETIVOS DO PRODUTO
------------------------------------------------
- Reduzir fricção de uso
- Simplificar controle financeiro
- Criar hábito de organização
- Aumentar constância de uso
- Criar vínculo emocional
- Tornar finanças algo leve e cotidiano

💎 PROPOSTA DE VALOR
------------------------------------------------
“Organize seu dinheiro conversando.
Sem planilhas. Sem formulários. Sem complicação.”

🎨 PRINCÍPIOS DE DESIGN UNIVERSAL
------------------------------------------------

1) Simplicidade Cognitiva
- Linguagem clara
- Frases curtas
- Vocabulário não técnico
- Sem jargões
- Comunicação educativa

2) Acessibilidade Visual
- Alto contraste
- Tipografia legível
- Hierarquia clara
- Interface limpa
- Pouca informação por tela

3) Acessibilidade de Interação
- Poucos cliques
- Fluxos curtos
- Navegação previsível
- Botões grandes
- Feedback imediato
- Ações reversíveis

4) Inclusão Funcional
- Uso sem conhecimento prévio
- Sem leitura longa
- Sem dependência de memória
- Sem aprendizagem técnica
- Intuitivo desde o primeiro acesso

🚀 FUNCIONALIDADES DO MVP
------------------------------------------------

💬 Conversa Financeira
- Registro de gastos por linguagem natural
- Registro de ganhos por linguagem natural
- Detecção automática de transações
- Classificação automática por categoria
- Confirmação simples
- Correção manual simplificada

🎯 Metas Financeiras
- Criação por conversa
- Metas mensais automáticas
- Acompanhamento visual simples
- Alertas proativos
- Replanejamento automático

📊 Relatórios
- Resumo mensal
- Categorias principais
- Tendências simples
- Comparação mensal
- Insights automatizados

🤖 Agente Financeiro
- Personagem digital
- Tom empático
- Linguagem educativa
- Comunicação humana
- Dicas contextualizadas
- Alertas inteligentes
- Feedback positivo

🧱 TELAS DO MVP
------------------------------------------------
- Onboarding conversacional
- Chat principal
- Dashboard financeiro
- Metas
- Relatórios
- Perfil financeiro
- Configurações acessíveis

🎨 REQUISITOS DE UX/UI
------------------------------------------------
- Interface minimalista
- Chat como núcleo
- Navegação híbrida (chat + abas)
- Sem menus profundos
- Feedback visual constante
- Microinterações leves
- Animações suaves
- Sem overload de informação

⚙️ REQUISITOS FUNCIONAIS
------------------------------------------------
- NLP (Processamento de linguagem natural)
- Classificação automática
- Sistema de metas
- Histórico
- Relatórios
- Perfil do usuário
- Insights
- Persistência local
- Sincronização em nuvem (futuro)

🛡️ REQUISITOS NÃO FUNCIONAIS
------------------------------------------------
- Baixo consumo cognitivo
- Baixo consumo de bateria
- Alta performance
- Baixa latência
- Interface responsiva
- Suporte offline básico
- Segurança de dados
- Privacidade por padrão

✅ CRITÉRIOS DE SUCESSO (MVP)
------------------------------------------------
- Registrar gasto em < 10s
- Uso sem tutorial
- Criar ao menos 1 meta
- Retorno no dia seguinte
- Compreensão dos gastos
- Confiança nas classificações

🧪 VALIDAÇÃO INICIAL
------------------------------------------------
- Testes com usuários reais
- Teste de onboarding
- Teste de entendimento
- Teste de retenção (7 dias)
- Teste de confiança
- Teste de clareza de linguagem

🗣️ DIRETRIZES DE LINGUAGEM
------------------------------------------------
- Tom humano
- Tom empático
- Sem termos técnicos
- Sem julgamento
- Sem culpa
- Sem pressão
- Comunicação positiva
- Comunicação educativa

📈 ESCALABILIDADE FUTURA
------------------------------------------------
- Integração bancária
- Open Finance
- Cartões
- Investimentos
- Crédito
- Planejamento financeiro
- Educação financeira
- Marketplace financeiro
- Parcerias com fintechs

```

---

## 💬 Interações com o Lovable

> eu quero criar app de finanças pessoais baseado no seguinte PRD (Product Requirements Document), mas não adiciona a parte de interação com o chat, eu quero um processo mais manual mesmo, onde eu mesmo personalizo o meus gastos e ganhos: {PRD}

---

## 🎯 Resultado Final

Acesse o protótipo funcional no Lovable:  
**[my-finance-craft.lovable.app](https://my-finance-craft.lovable.app/)**

<img width="1920" height="945" alt="image" src="https://github.com/CauiDavis/dio-lab-vibe-coding-app-financas/blob/main/Lovable%20App.png" />

---

# 📱 FinControl — Funcionalidades do App

## 🧭 Navegação
- Dashboard principal
- Tela de transações
- Navegação superior simples:
  - Dashboard
  - Transações

---

## ➕ Gestão de Transações
- Botão **+ Nova transação**
  - Cadastro de receitas
  - Cadastro de despesas

---

## 💰 Visão Financeira Geral (Dashboard)

### 📊 Cards principais
- **Saldo**
  - Exibe o saldo total atual
- **Receitas**
  - Total de entradas financeiras
- **Despesas**
  - Total de saídas financeiras

---

## 📁 Organização Financeira

### 🧾 Despesas por categoria
- Visualização de gastos categorizados
- Estrutura para gráficos por categoria
- Estado vazio:
  - “Nenhuma despesa este mês”

---

## 🔁 Histórico de Movimentações

### 📄 Transações recentes
- Lista das últimas transações
- Link **Ver todas**
  - Acesso à listagem completa
- Estado vazio:
  - “Nenhuma transação encontrada”

---

## 📅 Filtro Temporal
- Visualização por período (mês/ano)
  - Exemplo: Fevereiro de 2026

---

## ⚙️ Funcionalidades Estruturais
- Sistema de categorias
- Sistema de receitas e despesas
- Sistema de saldo automático
- Histórico financeiro
- CRUD de transações
- Organização mensal
- Dashboard analítico
- Estrutura de relatórios
- Separação lógica de dados (receita vs despesa)

---

## 🧠 Arquitetura Funcional
- Persistência de dados
- Sistema de transações
- Sistema de categorias
- Sistema de agregação de valores
- Filtros por data
- Estado global financeiro
- Camada analítica
- Camada de visualização

---

## 📌 Resumo
- Controle financeiro pessoal
- Registro de receitas e despesas
- Organização por categorias
- Histórico mensal
- Dashboard financeiro
- Estrutura escalável
- Base para automação
- Base para IA financeira
- Base para relatórios inteligentes


## 🧠 Reflexão

### O que funcionou bem?  
O refinamento do PRD previamente feito no Chatgpt ajudou muito, ele deu mais dados que o copilot da aula, eu usei poucos créditos no Lovable acabaram em apenas 1 interação (não adicionei o chat para não correr risco de ficar sem créditos para conserta-lo).

### O que não funcionou como o esperado?  
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding, além disso, eu usei o v0 e fiquei sem crédito por conta da conta free, seria bom se tivesse mais interações.

### O que aprendi sobre conversar com IAs?  
Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você dá, melhor é a interação, porém tem algumas IAs que tem as suas limitações como a v0 que não funcionou de jeito nenhum o chat para interação, não sei se é por que eu preciso fazer alguma integração antes.
