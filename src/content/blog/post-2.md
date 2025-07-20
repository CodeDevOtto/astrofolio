---
title: "Diseño responsive con CSS Grid"
pubDate: 2024-01-20
author: "Tu Nombre"
description: "Aprende a crear layouts modernos con CSS Grid."
image: "https://images.unsplash.com/photo-1547658719-da2b51169166?w=800&auto=format" # Imagen de Unsplash (design)
---

## ¿Por qué CSS Grid?

CSS Grid permite diseños complejos con **poco código**.

![Ejemplo de Grid](https://via.placeholder.com/600x300?text=CSS+Grid+Example "Placeholder de Grid")

### Código básico:

```css
.container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
}
```
