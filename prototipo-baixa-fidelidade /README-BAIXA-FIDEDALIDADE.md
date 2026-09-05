# Protótipo de Baixa Fidelidade — GoSilo

Esta pasta contém os **protótipos de baixa fidelidade** desenvolvidos para explorar a estrutura, organização das informações e os principais fluxos de navegação do GoSilo.

A baixa fidelidade foi utilizada como uma etapa inicial de UX/UI, permitindo validar a lógica da solução antes da definição detalhada da identidade visual e dos componentes da interface.

---

## Objetivo

O objetivo desta etapa foi representar de forma simples e objetiva:

* A estrutura das principais telas;
* A hierarquia das informações;
* A navegação entre telas;
* As principais ações de cada usuário;
* O fluxo necessário para realizar as tarefas principais do sistema.

Nesta etapa, o foco está na **usabilidade e organização da informação**, e não na aparência final da aplicação.

---

## Perfis

Foram desenvolvidos dois fluxos principais:

### Dono do Silo

Representa o usuário que possui espaço de armazenamento disponível.

Principais etapas:

```text
Login
  ↓
Dashboard
  ↓
Criar anúncio
  ↓
Cadastrar informações do silo
  ↓
Publicar anúncio
  ↓
Receber propostas
  ↓
Acompanhar leilão
  ↓
Selecionar proposta
  ↓
Reserva
```

### Produtor Rural

Representa o usuário que procura espaço para armazenar sua produção.

Principais etapas:

```text
Login
  ↓
Mapa
  ↓
Buscar silo
  ↓
Visualizar anúncio
  ↓
Realizar proposta/lance
  ↓
Acompanhar leilão
  ↓
Resultado
  ↓
Reserva
```

---

## Organização

Os protótipos estão separados de acordo com o perfil de usuário:

* [`dono-silo/`](dono-silo) — telas relacionadas ao proprietário do silo.
* [`produtor-rural/`](produtor-rural) — telas relacionadas ao produtor que procura espaço.

---

## Figma

Os protótipos foram desenvolvidos no **Figma**.

**Protótipo de Baixa Fidelidade:** [Inserir link do Figma]

> O link acima direciona para o arquivo utilizado durante a criação e validação dos protótipos.

---

## O que foi validado

Durante esta etapa foram analisados principalmente:

* Clareza da navegação;
* Organização das informações;
* Sequência das telas;
* Facilidade para encontrar as principais funcionalidades;
* Separação das jornadas dos dois perfis;
* Fluxo de criação e gerenciamento de anúncios;
* Fluxo de busca e contratação de espaços.

---

## Evolução

O protótipo de baixa fidelidade serviu como base para o desenvolvimento das etapas seguintes:

```text
Baixa Fidelidade
       ↓
Validação
       ↓
Média Fidelidade
       ↓
Refinamento
       ↓
Alta Fidelidade
```

As decisões tomadas nesta etapa foram utilizadas para orientar a evolução da interface e reduzir problemas de usabilidade antes da implementação.

---

## Relação com o Projeto

O protótipo de baixa fidelidade é parte do processo de UX/UI do GoSilo e está relacionado aos requisitos, pesquisas e fluxos definidos no repositório de planejamento.

* **Planejamento:** pesquisa, requisitos e modelagem.
* **Baixa fidelidade:** estrutura e navegação.
* **Média fidelidade:** refinamento dos componentes.
* **Alta fidelidade:** interface visual e interação.
* **Desenvolvimento:** implementação da solução.

---

> **"Menos burocracia, mais receita."**
