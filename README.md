# Projeto de Engenharia de Software — Sports Perfomance

Repositório com artefatos de documentação e modelagem do sistema **Sports Performance**, desenvolvido no contexto da disciplina de Engenharia de Software.

## Visão geral

O foco deste projeto é organizar as entregas de engenharia de software, incluindo:

- Documentações (Modelo SBC);
- Especificacao de Casos de Uso;
- Modelagem UML (DCU, Classes, Implantação);
- Modelagem de processos BPMN.


## Estrutura do repositorio

```text
.
├── docs/
│   └── engSoft_I/
│       ├── AvaliacaoE2.md
│       ├── ESI_-_Trabalho_I.pdf
│       ├── ESI___Trabalho_II-04-12.pdf
│       ├── Trabalho_ESOFT_I_E1.pdf
│       └── Trabalho_ESOFT_I_E2.pdf
└── modelagem/
    ├── Documento de Especificação Casos de Uso.docx
    ├── sportsPerfomanceUML.asta
    ├── bpmn/
    │   ├── Processo de Onboarding e Configuracao.bpmn
    │   ├── gestao-vinculo-permissoes.bpmn
    │   └── ciclo-treinamento-feedback.bpmn
```

## Processos BPMN mapeados

- **Onboarding e Configuração**: cadastro, autenticação e integração externa.
- **Gestão de Vínculo e Permissões**: convite, aceite/recusa e liberacao de acesso.
- **Ciclo de Treinamento e Feedback**: planejamento, execução, análise e retorno de desempenho.

## Como visualizar os artefatos

1. Abra `modelagem/sportsPerfomanceUML.asta` no **Astah UML**.
2. Abra os arquivos `.bpmn` em `modelagem/bpmn/` no **Camunda Modeler**.

## Softwares de modelagem

Use esta seção para manter os links/fonte dos softwares, sem versionar instaladores no repositório:

- **Astah UML**: https://astah.net/download
- **Camunda Modeler**: https://camunda.com/download/modeler/

Local sugerido para uso local (ignorado pelo Git): `modelagem/softwares-local/`

## Como clonar

```bash
git clone git@github.com:John5626/projetoEngSoftware.git
cd projetoEngSoftware
```

## Status

Projeto acadêmico em evolução, com foco nas entregas de modelagem e documentação.
