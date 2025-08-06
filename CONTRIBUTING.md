# 🧩 Guia de Contribuição

Para garantir organização e colaboração saudável no projeto, siga as diretrizes abaixo.

## 🚧 Fluxo de trabalho

1. Sempre crie uma branch para suas tarefas:
```bash
git checkout -b feat/nome-da-funcionalidade
```

2. Faça commits pequenos e claros
3. Ao terminar, envie a branch:
```bash
git push origin feat/nome-da-funcionalidade
```

4. Crie um **Pull Request** no GitHub
5. Aguarde revisão antes do merge

## 💬 Padrão de nomes de branch

| Tipo      | Prefixo      | Exemplo                     |
|-----------|--------------|-----------------------------|
| Funcionalidade | `feat/` | `feat/cadastro-usuario`     |
| Correção  | `fix/`       | `fix/validacao-email`       |
| Refatoração | `refactor/` | `refactor/persistencia`     |
| Testes    | `test/`      | `test/filme-controller`     |

## ✍️ Padrão de commit

```bash
git commit -m "feat: adiciona classe Usuario"
```

| Prefixo     | Uso                       |
|-------------|---------------------------|
| feat        | Nova funcionalidade       |
| fix         | Correção de bug           |
| refactor    | Refatoração de código     |
| docs        | Documentação              |
| test        | Adição/ajuste de testes   |
| chore       | Tarefas de infraestrutura |

## 🧪 Como rodar testes

> (inserir instruções, se houver testes)

## 📌 Observações

- Nunca envie código direto para a `main`
- Sempre revise e aprove Pull Requests dos colegas