# Portal de Noticias Vale do Sul

README.md

# 📰 Portal Vale do Sul

> Status do Projeto: 🚀 Em desenvolvimento ( Arquitetura e Layout)
> 

O **Vale do Sul** é um portal de notícias regional focado em alta legibilidade, organização de informação e credibilidade. Este projeto foi concebido para centralizar e organizar os fatos da região em uma plataforma robusta, combatendo a desinformação com uma interface inspirada na hierarquia visual dos grandes periódicos globais.

---

## 🎯 Objetivo do Projeto

Demonstrar domínio sólido dos **Fundamentos Web** (Vanilla JS, HTML5 Semântico e CSS Avançado com Sass), aplicando padrões de arquitetura de software e metodologias de nomenclatura que garantam a manutenção do código em projetos de longo prazo.

## 🛠️ Tecnologias e Metodologias

- **HTML5 Semântico:** Estrutura focada em SEO e acessibilidade (A11y).
- **Sass (SCSS):** Pré-processamento de estilos com arquitetura modular e variáveis.
- **JavaScript Vanilla (ES6+):** Manipulação nativa do DOM e lógica de renderização sem frameworks.
- **BEM (Block, Element, Modifier):** Metodologia de nomenclatura para um CSS escalável e organizado.
- **Mobile First:** Priorização do consumo de notícias via dispositivos móveis.

---

## 🏗️ Arquitetura e Organização

O projeto segue uma estrutura de pastas organizada por responsabilidades, facilitando a escalabilidade:

Plaintext

`vale-do-sul/              
├── src/
│   ├── assets/            # Imagens, ícones e recursos visuais
│   ├── data/              # Notícias e base de dados (noticias.js)
│   ├── scripts/           # Funções de manipulação do DOM e utilitários
│   ├── styles/            # Arquivos-fonte Sass (.scss) organizados por módulos
│   │   ├── variables/     # Definições de cores, fontes e espaçamentos
│   │   ├── base/          # Reset de estilos e tipografia global
│   │   ├── components/    # Componentes independentes (cards, botões)
│   │   ├── layout/        # Grandes blocos estruturais (header, grid)
│   │   └── main.scss      # Arquivo centralizador de imports
│   ├── style.css          # CSS compilado e interpretado pelo navegador
│   └── main.js            # Arquivo principal que orquestra a aplicação
├── index.html             # Estrutura HTML única do portal
└── README.md              # Guia técnico do projeto`

---

## 📜 Padrão de Commits

Para manter um histórico de alterações limpo e profissional, utilizamos o padrão **Conventional Commits**:

- `feat`: Adição de novas funcionalidades ou componentes.
- `style`: Ajustes de design, cores e CSS/Sass.
- `fix`: Correção de bugs ou ajustes de comportamento.
- `docs`: Melhorias na documentação e README.
- `chore`: Configurações de pastas e tarefas de manutenção.



---

## 🚀 Como Executar o Projeto

1. **Clonar o repositório:**Bash
    
    `git clone https://github.com/seu-usuario/vale-do-sul-portal.git`
    
2. **Compilar o Sass:**Bash
    - Este projeto utiliza **Sass** puro. Para refletir alterações de estilo, utilize a extensão **Live Sass Compiler** no VS Code (clique em `Watch Sass`) ou execute o comando:
    
    `sass --watch src/styles/main.scss:src/style.css`
    
3. **Visualizar no Navegador:**
    - Abra o arquivo `index.html` utilizando a extensão **Live Server** para visualização em tempo real.

---

## 👨‍💻 Autor

Desenvolvido por **Felipe Luan** como projeto central do plano de migração de carreira para Desenvolvimento Front-end.