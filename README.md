# TOTAL ADS 360º - Landing Page

Landing page de alta conversão para o curso "Total Ads 360º - Curso de Anúncios Inteligentes".

## 🚀 Tecnologias

- **React 18** com TypeScript
- **Vite** - Build tool
- **Tailwind CSS** - Estilização
- **Framer Motion** - Animações
- **Swiper** - Slider de depoimentos

## 📦 Deploy no CloudFlare Pages

### Configurações de Build:

```
Framework preset:      Vite
Build command:         npm run build
Build output:          dist
Node version:          18 ou superior
```

### Passo a passo:

1. Acesse [CloudFlare Pages](https://pages.cloudflare.com/)
2. Clique em **Create a project**
3. Conecte este repositório GitHub
4. Configure:
   - **Production branch:** `claude/clone-test-repo-01KB298BWJQKP5iy4yGT9VCi`
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
5. Clique em **Save and Deploy**

## 🔧 Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Rodar em modo desenvolvimento
npm run dev

# Build para produção
npm run build

# Preview do build
npm run preview
```

## 📁 Estrutura do Projeto

```
/src
  /components      # Componentes reutilizáveis
    - CTAButton.tsx
    - CountdownTimer.tsx
    - Footer.tsx
  /sections        # Seções da landing page (1-15)
    - Section1Hero.tsx
    - Section2Validation.tsx
    - ... (até Section15FinalChoice.tsx)
  /hooks           # Custom hooks
    - useCountdown.ts
  - App.tsx        # Componente principal
  - index.css      # Estilos globais e Tailwind
  - main.tsx       # Entry point

/public
  /assets          # Imagens da landing page
```

## 🎨 Design

### Paleta de Cores:
- **Background principal:** `#111111` (preto intenso)
- **Background secundário:** `#191919` (grafite escuro)
- **Dourado:** `#B8860B` → `#F0E68C` (gradiente)
- **Texto principal:** `#FFFFFF`
- **Texto secundário:** `#F3EFE0`

### Tipografia:
- **Fontes:** Inter e Poppins
- **Títulos:** 48-64px (desktop), 32-40px (mobile)
- **Corpo:** 18px (desktop), 16px (mobile)

## 📱 Responsividade

A landing page é totalmente responsiva (mobile-first):

- **Mobile:** < 640px
- **Tablet:** 640px - 1024px
- **Desktop:** > 1024px

## ⚡ Performance

- Lazy loading de imagens
- Animações otimizadas com GPU
- Build otimizado com Vite
- Code splitting automático

## 🎯 Seções da Landing Page

1. **Hero** - Above the fold com headline e CTA
2. **Validação da Dor** - Pain points do público
3. **Consequências** - Agitação da dor
4. **Andromeda** - A causa raiz do problema
5. **Revelação** - Apresentação Paulo Berto
6. **Framework EM-SA** - Explicação do método
7. **Depoimentos** - Prova social com slider
8. **Produto** - Apresentação do curso
9. **Diferenciais** - Diferenciais pedagógicos
10. **Incluso** - O que está incluído
11. **Resultados** - Resultados esperados
12. **Autoridade** - Credenciais
13. **Oferta** - Preço e countdown
14. **Garantia** - Garantia incondicional
15. **Escolha Final** - Última chamada + CTA

## 🔄 Countdown Timer

O countdown está configurado para 7 dias a partir da data atual. Para alterar:

```typescript
// Em src/sections/Section13Offer.tsx
const targetDate = new Date();
targetDate.setDate(targetDate.getDate() + 7); // Altere aqui
```

## 📝 Customização

### Alterar textos:
Cada seção é um componente separado em `/src/sections/`. Edite o componente correspondente.

### Alterar cores:
Edite `tailwind.config.js` para modificar a paleta de cores.

### Adicionar/remover seções:
1. Crie/remova o componente em `/src/sections/`
2. Importe/remova em `App.tsx`

## 🐛 Troubleshooting

### Erros de build:
```bash
# Limpar cache e reinstalar
rm -rf node_modules package-lock.json
npm install
npm run build
```

## 📄 Licença

Todos os direitos reservados © 2024 Total Ads 360º

## 👨‍💻 Desenvolvimento

Desenvolvido com Claude Code seguindo especificações de design moderno, minimalista e focado em conversão.
