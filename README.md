# ✨ NeoUI - Design Micro-Interações / Neomorfismo

![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Neomorfismo](https://img.shields.io/badge/design-neumorphism-FF69B4)
![Micro-Interações](https://img.shields.io/badge/micro--interações-ativas-success)

## 📋 Sobre o Projeto

Este é um protótipo funcional de um site com **Design Micro-Interações / Neomorfismo**, desenvolvido a partir de um diagrama ASCII art. O projeto demonstra elementos que parecem "flutuar" ou ser "esculpidos" na tela, com sombras duplas e micro-interações, típico de apps modernos, produtos tech e startups inovadoras.

### 🎯 Características do Design

- Elementos com sombras duplas (relevo 3D)
- Ícones que parecem esculpidos na tela
- Cards com efeito "pulsante"
- Barra de progresso animada
- Botões com micro-interações (ripple, hover effects)
- Fundo neutro #e0e5ec (característico do neomorfismo)
- Sensação de profundidade sem cores vibrantes

## 🏗️ Estrutura do Site

```
+--------------------------------------------------------------------+
|                                                                    |
|     +--------------------------+                                   |
|     |                          |                                   |
|     |      ÍCONE 3D            |   ELEMENTOS COM                   |
|     |     COM SOMBRA           |   SOMBRA DUPLA                    |
|     |                          |   (relevo 3D)                     |
|     +--------------------------+                                   |
|                                                                    |
|  +-----+  +-----+  +-----+                                         |
|  |     |  |     |  |     |  CARDS COM EFEITO                       |
|  |  1  |  |  2  |  |  3  |  "PULSANTE"                            |
|  |     |  |     |  |     |                                         |
|  +-----+  +-----+  +-----+                                         |
|                                                                    |
|     [BARRA DE PROGRESSO ANIMADA]                                   |
|     =================================                              |
|                                                                    |
|     [BOTÃO COM MICRO-INTERAÇÃO]                                    |
|     (muda ao passar o mouse)                                       |
|                                                                    |
+--------------------------------------------------------------------+
```

## ✨ Funcionalidades Implementadas

### Ícone 3D com Sombra Dupla

- ✅ Ícone ⚡ em tamanho 80px
- ✅ Box-shadow: externa (12px) e interna (inset)
- ✅ Efeito hover: muda as sombras e escala
- ✅ Border-radius: 60px (formato arredondado)
- ✅ Cursor pointer com feedback

### Elementos com Sombra Dupla (Relevo 3D)

- ✅ 3 cards em relevo: "Design System", "Micro-Interações", "Neomorfismo"
- ✅ Ícones decorativos (🎨, ⚙️, ✨)
- ✅ Sombras externas e internas combinadas
- ✅ Efeito hover: sombras mais intensas
- ✅ Clicáveis com alertas

### Cards com Efeito "Pulsante"

- ✅ 3 cards numerados (1, 2, 3)
- ✅ Labels: NOVO, HOT, TOP
- ✅ Animação `softPulse` com escala 1.05
- ✅ Delays diferentes (0s, 0.5s, 1s)
- ✅ Hover interrompe animação e eleva card

### Barra de Progresso Animada

- ✅ Container com sombras internas (inset)
- ✅ Barra de preenchimento gradiente (roxo-azul)
- ✅ Animação `progressAnimation` de 0% a 78% em 3s
- ✅ Efeito `shimmer` deslizante na barra
- ✅ Label com percentual (78%)
- ✅ Clicável com alerta

### Botão com Micro-Interação

- ✅ Botão "INTERAGIR" com ícones ✨
- ✅ 3 estados: normal, hover, active
- ✅ Efeito ripple no hover (pseudo-elemento)
- ✅ Transform scale no active
- ✅ Transições suaves em todas propriedades

### ASCII Art Demonstrativo

- ✅ Representação fiel do diagrama no topo
- ✅ Estilo neomórfico também no ASCII (sombra interna)

### Rodapé Neomórfico

- ✅ Texto centralizado com sombras internas
- ✅ Créditos e descrição do conceito

## 🎨 Paleta de Cores (Neomorfismo)

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| Fundo Neutro | `#e0e5ec` | Base de todos elementos |
| Sombra Escura | `#a3b1c6` | Sombras externas/inset escuras |
| Sombra Clara | `#ffffff` | Sombras externas/inset claras |
| Texto Escuro | `#4a5a6e` | Textos principais |
| Texto Mais Escuro | `#2c3e50` | Números dos cards |
| Gradiente Roxo | `#667eea` a `#764ba2` | Barra de progresso |

## 📱 Responsividade

O design neomórfico se adapta:

- **Desktop:** Layout completo com ícone grande (200px)
- **Tablet:** Ícone reduz para 150px, cards mantêm proporção
- **Mobile (< 768px):**
  - Ícone 150px
  - Cards pulsantes 90px
  - Botão com padding reduzido
  - Tudo centralizado

## 🔗 Links e Navegação

| Elemento | Ação (alerta) |
|----------|---------------|
| Ícone 3D (⚡) | "Ícone 3D clicado - Efeito neomórfico" |
| Relevo Design System | "Elemento em relevo: Design System" |
| Relevo Micro-Interações | "Elemento em relevo: Micro-Interações" |
| Relevo Neomorfismo | "Elemento em relevo: Neomorfismo" |
| Card 1 | "Card 1 - Efeito pulsante" |
| Card 2 | "Card 2 - Efeito pulsante" |
| Card 3 | "Card 3 - Efeito pulsante" |
| Barra de progresso | "Barra de progresso: 78% concluído" |
| Botão INTERAGIR | "Botão com micro-interação! Efeito ripple simulado" |

## 🚀 Como Executar

1. Clone este repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Passe o mouse sobre os elementos para ver as micro-interações
4. Clique em cada componente para feedback
5. Observe as animações pulsantes e a barra de progresso
6. Redimensione a tela para testar responsividade

## 💻 Tecnologias Utilizadas

- **HTML5 semântico** - Estrutura limpa
- **CSS3 Avançado:**
  - **Box-shadow dupla** (externa + interna) para efeito neomórfico
  - **Animações keyframes** (softPulse, progressAnimation, shimmer)
  - **Gradientes** na barra de progresso
  - **Transitions** para micro-interações suaves
  - **Pseudo-elementos** (::before, ::after) para ripple e shimmer
  - **Flexbox** para alinhamentos
  - **Border-radius** para elementos orgânicos
  - **Media queries** para responsividade
- **JavaScript mínimo** - Ripple manual e alertas
- **Design System** - Consistência visual neomórfica

## 📊 Animações Detalhadas

| Animação | Elemento | Duração | Efeito |
|----------|----------|---------|--------|
| softPulse | Cards | 3s | Escala 1.05 com delay |
| progressAnimation | Barra | 3s | Preenche até 78% |
| shimmer | Barra | 2s | Brilho deslizante |
| ripple | Botão | 0.6s | Efeito de onda (JS) |

## 📌 Técnicas de Neomorfismo

| Técnica | Implementação |
|---------|----------------|
| Sombra externa dupla | `box-shadow: 12px 12px 24px #a3b1c6, -12px -12px 24px #ffffff` |
| Sombra interna (inset) | `box-shadow: inset 5px 5px 10px #a3b1c6, inset -5px -5px 10px #ffffff` |
| Relevo 3D | Combinação de sombras externas e internas |
| Estado pressionado | Aumento de sombras internas no hover/active |
| Fundo neutro | `#e0e5ec` - tom médio para contraste das sombras |

## 📌 Casos de Uso

Este template é ideal para:

- **Apps modernos** - Interfaces limpas e táteis
- **Produtos tech** - Dashboards, configurações
- **Startups inovadoras** - Landing pages diferenciadas
- **Design systems** - Componentes base
- **Portfólios criativos** - Apresentação de conceitos
- **Prototipação** - Demonstração de interações

## 🧩 Diferenciais

- ✅ **Neomorfismo autêntico** - Sombras duplas em todos elementos
- ✅ **Cards pulsantes** - 3 animações com delays diferentes
- ✅ **Barra de progresso com shimmer** - Efeito profissional
- ✅ **Botão com ripple** - Micro-interação avançada
- ✅ **Ícone 3D interativo** - Muda sombras no hover
- ✅ **Relevos clicáveis** - 3 cards informativos
- ✅ **ASCII art integrado** ao design neomórfico
- ✅ **Sem dependências externas** - CSS/JS puro

## 🧪 Validação do ASCII Art

| Elemento ASCII | Implementação |
|----------------|---------------|
| ÍCONE 3D COM SOMBRA | ✅ Ícone ⚡ com sombras duplas |
| ELEMENTOS COM SOMBRA DUPLA | ✅ 3 relevos com ícones |
| CARDS COM EFEITO PULSANTE | ✅ 3 cards com animação |
| BARRA DE PROGRESSO ANIMADA | ✅ Barra com shimmer e label 78% |
| BOTÃO COM MICRO-INTERAÇÃO | ✅ Botão com ripple e hover |

## 👨‍💻 Autor

Desenvolvido como demonstração de design neomórfico com micro-interações baseado em diagrama ASCII art por Daniel Gehlen.

---

## 📝 Notas de Versão

### v1.0.0 (24/02/2026)

- ✅ Implementação completa do design ASCII art
- ✅ Ícone 3D com sombras externas e internas
- ✅ 3 relevos com ícones e efeito hover
- ✅ 3 cards pulsantes com delays
- ✅ Barra de progresso animada até 78% com shimmer
- ✅ Botão com ripple, hover e active states
- ✅ Todos elementos clicáveis
- ✅ Design responsivo
- ✅ Estética neomórfica consistente

### Próximas Melhorias (Sugestões)

- [ ] Mais cards com diferentes animações
- [ ] Toggle light/dark mode (mantendo neomorfismo)
- [ ] Sliders neomórficos
- [ ] Inputs e formulários com relevo
- [ ] Loading spinners neomórficos
- [ ] Mais micro-interações (vibration, shake)
- [ ] Componentes para biblioteca UI

---

**📅 Última atualização:** 24 de Fevereiro de 2026
