# Demonstração do Comando git log

Este repositório contém uma demonstração do comando `git log` aplicado a um arquivo específico.

## Estrutura Criada

Foi criada a seguinte estrutura de diretórios e arquivo:
```
path/para/o/arquivo
```

## Histórico de Commits

O arquivo `path/para/o/arquivo` possui um histórico de 3 commits que demonstram como o git rastreia mudanças:

1. **Commit 1**: Criação inicial do arquivo
2. **Commit 2**: Segunda atualização com conteúdo adicional
3. **Commit 3**: Terceira atualização demonstrando rastreamento

## Como Usar

Para visualizar o histórico de commits deste arquivo, execute:

```bash
git log path/para/o/arquivo
```

### Opções Úteis

- Ver histórico resumido (uma linha por commit):
  ```bash
  git log --oneline path/para/o/arquivo
  ```

- Ver histórico com as mudanças (diff):
  ```bash
  git log -p path/para/o/arquivo
  ```

- Ver estatísticas das mudanças:
  ```bash
  git log --stat path/para/o/arquivo
  ```

## Resultado Esperado

O comando deve mostrar todos os 3 commits que modificaram o arquivo `path/para/o/arquivo`, em ordem cronológica reversa (mais recente primeiro).
