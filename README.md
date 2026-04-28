# poc-new-repo

Repositório novo — destino da migração de `poc-legacy-repo`.

## Deploy

Utiliza Helm charts em `./charts/`.

## Arquivos exclusivos deste repo

- `charts/` — Helm charts (não existem no legado)
- `new-only-config.yaml` — configurações exclusivas do novo
- `.github/workflows/deploy-new.yml` — pipeline de deploy com Helm

Esses arquivos nunca são sobrescritos pelo sync do legado.
