# 🛒 SyntaxWear - E-commerce de Tênis e Sneakers

![SyntaxWear Logo](./images/logo/logo.svg)

## 📋 Sobre o Projeto

**SyntaxWear** é um e-commerce moderno e responsivo especializado em tênis e sneakers. O projeto foi desenvolvido com foco em **design clean**, **experiência do usuário** e **acessibilidade**, oferecendo uma interface elegante para compra de calçados esportivos e casuais.

### 🎯 Objetivos
- Criar uma experiência de compra intuitiva e moderna
- Implementar design responsivo para todos os dispositivos  
- Garantir acessibilidade e usabilidade
- Desenvolver código limpo e bem estruturado

---

## 🚀 Tecnologias Utilizadas

### 🎨 Frontend
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna com Flexbox e Grid
- **JavaScript** - Interatividade e funcionalidades dinâmicas

### 🎯 Metodologias
- **Mobile First** - Design responsivo priorizando dispositivos móveis
- **CSS BEM** - Metodologia de nomenclatura de classes
- **Semantic HTML** - Marcação semântica para melhor SEO e acessibilidade

### 🔧 Ferramentas
- **Git** - Controle de versão
- **VS Code** - Editor de código
- **Google Fonts** - Tipografia (Ubuntu)

---

## 📁 Estrutura do Projeto

```
eccomerce-syntaxwear/
│
├── 📄 index.html              # Página principal
├── 📄 README.md               # Documentação do projeto
│
├── 🎨 css/                    # Arquivos de estilo
│   ├── reset.css             # Reset CSS (Andy Bell)
│   ├── variables.css         # Variáveis CSS e imports
│   ├── base.css              # Estilos base e componentes
│   ├── header.css            # Estilos do cabeçalho
│   ├── hero.css              # Estilos da seção hero
│   ├── product-category.css  # Estilos das categorias
│   ├── products-grid.css     # Estilos do grid de produtos
│   └── footer.css            # Estilos do rodapé
│
└── 🖼️ images/                 # Assets visuais
    ├── banners/              # Imagens de banner
    │   ├── hero.jpg         # Banner principal desktop
    │   └── hero-mobile.png  # Banner principal mobile
    │
    ├── products/             # Imagens de produtos
    │   ├── casual.jpg       # Categoria casual
    │   ├── esportivo.jpg    # Categoria esportiva
    │   ├── moderno.jpg      # Categoria moderna
    │   ├── futurista.jpg    # Categoria futurista
    │   └── ...              # Outras imagens de produtos
    │
    ├── icons/               # Ícones SVG
    │   ├── instagram.svg    # Ícone Instagram
    │   ├── facebook.svg     # Ícone Facebook
    │   ├── shopping-cart.svg # Ícone carrinho
    │   └── ...              # Outros ícones
    │
    ├── logo/                # Logo da marca
    │   └── logo.svg         # Logo principal
    │
    └── favicons/            # Favicons (pasta preparada)
```

---

## 🎨 Design e Layout

### 📱 Seções Principais

#### 🏠 **Header**
- Logo responsivo da SyntaxWear
- Navegação principal (Masculino, Feminino, Outlet)
- Menu secundário (Nossas lojas, Sobre, Ícones de ação)
- Design fixo com background blur

#### 🦸 **Hero Section**
- Banner full-width com call-to-action
- Imagens otimizadas para desktop e mobile
- Botões de ação destacados
- Overlay com gradiente para legibilidade

#### 👟 **Categorias de Produtos**
- Grid responsivo de categorias
- Cards visuais para cada estilo:
  - **Casual** - Para o dia a dia
  - **Esportivo** - Para atividades físicas  
  - **Moderno** - Design contemporâneo
  - **Futurista** - Tecnologia avançada

#### ⭐ **Grid de Produtos em Destaque**
- Layout em grid assimétrico
- Produtos destacados com diferentes tamanhos
- Hover effects e transições suaves
- Calls-to-action para cada produto

#### 📞 **Footer**
- Newsletter com campo de email
- Links organizados por categoria
- Redes sociais com ícones SVG
- Informações de copyright

