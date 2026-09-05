# GoSilo-Prototipos

![Status](https://img.shields.io/badge/status-em%20andamento-yellow)
![Fase](https://img.shields.io/badge/fase-prototipação-purple)
![Período](https://img.shields.io/badge/período-2º%20semestre-green)

Repositório de **UX/UI, fluxos de navegação e prototipação** do GoSilo.

Este repositório reúne a evolução visual e estrutural da solução, desde os primeiros wireframes de baixa fidelidade até os protótipos de alta fidelidade, além dos fluxos de navegação dos diferentes perfis de usuário.

---

## Sobre o GoSilo

O **GoSilo** é uma aplicação mobile desenvolvida para conectar produtores rurais que precisam de espaço para armazenar sua produção a proprietários de silos que possuem capacidade de armazenamento disponível.

A proposta funciona como um **marketplace de espaços para armazenamento agrícola**, permitindo que:

* **Donos de silos** anunciem espaços disponíveis;
* **Produtores rurais** encontrem espaços de armazenamento;
* Os usuários visualizem oportunidades por meio de **mapa e localização**;
* Produtores realizem **propostas e lances** pelos espaços disponíveis;
* Donos de silos acompanhem e gerenciem as propostas recebidas;
* As partes acompanhem o andamento das reservas e negociações.

O objetivo da prototipação é transformar os requisitos e pesquisas realizados na fase de planejamento em uma experiência de usuário clara, simples e adequada ao contexto do agronegócio.

---

## Objetivo do Repositório

Este repositório tem como objetivo documentar e armazenar a evolução da interface do GoSilo, permitindo validar a solução antes da implementação do sistema.

A prototipação é utilizada para:

* Explorar a organização das informações;
* Definir a estrutura das telas;
* Representar os fluxos de navegação;
* Validar a usabilidade da solução;
* Identificar problemas de experiência do usuário;
* Refinar a interface antes do desenvolvimento;
* Servir como referência para a implementação futura.

---

## Perfis de Usuário

O GoSilo possui dois principais perfis de utilização:

### Dono do Silo

Usuário que possui capacidade de armazenamento disponível e deseja disponibilizá-la na plataforma.

Principais ações:

* Criar e gerenciar anúncios;
* Informar características do silo;
* Definir disponibilidade e condições;
* Receber propostas;
* Acompanhar negociações;
* Visualizar reservas;
* Acompanhar resultados de leilões;
* Conversar com produtores.

### Produtor Rural

Usuário que precisa encontrar espaço para armazenar sua produção.

Principais ações:

* Buscar silos disponíveis;
* Visualizar opções no mapa;
* Consultar detalhes dos anúncios;
* Realizar propostas e lances;
* Acompanhar suas negociações;
* Confirmar reservas;
* Acompanhar reservas ativas.

---

## Estrutura do Repositório

```text
GoSIlo-Prototipos/
│
├── UX-UI/
│   ├── funcionalidades-mvp.md
│   ├── glossario-visual/
│   ├── wireframes-inciai/
│   ├── guia-estilo/
│   ├── teste-prototipo-baixafidelidade-feedback.md
│   ├── validacao-baixafidelidade-prototipo.md
│  
│
├── fluxo-navegacao/
│   ├── README-FLUXO.md/
│   ├── dono-silo/
│   └── produtor-rural/
│
├── prototipo-baixa-fidelidade/
│   ├── README-BAIXA-FIDELIDADE.md/
│   ├── dono-silo/
│   └── produtor-rural/
│
├── prototipo-media-fidelidade/
│   ├── README-MEDIA-FIDELIDADE.md/
│   ├── dono-silo/
│   └── produtor-rural/
│
├── prototipo-alta-fidelidade/
│   ├── dono-silo/
│   └── produto-rural/
│
└── README.md
```

---

## UX/UI

A pasta [`UX-UI`](UX-UI) concentra os documentos utilizados para orientar e registrar as decisões de experiência e interface do GoSilo.

## Wireframes Iniciais

A pasta [`wireframes-iniciais/`](wireframes-iniciai) reúne os primeiros estudos estruturais das telas.

### Funcionalidades do MVP

O arquivo [`funcionalidades-mvp.md`](UX-UI/funcionalidades-mvp.md) reúne as funcionalidades consideradas prioritárias para a primeira versão da solução.

### Glossário visual

A pasta [`glossario-visual`](UX-UI/glossario-visual) documenta termos e elementos visuais utilizados na interface.

### Guia de estilo

A pasta [`guia-estilo`](UX-UI/guia-estilo) reúne as definições relacionadas à identidade visual do aplicativo, incluindo elementos como:

* Cores;
* Tipografia;
* Componentes;
* Ícones;
* Padrões visuais;
* Diretrizes de interface.

### Validação Baixa Fidelidade

O arquivo [`validacao-baixafidelidade-prototipo.md`](UX-UI/validacao-baixafidelidade-prototipo.md) registra a validação realizada sobre o protótipo de baixa fidelidade e os ajustes identificados durante o processo.

### Validação Média Fidelidade

O arquivo [`teste-prototipo-mediafidelidade-feedback.md`](UX-UI/teste-prototipo-mediafidelidade-feedback.md) registra a validação realizada sobre o protótipo de baixa fidelidade e os ajustes identificados durante o processo.

---

## Fluxos de Navegação

A pasta [`fluxo-navegacao`](fluxo-navegacao) apresenta a sequência de telas e interações previstas para cada perfil de usuário.

### Dono do Silo

O fluxo representa, entre outras etapas:

```text
Splash
  ↓
Login
  ↓
Dashboard
  ↓
Painel
  ↓
Criar Anúncio
  ↓
Anúncio Criado
  ↓
Propostas Recebidas
  ↓
Resultado do Leilão
  ↓
Reserva
```

As telas do fluxo incluem elementos como **Dashboard, criação de anúncio, painel, propostas recebidas, resultado do leilão e reservas**.

### Produtor Rural

O fluxo representa, entre outras etapas:

```text
Splash
  ↓
Login
  ↓
Mapa
  ↓
Detalhes do Anúncio
  ↓
Lance / Proposta
  ↓
Confirmação
  ↓
Reserva
```

O fluxo contempla a busca de espaços, consulta dos detalhes, realização de lances e confirmação da reserva.

---

## Níveis de Fidelidade

A evolução dos protótipos foi organizada em três níveis de fidelidade.

### Baixa Fidelidade

O protótipo de baixa fidelidade tem como objetivo explorar principalmente:

* Estrutura das telas;
* Hierarquia das informações;
* Organização dos elementos;
* Fluxos de navegação;
* Facilidade de compreensão das tarefas.

Nesta etapa, a preocupação principal é **validar a estrutura e a lógica da experiência**, e não a aparência final da interface.

Os protótipos estão separados entre os perfis **dono do silo** e **produtor rural**.

### Média Fidelidade

O protótipo de média fidelidade representa uma evolução dos wireframes iniciais, incorporando maior definição dos componentes e da organização visual da aplicação.

Nesta etapa são refinados:

* Componentes de interface;
* Hierarquia visual;
* Navegação;
* Informações exibidas;
* Interações principais.

### Alta Fidelidade

O protótipo de alta fidelidade representa a versão visual mais próxima da interface planejada para o aplicativo.

Nesta etapa são considerados elementos como:

* Identidade visual;
* Cores;
* Tipografia;
* Ícones;
* Componentes;
* Hierarquia visual;
* Estados das telas;
* Interações previstas.

---

## Evolução da Prototipação

O desenvolvimento da interface segue uma evolução progressiva:

```text
Pesquisa com usuários
        ↓
Requisitos e funcionalidades
        ↓
Wireframes iniciais
        ↓
Baixa fidelidade
        ↓
Validação
        ↓
Média fidelidade
        ↓
Refinamento visual
        ↓
Alta fidelidade
        ↓
Validação final
        ↓
Implementação
```

Essa abordagem permite identificar problemas de navegação e usabilidade antes que a interface seja transformada em código.

---

## Ferramentas

### Figma

Utilizado para criação, organização e prototipação das interfaces e fluxos de usuário.

### Lovable

Utilizado como ferramenta auxiliar na exploração e construção inicial de interfaces.

### GitHub

Utilizado para versionamento e documentação dos artefatos de prototipação.

---

## Relação com o Repositório de Planejamento

O repositório de protótipos é complementar ao repositório **GoSilo-Planejamento**.

Enquanto o repositório de planejamento concentra:

* Pesquisa;
* Problema;
* Requisitos;
* Tecnologias;
* Modelagem;
* Documentação;

este repositório concentra:

* UX/UI;
* Wireframes;
* Fluxos de navegação;
* Protótipos;
* Validação da interface;
* Evolução visual da solução.

Dessa forma, os dois repositórios representam etapas complementares do desenvolvimento do GoSilo.

---

## Metodologia

A prototipação acompanha a metodologia de desenvolvimento adotada pelo projeto, utilizando ciclos de **exploração, validação e refinamento**.

Cada evolução do protótipo é realizada a partir dos requisitos definidos, das pesquisas com usuários e dos feedbacks obtidos durante as validações.

### Etapas

| Etapa               | Objetivo                         | Status        |
| ------------------- | -------------------------------- | ------------- |
| Wireframes iniciais | Explorar estrutura das telas     | Concluído     |
| Baixa fidelidade    | Validar estrutura e navegação    | Concluído     |
| Média fidelidade    | Refinar componentes e interações | Concluído     |
| Alta fidelidade     | Definir interface visual         | Pendente     |
| Validação final     | Avaliar e ajustar a solução      | Pendente     |
| Implementação       | Transformar protótipo em sistema | Próxima etapa |

---

## Status Atual

* [x] Wireframes iniciais definidos
* [x] Fluxos de navegação definidos
* [x] Fluxo do dono do silo desenvolvido
* [x] Fluxo do produtor rural desenvolvido
* [x] Protótipo de baixa fidelidade desenvolvido
* [x] Protótipo de média fidelidade desenvolvido
* [ ] Protótipo de alta fidelidade desenvolvido
* [x] Guia de estilo documentado
* [x] Glossário visual documentado
* [ ] Validação final do protótipo
* [ ] Implementação do aplicativo

---

## Links

* **Repositório de Planejamento:** [GoSilo-Planejamento](https://github.com/cakketobio/GoSilo-Planejamento)
* **Repositório de Protótipos:** [GoSilo-Prototipos](https://github.com/cakketobio/GoSilo-Prototipos)
* **Repositório de Código:** Em desenvolvimento
* **Board Kanban:** [Board Kanban do GoSilo](https://trello.com/invite/b/gdIdj7zz/ATTI027b16c041f19ee0085082933894d026F77FA151/projeto-integrador)

---

> **"Menos burocracia, mais receita."**
