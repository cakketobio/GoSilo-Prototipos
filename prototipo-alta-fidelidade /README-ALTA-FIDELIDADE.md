# GoSilo — Protótipo de Alta Fidelidade

## Sobre o projeto

O **GoSilo** é uma aplicação mobile desenvolvida para conectar **produtores rurais que necessitam de espaço para armazenagem** a **proprietários de silos que possuem capacidade disponível**.

A solução utiliza um modelo de marketplace, permitindo que proprietários disponibilizem seus silos e que produtores rurais encontrem oportunidades de armazenagem por meio de anúncios e leilões.

Este diretório contém os artefatos referentes ao **protótipo de alta fidelidade** do GoSilo, desenvolvido durante o Projeto Integrador.

---

## Objetivo

O protótipo de alta fidelidade tem como objetivo representar visualmente a interface da aplicação, aproximando a experiência de navegação do produto final e permitindo avaliar a apresentação das informações, a identidade visual e a organização dos componentes.

Nesta etapa, foram refinadas as interfaces dos dois principais perfis do sistema:

- **Dono do Silo**
- **Produtor Rural**

Também foram desenvolvidas telas relacionadas à autenticação e às configurações gerais da aplicação.

O protótipo representa uma evolução das etapas anteriores de UX/UI, utilizando elementos visuais mais próximos daqueles previstos para a implementação do GoSilo.

---

## Alta fidelidade

O protótipo de alta fidelidade representa uma evolução dos protótipos de baixa e média fidelidade.

Enquanto as etapas anteriores priorizaram a estrutura das telas e a organização dos fluxos de navegação, esta etapa concentra-se no refinamento visual da interface.

Entre os aspectos contemplados estão:

- Identidade visual da aplicação;
- Padronização dos componentes;
- Organização e hierarquia visual das informações;
- Tipografia e elementos gráficos;
- Cores e elementos de destaque;
- Botões, ícones e campos de entrada;
- Apresentação das funcionalidades de cada perfil;
- Consistência visual entre as diferentes telas;
- Refinamento da experiência de navegação.

O objetivo é proporcionar uma representação visual mais próxima da aplicação pretendida, servindo como referência para as etapas posteriores de desenvolvimento.

---

# Telas do protótipo

O protótipo está organizado em quatro diretórios, agrupando as interfaces de acordo com sua finalidade e perfil de utilização.

## 1. Autenticação

O diretório `pagina-login` reúne as telas relacionadas ao acesso e à autenticação dos usuários na plataforma.

| **Arquivo** | **Descrição** |
|---|---|
| [cadastro-usuario.png](./pagina-login/cadastro-usuario.png) | Tela de cadastro de um novo usuário na plataforma. |
| [selecao-funcao.png](./pagina-login/selecao-funcao.png) | Tela de seleção da função de utilização da plataforma. |
| [login.png](./pagina-login/login.png) | Tela de acesso à plataforma por meio das credenciais do usuário. |
| [recuperacao-senha.png](./pagina-login/recuperacao-senha.png) | Tela destinada à recuperação de acesso à conta. |
| [criar-nova-senha.png](./pagina-login/criar-nova-senha.png) | Tela para definição de uma nova senha. |
| [sac.png](./pagina-login/sac.png) | Tela relacionada ao Serviço de Atendimento ao Consumidor (SAC). |

---

## 2. Dono do Silo

O diretório `dono-silo` reúne as interfaces destinadas aos proprietários de silos.

As telas representam a experiência do usuário responsável por disponibilizar espaços de armazenagem, gerenciar seus silos e acompanhar as oportunidades relacionadas à plataforma.

| Arquivo | Descrição |
|---|---|
| [criacao-anuncio.png](./dono-silo/criacao-anuncio.png) | Interface para criação de um anúncio de armazenagem. |
| [criacao-anuncios.png](./dono-silo/criacao-anuncios.png) | Captura complementar do fluxo de criação de anúncios. |
| [edicao-perfil.png](./dono-silo/edicao-perfil.png) | Interface de edição dos dados do perfil do proprietário. |
| [edicao-silos.png](./dono-silo/edicao-silos.png) | Interface de edição das informações dos silos cadastrados. |
| [historico-conversas.png](./dono-silo/historico-conversas.png) | Histórico de conversas do proprietário. |
| [home-page-dono.png](./dono-silo/home-page-dono.png) | Página inicial do perfil Dono do Silo. |
| [leilao-ocorrendo-enceraddo.png](./dono-silo/leilao-ocorrendo-enceraddo.png) | Interface relacionada ao acompanhamento e encerramento de leilão. |
| [leiloes-png](./dono-silo/leiloes-png) | Captura relacionada à área de leilões do proprietário. |
| [perfil-dono.png](./dono-silo/perfil-dono.png) | Página de perfil do proprietário do silo. |
| [resultado-leilao.png](./dono-silo/resultado-leilao.png) | Interface de apresentação do resultado de um leilão. |
| [silos-cadastrados.png](./dono-silo/silos-cadastrados.png) | Listagem dos silos cadastrados pelo proprietário. |

---

## 3. Produtor Rural

O diretório `produto-rural` reúne as interfaces destinadas aos produtores rurais.

As telas representam a experiência do usuário que procura oportunidades de armazenagem, consulta as opções disponíveis, realiza reservas e acompanha os leilões da plataforma.

