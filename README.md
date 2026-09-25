# FinanceAgent

<div align="center">

![Status](https://img.shields.io/badge/status-portfolio-2563EB?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Privacy](https://img.shields.io/badge/processamento-local--first-10B981?style=for-the-badge)

**Plataforma desktop para conciliação bancária, análise financeira e auditoria local.**

</div>

## Visão geral

O FinanceAgent é uma plataforma desktop local-first para processar extratos bancários, organizar movimentações e gerar indicadores financeiros com foco em privacidade e rastreabilidade.

## O que o produto demonstra

- Importação de extratos OFX e CSV.
- Deduplicação e validação de transações.
- Categorização por regras de negócio.
- Dashboards e relatórios financeiros.
- Persistência local sem envio automático de dados para a nuvem.
- Fluxo auditável para processamento em lote.

## Arquitetura resumida

```text
OFX / CSV
   ↓
Ingestão e sanitização
   ↓
Regras de categorização
   ↓
Armazenamento local
   ↓
Dashboards e relatórios
```

## Stack

Python · CustomTkinter · SQLite · Pandas · Matplotlib · OpenPyXL

## Privacidade e disponibilidade

Este repositório é uma vitrine de produto e arquitetura. A implementação completa, as regras internas e os componentes de produção permanecem no repositório privado. Não envie dados bancários reais, credenciais ou documentos de clientes.

**Todos os direitos reservados — TLopeSolutions.**