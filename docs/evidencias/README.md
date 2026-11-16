# Evidências do Projeto

Esta pasta registra evidências usadas para comprovar a evolução e as entregas do **Aura Smart Apartment**.

## MVP do Aura

- **Bubble:** https://gustavosanchesec-40441.bubbleapps.io/version-test?debug_mode=true
- **Descrição:** primeiro MVP funcional utilizado para testar os fluxos do sistema.

## Automação Make

### Cenário inicial — Eduardo José

- https://us2.make.com/3068116/scenarios/6796556/edit
- Cenário inicial criado para a etapa de Low-Code e validação/cadastro.

### Cenário final — Gustavo Soares

- https://us2.make.com/3068116/scenarios/6986544/edit
- Cenário final integrado ao Bubble e à API Python/Vercel.
- Fluxo funcional: **Bubble → Make → Python/Vercel → Make → Bubble**.

## Vídeos de apresentação da disciplina de Low-Code

Eduardo José produziu os seguintes vídeos para apresentar ao professor **Lucas Alves** as partes do projeto relacionadas à disciplina:

| Arquivo | Duração aproximada | Observação |
|---|---:|---|
| `2026-11-11 17-36-01.mp4` | 4min20s | Evidência de apresentação da parte de Low-Code. |
| `2026-11-11 18-06-27(1).mp4` | 2min00s | Evidência de apresentação da parte de Low-Code. |

Os arquivos originais foram preservados pela equipe. O vídeo de aproximadamente 4min20s possui cerca de 192 MB, acima do limite normal de 100 MB por arquivo do GitHub sem Git LFS.

## API Python

- **Endpoint:** https://expotech-aura.vercel.app/validar
- **Método:** `POST`
- **Responsabilidade:** validar dados da autorização e retornar `APROVADA` ou `INVALIDA` com o motivo.

## Resultado técnico validado

O fluxo de integração foi testado com casos válidos e inválidos:

```text
Bubble
  ↓
Make
  ↓
Python / Vercel
  ↓
Make
  ↓
Bubble
```

O Bubble cria a autorização como `VERIFICANDO`, o Python executa as regras de validação e o registro é atualizado com o resultado retornado.
