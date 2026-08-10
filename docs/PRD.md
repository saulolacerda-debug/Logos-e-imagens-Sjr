# PRD — Biblioteca de ativos visuais

- **Status:** proposta para aprovação
- **Repositório:** `Logos-e-imagens-Sjr`
- **Atualizado em:** 2026-08-10

## Problema

Ativos de marca precisam de fonte organizada, licença e versões confiáveis.

## Objetivo

Manter repositório curado de logos e imagens aprovadas para uso.

## Escopo da primeira versão

- arquivos fonte
- variações
- metadados de uso
- guia de aplicação.

## Fora do escopo

- não é design system de componentes nem armazena material sem direitos.

## Requisitos de governança

- Todo requisito material, fonte de dados e integração deve ter responsável e trilha de decisão.
- Segredos, credenciais e dados reais de clientes ou pessoas não podem entrar no Git.
- Mudanças automatizadas devem ter limites de permissão, logs e revisão humana proporcional ao risco.
- APIs, contratos e regras relevantes precisam de versão e testes de regressão.

## Critérios de aceitação

- ativo tem versão, licença/uso e variante identificada.

## Métricas de sucesso

- adoção e utilização do fluxo principal;
- taxa de execução concluída sem erro;
- tempo de tratamento/retrabalho evitado;
- eventos, decisões e evidências rastreáveis.

## Dependências e riscos

Dependências específicas devem ser registradas em ADRs/decisões técnicas. Riscos comuns: alteração de fontes ou integrações, dados incorretos, acesso indevido, regressão e expansão de escopo. Mitigar com versionamento, testes, menor privilégio, evidência e revisão humana.
