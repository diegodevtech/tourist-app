# 🌏 Tourist App

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)
![Accessibility](https://img.shields.io/badge/A11y-WCAG%202.1-green?style=for-the-badge)

**Uma experiência web moderna e acessível para descobrir os melhores destinos. Estrelando: Busan, Coreia do Sul** ✨

[🚀 Demo](#-demonstração) • [📋 Características](#-características) • [🛠️ Tecnologias](#️-tecnologias) • [🚀 Como Usar](#-como-usar) • [📱 Responsividade](#-responsividade) • [♿ Acessibilidade](#-acessibilidade)

</div>

## 📖 Sobre o Projeto

**Tourist App** é uma aplicação web estática elegante e moderna que apresenta os principais destinos turísticos. O projeto foi desenvolvido com foco em **design limpo**, **acessibilidade** e **performance**, oferecendo uma experiência imersiva para viajantes que desejam explorar culturais únicas.

### 🎯 Objetivo

Criar uma plataforma informativa e visualmente atraente que inspire pessoas a viajar, destacando três destinos imperdíveis com informações detalhadas, categorização por tags para o destino desejado, contanto também com design responsivo que funciona perfeitamente em qualquer dispositivo.

---

## ✨ Características

### 🎨 Design Moderno
- ✨ Interface limpa e minimalista
- 🎨 Paleta de cores harmoniosa com CSS Variables
- 📐 Layout responsivo com breakpoints otimizados
- 🖼️ Imagens otimizadas com lazy loading
- 🎯 Tipografia fluida com `clamp()` para escalabilidade perfeita

### 📱 Totalmente Responsivo
- 💻 **Desktop**: Layout espaçoso com máximo de 1280px
- 📱 **Tablet**: Adaptação automática para telas médias
- 📱 **Mobile**: Design otimizado para smartphones (480px+)
- 🖨️ **Print**: Estilos específicos para impressão

### ♿ Acessibilidade de Primeira Classe
- ⌨️ **Skip Links** para navegação por teclado
- 🏷️ **ARIA Labels** em todos os elementos interativos
- 🎯 **Semantic HTML5** para melhor compreensão por leitores de tela
- 🎨 **High Contrast Mode** suportado
- 🎬 **Reduced Motion** respeitado para usuários sensíveis a animações
- 📝 **Alt Text** descritivo em todas as imagens

### 🏷️ Sistema de Tags Inteligente
Cada atração é categorizada com tags coloridas:
- 🔵 **História** - Para amantes de cultura e tradição
- 💜 **Casais** - Destinos românticos perfeitos
- 💗 **Famílias** - Atrações ideais para todas as idades
- 🟠 **Orçamento** - Opções econômicas e acessíveis

### ⚡ Performance Otimizada
- 🚀 **Lazy Loading** de imagens para carregamento rápido
- 📦 **CSS Puro** - Zero dependências externas
- 🎯 **Código Limpo** - Organizado e mantível
- 🔧 **CSS Variables** - Fácil customização de temas

---

## 🛠️ Tecnologias

Este projeto foi construído utilizando apenas tecnologias web nativas:

| Tecnologia | Versão | Uso |
|------------|--------|-----|
| **HTML5** | Latest | Estrutura semântica e acessível |
| **CSS3** | Latest | Estilização moderna com variáveis CSS |
| **CSS Variables** | - | Sistema de design consistente |
| **Media Queries** | - | Responsividade em múltiplos dispositivos |
| **Semantic HTML** | - | Acessibilidade e SEO |

### 🎨 Recursos CSS Avançados Utilizados

- ✅ **CSS Custom Properties** (Variáveis CSS)
- ✅ **Flexbox** para layouts flexíveis
- ✅ **Clamp()** para tipografia responsiva
- ✅ **Object-fit** para imagens
- ✅ **Media Queries** para breakpoints
- ✅ **Print Media Queries** para impressão
- ✅ **Prefers-reduced-motion** para acessibilidade
- ✅ **Prefers-contrast** para alto contraste

---

## 🚀 Como Usar

### 📥 Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/diegodevtech/tourist-app.git
   cd tourist-app
   ```

2. **Abra o projeto**
   ```bash
   # Simplesmente abra o index.html no seu navegador
   open index.html
   # ou
   # Use um servidor local (recomendado)
   python -m http.server 8000
   # ou
   npx serve
   # ou use a extensão Live Server direto em sua IDE
   ```

3. **Acesse no navegador**
   ```
   http://localhost:8000
   ```
   ou
   ```bash
   http://localhost:5500 
   # se utilizando o Live Server
   ```

### 📁 Estrutura do Projeto

```
tourist-app/
│
├── 📄 index.html          # Página principal
├── 🎨 style.css           # Estilos e variáveis CSS
├── 📁 assets/             # Imagens e recursos
│   ├── Image_01.jpg      # Vista aérea de Busan
│   ├── Image_02.jpg      # Templo Haedong Yonggungsa
│   ├── Image_03.jpg      # Templo Beomeo-sa
│   └── Image_04.jpg      # Parque Yongdusan
└── 📖 README.md          # Este arquivo
```

---

## 📱 Responsividade

O projeto foi desenvolvido com uma abordagem **mobile-first**, garantindo uma experiência perfeita em todos os dispositivos:

### 📐 Breakpoints

| Dispositivo | Largura | Características |
|-------------|---------|-----------------|
| 📱 **Mobile** | < 480px | Layout compacto, imagens menores |
| 📱 **Tablet** | 481px - 768px | Layout intermediário |
| 💻 **Desktop** | > 768px | Layout completo com espaçamento otimizado |

### 🎯 Recursos Responsivos

- ✅ Tipografia fluida com `clamp()`
- ✅ Imagens adaptáveis com `object-fit`
- ✅ Espaçamento dinâmico baseado em viewport
- ✅ Navegação otimizada para touch
- ✅ Layout flexível com Flexbox

---

## ♿ Acessibilidade

Este projeto segue as diretrizes **WCAG 2.1** e implementa as melhores práticas de acessibilidade:

### ✅ Recursos Implementados

- **Skip Links**: Permite pular para o conteúdo principal
- **ARIA Labels**: Descrições para leitores de tela
- **Semantic HTML**: Uso correto de `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **Alt Text**: Descrições detalhadas em todas as imagens
- **Keyboard Navigation**: Navegação completa via teclado
- **High Contrast**: Suporte para modo de alto contraste
- **Reduced Motion**: Respeita preferências de movimento reduzido
- **Focus Indicators**: Indicadores visuais claros para foco

### 🎯 Níveis de Conformidade

- ✅ **Nível A**: Conformidade básica
- ✅ **Nível AA**: Conformidade recomendada (alvo principal)
- 🎯 **Nível AAA**: Alguns recursos implementados

---

## 🎨 Sistema de Design

### 🎨 Paleta de Cores

```css
--color-primary: #1B1B1B      /* Preto principal */
--color-secondary: #333       /* Cinza escuro */
--color-accent: #E1624F      /* Laranja/coral de destaque */
--color-tag-history: #0C51A7 /* Azul para História */
--color-tag-couples: #591B98  /* Roxo para Casais */
--color-tag-families: #E5245E /* Rosa para Famílias */
--color-tag-budget: #E95E10   /* Laranja para Orçamento */
```

### 📏 Espaçamento

O projeto utiliza um sistema de espaçamento consistente baseado em múltiplos de `0.25rem`:

- `--spacing-xs`: 0.25rem
- `--spacing-sm`: 0.5rem
- `--spacing-md`: 1rem
- `--spacing-lg`: 1.5rem
- `--spacing-xl`: 2.5rem
- `--spacing-2xl`: 4rem
- `--spacing-3xl`: 5.5rem

### 🔤 Tipografia

- **Fonte**: Lucida Sans (fallback para sistema)
- **Tamanhos**: Utilizando `clamp()` para responsividade fluida
- **Line Height**: 1.5 (base) e 1.3 (tight)

---

## 🌟 Destaques Técnicos

### 🎯 Melhores Práticas Implementadas

1. **CSS Variables** para fácil manutenção e customização
2. **Mobile-First** approach para melhor performance
3. **Semantic HTML** para SEO e acessibilidade
4. **Lazy Loading** de imagens para otimização
5. **Print Styles** para impressão profissional
6. **Progressive Enhancement** garantindo funcionamento básico sempre

### 🚀 Performance

- ⚡ **Zero JavaScript** - Carregamento instantâneo
- 📦 **CSS Puro** - Sem dependências externas
- 🖼️ **Lazy Loading** - Imagens carregam sob demanda
- 🎯 **Otimização de Imagens** - Tamanhos apropriados definidos

---

### 🎬 Funcionalidades Visuais

- ✨ Transições suaves
- 🎨 Tags coloridas por categoria
- 📐 Layout responsivo fluido
- 🖼️ Imagens com bordas arredondadas
- 📱 Adaptação automática de espaçamento

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

1. 🍴 Fazer um Fork do projeto
2. 🌿 Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push para a branch (`git push origin feature/AmazingFeature`)
5. 🔀 Abrir um Pull Request

### 📝 Padrões de Código

- ✅ Use HTML5 semântico
- ✅ Siga a convenção de nomes CSS existente
- ✅ Mantenha a acessibilidade em mente
- ✅ Teste em múltiplos navegadores
- ✅ Verifique responsividade em diferentes dispositivos

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

<div align="center">

### ⭐ Se este projeto foi útil para você, considere dar uma estrela! ⭐

**Feito com ❤️ por Diegodevtech**

</div>
