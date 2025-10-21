# Dinâmica de Pull Request – Sala de Aula

Bem-vindos!  
Esta dinâmica tem como objetivo simular o fluxo real de trabalho em equipes de desenvolvimento usando **Pull Requests** no GitHub.

---

## 🎭 Papéis na dinâmica

Cada trio terá os papéis:
- **DEV** → cria a branch, faz alteração e abre a Pull Request
- **REVISOR** → analisa a PR e aprova ou solicita melhorias
- **MASTER** → faz o merge quando houver aprovação válida

Ao final de cada rodada, os papéis trocam entre os alunos.

---

## 🛑 Regras da Branch `main`

- A branch `main` está **protegida**
- **Não é permitido push direto**
- Só é possível integrar alterações através de Pull Request com **aprovador**
- Somente o Master pode dar o **merge**

---

## 🔀 Fluxo de Trabalho

1️⃣ DEV cria uma branch  
2️⃣ DEV edita o arquivo `atividade.md`  
3️⃣ DEV abre uma Pull Request direcionada para `main`  
4️⃣ REVISOR analisa e aprova a PR  
5️⃣ MASTER faz o merge

---

## 📍 Troca de Papéis

Após cada PR concluída, os papéis giram:

DEV → REVISOR → MASTER → DEV

---

## 🧪 Como participar

```bash
# 1. Clonar o repositório
git clone <url-do-repositorio>

# 2. Entrar na pasta
cd dinamica-pull-request

# 3. Criar uma nova branch (use nome do trio)
git checkout -b trio01-dev

# 4. Editar o arquivo atividade.md
# 5. Commit + Push
git add .
git commit -m "Alteração trio 01"
git push origin trio01-dev

# 6. Abrir Pull Request no GitHub


