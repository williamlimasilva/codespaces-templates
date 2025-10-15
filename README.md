# 🚀 Codespaces Templates

Este repositório centraliza diversos **templates prontos para uso no GitHub Codespaces**, organizados em subpastas conforme diferentes stacks, frameworks e versões de linguagens. O objetivo é facilitar a inicialização rápida de ambientes de desenvolvimento padronizados, promovendo agilidade, consistência e produtividade em projetos individuais ou de equipe.

---

## 📂 Estrutura do Repositório

Cada subpasta deste repositório representa um template para uma stack específica, contendo toda a configuração necessária para o Codespaces, exemplos mínimos de código e documentação de uso. Exemplos de subpastas:

```
codespaces-templates/
├── README.md                 # Este arquivo
├── vue/                      # Template para Vue.js
├── angular/                  # Template para Angular
├── next/                     # Template para Next.js
├── java8/                    # Template para Java 8
└── ...                       # Outras stacks/versões
```

Cada subpasta contém:

- `.devcontainer/` — Configuração do ambiente Codespaces (devcontainer.json, Dockerfile, etc.)
- Código e arquivos mínimos para iniciar o projeto
- README.md próprio explicando o funcionamento do template

---

## 🛠️ Como Utilizar um Template

Você pode utilizar qualquer template deste repositório para iniciar rapidamente um projeto no Codespaces. Siga um destes caminhos:

### 1. **Via interface do GitHub Codespaces**

1. Acesse este repositório.
2. Clique em **Code** > **Create codespace on main**.
3. No modal, selecione a opção **Location** e escolha a subpasta desejada como contexto (ex: `vue/`, `java17/`).
4. O Codespaces irá criar um ambiente já configurado conforme o template da subpasta escolhida.

> **Obs:** Caso a interface não permita selecionar subpasta diretamente, você pode clonar o repositório, entrar na subpasta desejada e abrir o Codespaces a partir dela pelo VS Code.

### 2. **Clonando e abrindo localmente no Codespaces/VS Code**

```sh
git clone https://github.com/seu-usuario/codespaces-templates.git
cd codespaces-templates/nome-da-stack
```
Depois, abra o Codespaces (ou VS Code com extensão Remote - Containers).

---

## 📖 Como Criar ou Atualizar um Template

1. **Crie uma nova subpasta** com nome representativo (ex: `java21/`, `react/`).
2. Adicione um arquivo `README.md` explicando o template, dependências e comandos principais.
3. Crie a pasta `.devcontainer/` com um `devcontainer.json` configurando a stack desejada.
4. Inclua um exemplo mínimo de projeto (ex: `src/Main.java`, `package.json`, etc).
5. Faça um Pull Request ou commit direto (dependendo do fluxo da equipe).

**Dicas:**
- Mantenha os templates sempre atualizados com as melhores práticas e versões estáveis.
- Adicione extensões do VS Code no `devcontainer.json` para facilitar o desenvolvimento.
- Documente comandos úteis no `README.md` de cada template.

---

## ❓ Dúvidas Frequentes

- **Posso criar meus próprios templates?**  
  Sim! Basta seguir o modelo das subpastas já existentes.

- **Posso sugerir melhorias?**  
  Claro! Abra uma issue ou pull request.

- **O Codespaces sempre usará o contexto correto?**  
  Recomendamos iniciar o Codespaces já na subpasta da stack desejada para garantir o ambiente correto.

---

## 💡 Exemplos de Subpastas

- `vue/` — Ambiente Node.js com extensões para Vue, projeto de exemplo com Vue CLI.
- `java21/` — Ambiente com Java 21, Maven configurado, exemplo Hello World.
- `next/` — Ambiente Node.js com Next.js instalado e pronto para desenvolvimento SSR.

---

## 👥 Colabore!

Este repositório é colaborativo. Sinta-se à vontade para sugerir novos templates, reportar problemas ou abrir pull requests com correções e melhorias.

---

**Mantenedores:**  
- [Seu Nome/Organização](https://github.com/williamlimasilva)

---
