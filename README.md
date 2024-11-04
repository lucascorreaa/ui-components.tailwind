
# UI Components - Tailwind CSS

Este repositório é um projeto open source que utiliza o projetos com Tailwind CSS. A ideia é que a comunidade faça forks, crie suas próprias branches, contribua com novos componentes e abra Pull Requests para revisão e aprovação.

## 🚀 Como Contribuir

1. **Faça um Fork do Repositório**:
   - Clique no botão "Fork" no canto superior direito desta página para criar uma cópia deste repositório em sua conta do GitHub.

2. **Clone o Repositório Forkado**:
   - Clone o repositório para sua máquina local.
   ```bash
   git clone https://github.com/lucascorreaa/ui-components.tailwind
   cd ui-components.tailwind
   ```

3. **Crie uma Nova Branch**:
   - Crie uma nova branch para o seu componente.
   ```bash
   git checkout -b feat/nome-do-componente
   ```

4. **Adicione Seu Componente**:
   - Crie uma nova pasta dentro de `src/components/` com o nome do seu componente.
   - Dentro dessa pasta, adicione os arquivos `index.html`.
   - Siga o padrão de estrutura de pastas demonstrado na captura adicionada.

5. **Exporte e Adicione Imagens SVG**:
   - Exporte todas as imagens usadas no seu componente como arquivos SVG e coloque-os dentro da pasta `src/assets/images/`.

6. **Adicione o CSS Global**:
   - No seu arquivo `index.html`, importe o CSS global para garantir a padronização dos estilos:
   ```html
   <link rel="stylesheet" href="../../style/global.css">
   ```

7. **Faça o Commit das Suas Alterações**:
   - Faça o commit das suas alterações com uma mensagem descritiva.
   ```bash
   git add .
   git commit -m "Adicionei componente [nome-do-componente]"
   ```

8. **Faça o Push da Sua Branch**:
   - Envie suas alterações para o GitHub.
   ```bash
   git push origin feat/nome-do-componente
   ```

9. **Abra um Pull Request**:
   - No repositório original, abra um Pull Request para que sua contribuição possa ser revisada e aprovada.

## 📁 Estrutura de Pastas

```
ui-components.tailwind/
│
├── src/
│   ├── assets/
│   │   └── images/
│   │       ├── company-logo.svg
│   │  
│   │
│   ├── components/
│   │   └── nome do componente/
│   │       └── index.html/
│   │
│   └── style/
│       └── global.css
│
├── index.html
├── LICENSE
└── README.md
```

## 📝 Regras de Contribuição

- Todos os componentes devem ser criados em uma nova pasta dentro de `src/components/`.
- Cada componente deve conter um `index.html`.
- As imagens devem ser exportadas como SVG e colocadas em `src/assets/images/`.
- Mantenha seu código limpo e bem documentado.

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
