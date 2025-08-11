# Ivox Scale - Assessoria em Marketing Digital

Site moderno e responsivo para agência de marketing digital com tema claro/escuro, suporte a múltiplos idiomas (PT-BR/EN) e design profissional.

## 🚀 Características

- ✅ **Design Responsivo**: Otimizado para desktop, tablet e mobile
- ✅ **Tema Claro/Escuro**: Alternância suave com persistência local
- ✅ **Múltiplos Idiomas**: Português (Brasil) e Inglês (US)
- ✅ **Performance Otimizada**: Imagens SVG locais, CSS otimizado
- ✅ **SEO Friendly**: Meta tags, sitemap, robots.txt
- ✅ **Acessibilidade**: Navegação por teclado, contraste adequado
- ✅ **Animações Modernas**: Transições suaves e efeitos visuais

## 🛠️ Tecnologias

- **React 18** + **TypeScript**
- **Vite** para build e desenvolvimento
- **Tailwind CSS** para estilização
- **Radix UI** componentes acessíveis
- **Wouter** para roteamento
- **Lucide React** para ícones

## 📦 Deploy

### Para Netlify

O projeto já está configurado para deploy direto na Netlify:

1. Conecte seu repositório à Netlify
2. As configurações estão no arquivo `netlify.toml`
3. Diretório de publicação: `dist/public`
4. Comando de build: `npm run build`

### Para outras plataformas

```bash
# Build do projeto
npm run build

# Os arquivos estarão em dist/public/
```

## 🏃‍♂️ Executar Localmente

```bash
# Instalar dependências
npm install

# Executar em modo desenvolvimento
npm run dev

# Build de produção
npm run build
```

## 📁 Estrutura

```
client/
├── src/
│   ├── components/     # Componentes React
│   ├── contexts/       # Contextos (Tema, Idioma)
│   ├── hooks/          # Hooks personalizados
│   ├── data/           # Traduções e dados
│   ├── assets/         # Imagens SVG locais
│   └── pages/          # Páginas da aplicação
├── public/
│   ├── _redirects      # Configuração SPA
│   ├── robots.txt      # SEO
│   └── sitemap.xml     # SEO
└── index.html

netlify.toml            # Configuração Netlify
```

## 🎨 Personalização

### Cores e Tema

As cores são definidas em `client/src/index.css` usando CSS custom properties para suporte completo a modo escuro.

### Traduções

Adicione novas traduções em `client/src/data/translations.ts` para ambos os idiomas (pt/en).

### Seções

Cada seção do site está em um componente separado em `client/src/components/`.

## 📝 Licença

MIT License - Projeto desenvolvido para Ivox Scale.