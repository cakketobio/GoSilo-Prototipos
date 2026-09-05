# Fluxo de Navegação — GoSilo

Esta pasta contém os **fluxos de navegação do GoSilo**, desenvolvidos para representar a sequência de telas e as principais interações dos dois perfis de usuário da aplicação:

* **Dono do Silo**
* **Produtor Rural**

Os fluxos foram elaborados durante a etapa de UX/UI e servem como base para o desenvolvimento dos protótipos de baixa, média e alta fidelidade.

---

## Objetivo

Os fluxos de navegação têm como objetivo representar de forma visual o caminho que cada usuário percorre dentro do aplicativo para realizar suas principais tarefas.

A definição desses fluxos permite:

* Organizar a sequência das telas;
* Identificar as principais ações do usuário;
* Representar as transições entre telas;
* Separar as jornadas de cada perfil;
* Identificar possíveis pontos de decisão;
* Servir como base para a criação dos protótipos;
* Facilitar a validação da experiência antes da implementação.

---

# Perfis de Usuário

O GoSilo possui dois fluxos principais, correspondentes aos dois perfis da plataforma.

## Dono do Silo

O **Dono do Silo** é o usuário que possui espaço de armazenamento disponível e deseja disponibilizá-lo para outros produtores.

Seu fluxo contempla principalmente:

* Acesso à plataforma;
* Visualização do dashboard;
* Acesso ao painel de gerenciamento;
* Criação de anúncios;
* Visualização do anúncio criado;
* Acompanhamento do anúncio;
* Visualização do resultado do leilão.

### Fluxo

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
Anúncio Criado 2
   ↓
Resultado do Leilão
```

### Telas do fluxo

| Etapa | Tela                | Arquivo                                                                             |
| ----- | ------------------- | ----------------------------------------------------------------------------------- |
| 01    | Splash              | [`Splash - Dono.png`](dono-silo/Splash%20-%20Dono.png)                              |
| 02    | Login               | [`Login - Dono.png`](dono-silo/Login%20-%20Dono.png)                                |
| 03    | Dashboard           | [`Dashboard - Dono.png`](dono-silo/Dashboard%20-%20Dono.png)                        |
| 04    | Painel              | [`Painel - Dono.png`](dono-silo/Painel%20-%20Dono.png)                              |
| 05    | Criar Anúncio       | [`Criar Anúncio - Dono.png`](dono-silo/Criar%20An%C3%BAncio%20-%20Dono.png)         |
| 06    | Anúncio Criado      | [`Anúncio Criado - Dono.png`](dono-silo/An%C3%BAncio%20Criado%20-%20Dono.png)       |
| 07    | Anúncio Criado 2    | [`Anúncio Criado 2 - Dono.png`](dono-silo/An%C3%BAncio%20Criado%202%20-%20Dono.png) |
| 08    | Resultado do Leilão | [`Resultado Leilão - Dono.png`](dono-silo/Resultado%20Leil%C3%A3o%20-%20Dono.png)   |

---

# Produtor Rural

O **Produtor Rural** é o usuário que procura espaços disponíveis para armazenar sua produção.

Seu fluxo contempla principalmente:

* Acesso à plataforma;
* Visualização dos silos disponíveis;
* Navegação pelo mapa;
* Consulta das informações do silo;
* Realização de um lance;
* Confirmação do lance;
* Continuação do processo de contratação.

### Fluxo

```text
Splash
   ↓
Login
   ↓
Mapa
   ↓
Detalhes
   ↓
Detalhes 2
   ↓
Lance
   ↓
Lance 2
   ↓
Confirmação
   ↓
