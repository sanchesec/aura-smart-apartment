# Plano da Equipe — Aura Smart Apartment

> Documento derivado da planilha de planejamento da equipe. O planejamento original foi criado para o MVP acadêmico com Bubble + Make + Python + GitHub.

## Arquitetura do projeto

| Tecnologia | Responsabilidade |
|---|---|
| Bubble | Aplicativo central e banco principal do Aura |
| Make | Automações, webhooks e comunicação entre serviços |
| Python | Validações e regras de negócio |
| GitHub | Código, backlog, documentação, testes e histórico do projeto |

## Responsabilidades da equipe

| Integrante | Papel principal | Entrega principal |
|---|---|---|
| Gustavo | Product Owner + Python + Integração | Produto definido, arquitetura documentada, integração técnica e apoio ao Python |
| Pedro | No-Code Developer — Bubble | Aura navegável e armazenando os dados no Bubble |
| Matheus | Python / Regras de Negócio | Módulos Python funcionando e testados |
| Eduardo | Low-Code / Automação — Make | Fluxos automáticos conectando Bubble, Python e usuários |
| Marlon | Git / Agile / QA | Projeto organizado, testado e documentado no GitHub |

## Regras de trabalho

1. Responsável principal não significa que só ele precisa entender a área.
2. Uma tarefa só vai para **DONE** quando existe evidência testável.
3. Integrações não devem ser deixadas apenas para a última semana.
4. Bubble é a fonte principal dos dados; Python aplica regras e devolve resultados; Make automatiza.
5. Após o congelamento do escopo, entram apenas correções, documentação e ensaio.

## Cronograma planejado

| Sprint | Período | Objetivo |
|---|---|---|
| Sprint 1 | 29/09–04/10 | Fundação do projeto |
| Sprint 2 | 05/10–11/10 | Partes funcionando |
| Sprint 3 | 12/10–18/10 | Primeira integração completa |
| Sprint 4 | 19/10–25/10 | Fluxo de solicitações |
| Sprint 5 | 26/10–01/11 | Gestão + documentação |
| Sprint final | 02/11–08/11 | Congelamento e preparação |

## Fluxos principais planejados

### Acesso
Morador → autorização → Portaria → entrada → saída → histórico.

### Solicitação
Morador/Admin → Administração → responsável escolhido → execução → conclusão.

### Gestão preventiva
Equipamentos/Insumos → alerta → Administração → possível solicitação.

## Limites do MVP

### Dentro do MVP
- acessos;
- solicitações;
- equipamentos e insumos simples;
- automações;
- regras Python.

### Fora do MVP
- marketplace de prestadores;
- pagamentos;
- chat;
- biometria/catraca física;
- ERP de estoque.

## Observação sobre evolução do projeto

A planilha original foi criada quando o Aura trabalhava com três perfis principais. A implementação atual evoluiu para cinco perfis: **MORADOR, PORTARIA, ADMIN, FUNCIONARIO e PRESTADOR_TERCEIRIZADO**. Por isso, esta documentação deve ser atualizada sempre que uma decisão antiga divergir da implementação atual.
