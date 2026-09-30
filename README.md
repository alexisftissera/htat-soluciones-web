# HTAT Soluciones — sitio web

Sitio institucional de **HTAT Soluciones**, mantenimiento predictivo y preventivo de
refrigeración y climatización en Córdoba Capital, Argentina.

**En línea:** https://htat-soluciones.netlify.app

## Qué es

Sitio estático de una sola página. Sin build, sin dependencias, sin framework.
Son 7 archivos: un HTML y 6 imágenes. Se sube arrastrando la carpeta a cualquier
hosting estático.

## Estructura

```
index.html          la página completa (HTML + CSS + JS en un solo archivo)
img/                6 fotos de servicio, recortadas a 900x562 y comprimidas
```

## Contenido de la página

- **Hero** — "Medimos antes de que falle. Eso es mantenimiento."
- **Qué hacemos** — 6 servicios con foto
- **Un proceso ordenado** — las 6 etapas reales de trabajo:
  presupuesto sin cargo → revisamos el equipo → informe de estado →
  tu confirmación → realizamos la operación → finaliza con informe
- **Planes** — 3 planes por cantidad de equipos, sin precios inventados
- **Sectores** — a qué industrias se atiende
- **Preguntas** — 7 preguntas frecuentes
- **Contacto** — WhatsApp y teléfono

## Datos de contacto

- WhatsApp: `wa.me/5493512869817` (formato internacional, el 9 es obligatorio)
- Teléfono: 3512 869-817
- Zona: Córdoba Capital

## Decisiones de diseño

- Azul marino `#0D2B45` y naranja `#F08C28`
- El hero y el header van en azul marino; el resto del cuerpo en gris difuminado
  (`#F4F6F8` y `#EDF1F5`) con tarjetas blancas
- El naranja se usa en dos tonos según el fondo: el brillante `#F08C28` sobre azul
  marino, y uno más profundo `#A85500` sobre gris claro, para que el texto se lea
- Todos los textos pasan el estándar de contraste AA (4.5:1 o más)

## Sobre las imágenes

Las 6 fotos de la sección de servicios son **illustrativas**, con licencia de uso
gratuito de Pexels. No son trabajos propios. Cuando haya fotos reales de trabajos
terminados, reemplazarlas y borrar la nota del pie de página.

## Actualizar el sitio

1. Editar `index.html`
2. Reemplazar las fotos de `img/` respetando el nombre y las 900x562 px
3. Subir la carpeta a https://app.netlify.com/drop

Para cambiar la dirección declarada en el código (canonical y og:url), reemplazar
`https://htat-soluciones.netlify.app/` en el `<head>`.
