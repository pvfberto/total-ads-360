# Total Ads 360º - Landing Page Deployment

Este repositório contém a landing page do curso "Total Ads 360º" pronta para deploy no CloudFlare Pages.

## 📁 Estrutura

```
/landing-page    # Código fonte da landing page (React + Vite + Tailwind)
```

## 🚀 Deploy no CloudFlare Pages

### Configurações de Build:

- **Framework preset:** Vite
- **Build command:** `npm run build`
- **Build output directory:** `dist`
- **Root directory:** `landing-page`
- **Node version:** 18 ou superior

### Passos para Deploy:

1. Acesse [CloudFlare Pages](https://pages.cloudflare.com/)
2. Conecte este repositório GitHub
3. Configure as seguintes opções:
   - **Project name:** total-ads-360 (ou nome de sua preferência)
   - **Production branch:** `claude/clone-test-repo-01KB298BWJQKP5iy4yGT9VCi`
   - **Root directory:** `landing-page`
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Clique em "Save and Deploy"

### Variáveis de Ambiente (opcional):

Não são necessárias variáveis de ambiente para esta landing page.

## 📋 Requisitos

A landing page requer as seguintes imagens na pasta `landing-page/public/assets/`:

1. sessao_1.png - Hero image
2. sessao_4.png - Infográfico Andromeda
3. sessao_5.png - Foto Paulo Berto
4. sessao_6.png - Diagrama Framework
5. sessao_7_aluno_1.png até sessao_7_aluno_5.png - Fotos depoimentos
6. sessao_11.png - Infográfico Antes/Depois
7. sessao_14.png - Selo de Garantia

## 🔄 Desenvolvimento Local

```bash
cd landing-page
npm install
npm run dev
```

## 📦 Build Manual

```bash
cd landing-page
npm run build
# Arquivos de produção em: landing-page/dist/
```

## 📖 Documentação Completa

Consulte `landing-page/README.md` para documentação detalhada do projeto.
