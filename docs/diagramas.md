# Diagram Examples

## Flowcharts

```mermaid
graph LR
  A[Start] --> B{Failure?};
  B -->|Yes| C[Investigate...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Success!];
```

## Sequence Diagrams

```mermaid
---
config:
  theme: default
  look: handDrawn
  fontFamily: '''Merriweather Variable'', serif'
  themeVariables:
    fontFamily: '''Merriweather Variable'', serif'
---
sequenceDiagram
  autonumber
  actor Servidor
  Servidor->>Secretaria: Send request
  loop Avaliação
      Secretaria->>Secretaria: Verificação dos dados
  end
  Note right of Secretaria: Análise do caso
  Secretaria-->>Terminal: Consulta aos dados
  Terminal->>BancoDados: Requisição de dados do servidor
  BancoDados-->>Terminal: Dados do servidor
  Terminal-->>Secretaria: Retorno da consulta
  Note left of Secretaria: Redação do relatório
  loop Relatório
    Secretaria->>Secretaria: Avaliação dos dados
  end
  Secretaria-->>Servidor: Envio de resposta

```
