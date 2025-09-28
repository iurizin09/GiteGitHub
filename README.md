# Git e GitHub – CbfCursos

Este README reúne os principais comandos do Git e boas práticas para trabalhar com repositórios no GitHub.

---

## 🟢 Comandos Básicos

- **`git status`** – Mostra o status dos arquivos (modificados, adicionados, não rastreados).  
- **`git add .`** – Adiciona todos os arquivos modificados ao stage (preparando para commit).  
- **`git add <nome_arquivo>`** – Adiciona apenas o arquivo especificado ao stage.  
- **`git commit -m "Mensagem"`** – Cria um commit com a mensagem informada.  
- **`git log`** – Exibe o histórico de commits.  
- **`git log --graph`** – Exibe o histórico de commits em forma de gráfico.  
- **`git log --oneline`** – Exibe os commits em uma linha cada.  
- **`git diff`** – Mostra as alterações que ainda não foram adicionadas ao stage.  
- **`git diff --cached`** – Mostra as alterações que estão no stage e prontas para commit.  

---

## 📝 Arquivo `.gitignore`

O `.gitignore` define arquivos e pastas que **não devem ser rastreados pelo Git**.  
Exemplo: arquivos de configuração local, compilados ou dados temporários.

---

## 🔄 Alterando Commits

- **`git restore <arquivo>`** – Restaura o arquivo para o estado do último commit.  
- **`git restore --staged <arquivo>`** – Remove um arquivo do stage (voltando para o estado não adicionado).  
- **`git reset --soft HEAD~1`** – Desfaz o último commit **sem alterar os arquivos**.  

---

## 🌿 Trabalhando com Branches

- **Criar branch:**  
```bash
git branch nome_da_branch
