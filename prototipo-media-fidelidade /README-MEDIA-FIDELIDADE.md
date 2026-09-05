# GoSilo — Protótipo de Média Fidelidade

## Sobre o projeto

O **GoSilo** é uma aplicação mobile desenvolvida para conectar **produtores rurais que necessitam de espaço para armazenagem** a **proprietários de silos que possuem capacidade disponível**.

A solução utiliza um modelo de marketplace, permitindo que proprietários disponibilizem seus silos e que produtores rurais encontrem oportunidades de armazenagem por meio de anúncios e leilões.

Este diretório contém os artefatos referentes ao **protótipo de média fidelidade** do GoSilo, desenvolvido durante o Projeto Integrador.

---

## Objetivo

O protótipo de média fidelidade tem como objetivo representar a estrutura das principais telas e fluxos de navegação do sistema, permitindo validar a organização das informações e a experiência dos usuários antes da implementação da aplicação.

Nesta etapa foram desenvolvidas telas para os dois principais perfis do sistema:

* **Dono do Silo**
* **Produtor Rural**

O protótipo contempla funcionalidades relacionadas a cadastro, autenticação, perfil, configurações, anúncios, silos cadastrados, leilões e comunicação entre usuários.

---

## Média fidelidade

A média fidelidade representa uma evolução dos wireframes iniciais de baixa fidelidade.

Nesta etapa, além da estrutura das telas, foram definidos elementos mais próximos da interface que será utilizada posteriormente, incluindo:

* Organização dos componentes;
* Hierarquia das informações;
* Botões e ações;
* Campos de entrada;
* Menus e configurações;
* Fluxos de navegação;
* Informações específicas de cada perfil;
* Estrutura das telas de leilão e comunicação.

O protótipo ainda não representa necessariamente o design visual definitivo da aplicação.

---

# Fluxos do protótipo

O protótipo está dividido em dois fluxos principais:

```text
                         GoSilo
                           │
              ┌────────────┴────────────┐
              │                         │
        Dono do Silo              Produtor Rural
              │                         │
       ┌──────┴──────┐           ┌──────┴──────┐
       │             │           │             │
  Gerenciamento   Leilões     Busca/Leilão   Histórico
   do Silo                     e interação
```

---

# Fluxo — Dono do Silo

O fluxo do proprietário foi desenvolvido considerando as ações necessárias para cadastrar e gerenciar seus silos, disponibilizar espaços para armazenagem e acompanhar os leilões realizados na plataforma.

### Fluxo principal

```text
Cadastro do Usuário
        ↓
Login
        ↓
Home Page
        ↓
 ┌──────┼───────────────┬──────────────┐
 ↓      ↓               ↓              ↓
Perfil  Silos         Leilões       Configurações
        Cadastrados
          ↓               ↓
     Criação/Edição   Leilões nos
       do Anúncio      Arredores
                          ↓
                    Leilão Ocorrendo/
                       Encerrado
                          ↓
                 Histórico de Conversas
```

## Telas do Dono do Silo

### Autenticação

| Tela                                                               | Descrição                                                    |
| ------------------------------------------------------------------ | ------------------------------------------------------------ |
| [Cadastro Usuário.png](./Cadastro%20Usuário.png)                   | Tela destinada ao cadastro de um novo usuário na plataforma. |
| [Longin do Dono do Silo.png](./Longin%20do%20Dono%20do%20Silo.png) | Tela de autenticação para acesso à conta do proprietário.    |

> **Observação:** o arquivo `Longin` mantém a nomenclatura atualmente utilizada no repositório.

---

### Página inicial

| Tela                                                                       | Descrição                                                    |
| -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| [Home Page do Dono do Silo.png](./Home%20Page%20do%20Dono%20do%20Silo.png) | Página principal do proprietário após o acesso à plataforma. |

A Home Page funciona como ponto central para acesso às principais funcionalidades do perfil.

---

### Perfil

| Tela                                                               | Descrição                                           |
| ------------------------------------------------------------------ | --------------------------------------------------- |
| [Perfil do Dono do Silo.png](./Perfil%20do%20Dono%20do%20Silo.png) | Apresenta as informações do perfil do proprietário. |

---

### Configurações

O fluxo de configurações permite personalizar diferentes aspectos da experiência do usuário.

| Tela                                                                                                                             | Descrição                                                |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [Configurações do Dono do Silo.png](./Configurações%20do%20Dono%20do%20Silo.png)                                                 | Tela principal de configurações.                         |
| [Configuraçõs de Lingua do Dono do Silo.png](./Configuraçõs%20de%20Lingua%20do%20Dono%20do%20Silo.png)                           | Configuração do idioma utilizado na aplicação.           |
| [Configurações de Tamanho de Letra do Dono do Silo.png](./Configurações%20de%20Tamanho%20de%20Letra%20do%20Dono%20do%20Silo.png) | Permite configurar o tamanho da fonte da interface.      |
| [Configurações de SAC do Dono do Silo.png](./Configurações%20de%20SAC%20do%20Dono%20do%20Silo.png)                               | Acesso às configurações relacionadas ao atendimento/SAC. |

