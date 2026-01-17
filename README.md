# Curriculum Vitae

Um site elegante e responsivo de currículo criado com Jekyll, apresentando experiência profissional, habilidades técnicas, idiomas e educação.

## 🌐 Demo

Acesse em: [https://BentoCarlos.github.io](https://BentoCarlos.github.io)

## 📋 Conteúdo

O projeto inclui as seguintes seções:

- **Experiência Profissional** - Histórico de empregos com funções e principais projetos
- **Habilidades Técnicas** - Categorias de competências técnicas
- **Idiomas** - Idiomas e níveis de proficiência
- **Educação** - Formação acadêmica

## 🚀 Como Começar

### Pré-requisitos

- Ruby 2.7.0 ou superior
- Bundler

### Instalação

1. Clone ou faça download deste repositório:

```bash
git clone https://github.com/BentoCarlos/curriculumvitae.git
cd curriculumvitae
```

2. Instale as dependências:

```bash
bundle install
```

3. Execute o Jekyll:

```bash
bundle exec jekyll serve
```

O site estará disponível em `http://localhost:4000`

## 📁 Estrutura do Projeto

```
curriculumvitae/
├── _config.yml              # Configurações do Jekyll
├── _data/                   # Dados estruturados (YAML)
│   ├── education.yml        # Educação
│   ├── experience.yml       # Experiência profissional
│   ├── languages.yml        # Idiomas
│   └── skills.yml           # Habilidades técnicas
├── _includes/               # Componentes reutilizáveis
│   ├── footer.html
│   └── header.html
├── _layouts/                # Layouts HTML
│   └── curriculum.html      # Layout principal
├── assets/                  # Estilos CSS
│   ├── main.css
│   └── resume.css
├── Gemfile                  # Dependências Ruby
└── README.md               # Este arquivo
```

## 🎨 Personalizando

### Informações Pessoais

Edite o arquivo [_config.yml](_config.yml):

```yaml
title: Curriculum Vitae
email: seu-email@example.com
github_username: seu-usuario
full_name: "Seu Nome Completo"
linkedin_username: seu-usuario-linkedin
```

### Dados do Currículo

Todos os dados de conteúdo estão nos arquivos YAML em `_data/`:

- **[_data/experience.yml](_data/experience.yml)** - Adicione ou edite experiência profissional
- **[_data/skills.yml](_data/skills.yml)** - Adicione habilidades técnicas
- **[_data/languages.yml](_data/languages.yml)** - Adicione idiomas
- **[_data/education.yml](_data/education.yml)** - Adicione educação

### Estilos

Customize a aparência editando:

- [assets/main.css](assets/main.css) - Estilos gerais
- [assets/resume.css](assets/resume.css) - Estilos específicos do currículo

## 📱 Responsividade

O site é totalmente responsivo e funciona em dispositivos móveis, tablets e desktops.

## 🛠️ Tecnologias

- **Jekyll** - Static site generator
- **Minima** - Tema Jekyll padrão
- **HTML5** - Markup
- **CSS3** - Estilos
- **YAML** - Estrutura de dados

## 🌍 Deploy

O site está configurado para ser hospedado no GitHub Pages. Para fazer deploy:

1. Faça push das suas alterações para a branch `main`
2. O GitHub Pages construirá e publicará automaticamente

## 📝 Licença

Este projeto é de uso pessoal. Sinta-se à vontade para usar como base para seu próprio currículo.

## 👤 Autor

**Bento Carlos Silva dos Santos**

- Email: bc.santos@pm.me
- GitHub: [@BentoCarlos](https://github.com/BentoCarlos)
- LinkedIn: [bento-carlos-silva-dos-santos-1b9786128](https://linkedin.com/in/bento-carlos-silva-dos-santos-1b9786128)

## 💡 Dicas

- Use o comando `bundle exec jekyll build` para gerar apenas o site (sem iniciar servidor)
- O site compilado fica na pasta `_site/`
- Para alterar o tema, edite a variável `theme` no `_config.yml`

---

Desenvolvido com ❤️ usando Jekyll
