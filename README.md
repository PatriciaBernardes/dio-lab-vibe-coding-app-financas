# 💸 FinPilot · App de Finanças Pessoais com IA

> Desafio do bootcamp **Criando produtos com IA** · Riachuelo + DIO
> Tema: Primeiro projeto, app de organização de finanças pessoais com
> vibe coding (Lovable + IA generativa)

<div align="center">

**Seu copiloto financeiro pessoal com IA: controle de gastos, metas
financeiras e orientação inteligente em um só lugar.**

</div>

---

## ✨ Resumo do conceito

O **FinPilot** nasceu de uma necessidade simples: a maioria das pessoas
não organiza as finanças porque o processo exige planilha, disciplina
e vocabulário de banco. O app resolve isso unindo três frentes em uma
experiência única:

- **Controle de gastos** com categorização automática por IA: o usuário
  digita "iFood ontem 45" e o app classifica, registra e organiza.
- **Metas financeiras** com simulações: o app mostra quanto depositar
  por mês para atingir o objetivo e sugere metas a partir dos hábitos
  reais do usuário.
- **Assistente de IA (FinBot)**: um chat que responde perguntas sobre
  os dados reais do usuário, em linguagem simples, e entrega dicas
  semanais personalizadas com impacto calculado ("cortar 2 deliveries
  por semana economiza ~R$ 360/mês").

O objetivo é traduzir a vida financeira do usuário em orientações
claras e acionáveis, para qualquer perfil: do estudante ao autônomo.

---

## 🎯 O prompt final (PRD) usado com a IA

Este é o prompt completo (Product Requirements Document) utilizado na
ferramenta de vibe coding para gerar o produto. Foi construído para ser
autossuficiente: descreve visão, público, funcionalidades, fluxo,
interface e arquitetura de dados.
```markdown
<!-- COLE AQUI O SEU PRD FINAL, EXATAMENTE COMO USADO NO LOVABLE -->

# PRD: FinPilot, App de Finanças Pessoais com IA

## 1. Visão do produto
App mobile-first e web responsivo de finanças pessoais que combina
controle de gastos, metas financeiras e um assistente de IA em uma
única experiência. O diferencial é a linguagem simples: o app traduz
a vida financeira do usuário em orientações claras e acionáveis,
sem jargão bancário.

## 2. Público-alvo
Qualquer pessoa que queira organizar as próprias finanças, sem
conhecimento prévio de planilhas ou mercado financeiro. Inclui
estudantes, famílias e profissionais autônomos.

## 3. Funcionalidades principais

### 3.1 Controle de gastos
- Registro manual de transações com valor, descrição, data e categoria.
- Categorias padrão: Alimentação, Transporte, Moradia, Lazer, Saúde,
  Educação, Assinaturas, Compras, Renda, Investimentos, Outros.
- Categorização automática por IA: ao digitar "iFood ontem 45 reais",
  o app identifica descrição, valor, data e categoria sugerida.
- Edição e exclusão de transações.

### 3.2 Dashboard financeiro
- Saldo do mês atual (receitas menos despesas).
- Gastos por categoria em gráfico de rosca.
- Evolução dos gastos nos últimos 6 meses em gráfico de linhas.

### 3.3 Metas financeiras
- Criação de metas: nome, valor alvo, prazo e categoria.
- Barra de progresso com percentual e valor faltante.
- Simulação de aporte mensal: "depositando R$ 300/mês, você atinge
  a meta em X meses".

### 3.4 Assistente de IA (FinBot)
- Chat que responde sobre as finanças do usuário.
- Dicas semanais personalizadas com base nos dados reais.

### 3.5 Configurações
- Moeda (R$), limite de orçamento mensal, exportação CSV, tema claro/escuro.

## 4. Fluxo principal
Onboarding com perfil e objetivo → sugestão da primeira meta →
registro de transações (manual ou com IA) → acompanhamento no
dashboard e metas → conversa com o FinBot.

## 5. Requisitos técnicos
- Banco de dados: usuarios, transacoes, metas, categorias.
- Autenticação simples por e-mail.
- Arquitetura pronta para receber API de IA de categorização e chat.
