# NutriGo — Landing page

Landing page de **NutriGo S.A.S.** (platos balanceados ultrcongelados, tecnología IQF).
HTML + CSS + JavaScript puros, sin frameworks ni dependencias.

## Requisitos

- Node.js >= 18.11 (probado con v24.15.0)

## Arranque

```bash
npm start    # http://localhost:3000
npm run dev  # servidor con recarga automática (node --watch)
```

`server.js` usa solo módulos nativos de Node: no hay `npm install` que hacer.

## Estructura

```
├── index.html      # página completa (una sola)
├── css/styles.css  # tokens de diseño + estilos
├── js/main.js      # nav móvil, reveal en scroll, contadores
├── server.js       # servidor estático sin dependencias
└── package.json
```

## Antes de publicar

- Reemplazar el número de WhatsApp (`573001234567`) y el correo `hola@nutrigo.co`.
- Los precios, datos de ahorro y el lote de la ficha técnica son de ejemplo.

## Diseño

Dirección **Botanical Organic**: base hueso, tinta verde bosque, acento terracota;
Young Serif (display) + Outfit (texto); radio único de 14px; escala tipográfica
perfect fourth (1.333). Contraste verificado WCAG AA en todos los textos.