### 🎨 **Paleta de Cores**
```css
:root {
  --cor-primaria: #6329A2;      /* Roxo principal */
  --cor-secundaria: #7c3aed;    /* Roxo hover */
  --cor-texto: #333333;         /* Texto principal */
  --cor-texto-claro: #ededed;   /* Texto claro */
  --cor-fundo: #ffffff;         /* Fundo branco */
  --cor-footer: #333333;        /* Fundo footer */
}
```

### 🔤 **Tipografia**
- **Família:** Ubuntu (Google Fonts)
- **Pesos:** 300, 400, 500, 700
- **Variações:** Normal e Itálico

---

## 🚀 Como Executar

### 📋 **Pré-requisitos**
- Navegador web moderno
- Editor de código (VS Code recomendado)
- Git (opcional)

### 💻 **Instalação**

1. **Clone o repositório:**
```bash
git clone https://github.com/psjoaopedro/eccomerce-syntaxwear.git
```

2. **Navegue até o diretório:**
```bash
cd eccomerce-syntaxwear
```

3. **Abra o projeto:**
```bash
# No VS Code
code .

# Ou abra o index.html diretamente no navegador
```

4. **Visualize no navegador:**
- Abra o arquivo `index.html` em qualquer navegador moderno
- Ou use uma extensão como **Live Server** no VS Code

---

## ⚡ Funcionalidades

### ✅ **Implementadas**
- [x] Design responsivo completo
- [x] Navegação intuitiva
- [x] Grid de produtos interativo
- [x] Footer com newsletter
- [x] Otimização de imagens
- [x] Acessibilidade (ARIA labels, semântica)
- [x] SEO otimizado

### 🔄 **Em Desenvolvimento**
- [ ] Carrinho de compras funcional
- [ ] Sistema de filtros
- [ ] Página de produto individual
- [ ] Sistema de checkout
- [ ] Integração com API de pagamento

### 🎯 **Próximas Funcionalidades**
- [ ] Área do usuário
- [ ] Wishlist
- [ ] Avaliações de produtos
- [ ] Chat de suporte
- [ ] Progressive Web App (PWA)

---

## 🎨 Padrões de Código

### 📐 **CSS**
- **Unidades:** Uso de `rem` para responsividade
- **Nomenclatura:** BEM methodology
- **Organização:** Arquivos separados por componente
- **Reset:** Andy Bell's Modern CSS Reset

### 🏗️ **HTML**
- **Semântica:** Tags semânticas (header, nav, main, section, footer)
- **Acessibilidade:** ARIA labels e alt texts
- **SEO:** Meta tags otimizadas

### 📱 **Responsividade**
- **Abordagem:** Mobile First
- **Breakpoints:** Flexíveis com CSS Grid e Flexbox
- **Imagens:** Otimizadas para diferentes resoluções

---

## 🤝 Contribuição

### 📋 **Como Contribuir**

1. **Fork o projeto**
2. **Crie uma branch para sua feature:**
```bash
git checkout -b feature/nova-funcionalidade
```
3. **Commit suas mudanças:**
```bash
git commit -m 'Adiciona nova funcionalidade'
```
4. **Push para a branch:**
```bash
git push origin feature/nova-funcionalidade
```
5. **Abra um Pull Request**

### 📝 **Guidelines**
- Siga os padrões de código existentes
- Teste em diferentes navegadores
- Mantenha a responsividade
- Documente mudanças significativas

---

## 📞 Contato

### 👨‍💻 **Desenvolvedor**
- **GitHub:** [@psjoaopedro](https://github.com/psjoaopedro)
- **LinkedIn:** [João Pedro](https://www.linkedin.com/in/jo%C3%A3o-pedro-pereira-da-silva-068079b8/)
- **Email:** joao@syntaxwear.com

### 🏢 **SyntaxWear**
- **Website:** [syntaxwear.com](https://syntaxwear.com)

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 🎯 Status do Projeto

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Versão](https://img.shields.io/badge/Versão-1.0.0-blue)
![Licença](https://img.shields.io/badge/Licença-MIT-green)

---

**⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!**

---

*Desenvolvido com 💜 por [João Pedro](https://github.com/psjoaopedro) - © 2025 SyntaxWear. Todos os direitos reservados.*
