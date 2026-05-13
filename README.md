# Nutrición Multi-Pet

Landing page de venda do produto **Multi-Pet Nutrición Natural — Comida casera para perro y gato**.

## Stack

- HTML/CSS estático single-page
- Google Fonts: Inter (única família)
- Imagens WebP otimizadas (~2 MB total)
- Meta Pixel + tracking de eventos (PageView, ViewContent, AddToCart, InitiateCheckout)

## Estrutura

```
.
├── index.html              # LP single-page (19 seções)
├── imagens/                # 11 imagens WebP otimizadas
│   ├── 01-hero-composition.webp
│   ├── 02-mockup-pdf-capa.webp
│   └── ... (09 mais)
└── README.md
```

## Placeholders a substituir antes de produção

| Placeholder | Onde aparece | O que colocar |
|---|---|---|
| `PIXEL_ID` | head + noscript | ID do pixel Meta |
| `HOTMART_CHECKOUT_URL` | 4 CTAs (hero, pricing, final, PS) | URL do pay link do Hotmart |
| `FECHA_LIMITE` | bloco urgência + PS | Data de fim da promo (ex: `20/05/2026`) |
| `POLITICA_PRIVACIDAD_URL` | footer | URL da política de privacidade |
| `TERMINOS_URL` | footer | URL dos termos |
| `CONTACTO_EMAIL` | footer | E-mail de contato |

## Deploy

Vercel auto-deploy a cada push pra `main`.

URL pública: https://nutricion-multipet.vercel.app

## Produto

- **Ticket**: $14.90 USD (cheio $24.90)
- **Plataforma**: Hotmart
- **Order bump**: Recetario de Premios y Galletas +$4.90
- **Upsell OTO**: Protocolo Pet Calmo $37 (de $47)
- **Conteúdo entregue**: PDF 40 recetas + Calculadora Sheets + Tabla prohibidos + Plan transición 14 días + Manual Primeros Auxilios (bônus)
