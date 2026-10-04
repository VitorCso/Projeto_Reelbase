# Reelbase

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow) ![Versão](https://img.shields.io/badge/vers%C3%A3o-0.1.0-blue) ![Licença](https://img.shields.io/badge/licen%C3%A7a-acad%C3%AAmica-lightgrey)

**Instituição:** Centro Universitário de Brasília (UniCEUB)  
**Curso:** Superior de Tecnologia em Análise e Desenvolvimento de Sistemas  
**Disciplina:** Desenvolvimento Web  
**Turma / Semestre:** Turma A — 2026.2  
**Professor(a):** Felippe Pires Ferreira  
**Status do projeto:** Em desenvolvimento — Fase 1 (documentação e arquitetura)

---

## Sumário

- [1. Descrição do projeto](#1-descrição-do-projeto)
- [2. Funcionalidades](#2-funcionalidades)
- [3. Demonstração](#3-demonstração)
- [4. Tecnologias utilizadas](#4-tecnologias-utilizadas)
- [5. Arquitetura](#5-arquitetura)
- [6. Organização dos diretórios](#6-organização-dos-diretórios)
- [7. Participantes](#7-participantes)
- [8. Como executar](#8-como-executar)
- [9. Configuração](#9-configuração)
- [10. Testes](#10-testes)
- [11. Uso de inteligência artificial](#11-uso-de-inteligência-artificial)
- [12. Contribuição e fluxo de trabalho](#12-contribuição-e-fluxo-de-trabalho)
- [13. Histórico de versões](#13-histórico-de-versões)
- [14. Limitações e próximos passos](#14-limitações-e-próximos-passos)
- [15. Licença, referências e contato](#15-licença-referências-e-contato)

---

## 1. Descrição do projeto

*Apresente o contexto, o problema e a solução proposta. Use linguagem objetiva (dois a quatro parágrafos).*

[Descreva o que o sistema faz, para quem ele se destina e qual problema ele resolve.]

Os dados de filmes exibidos na aplicação são obtidos da API do [TMDB](https://www.themoviedb.org/).

### Objetivos

- **Objetivo geral:** [preencher]
- **Objetivos específicos:**
  - [preencher]

### Público-alvo

- [preencher]

---

## 2. Funcionalidades

*Liste as funções previstas no sistema e marque o status de cada uma.*

| Funcionalidade | Descrição | Status |
| -------------- | --------- | ------ |
| [preencher]    | [preencher] | Planejada |

### Requisitos não funcionais

- **Desempenho:** [preencher]
- **Segurança:** [preencher]
- **Usabilidade:** [preencher]
- **Disponibilidade:** [preencher]

---

## 3. Demonstração

A aplicação ainda não foi implementada (Fase 1). Os protótipos das telas essenciais e a identidade visual estão em [`docs/prototipos/`](docs/prototipos/).

| Tela        | Descrição   |
| ----------- | ----------- |
| [preencher] | [preencher] |

**Protótipo:** [URL do Figma ou arquivo em `docs/prototipos/`]  
**Aplicação publicada:** disponível a partir da Fase 2.

---

## 4. Tecnologias utilizadas

| Camada             | Tecnologia                                        | Versão      |
| ------------------ | ------------------------------------------------- | ----------- |
| Linguagem          | Python                                            | 3.12+       |
| Backend            | Django                                            | 5.2 LTS     |
| API REST           | Django REST Framework                             | 3.x         |
| Frontend           | Django Templates, HTML5, CSS3, JavaScript         | —           |
| Banco de dados     | [PostgreSQL / outro — confirmar]                  | [versão]    |
| API externa        | TMDB API (The Movie Database)                     | v3          |
| Testes             | Django Test Framework, Postman ou Insomnia        | —           |
| Segurança          | [Bandit ou Semgrep] (SAST), OWASP ZAP (DAST)      | —           |
| Modelagem          | [draw.io / brModelo / outra — confirmar]          | —           |
| Outras ferramentas | Git, GitHub                                       | —           |

---

## 5. Arquitetura

*Explique como o sistema está organizado: camadas, principais componentes e o fluxo entre eles. O diagrama completo e as justificativas estão em [`docs/arquitetura/`](docs/arquitetura/).*

[preencher]

**Decisões relevantes:**

- [preencher]

### Endpoints principais

| Método | Rota        | Descrição   |
| ------ | ----------- | ----------- |
| [—]    | [preencher] | [preencher] |

Contrato completo da API: [`docs/api/`](docs/api/)

---

## 6. Organização dos diretórios

```
.
├── README.md                 # Documentação principal do projeto
├── LICENSE                   # Termos de uso acadêmico
├── .gitignore                # Arquivos que não devem ser versionados
├── .env.example              # Modelo de variáveis de ambiente (Fase 2)
├── docs/                     # Documentação do projeto
│   ├── visao/                # Documento de Visão
│   ├── modelagem/
│   │   ├── casos-de-uso/     # Diagrama UML e especificações textuais
│   │   └── banco-de-dados/   # Modelo de dados (fonte editável + exportação)
│   ├── arquitetura/          # Diagramas de componentes/implantação e justificativas
│   ├── api/                  # Contrato da API própria e plano de integração externa
│   ├── prototipos/           # Identidade visual e protótipos das telas
│   ├── planejamento/         # Backlog, responsáveis e cronograma
│   └── seguranca/            # Relatórios SAST e DAST (Fase 2)
├── images/                   # Figuras da documentação geral
├── src/                      # Código-fonte da aplicação Django (Fase 2)
├── tests/                    # Testes automatizados (Fase 2)
└── scripts/                  # Scripts auxiliares de setup e deploy
```

| Diretório / arquivo | Função |
| ------------------- | ------ |
| `README.md`         | Apresentação do projeto e guia de navegação pelos documentos |
| `LICENSE`           | Condições de uso do código e da documentação |
| `.env.example`      | Lista das variáveis necessárias, sem credenciais reais |
| `docs/`             | Artefatos de análise, modelagem, planejamento e segurança |
| `images/`           | Figuras do README (não usar para diagramas de modelagem) |
| `src/`              | Código-fonte da aplicação |
| `tests/`            | Casos de teste e evidências de verificação |
| `scripts/`          | Automação de ambiente e execução |

Todo diagrama é versionado com o **arquivo-fonte editável** e uma **exportação em PDF, PNG ou SVG**.

---

## 7. Participantes

| Nome                           | Matrícula | Função no projeto |
| ------------------------------ | --------- | ----------------- |
| Luís Eduardo Carvalho Ferreira | [000000]  | [preencher]       |
| [Nome completo]                | [000000]  | [preencher]       |
| [Nome completo]                | [000000]  | [preencher]       |
| [Nome completo]                | [000000]  | [preencher]       |

**Professor responsável:** Felippe Pires Ferreira

---

## 8. Como executar

> A implementação será entregue na Fase 2. As instruções abaixo descrevem o procedimento previsto e serão revisadas quando o código estiver no repositório.

### Pré-requisitos

- Git
- Python 3.12+
- [PostgreSQL ou outro banco — confirmar]
- Conta no TMDB com um API Read Access Token

### Instalação e execução

```bash
# 1. Clonar o repositório
git clone [URL_DO_REPOSITORIO]
cd [NOME_DA_PASTA]

# 2. Criar e ativar o ambiente virtual
python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux/macOS:
source .venv/bin/activate

# 3. Instalar as dependências
pip install -r requirements.txt

# 4. Configurar as variáveis de ambiente
cp .env.example .env
# edite o arquivo .env com as credenciais locais

# 5. Aplicar as migrations
python manage.py migrate

# 6. (Opcional) Criar um superusuário
python manage.py createsuperuser

# 7. Executar a aplicação
python manage.py runserver
```

**Acesso local:** http://127.0.0.1:8000

### Implantação

- **Ambiente:** [provedor de hospedagem — Fase 2]
- **URL de produção:** [https://... — Fase 2]
- **Documentação da API:** [URL — Fase 2]
- **Observações:** as variáveis de ambiente devem ser configuradas no painel do provedor; em produção, `DEBUG=False` e HTTPS obrigatório.

---

## 9. Configuração

Variáveis de ambiente usadas pelo sistema. **Nunca publique senhas, tokens ou chaves neste arquivo.**

| Variável                 | Obrigatória | Descrição                                        | Exemplo |
| ------------------------ | ----------- | ------------------------------------------------ | ------- |
| `SECRET_KEY`             | Sim         | Chave secreta do Django                          | `[gerar localmente]` |
| `DEBUG`                  | Sim         | Modo de depuração (`False` em produção)          | `True` |
| `ALLOWED_HOSTS`          | Sim         | Domínios autorizados, separados por vírgula      | `localhost,127.0.0.1` |
| `CSRF_TRUSTED_ORIGINS`   | Produção    | Origens confiáveis para requisições com CSRF     | `https://[dominio]` |
| `DATABASE_URL`           | Sim         | Conexão com o banco de dados                     | `postgresql://usuario:senha@localhost:5432/app` |
| `TMDB_READ_ACCESS_TOKEN` | Sim         | Token de leitura da API do TMDB (cabeçalho Bearer) | `[obter em themoviedb.org]` |

Credenciais reais ficam apenas no arquivo `.env`, que está listado no `.gitignore` e não é versionado.

---

## 10. Testes

> Os testes serão implementados na Fase 2.

```bash
python manage.py test
```

| Tipo       | Ferramenta                       | O que verifica |
| ---------- | -------------------------------- | -------------- |
| Unitários  | Django Test Framework            | [preencher na Fase 2] |
| API        | Django REST Framework (APITestCase), Postman ou Insomnia | [preencher na Fase 2] |
| Manuais    | Roteiro em `tests/` ou `docs/`   | [preencher na Fase 2] |
| SAST       | [Bandit ou Semgrep]              | Código-fonte e dependências — relatório em `docs/seguranca/` |
| DAST       | OWASP ZAP                        | Aplicação publicada do próprio grupo — relatório em `docs/seguranca/` |

**Cobertura atual:** não medida (Fase 1).

---

## 11. Uso de inteligência artificial

Este repositório segue a política de uso de IA da disciplina (semáforo pedagógico):

![Política de uso de IA — semáforo](images/semaforo.png)

| Situação                    | Significado |
| --------------------------- | ----------- |
| **Vermelho — uso proibido** | Atividades de autonomia intelectual (ex.: provas presenciais sem consulta). |
| **Amarelo — uso limitado**  | IA pode ser ferramenta auxiliar, desde que haja declaração de uso. |
| **Verde — uso permitido**   | Uso livre ao longo da atividade acadêmica. |

### Declaração de uso

- **Houve uso de IA neste projeto?** Sim
- **Ferramentas utilizadas:** Claude (Anthropic)
- **Finalidade:** configuração do repositório e do fluxo de trabalho no Git; preenchimento das seções técnicas padrão deste README (estrutura de diretórios, instruções de execução, variáveis de ambiente, fluxo de contribuição); consulta técnica sobre a API do TMDB; esclarecimento de conceitos.
- **O que NÃO foi delegado à IA:** definição do problema, objetivos, público-alvo, funcionalidades, requisitos, casos de uso, arquitetura e modelagem de dados.

---

## 12. Contribuição e fluxo de trabalho

### Branches

- `main` — versão estável para avaliação
- `feat/[nome]` — nova funcionalidade
- `fix/[nome]` — correção de defeito
- `docs/[nome]` — alterações só de documentação (ex.: `docs/visao`, `docs/casos-de-uso`)

### Commits

Mensagens curtas, no imperativo, seguindo o padrão:

- `feat: adiciona busca de filmes`
- `fix: corrige validação de formulário`
- `docs: adiciona documento de visão`
- `chore: atualiza dependências`

### Passos

1. Criar uma branch a partir de `main`.
2. Fazer as alterações e commitar **pela própria conta do GitHub**.
3. Abrir um *pull request* para revisão de outro integrante.
4. Integrar à `main` somente após a revisão.

**Issues e quadro de tarefas:** [link do GitHub Projects, Trello ou similar]

---

## 13. Histórico de versões

| Versão  | Data       | Descrição |
| ------- | ---------- | --------- |
| `0.1.0` | 2026-10-05 | Entrega da Fase 1 — documentação e arquitetura (tag `v0.1-fase1`) |
| `0.0.1` | 2026-10-04 | Estrutura inicial do repositório |

---

## 14. Limitações e próximos passos

### Problemas conhecidos

- A aplicação ainda não foi implementada; esta versão contém apenas a documentação da Fase 1.

### Roadmap (Fase 2)

- [ ] Implementar a aplicação Django conforme a documentação da Fase 1
- [ ] Implementar cadastro, busca e relatório
- [ ] Implementar e documentar a API REST própria (OpenAPI/Swagger)
- [ ] Integrar a API do TMDB com tratamento de timeout, falhas e limites
- [ ] Publicar a aplicação com HTTPS e configurações seguras de produção
- [ ] Executar SAST e DAST, corrigir achados e registrar a nova verificação
- [ ] Registrar evidências de testes
- [ ] Preparar a apresentação final

---

## 15. Licença, referências e contato

**Licença:** uso exclusivamente acadêmico — consulte o arquivo [`LICENSE`](LICENSE).

Este produto usa a API do TMDB, mas não é endossado nem certificado pelo TMDB.

### Documentação complementar

- Documento de Visão: [`docs/visao/`](docs/visao/)
- Casos de uso (diagrama + especificações): [`docs/modelagem/casos-de-uso/`](docs/modelagem/casos-de-uso/)
- Modelo de dados: [`docs/modelagem/banco-de-dados/`](docs/modelagem/banco-de-dados/)
- Arquitetura: [`docs/arquitetura/`](docs/arquitetura/)
- Contrato da API e plano de integração externa: [`docs/api/`](docs/api/)
- Identidade visual e protótipos: [`docs/prototipos/`](docs/prototipos/)
- Planejamento: [`docs/planejamento/`](docs/planejamento/)
- Relatórios de segurança: [`docs/seguranca/`](docs/seguranca/) (Fase 2)

### Referências

- FERREIRA, Felippe Pires. *Trabalho Prático — Desenvolvimento de Aplicação Web com Python e Django*. UniCEUB, 2026.
- Django Software Foundation. *Django documentation*. https://docs.djangoproject.com/
- Encode. *Django REST Framework*. https://www.django-rest-framework.org/
- TMDB. *TMDB API — Developer documentation*. https://developer.themoviedb.org/
- OWASP. *ZAP*. https://www.zaproxy.org/

### Contato

Dúvidas sobre o projeto: [e-mail institucional do grupo ou issue no repositório]

**Agradecimentos:** Prof. Felippe Pires Ferreira.