| Arquivo | Descrição |
|---|---|
| [cadastro-produto.png](./produto-rural/cadastro-produto.png) | Interface de cadastro das informações do produto agrícola. |
| [confirmar-reserva.png](./produto-rural/confirmar-reserva.png) | Etapa de confirmação de uma reserva de armazenagem. |
| [edicao-perfil.png](./produto-rural/edicao-perfil.png) | Interface de edição dos dados do perfil do produtor. |
| [historico-conversas.png](./produto-rural/historico-conversas.png) | Histórico de conversas do produtor rural. |
| [historico-leiloes.png](./produto-rural/historico-leiloes.png) | Histórico de leilões relacionados ao produtor. |
| [home-page-andamento.png](./produto-rural/home-page-andamento.png) | Página inicial com informações de uma reserva ou processo em andamento. |
| [home-page-programado.png](./produto-rural/home-page-programado.png) | Página inicial com informações de uma reserva programada. |
| [home-page-reserva.png](./produto-rural/home-page-reserva.png) | Página inicial relacionada à consulta ou realização de reservas. |
| [leilao.png](./produto-rural/leilao.png) | Interface de participação em leilão. |
| [perfil-produtor.png](./produto-rural/perfil-produtor.png) | Página de perfil do produtor rural. |

---

## 4. Configurações

O diretório `configuracoes` reúne as interfaces relacionadas às preferências e configurações gerais da aplicação.

Essas telas complementam a experiência dos usuários, contemplando opções de personalização e ajustes da interface.

| Arquivo | Descrição |
|---|---|
| [idioma.png](./configuracoes/idioma.png) | Opção de configuração do idioma da aplicação. |
| [pagina-configuracoes.png](./configuracoes/pagina-configuracoes.png) | Página principal de configurações. |
| [sac.png](./configuracoes/sac.png) | Interface de acesso ao Serviço de Atendimento ao Consumidor (SAC). |
| [tamanho-letra.png](./configuracoes/tamanho-letra.png) | Opção de ajuste do tamanho da fonte. |

---

# Estrutura do diretório

A organização dos arquivos separa as capturas de tela de acordo com os perfis de usuário e as funcionalidades gerais da aplicação.

```text
prototipo-alta-fidelidade/
│
├── README-ALTA-FIDELIDADE.md
│
├── configuracoes/
│   ├── idioma.png
│   ├── pagina-configuracoes.png
│   ├── sac.png
│   └── tamanho-letra.png
│
├── dono-silo/
│   ├── criacao-anuncio.png
│   ├── criacao-anuncios.png
│   ├── edicao-perfil.png
│   ├── edicao-silos.png
│   ├── historico-conversas.png
│   ├── home-page-dono.png
│   ├── leilao-ocorrendo-enceraddo.png
│   ├── leiloes-png
│   ├── perfil-dono.png
│   ├── resultado-leilao.png
│   └── silos-cadastrados.png
│
├── pagina-login/
│   ├── Captura de tela 2026-11-16 111144.png
│   ├── Captura de tela 2026-11-16 111156.png
│   ├── Captura de tela 2026-11-16 111208.png
│   ├── Captura de tela 2026-11-16 111222.png
│   ├── Captura de tela 2026-11-16 111234.png
│   └── Captura de tela 2026-11-16 111243.png
│
└── produto-rural/
    ├── cadastro-produto.png
    ├── confirmar-reserva.png
    ├── edicao-perfil.png
    ├── historico-conversas.png
    ├── historico-leiloes.png
    ├── home-page-andamento.png
    ├── home-page-programado.png
    ├── home-page-reserva.png
    ├── leilao.png
    └── perfil-produtor.png
```

---

# Resumo das telas

| Categoria | Quantidade de arquivos |
|---|---:|
| Autenticação | 6 |
| Dono do Silo | 11 |
| Produtor Rural | 10 |
| Configurações | 4 |
| **Total** | **31** |

> A quantidade considera os arquivos presentes nos diretórios do protótipo, incluindo o arquivo `leiloes-png`, que está publicado sem extensão no repositório.

---

# Evolução do projeto

O protótipo de alta fidelidade faz parte do processo evolutivo de desenvolvimento da interface do GoSilo.

```text
Pesquisa com usuários
        ↓
Levantamento de requisitos
        ↓
Definição dos fluxos de navegação
        ↓
Protótipo de baixa fidelidade
        ↓
Protótipo de média fidelidade
        ↓
Validação e feedback
        ↓
Protótipo de alta fidelidade
        ↓
Refinamento da interface
        ↓
Implementação da aplicação
```

Cada etapa contribui para a evolução da solução, permitindo aprimorar progressivamente a estrutura, a navegação e a apresentação visual do sistema.

---

# Validação

O protótipo de alta fidelidade poderá ser utilizado como referência para avaliar:

- Consistência da identidade visual;
- Clareza da hierarquia das informações;
- Padronização dos componentes;
- Legibilidade dos elementos da interface;
- Facilidade de navegação;
- Organização das funcionalidades;
- Experiência dos dois perfis de usuário;
- Correspondência entre os fluxos e os requisitos do sistema.

Os resultados das avaliações poderão orientar ajustes antes da implementação das interfaces na aplicação.

---

# Próximas etapas

- [x] Desenvolver a estrutura inicial dos fluxos;
- [x] Elaborar os protótipos de baixa e média fidelidade;
- [x] Desenvolver as interfaces de alta fidelidade;
- [x] Revisar a consistência visual das telas;
- [x] Realizar validação da interface;
- [x] Aplicar possíveis melhorias identificadas;
- [x] Preparar as referências visuais para implementação;
- [ ] Integrar as interfaces ao desenvolvimento da aplicação.

---

## Status

**Protótipo de Alta Fidelidade — Em desenvolvimento.**

O protótipo representa a etapa de refinamento visual da interface do GoSilo, estabelecendo uma referência para a implementação da aplicação e para as próximas atividades de validação e desenvolvimento do Projeto Integrador.
