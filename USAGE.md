# 📚 Guia de Uso dos Arquivos do Repositório

Este repositório contém documentação e assets para uso em diferentes contextos do GitHub.

## 📁 Estrutura de Arquivos

### Arquivos Principais

- **`README.md`** - README principal do repositório organizacional/corporativo
  - 📍 **Usar em**: Repositórios da organização CW-Software-Apps
  - 🎯 **Propósito**: Apresentar a empresa, tecnologias e projetos

- **`PROFILE.md`** - README de perfil pessoal do GitHub
  - 📍 **Usar em**: Repositório `wagenheimer/wagenheimer` (perfil pessoal)
  - 🎯 **Propósito**: Apresentação profissional no perfil do GitHub
  - ⚠️ **Importante**: Deve ser colocado em um repositório com o mesmo nome do usuário

### Assets

A pasta `assets/` contém todas as imagens usadas nos arquivos Markdown:

- **`cw_software_banner.png`** - Banner principal da CW Software
- **`CWSoftwareLogoFull.png`** - Logo completo da empresa
- **`tech_stack_showcase.png`** - Showcase visual das tecnologias
- **`logo_greensaucegames.png`** - Logo do parceiro Green Sauce Games
- **`sevensails.png`** - Logo do parceiro Seven Sails Games

## 🚀 Como Usar

### Para o Repositório Organizacional

1. Copie `README.md` para o repositório raiz da organização
2. Copie a pasta `assets/` completa
3. Commit e push:

```bash
git add README.md assets/
git commit -m "docs: adiciona README corporativo com assets"
git push origin main
```

### Para o Perfil Pessoal do GitHub

1. Crie um repositório chamado `wagenheimer` (mesmo nome do usuário)
2. Renomeie `PROFILE.md` para `README.md`
3. Copie a pasta `assets/`
4. Commit e push:

```bash
# No repositório wagenheimer/wagenheimer
cp PROFILE.md README.md
git add README.md assets/
git commit -m "docs: adiciona README de perfil"
git push origin main
```

## 🎨 Personalização

### Badges

Os badges usam o serviço `shields.io`. Para personalizar cores e estilos:

- **Estilos disponíveis**: `flat`, `flat-square`, `for-the-badge`, `plastic`, `social`
- **Cores**: Hex codes ou nomes (blue, green, red, etc.)

Exemplo:

```markdown
![Badge](https://img.shields.io/badge/LABEL-MESSAGE-COLOR?style=for-the-badge&logo=LOGO)
```

### GitHub Stats

As estatísticas usam o serviço `github-readme-stats`:

```markdown
![Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=THEME)
```

**Temas disponíveis**: `radical`, `dark`, `default`, `tokyonight`, `dracula`, etc.

### Imagens

Para adicionar novas imagens:

1. Adicione o arquivo na pasta `assets/`
2. Referencie no Markdown: `![Alt Text](./assets/nome-da-imagem.png)`

## 🔧 Manutenção

### Atualizar Links

Procure e substitua os seguintes placeholders conforme necessário:

- URLs do website
- Links do LinkedIn
- Email de contato
- WhatsApp
- Username do GitHub

### Atualizar Versões

Mantenha as badges atualizadas com as versões corretas:

- .NET version
- C# version
- Frameworks e libraries

### Imagens

Se precisar atualizar logos ou banners:

1. Substitua o arquivo em `assets/`
2. Mantenha o mesmo nome para evitar quebrar links
3. Ou atualize as referências no Markdown

## 📝 Convenções de Commit

Use Conventional Commits para manter um histórico limpo:

```
docs: atualiza README com novas informações
feat: adiciona nova seção de projetos
fix: corrige link quebrado
style: melhora formatação do código
chore: atualiza assets
```

## 🌟 Dicas

### SEO

Os README files do GitHub são indexados pelo Google. Use:

- Títulos descritivos (H1, H2, H3)
- Palavras-chave relevantes
- Alt text nas imagens
- Links internos e externos

### Acessibilidade

- Use alt text descritivo em todas as imagens
- Estruture o conteúdo com headings apropriados
- Evite usar apenas cores para transmitir informação

### Performance

- Otimize imagens antes de fazer commit (use WebP quando possível)
- Use badges apenas quando necessário
- Prefira texto a imagens quando possível

## 📞 Suporte

Para dúvidas ou sugestões sobre estes documentos:

- 📧 Email: [cezar@cwsoftware.com.br](mailto:cezar@cwsoftware.com.br)
- 💼 LinkedIn: [Cezar Wagenheimer](https://www.linkedin.com/in/cezar-wagenheimer/)

---

**Última atualização**: Janeiro 2026
