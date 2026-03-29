# Convenções de Desenvolvimento

## Branches

```
main          produção — protegida, merge via PR
develop       integração — base para features
feat/xxx      nova funcionalidade
fix/xxx       correção de bug
chore/xxx     manutenção, infra, sem lógica de negócio
docs/xxx      documentação
```

## Commits (Conventional Commits)

```
feat: descrição curta
fix: descrição curta
docs: descrição curta
chore: descrição curta
refactor: descrição curta
```

## Pull Requests

- Título segue o padrão de commit
- Descrição obrigatória: o que faz, por que, como testar
- Review obrigatório antes de merge em main

## Tasks

- Cada task tem um ID (futuro: Linear)
- Branch nomeada com o ID quando aplicável: `feat/DUE-42-bot-transbordo`

