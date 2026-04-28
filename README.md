# poc-legacy-repo

Repositório legado em processo de migração para `poc-new-repo`.

## Deploy

Utiliza manifests Kubernetes em `.k8s/`.

## Migração

Todo merge na `main` sincroniza automaticamente as mudanças elegíveis
para `poc-new-repo` via `legacy-relay`.

### O que vai para o novo repo

- `src/` — código da aplicação
- `.github/CODEOWNERS`
- `.github/workflows/validate.yml`

### O que fica só no legado

- `.k8s/` — infra específica do legado
- `.github/workflows/deploy-legacy.yml`
- `.github/workflows/sync-to-new.yml`


## nova sessao 2