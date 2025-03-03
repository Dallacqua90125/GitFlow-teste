Aqui está todo o conteúdo formatado em Markdown para você usar no seu `README.md`:

```markdown
# Git Flow - Fluxo de Trabalho

Este repositório segue a abordagem **Git Flow**, um modelo de ramificação que estrutura o desenvolvimento de software com branches bem definidas para diferentes estágios do projeto.

### 🔄 Instalação do Git Flow

Para instalar o Git Flow, execute o comando correspondente ao seu sistema operacional:

- **Windows (via Chocolatey)**

```bash
choco install git-flow-avh -y
```

- **macOS (via Homebrew)**

```bash
brew install git-flow-avh
```

- **Linux (via apt-get)**

```bash
sudo apt-get install git-flow
```

### 📋 Estrutura de Branches

O Git Flow utiliza as seguintes branches principais:

- **`main`**: Representa a versão estável e pronta para produção.
- **`develop`**: Branch de desenvolvimento, onde as novas funcionalidades são integradas.
- **`feature/`**: Branches para desenvolvimento de novas funcionalidades.
- **`release/`**: Branches para preparação de novas versões.
- **`hotfix/`**: Branches para correções críticas em produção.

### 🛠️ Comandos Básicos

- **Iniciar Git Flow no repositório:**

```bash
git flow init
```

- **Criar uma nova feature:**

```bash
git flow feature start <nome-da-feature>
```

- **Finalizar uma feature:**

```bash
git flow feature finish <nome-da-feature>
```

- **Criar uma nova release:**

```bash
git flow release start <versão>
```

- **Finalizar uma release:**

```bash
git flow release finish <versão>
```

- **Criar um hotfix:**

```bash
git flow hotfix start <versão>
```

- **Finalizar um hotfix:**

```bash
git flow hotfix finish <versão>
```

### 📚 Recursos Adicionais

Para mais informações sobre o Git Flow, consulte a [documentação oficial](https://github.com/nvie/gitflow).
```

Agora é só copiar e colar no seu `README.md`! 😊