Confirmação 2
```

### Telas do fluxo

| Etapa | Tela          | Arquivo                                                                                       |
| ----- | ------------- | --------------------------------------------------------------------------------------------- |
| 01    | Splash        | [`Splash - Produtor.png`](produtor-rural/Splash%20-%20Produtor.png)                           |
| 02    | Login         | [`Login - Produtor.png`](produtor-rural/Login%20-%20Produtor.png)                             |
| 03    | Mapa          | [`Mapa - Produtor.png`](produtor-rural/Mapa%20-%20Produtor.png)                               |
| 04    | Detalhes      | [`Detalhes - Produtor.png`](produtor-rural/Detalhes%20-%20Produtor.png)                       |
| 05    | Detalhes 2    | [`Detalhes 2 - Produtor.png`](produtor-rural/Detalhes%202%20-%20Produtor.png)                 |
| 06    | Lance         | [`Lance - Produtor.png`](produtor-rural/Lance%20-%20Produtor.png)                             |
| 07    | Lance 2       | [`Lance 2 - Produtor.png`](produtor-rural/Lance%202%20-%20Produtor.png)                       |
| 08    | Confirmação   | [`Confirmação - Produtor.png`](produtor-rural/Confirma%C3%A7%C3%A3o%20-%20Produtor.png)       |
| 09    | Confirmação 2 | [`Confirmação 2 - Produtor.png`](produtor-rural/Confirma%C3%A7%C3%A3o%202%20-%20Produtor.png) |

---

# Relação entre os Fluxos

Os dois fluxos representam lados diferentes do mesmo processo de negócio.

```text
                    GoSilo
                       │
             ┌─────────┴─────────┐
             │                   │
       DONO DO SILO        PRODUTOR RURAL
             │                   │
        Cria anúncio         Busca espaço
             │                   │
        Disponibiliza        Visualiza mapa
           espaço                │
             │              Consulta detalhes
             │                   │
        Recebe lances        Realiza lance
             │                   │
             └─────────┬─────────┘
                       │
                  Negociação
                       │
                 Resultado
                       │
                    Reserva
```

O **Dono do Silo** representa o lado da oferta de armazenamento, enquanto o **Produtor Rural** representa o lado da demanda.

Essa relação é fundamental para o funcionamento do GoSilo como marketplace de espaços de armazenamento agrícola.

---

# Organização dos Arquivos

```text
fluxo-navegacao/
│
├── dono-silo/
│   ├── Splash - Dono.png
│   ├── Login - Dono.png
│   ├── Dashboard - Dono.png
│   ├── Painel - Dono.png
│   ├── Criar Anúncio - Dono.png
│   ├── Anúncio Criado - Dono.png
│   ├── Anúncio Criado 2 - Dono.png
│   └── Resultado Leilão - Dono.png
│
├── produtor-rural/
│   ├── Splash - Produtor.png
│   ├── Login - Produtor.png
│   ├── Mapa - Produtor.png
│   ├── Detalhes - Produtor.png
│   ├── Detalhes 2 - Produtor.png
│   ├── Lance - Produtor.png
│   ├── Lance 2 - Produtor.png
│   ├── Confirmação - Produtor.png
│   └── Confirmação 2 - Produtor.png
│
└── README.md
```

---

# Relação com os Protótipos

Os fluxos de navegação foram utilizados como referência para a evolução das interfaces do GoSilo.

```text
Pesquisa com usuários
        ↓
Requisitos
        ↓
Funcionalidades do MVP
        ↓
Fluxos de navegação
        ↓
Baixa fidelidade
        ↓
Média fidelidade
        ↓
Alta fidelidade
        ↓
Validação
        ↓
Desenvolvimento
```

Dessa forma, os fluxos funcionam como uma **ponte entre o planejamento do sistema e a prototipação da interface**.

---

# Evolução da Navegação

Os fluxos poderão ser atualizados conforme novos requisitos forem identificados ou conforme a validação dos protótipos indicar a necessidade de alterações.

Alterações futuras podem incluir:

* Novas telas;
* Novos caminhos de navegação;
* Estados alternativos;
* Tratamento de erros;
* Cancelamento de ações;
* Retorno para telas anteriores;
* Novas funcionalidades do MVP.

---

# Próximas Etapas

Os fluxos definidos nesta pasta servem como referência para:

* [x] Definição das principais jornadas;
* [x] Fluxo do Dono do Silo;
* [x] Fluxo do Produtor Rural;
* [x] Representação das principais telas;
* [x] Desenvolvimento dos protótipos;
* [x] Validação da navegação;
* [ ] Implementação dos fluxos no aplicativo.

---

> **"Menos burocracia, mais receita."**
