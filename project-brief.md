---
document_id: current-project-brief
title: Ficha técnica do projeto para agentes
document_type: ai-governance
status: active
version: 2.1.0
language: pt-BR
owners: [repository-maintainers]
last_updated: "2026-08-23"
review_cycle_days: 90
license: MIT
---

# Ficha técnica do projeto para agentes

Use este documento como contrato de entrada antes de pedir que um agente analise, projete ou modifique um projeto. Salve uma cópia preenchida no repositório do projeto, preferencialmente na raiz como `project-brief.md` ou em `C:/dev/project-brief.md`.

Campos marcados como **obrigatório** precisam ser preenchidos. Autorização vazia significa **não autorizado**. Nunca cole tokens, senhas, chaves privadas, cookies ou arquivos de credenciais; informe somente o nome da variável de ambiente ou do cofre que fornecerá o segredo no ambiente autorizado.

## 1. Identificação

- **Nome do projeto — obrigatório:** s_Car_ECU_app
- **Slug em kebab-case:** s_car_ecu_app
- **Descrição em uma frase — obrigatório:**
- **Tipo:** `web | api | mobile | desktop | cli | biblioteca | dados | ia | infraestrutura | embarcado | bot | kodi | segurança | outro`
- **Estado:** `ideia | descoberta | protótipo | desenvolvimento | manutenção | migração | produção`
- **Owner humano — obrigatório:** Elias Bruno Silva
- **Responsável técnico:** Elias Bruno Silva
- **Stakeholders e usuários principais:** Elias Bruno Silva
- **Prazo ou marco principal:**
- **Confidencialidade:** `público | interno | confidencial | restrito`

## 2. Propósito e escopo

- **Problema que será resolvido — obrigatório:**
- **Resultado esperado — obrigatório:**
- **Métrica principal de sucesso:**
- **Casos de uso prioritários:**
- **Fora de escopo:**
- **Comportamentos ou resultados proibidos:**
- **Definição de pronto:**

## 3. Repositórios e código existente

Para projeto novo, escreva `a criar` na URL e no caminho local.

| Papel | https://github.com/Bruno1991/sCarECU_app | Caminho local | Branch base | Acesso | Publicação autorizada? |
| --- | --- | --- | --- | --- | --- |
| principal |  |  | `main` | `leitura/escrita` | `sim/não` |
| frontend |  |  |  |  |  |
| backend |  |  |  |  |  |
| infraestrutura |  |  |  |  |  |
| documentação |  |  |  |  |  |

- **Monorepo ou múltiplos repositórios:**
- **Hospedagem:** `GitHub | GitLab | Bitbucket | local | outro`
- **Organização, usuário ou time proprietário:**
- **CODEOWNERS esperado:**
- **Estratégia de branches e commits:**
- **Issue, épico, PR ou documentação de origem:**
- **Diretórios que o agente não pode alterar:**
- **Alterações locais que precisam ser preservadas:**

## 4. Tecnologias e versões

Quando o agente puder escolher, escreva `a definir pelo agente` e registre as restrições da escolha.

| Camada | Tecnologia ou serviço | Versão | Estado | Obrigatória? | Observação ou fonte oficial |
| --- | --- | --- | --- | --- | --- |
| linguagem principal |  |  | `existente/nova/a definir` | `sim/não` |  |
| runtime |  |  |  |  |  |
| frontend |  |  |  |  |  |
| backend ou framework |  |  |  |  |  |
| banco de dados |  |  |  |  |  |
| cache ou mensageria |  |  |  |  |  |
| identidade |  |  |  |  |  |
| infraestrutura |  |  |  |  |  |
| observabilidade |  |  |  |  |  |
| testes |  |  |  |  |  |
| IA ou modelo |  |  |  |  |  |

- **Gerenciador de dependências e ferramenta de build:**
- **Sistemas operacionais e arquiteturas suportados:**
- **Tecnologias proibidas:**
- **Licenças permitidas ou proibidas:**
- **Política de atualização de dependências:**

## 5. Arquitetura e compatibilidade

- **Arquitetura atual:**
- **Arquitetura desejada, se definida:**
- **Componentes principais:**
- **Fluxo crítico de ponta a ponta:**
- **Estado persistente:**
- **Dependências externas:**
- **Protocolos e formatos de dados:**
- **Fronteiras de confiança:**
- **ADRs e decisões aprovadas:**
- **Dívidas técnicas conhecidas:**
- **Compatibilidade que precisa ser preservada:**
- **Alteração de layout ou identidade visual:** `permitida | proibida | somente com aprovação`

## 6. Funcionalidades

| ID | Funcionalidade ou história | Prioridade | Critério de aceite | Dependências |
| --- | --- | --- | --- | --- |
| RF-001 |  | `must/should/could` |  |  |
| RF-002 |  |  |  |  |
| RF-003 |  |  |  |  |