---

### Silos cadastrados

| Tela                                                                                       | Descrição                                                      |
| ------------------------------------------------------------------------------------------ | -------------------------------------------------------------- |
| [Silos Cadastrados do Dono do Silo.png](./Silos%20Cadastrados%20do%20Dono%20do%20Silo.png) | Lista e gerenciamento dos silos cadastrados pelo proprietário. |

A partir dessa área, o proprietário pode consultar seus espaços cadastrados e acessar as opções de gerenciamento.

---

### Criação e edição de anúncio

| Tela                                                                                           | Descrição                                                      |
| ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| [Criação de Anúncio do Dono do Silo.png](./Criação%20de%20Anúncio%20do%20Dono%20do%20Silo.png) | Permite criar um novo anúncio para disponibilizar um silo.     |
| [Edição Silo Cadastrado.png](./Edição%20Silo%20Cadastrado.png)                                 | Permite alterar informações de um silo previamente cadastrado. |

O fluxo permite ao proprietário controlar as informações disponibilizadas aos produtores interessados.

---

### Leilões

| Tela                                                                                                       | Descrição                                                                  |
| ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [Leilões do Dono do Silo.png](./Leilões%20do%20Dono%20do%20Silo.png)                                       | Área de acompanhamento dos leilões relacionados aos silos do proprietário. |
| [Leilões nos Arredores do Dono do Silo.png](./Leilões%20nos%20Arredores%20do%20Dono%20do%20Silo.png)       | Apresenta leilões disponíveis ou realizados na região de interesse.        |
| [Leilão OcorrendoEncerrado do Dono do Silo.png](./Leilão%20OcorrendoEncerrado%20do%20Dono%20do%20Silo.png) | Representa o acompanhamento de um leilão em andamento ou já encerrado.     |

---

### Comunicação

| Tela                                                                                                   | Descrição                                                                 |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------- |
| [Histórico de Conversas do Dono do Silo.png](./Histórico%20de%20Conversas%20do%20Dono%20do%20Silo.png) | Histórico das conversas realizadas pelo proprietário com outros usuários. |

---

# Fluxo — Produtor Rural

O fluxo do produtor rural foi desenvolvido considerando a jornada de um usuário que busca oportunidades de armazenagem, acompanha leilões e mantém comunicação com outros usuários da plataforma.

### Fluxo principal

```text
Cadastro do Usuário
        ↓
Login
        ↓
Home Page
        ↓
 ┌──────┼───────────────┬──────────────┐
 ↓      ↓               ↓              ↓
Perfil  Leilões       Histórico     Configurações
        ↓              de Leilões
     Leilão
        ↓
Acompanhamento/
Participação
        ↓
Histórico de Conversas
```

## Telas do Produtor Rural

### Autenticação

| Tela                                                                        | Descrição                               |
| --------------------------------------------------------------------------- | --------------------------------------- |
| [Cadastro Usuário.png](./produtor-rural/Cadastro%20Usuário.png)             | Tela de cadastro do produtor rural.     |
| [Longin Produtor Rural.png](./produtor-rural/Longin%20Produtor%20Rural.png) | Tela de autenticação do produtor rural. |

---

### Página inicial

| Tela                                                                                | Descrição                                        |
| ----------------------------------------------------------------------------------- | ------------------------------------------------ |
| [Home Page Produtor Rural.png](./produtor-rural/Home%20Page%20Produtor%20Rural.png) | Página principal do produtor rural após o login. |

---

### Perfil

| Tela                                                                                | Descrição                                       |
| ----------------------------------------------------------------------------------- | ----------------------------------------------- |
| [Perfil do Produtor Rural.png](./produtor-rural/Perfil%20do%20Produtor%20Rural.png) | Apresenta as informações do perfil do produtor. |

---

### ⚙️ Configurações

| Tela                                                                                                                                              | Descrição                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [Configurações do Produtor Rural.png](./produtor-rural/Configurações%20do%20Produtor%20Rural.png)                                                 | Tela principal de configurações do produtor.   |
| [Configurações de Lingua do Produtor Rural.png](./produtor-rural/Configurações%20de%20Lingua%20do%20Produtor%20Rural.png)                         | Configuração do idioma da aplicação.           |
| [Configurações do SAC do Produtor Rural.png](./produtor-rural/Configurações%20do%20SAC%20do%20Produtor%20Rural.png)                               | Configurações relacionadas ao atendimento/SAC. |
| [Configurações do Tamanho de Letra do Produtor Rural.png](./produtor-rural/Configurações%20do%20Tamanho%20de%20Letra%20do%20Produtor%20Rural.png) | Configuração do tamanho da fonte.              |

---

### Leilões

