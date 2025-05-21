# Dois Irmãos Marmoraria 🏛️

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
  <img src="https://img.shields.io/badge/Bootstrap_Icons-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap Icons"/>
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-tecnologias">Tecnologias</a> •
  <a href="#-funcionalidades">Funcionalidades</a> •
  <a href="#-como-iniciar">Como Iniciar</a> •
  <a href="#-estrutura-do-projeto">Estrutura do Projeto</a> •
  <a href="#-como-contribuir">Como Contribuir</a> •
  <a href="#-autor">Autor</a> •
  <a href="README_EN.md">English</a>
</p>

## 📋 Sobre o Projeto

Um site institucional elegante e responsivo para a **Dois Irmãos Marmoraria**, empresa especializada em produtos de mármore e granito de alta qualidade. O projeto demonstra as melhores práticas em desenvolvimento web moderno, combinando design estético com experiência de usuário funcional.

O site apresenta um layout sofisticado com elementos interativos como sliders automáticos de imagens e carrosséis de produtos, projetados para destacar a beleza e o artesanato das aplicações de mármore e granito em diversos ambientes.

## 🚀 Tecnologias

Este projeto utiliza diversas tecnologias web modernas:

- **HTML5** - Marcação semântica para estruturação de conteúdo
- **CSS3** - Estilização avançada com flexbox e design responsivo
- **JavaScript (Vanilla)** - Elementos interativos personalizados sem frameworks
- **Tailwind CSS** - Framework CSS utilitário com configuração personalizada
- **GSAP & ScrollTrigger** - Biblioteca de animação para efeitos de rolagem suaves
- **Bootstrap Icons** - Biblioteca abrangente de ícones
- **Integração com Google Maps** - Incorporação de localização

## ✨ Funcionalidades

### 1. Cabeçalho Responsivo com Navegação
- Menu fixo no topo com rolagem suave para seções
- Menu retrátil adaptado para dispositivos móveis
- Fundo dinâmico que se expande durante a rolagem

### 2. Hero Section com Efeito Parallax
- Imagem em tela cheia com efeito parallax na rolagem
- Elegante sobreposição de gradiente
- Botão de chamada para ação em destaque

### 3. Carrossel de Produtos Interativo
- Carrossel personalizado exibindo 3 produtos por vez
- Controles de navegação (botões anterior/próximo)
- Indicadores de pontos para posição do slide
- Rotação automática com tempo configurável

### 4. Seção de Perfil da Empresa
- Apresentação elegante dos valores e história da empresa
- Layout de conteúdo otimizado para todos os tamanhos de dispositivos

### 5. Integração de Localização
- Incorporação do Google Maps para localização física da loja
- Informações de contato com elementos clicáveis

### 6. Opções de Contato Direto
- Integração com WhatsApp para comunicação instantânea
- Botão de contato na seção inicial
- Botão flutuante para contato no whatsapp

### 7. Rodapé Profissional
- Informações da empresa e links de navegação
- Integração com redes sociais
- Informações de direitos autorais

## 🔧 Como Iniciar

### Pré-requisitos
- Qualquer navegador web moderno
- Conhecimento básico de desenvolvimento web (para modificações)
- Node.js e npm (opcional, para desenvolvimento com Tailwind CSS)

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/dois-irmaos-marmoraria.git
```

2. Navegue até o diretório do projeto:
```bash
cd dois-irmaos-marmoraria
```

3. Abra o arquivo `index.html` no seu navegador:
```bash
# No macOS
open index.html

# No Linux
xdg-open index.html

# No Windows
start index.html
```

### Desenvolvimento com Tailwind CSS (Opcional)

1. Instale as dependências:
```bash
npm install
```

2. Execute o processo de build do Tailwind CSS:
```bash
npx tailwindcss -i ./css/tailwind.css -o ./css/tailwind-build.css --watch
```

## 📁 Estrutura do Projeto

```
dois-irmaos-marmoraria/
├── assets/
│   ├── images/
│   │   ├── homepage/
│   │   │   ├── hero-image.jpg
│   │   │   ├── Cuba-esculpida.jpg
│   │   │   └── ...
│   │   └── logo.png
├── css/
│   ├── index.css
│   ├── tailwind-build.css
│   └── tailwind.css
├── scripts/
│   └── utils.js
├── index.html
├── index.js
├── tailwind.config.js
└── README.md
```

## 🔍 Detalhes Técnicos

### Componentes JavaScript Personalizados

O projeto inclui vários componentes JavaScript personalizados:

- **Classe SlideShow**: Gerencia a funcionalidade do carrossel com rotação automática configurável
- **Classe Modal**: Manipula diálogos popup para informações e formulários
- **Classe Dropdown**: Controla o comportamento do menu suspenso
- **Efeitos Parallax**: Efeitos de rolagem personalizados para a imagem principal

### Configuração do Tailwind CSS

O projeto utiliza uma configuração personalizada do Tailwind CSS:

- Prefixo personalizado (`tw-`) para evitar conflitos com outros CSS
- Paleta de cores estendida com cores da marca
- Breakpoints responsivos para vários tamanhos de dispositivos

### Otimizações de Desempenho

- Carregamento lazy para imagens
- Manipulação eficiente do DOM
- Carregamento otimizado de assets

## 👥 Como Contribuir

Contribuições são bem-vindas! Veja como você pode ajudar:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/recurso-incrivel`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona um recurso incrível'`)
4. Envie para a branch (`git push origin feature/recurso-incrivel`)
5. Abra um Pull Request

## 👨‍💻 Autor

**Estêvão Segatto Vieira**  
Desenvolvedor Full Stack | Especialista em APIs e Interfaces Responsivas

---

<p align="center">
  Feito com ❤️ para Dois Irmãos Mármore e Granito
</p>
