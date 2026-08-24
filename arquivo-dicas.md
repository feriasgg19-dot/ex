# 🛠️ Como Definir o Git Bash como Terminal Padrão no VS Code

Este guia prático demonstra como alterar o perfil de terminal padrão no Visual Studio Code para utilizar o Git Bash.

---

## 📋 Passo a Passo

### 1. Abrir o Terminal Integrado
* Abra o seu VS Code.
* Use o atalho **`Ctrl + '`** (ou `Ctrl + Shift + '`).
* Alternativamente, vá no menu superior em **Terminal > New Terminal**.

### 2. Acessar as Configurações de Perfil
* No canto superior direito do painel do terminal, localize o ícone de **seta para baixo** (ao lado do ícone `+`).
* Clique na seta para abrir o menu suspenso.
* Selecione a opção **Select Default Profile** (Selecionar Perfil Padrão).

### 3. Escolher o Git Bash
* Uma lista com os terminais disponíveis no seu sistema surgirá no topo do VS Code.
* Clique sobre a opção **Git Bash**.

### 4. Validar a Alteração
* Feche o terminal atual clicando no ícone de **lixeira** (Kill Terminal).
* Abra um novo terminal usando o atalho **`Ctrl + '`**.
* O terminal agora iniciará automaticamente com o prefixo do **Git Bash**.

---

## ⚡ Método Alternativo (Via settings.json)
Se preferir configurar diretamente pelo arquivo de configurações globais, adicione a seguinte linha ao seu `settings.json`:

```json
"terminal.integrated.defaultProfile.windows": "Git Bash"
```
