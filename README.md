# literal

Sitio web construido con [Astro](https://astro.build). Empieza como una web estática y está pensado para incorporar ecommerce más adelante (checkout vía Stripe/Shopify/Snipcart u otro) sin cambiar de framework.

## 🚀 Estructura del proyecto

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en `src/pages/`. Cada página se expone como una ruta según el nombre del archivo.

Los assets estáticos (imágenes, etc.) van en `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala dependencias                             |
| `npm run dev`             | Levanta el servidor local en `localhost:4321`    |
| `npm run build`           | Compila el sitio de producción a `./dist/`       |
| `npm run preview`         | Previsualiza el build antes de desplegar         |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |

## 👀 Más info

[Documentación de Astro](https://docs.astro.build)
