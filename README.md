# Teste2

[![Lint](https://github.com/MauroSon/teste2/workflows/Lint/badge.svg)](https://github.com/MauroSon/teste2/actions/workflows/lint.yml)

## Descrição

Repositório com CI/CD configurado usando GitHub Actions para linting automatizado.

## CI/CD

Este projeto utiliza GitHub Actions para validação automática de código:

- **Linting**: ESLint para qualidade de código
- **Formatação**: Prettier para formatação consistente
- **Dependabot**: Atualizações automáticas de dependências

## Scripts Disponíveis

```bash
# Instalar dependências
npm install

# Executar lint
npm run lint

# Corrigir problemas de lint automaticamente
npm run lint:fix

# Verificar formatação
npm run format:check

# Formatar código
npm run format
```

## Workflow

O workflow de CI executa automaticamente em:
- Push para branches `main` ou `develop`
- Pull requests para branches `main` ou `develop`