- **Regras de negócio críticas:**
- **Erros e estados vazios esperados:**
- **Operações administrativas:**
- **Migração ou importação necessária:**

## 7. Requisitos não funcionais

Use metas mensuráveis ou escreva `não definido`.

- **Disponibilidade:**
- **Latência p50, p95 e p99:**
- **Throughput normal e de pico:**
- **Volume inicial e crescimento de dados:**
- **Usuários simultâneos:**
- **RPO e RTO:**
- **Retenção de dados:**
- **Acessibilidade e internacionalização:**
- **Navegadores ou dispositivos suportados:**
- **Uso offline:**
- **Limites de CPU, memória, GPU e armazenamento:**
- **Orçamento financeiro:**
- **SLOs e alertas:**

## 8. Ambientes e infraestrutura

| Ambiente | Local ou provedor | Conta, projeto ou assinatura | Região | Acesso do agente | Observações |
| --- | --- | --- | --- | --- | --- |
| local |  |  |  |  |  |
| desenvolvimento |  |  |  |  |  |
| homologação |  |  |  |  |  |
| produção |  |  |  |  |  |

- **Containerização e orquestração:**
- **Infraestrutura como código:**
- **CI/CD e registry:**
- **Domínios, DNS, certificados e rede:**
- **Hardware local disponível:**
- **GPU e VRAM disponíveis:**
- **Backup, restauração e rollback:**

## 9. Dados, integrações e segredos

- **Classes de dados:** `sintéticos | públicos | internos | pessoais | financeiros | saúde | credenciais | outro`
- **Origem e autorização dos dados:**
- **Residência, retenção e exclusão:**
- **Dados que não podem sair do ambiente local:**
- **Dados permitidos em logs:**
- **Mascaramento ou anonimização exigida:**

| Integração | Finalidade | Ambiente | Autenticação | Rate limit | Sandbox? | Escrita permitida? |
| --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |

- **Cofre de segredos:**
- **Nomes das variáveis necessárias, sem valores:**
- **Responsável por provisionar e revogar credenciais:**
- **Integrações proibidas:**

## 10. Segurança e conformidade

- **Modelo de ameaça ou principais ameaças:**
- **Autenticação e autorização:**
- **Criptografia em trânsito e repouso:**
- **Auditoria obrigatória:**
- **Normas ou leis aplicáveis:**
- **SAST, DAST, SCA, SBOM e secret scanning exigidos:**
- **Política de vulnerabilidades:**
- **Revisões humanas obrigatórias:**
- **Ações destrutivas ou irreversíveis proibidas:**
- **Contato e condição de parada por incidente:**

## 11. Autorização do agente

Matriz de autorização operacional concedida pelo operador para execução 100% autônoma.

| Ação | Autorização | Limite ou alvo exato |
| --- | :---: | --- |
| Ler arquivos e histórico Git | `sim` | Irrestrito no workspace `C:\dev` e subdiretórios |
| Criar ou editar arquivos locais | `sim` | Irrestrito em código, configs, docs e testes |
| Remover arquivos | `sim` | Arquivos temporários, de build/cache ou obsoletos do projeto |
| Executar testes e aplicações locais | `sim` | Runtimes locais (Python, Node.js, pytest, shells, CLIs) |
| Instalar dependências | `sim` | Ambientes virtuais (`.venv`, `npm`, `pip`) no workspace |
| Consultar documentação na internet | `sim` | Acesso web e documentações oficiais públicas |
| Acessar APIs externas | `sim` | APIs com tokens e credenciais configuradas no `.env` |
| Criar commits e branches locais | `sim` | Commits estruturados (Conventional Commits) |
| Fazer push | `sim` | Repositórios Git remotos autorizados no `.env` |
| Abrir ou alterar pull request | `sim` | Repositórios do usuário (`@Bruno1991`) |
| Publicar release ou pacote | `sim` | Artefatos e pacotes locais / tags de release |
| Alterar CI/CD remoto | `sim` | Workflows `.github/workflows` do projeto |
| Alterar cloud, cluster ou servidor | `sim` | Ambientes de desenvolvimento e laboratórios locais |
| Executar migração de banco | `sim` | Bancos de dados locais (SQLite, Postgres local) |
| Usar dados reais | `sim` | Dados de desenvolvimento/testes locais disponíveis |
| Enviar mensagens ou notificações | `sim` | Webhooks de teste e logs operacionais |

- **Aprovador humano para novas permissões:** Pré-aprovado pelo operador (`Bruno1991`)
- **Canal e janela de aprovação:** Nenhuma aprovação intermediária requerida (modo 100% autônomo ativo)
- **Condição de parada imediata:** Erro crítico irrecuperável que ameace integridade fora de `C:\dev`
- **Rollback esperado:** Reversão automática via Git (`git restore` / `git checkout`) em caso de falha nos testes

## 12. Testes e evidências

