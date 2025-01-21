# TASK

## Criar 2 microserviços de exemplo

- [x] Criar microserviço de Orders

  - [x] Criar endpoint de Healfhcheck
  - [x] Criar endpoint de CRUD de Orders
  - [x] Adicione compatibilidade com Dockerfile

- [x] Criar microserviço de Products

  - [x] Criar endpoint de Healfhcheck
  - [x] Criar endpoint public de categoria de Produtos
  - [x] Criar endpoint de CRUD de Produtos

## Krakend

- [x] Estrutura

  - [x] Provisionar o Krakend no Docker Compose

- [ ] Funcionalidades

  - [x] Mapear endpoints de Orders
  - [x] Mapear endpoints de Products
  - [x] Adicionar Rate Limit em Orders
  - [x] Adicionar Autenticação (Keycloak)
  - [x] Adicionar Autorização (Keycloak)
  - [ ] Adicionar uma funcionalidade de BFF entre Orders e Products
  - [ ] Adicionar Monitoramento
    - [x] Métricas
    - [x] Traces
    - [ ] Logs
      - [ ] Tentativa com Open Telemetry sem sucesso
      - [ ] Tentativa com Fluent Bit sem sucesso
