# 🚀 Portfólio de Projetos Fullstack

Seja bem-vindo ao meu repositório central. Aqui você encontra uma coleção de soluções digitais de alta complexidade, variando de **SaaS (Software as a Service)** a **Games Multiplayer** e **Plataformas de IA**.

>  Todos os projetos listados abaixo foram **arquitetados e desenvolvidos integralmente por mim** (Frontend, Backend, Banco de Dados e Integrações de IA). Todas as aplicações encontram-se **hospedadas e operacionais**, prontas para uso em ambiente de produção.

---

## 🧠 SimulaENEM
> **Plataforma Adaptativa de Ensino com Inteligência Artificial Generativa**

<img width="1273" height="611" alt="Captura de tela 2025-11-26 130230" src="https://github.com/user-attachments/assets/e70e3ac7-c64a-48de-aee7-8445c142632a" />

Este projeto representa um ecossistema educacional completo. O objetivo foi criar uma ferramenta que superasse os bancos de questões tradicionais, oferecendo um "tutor digital" personalizado para cada estudante.
* **Engenharia de Prompt & IA:** Utiliza modelos de linguagem avançados (LLMs) para gerar questões inéditas em tempo real e corrigir redações com critérios oficiais do ENEM, fornecendo feedback gramatical e estrutural instantâneo.
* **Algoritmo de Recomendação:** O sistema monitora as taxas de erro do usuário por matéria e sugere automaticamente videoaulas de reforço, criando uma trilha de aprendizado adaptativa.
* **Big Data Educacional:** Possui um banco de dados estruturado com o histórico integral de todas as provas do ENEM de 2009 a 2023, permitindo simulados fiéis à realidade.

---

## 🕵️ Impostor
> **Jogo Social Multiplayer com Sincronização em Tempo Real**

<img width="686" height="420" alt="Captura de tela 2025-11-26 130100" src="https://github.com/user-attachments/assets/e3f6faec-34ee-4de0-b9d8-7fe55999473a" />

Um desafio técnico focado em *networking* e baixa latência. "Impostor" é um jogo de dedução social onde a integridade do estado do jogo entre todos os clientes é crucial.
* **Arquitetura Real-Time:** Utilização de bancos de dados em tempo real/sockets para garantir que quando um jogador realiza uma ação (votação, chat, movimento), todos os outros na sala recebam a atualização em milissegundos.
* **Gerenciamento de Salas (Lobby System):** Lógica complexa de criação de salas privadas, geração de códigos únicos de acesso e distribuição aleatória de funções (Inocente vs. Impostor) baseada no número de participantes conectados.

---

## 📅 LuLash System
> **SaaS (ERP/CRM) para Gestão de Negócios de Beleza**

<img width="688" height="405" alt="Captura de tela 2025-11-26 130034" src="https://github.com/user-attachments/assets/5bd448aa-d4e8-4d8c-ac06-0c630af44022" />

Solução comercial desenvolvida para resolver dores reais de agendamento e gestão financeira de profissionais autônomos. O foco aqui foi UX (Experiência do Usuário) e consistência de dados.
* **Painel de Controle Intuitivo:** Dashboard dinâmico que renderiza a agenda do dia/semana, permitindo visualização rápida de "buracos" na agenda e otimização do tempo.
* **CRUD & Relacionamento de Dados:** Sistema robusto de cadastro de clientes vinculado ao histórico de atendimentos, permitindo que o profissional tenha um CRM completo para fidelização.
* **Regras de Negócio:** Validações automáticas para impedir conflitos de horário (double-booking) e gestão de status de atendimento (agendado, realizado, cancelado).

---

## 🗣️ Mentor IA
> **Assistente de Saúde Mental com Processamento de Linguagem Natural (NLP)**

<img width="653" height="593" alt="Captura de tela 2025-11-26 130205" src="https://github.com/user-attachments/assets/1382d526-ce03-40a6-ac64-1182d781dbac" />

Uma aplicação sensível que une tecnologia e humanização. O Mentor IA foi treinado para oferecer suporte emocional inicial, simulando uma conversa empática e segura.
* **Multimodalidade & Acessibilidade:** O sistema não se limita a texto. Implementei APIs de *Speech-to-Text* (fala para texto) e *Text-to-Speech* (texto para voz), permitindo que o usuário converse com a IA como se estivesse em uma chamada, tornando a experiência mais orgânica.
* **Contexto Persistente:** A IA mantém o contexto da conversa, lembrando-se do que o usuário disse anteriormente para fornecer respostas coerentes e acolhedoras.

---

## 🍻 Faz ou Bebe - A Vingança
> **Gamificação Dinâmica Gerada por IA**

<img width="920" height="550" alt="Captura de tela 2025-11-26 130236" src="https://github.com/user-attachments/assets/6409b423-fcac-46ba-bae3-22621b5327a2" />

Uma modernização técnica do clássico "Verdade ou Desafio". Diferente de apps comuns que usam um banco de dados estático de frases, este projeto usa IA para gerar entretenimento infinito.
* **Geração Procedural de Conteúdo:** A cada rodada, a IA cria um desafio novo baseado em parâmetros de "intensidade" e contexto, garantindo que o jogo nunca se torne repetitivo.
* **Lógica de Jogo:** Algoritmos que asseguram a distribuição justa de turnos e punições, gerenciando a pontuação e a progressão da partida de forma automatizada.

---

## 🏫 Instituto Educacional Copacabana
> **Portal Institucional com CMS Próprio**

<img width="1296" height="609" alt="Captura de tela 2025-11-26 130224" src="https://github.com/user-attachments/assets/d710c5e3-4075-43fe-b7b0-931272c68bce" />

Plataforma web desenvolvida para centralizar a comunicação digital de uma instituição de ensino, servindo como ponto de contato entre administração, pais e alunos.
* **Gestão de Conteúdo (CMS):** Desenvolvi uma área administrativa segura onde a coordenação da escola pode postar notícias, editais e atualizações curriculares em tempo real, sem necessidade de tocar no código.
* **Arquitetura de Informação:** Design focado na facilidade de navegação e acesso rápido a informações institucionais críticas.

---

## 📊 Ferramentas de Análise de Dados e Finanças

Além das aplicações visuais acima, desenvolvi ferramentas focadas em **Data Science** e **Matemática Financeira**:

### 💸 Dashboard AI (Inteligência Financeira)
Uma aplicação de *Business Intelligence* pessoal.
* **Feature Principal:** Utiliza IA para analisar extratos, categorizar gastos automaticamente (ex: alimentação, transporte) e gerar gráficos visuais de tendências de consumo. O objetivo é identificar gargalos no orçamento através de análise de dados.

### 📈 Simulador de Investimentos Pro
Uma ferramenta de projeção financeira de alta precisão.
* **Cálculo & Consultoria:** Realiza cálculos complexos de juros compostos e aportes mensais para longo prazo. O diferencial é a integração de um **Consultor via IA**, que explica os resultados matemáticos e tira dúvidas sobre termos do mercado financeiro em linguagem natural.

---
