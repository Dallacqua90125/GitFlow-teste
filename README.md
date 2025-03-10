# Git Flow - Fluxo de Trabalho

Este repositório segue a abordagem **Git Flow**, um modelo de ramificação que estrutura o desenvolvimento de software com branches bem definidas para diferentes estágios do projeto.

## 🔄 Instalação do Git Flow

Para instalar o Git Flow, execute o comando correspondente ao seu sistema operacional:

- ### **Windows (via Chocolatey)**

1. **Instalar Chocolatey (Powershell)**
```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

choco --version
```
2. **Instalar Git Flow**
```bash
choco install git-flow-avh -y
```

- ### **macOS (via Homebrew)**

1. **Instalar Homebrew**
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew --version
```

2. **Instalar Git Flow**
```bash
brew install git-flow-avh
```

### 📋 Estrutura de Branches

O Git Flow utiliza as seguintes branches principais:

- **`master`**: Representa a versão estável e pronta para produção.
- **`develop`**: Branch de desenvolvimento, onde as novas funcionalidades são integradas.
- **`feature/`**: Branches para desenvolvimento de novas funcionalidades.
- **`bug-fix`**: Branches para corrigr bugs encontrados na branch develop.
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