| Tela                                                                                                                | Descrição                                                            |
| ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| [Leilão do Produtor Rural.png](./produtor-rural/Leilão%20do%20Produtor%20Rural.png)                                 | Tela de visualização e interação com um leilão.                      |
| [Histórico de Leilões do Produtor Rural.png](./produtor-rural/Histórico%20de%20Leilões%20do%20Produtor%20Rural.png) | Histórico dos leilões dos quais o produtor participou ou acompanhou. |

---

### Comunicação

| Tela                                                                                                                    | Descrição                                         |
| ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| [Histórico de Conversas do Produtor Rural.png](./produtor-rural/Histórico%20de%20Conversas%20do%20Produtor%20Rural.png) | Histórico das conversas realizadas pelo produtor. |

---

# 🔗 Protótipo no Figma

O protótipo de média fidelidade foi desenvolvido no Figma.

**Acesse o protótipo:**
[Protótipos PI — GoSilo](https://www.figma.com/design/vyZXoLuELx9Nwo2OkRgN3D/Prot%C3%B3tipos-PI-GoSilo?node-id=0-1&t=pI5b2SzVXjxvJUuh-1)

O arquivo contém as telas e fluxos utilizados para representar a experiência dos dois perfis de usuário.

---

# Estrutura do diretório

A organização dos arquivos foi definida separando os protótipos de acordo com o perfil de usuário.

```text
prototipo-media-fidelidade/
│
├── README.md
│
├── dono-silo/
│   ├── Cadastro Usuário.png
│   ├── Configurações de SAC do Dono do Silo.png
│   ├── Configurações de Tamanho de Letra do Dono do Silo.png
│   ├── Configurações do Dono do Silo.png
│   ├── Configuraçõs de Lingua do Dono do Silo.png
│   ├── Criação de Anúncio do Dono do Silo.png
│   ├── Edição Silo Cadastrado.png
│   ├── Histórico de Conversas do Dono do Silo.png
│   ├── Home Page do Dono do Silo.png
│   ├── Leilão OcorrendoEncerrado do Dono do Silo.png
│   ├── Leilões do Dono do Silo.png
│   ├── Leilões nos Arredores do Dono do Silo.png
│   ├── Longin do Dono do Silo.png
│   ├── Perfil do Dono do Silo.png
│   ├── Silos Cadastrados do Dono do Silo.png
│   
│
└── produtor-rural/
    ├── Cadastro Usuário.png
    ├── Configurações de Lingua do Produtor Rural.png
    ├── Configurações do Produtor Rural.png
    ├── Configurações do SAC do Produtor Rural.png
    ├── Configurações do Tamanho de Letra do Produtor Rural.png
    ├── Histórico de Conversas do Produtor Rural.png
    ├── Histórico de Leilões do Produtor Rural.png
    ├── Home Page Produtor Rural.png
    ├── Leilão do Produtor Rural.png
    ├── Longin Produtor Rural.png
    ├── Perfil do Produtor Rural.png
    
```

---

# Resumo das telas

| Perfil               | Quantidade de telas |
| -------------------- | ------------------: |
| Dono do Silo      |                  15 |
| Produtor Rural |                  12 |
| **Total**            |              **27** |

> A quantidade considera os arquivos de telas atualmente presentes nos diretórios de cada perfil.

---

# Evolução do projeto

O protótipo de média fidelidade faz parte da evolução da solução de UX/UI do GoSilo.

```text
Pesquisa
   ↓
Levantamento de requisitos
   ↓
Fluxos de usuário
   ↓
Protótipo de baixa fidelidade
   ↓
Protótipo de média fidelidade
   ↓
Validação e feedback
   ↓
Protótipo de alta fidelidade
   ↓
Implementação
```

A utilização de diferentes níveis de fidelidade permite validar progressivamente a estrutura, a navegação e posteriormente os aspectos visuais da aplicação.

---

# Validação

O protótipo poderá ser utilizado para validar principalmente:

* Clareza dos fluxos;
* Facilidade de navegação;
* Organização das funcionalidades;
* Compreensão das telas;
* Facilidade de acesso às configurações;
* Clareza das informações dos leilões;
* Gerenciamento dos silos pelo proprietário;
* Acompanhamento dos leilões pelo produtor;
* Comunicação entre os usuários.

Os resultados das validações poderão gerar alterações nas próximas versões do protótipo.

---

# 🚀 Próximas etapas

* [ ] Validar o protótipo com usuários;
* [ ] Coletar feedback sobre os fluxos;
* [ ] Corrigir problemas de usabilidade;
* [ ] Refinar os componentes visuais;
* [ ] Desenvolver o protótipo de alta fidelidade;
* [ ] Realizar nova rodada de validação;
* [ ] Preparar as telas para implementação;
* [ ] Integrar o design com a aplicação desenvolvida.

---

## Status

**Protótipo de Média Fidelidade — Concluído / em validação**

O protótipo representa a versão intermediária da interface do GoSilo e poderá ser atualizado conforme os resultados das validações e decisões tomadas durante o desenvolvimento do Projeto Integrador.