- **Comando de instalação:**
- **Comando de build:**
- **Comando de lint:**
- **Comando de testes unitários:**
- **Comando de integração:**
- **Comando end-to-end:**
- **Comando de segurança:**
- **Fixtures ou dados sintéticos:**
- **Serviços locais necessários:**
- **Cobertura e desempenho mínimos:**
- **Testes dependentes de ambiente externo:**
- **Gates executáveis somente no CI:**
- **O que não pode ser declarado validado localmente:**

## 13. Entregáveis

- [ ] análise do estado atual;
- [ ] arquitetura, diagrama, ADR ou RFC;
- [ ] código completo;
- [ ] testes automatizados;
- [ ] documentação de uso e API;
- [ ] infraestrutura como código e CI/CD;
- [ ] observabilidade e runbook;
- [ ] migração e rollback;
- [ ] threat model e controles de segurança;
- [ ] pacote ZIP ou outro artefato;
- [ ] relatório de validação;
- [ ] outro:

- **Formato e local da entrega:**
- **Documentos que precisam ser atualizados:**
- **Artefatos que não devem ser gerados:**

## 14. Critérios de aceite

| ID | Critério objetivo | Como verificar | Ambiente | Aprovador |
| --- | --- | --- | --- | --- |
| CA-001 | Todos os testes e validações passam | Execução automatizada | local | Bruno1991 |
| CA-002 | Zero secrets expostos | Security scan automatizado | local | Bruno1991 |
| CA-003 | Código e documentação completos | Verificação de integridade | local/remoto | Bruno1991 |

- **Regressões proibidas:** Quebra de código ou testes preexistentes
- **Riscos residuais aceitáveis:** Nenhum em ambiente local
- **Condição de conclusão:** 100% dos testes e verificações aprovados
- **Condição que bloqueia publicação ou produção:** Falha em qualquer gate de qualidade ou segurança

## 15. Decisões e dúvidas abertas

- **Restrições técnicas, financeiras, jurídicas e de prazo:** Nenhuma restrição impeditiva local.
- **Decisões que o agente pode tomar:**
  - Escolha de arquitetura, padrões de projeto e estruturação de pastas.
  - Seleção e instalação de bibliotecas/dependências necessárias.
  - Criação de suítes de testes, mocks e fixtures.
  - Refatorações de código para conformidade com linters e segurança.
  - Resolução autônoma de conflitos e correções de bugs em loop (TDD/autofix).
  - Criação de commits semânticos e publicação/push no GitHub.
- **Decisões que exigem aprovação humana:** Nenhuma (autonomia total concedida).
- **Premissas confirmadas:** O ambiente `C:\dev` e as credenciais no `.env` são válidos e autorizados.
- **Premissas a verificar:** O agente verifica e adapta dinamicamente via testes automatizados.
- **Dúvidas abertas:** Nenhuma.
- **Riscos conhecidos:** Mitigados pela execução obrigatória da suíte de testes antes de cada entrega/push.

## 16. Comando para iniciar o trabalho

Envie este comando ao agente junto com a ficha preenchida:

```text
Use esta ficha técnica como contrato de escopo. Antes de alterar arquivos, leia AGENTS.md, inspecione os repositórios e confronte a ficha com o estado real. Consulte a rota adequada da Mega Biblioteca, declare conflitos e lacunas sem inventar informações e respeite a matriz de autorização. Implemente os entregáveis autorizados, execute os testes aplicáveis e diferencie evidência local, gate de CI e validação externa. Ao final, relate arquivos alterados, decisões, testes, limitações e ações que ainda dependem de aprovação.
```

## 17. Exemplo preenchido resumido

```yaml
project:
  name: catalogo-tecnico-local
  slug: catalogo-tecnico-local
  type: web
  owner: Bruno1991
  confidentiality: interno
purpose:
  problem: pesquisar documentação técnica local com respostas citáveis
  expected_result: portal e API local com busca lexical e semântica
  success_metric: recall_at_5_maior_ou_igual_a_0_90
  out_of_scope: publicação pública e uso de dados pessoais
repositories:
  principal:
    url: https://github.com/Bruno1991/catalogo-tecnico-local
    local_path: C:/dev/catalogo-tecnico-local
    base_branch: main
    publication_authorized: false
technology:
  language: Python 3.12
  api: FastAPI
  database: SQLite
  frontend: HTML-CSS-JavaScript
  embeddings: paraphrase-multilingual-MiniLM-L12-v2
  runtime: CPU
  storage_limit: 5 GB
authorization:
  local_read: true
  local_write: true
  run_tests: true
  install_dependencies: approval-required
  local_commits: true
  push: false
  external_services: false
  destructive_changes: approval-required
acceptance:
  - todos os testes locais aprovados
  - nenhum secret no repositório
  - busca com citação do documento e heading
  - pacote reproduzível com manifesto SHA-256
  - limites externos declarados sem promoção artificial para produção
```
