# Divi Express LLC — Site Institucional

Site institucional da **Divi Express LLC**, empresa especializada na venda, importação e comercialização de veículos de qualidade. Conteúdo em inglês, com tom formal e adequado para análise bancária e compliance.

## Sobre o projeto

- **Página única** com seções: Company Overview, Our Services, End-to-End Process, Transparency and Compliance, Mission and Vision, About Us, How We Operate, Core Values e Our Commitment.
- **Linguagem objetiva**, sem claims financeiros; disclaimer explícito de que a empresa não oferece financiamento, crédito ou atua como credora.
- **Identificação legal** no footer (LLC registrada nos EUA) e **schema JSON-LD** (`LimitedLiabilityCompany`) para classificação e SEO.

## Estrutura do repositório

```
souzaglobal/
├── index.html      # Página principal
├── styles.css      # Estilos globais, responsividade, tema
├── main.js         # Menu mobile, botão voltar ao topo, scroll reveal
├── assets/
│   ├── logo.jpeg       # Logo da empresa
│   └── hero-index.png  # Imagem de fundo do hero
└── README.md
```

## Tecnologias

- **HTML5** — semântico, acessível (ARIA, skip link)
- **CSS3** — variáveis, layout responsivo, `prefers-reduced-motion`
- **JavaScript** — menu mobile, back-to-top, animações de revelação ao scroll

## Como rodar localmente

Não há build. Basta abrir o `index.html` no navegador ou usar um servidor local:

```bash
# Opção 1: Python 3
python3 -m http.server 8000

# Opção 2: Node.js (npx)
npx serve .

# Opção 3: PHP
php -S localhost:8000
```

Acesse `http://localhost:8000` (ou a porta indicada).

## SEO e metadados

- Meta description, Open Graph e Twitter Cards configurados
- URL canônica definida
- JSON-LD com `@type`: `LimitedLiabilityCompany`, `areaServed`, `knowsAbout`

## Acessibilidade

- Link “Skip to main content”
- Atributos ARIA no menu e botões
- Animações respeitam `prefers-reduced-motion: reduce`

## Licença e direitos

© Divi Express LLC. All rights reserved.
