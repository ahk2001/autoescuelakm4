# 🚗 Autoescuela KM4 Benimaclet (Valencia)

> Landing page profissional e de alta conversão para a **Autoescuela KM4**, localizada em Benimaclet (Valencia, Espanha). Foco em obtenção do Carnet de Coche B, superação de amaxofobia, cursos intensivos e preparação com professores qualificados.

---

## 🌟 Principais Recursos

- **Design Premium & Moderno**: Interface em modo dark/moderno, com microinterações, glassmorphism e tipografia refinada.
- **Performance de Alto Desempenho**: Assets otimizados (WebP e PNGs comprimidos), carregamento assíncrono e estrutura leve (< 5 MB).
- **SEO & Meta Tags**: Configurações completas de Open Graph, Schema, tags canônicas, `robots.txt` e `sitemap.xml`.
- **Deploy Automatizado**: Configurado com GitHub Actions para publicação contínua e segura no GitHub Pages.
- **Segurança & Boas Práticas**: Proteção contra MIME-sniffing, diretivas seguras de links externos (`rel="noopener"`) e higienização de assets.

---

## 📁 Estrutura do Projeto

```text
km4/
├── .github/
│   └── workflows/
│       └── deploy.yml          # Pipeline CI/CD automática para GitHub Pages
├── assets/                     # Recursos visuais e scripts de interface estritamente utilizados
│   ├── aprobado-[1-5].png      # Depoimentos e aprovações reais de alunos
│   ├── carro.png               # Imagem em destaque do veículo da autoescola
│   ├── fachada.webp            # Fachada oficial da unidade em Benimaclet
│   ├── favicon.webp            # Ícone de favoritos oficial
│   ├── feature-*.webp          # Ícones informativos de benefícios e diferenciais
│   ├── irene-profesora-alumna.png
│   ├── logo.png                # Logomarca oficial da KM4
│   └── wave-gradient.js        # Script de gradiente e animações fluidas
├── docs/                       # Documentação interna de pesquisa e dados operacionais
│   ├── dados.txt               # Contatos, endereços e links públicos
│   └── dossie_autoescola.md    # Dossiê de mercado, diferenciais e estratégia
├── .gitignore                  # Regras de exclusão e segurança para Git
├── index.html                  # Landing page completa, semântica e responsiva
├── README.md                   # Documentação do repositório
├── robots.txt                  # Diretrizes para indexadores e mecanismos de busca
└── sitemap.xml                 # Mapa do site para indexação no Google
```

---

## 🚀 Como Executar Localmente

Como se trata de um projeto estático moderno (HTML5, CSS3, JavaScript):

1. **Via VS Code / Extensão**:
   - Abra a pasta no VS Code e utilize a extensão **Live Server** (clique em *Go Live*).

2. **Via Python**:
   ```bash
   python -m http.server 8000
   ```
   Acesse no navegador: `http://localhost:8000`

---

## 🌐 Deploy em Produção (GitHub Pages)

O deploy está pré-configurado via GitHub Actions:
1. No repositório do GitHub, acesse **Settings** > **Pages**.
2. Na seção **Build and deployment** > **Source**, selecione **GitHub Actions**.
3. A cada commit na branch `main`, a publicação é realizada automaticamente em:
   `https://ahk2001.github.io/autoescuelakm4/`

---

## 📍 Localização & Contato da Autoescola

- **Endereço**: C/ del Reverend José María Pinazo, 4, Benimaclet, 46020 Valencia, Espanha
- **WhatsApp**: +34 622 27 90 51
- **Site Oficial**: [autoescuelakm4.com](https://www.autoescuelakm4.com/)
