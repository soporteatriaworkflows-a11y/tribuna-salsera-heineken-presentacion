# La Tribuna Salsera × Heineken — Presentación Fan Fest Oficial

Presentación interactiva HTML para el Fan Fest Oficial de Cali Mundialista 2026.  
Proyecto independiente. No relacionado con ATRIA ni con atriaworkflows.com.

## Abrir localmente

Doble clic en `index.html`, o desde terminal:

```
start index.html
```

Requiere un servidor local para que los audios funcionen correctamente en algunos navegadores:

```
npx serve .
```

Luego abrir: http://localhost:3000

## Publicar en Vercel

```
npx vercel --prod
```

O conectar este repo en vercel.com → New Project → seleccionar `tribuna-salsera-heineken-presentacion`.

## Navegación

- Flechas ← → del teclado
- Botones en pantalla
- Dots de navegación en la parte inferior

## Estructura

```
index.html          Presentación completa (21 slides)
assets/
  logos/            Logos de marcas y partners
  renders/          Renders 3D del recinto
  audio/            Pistas del evento
```

Deploy update: corrección carga inicial y soporte móvil.
