# FotoProtector · Proyecto Soludable

**Versión:** 2.0  
**Proyecto:** Soludable — Hospital Universitario Costa del Sol  
**Desarrollador:** DoncelProject · doncel.project@gmail.com

---

## ¿Qué es?

PWA de algoritmo clínico para recomendación de fotoprotector en atención primaria y dermatología. Evalúa 8 dominios clínicos para dar una recomendación personalizada con SPF, tipo de filtro, textura y características específicas.

## Dominios clínicos evaluados

1. Antecedentes oncológicos cutáneos
2. Fototipo Fitzpatrick (I–VI)
3. Tipo de exposición solar
4. Patología cutánea (melasma, rosácea, acné, D. atópica, lupus)
5. Medicación fotosensibilizante
6. Grupo de edad (niños, adultos, mayores, embarazadas)
7. Tipo de piel
8. Factores de adherencia

## Configuración

Edita `config.js` directamente desde GitHub para cambiar la clave de acceso:

```js
var CONFIG = {
  ACCESS_KEY: "soludable2025",   // ← cambia esto
  ...
};
```

## Despliegue en Netlify

1. Sube esta carpeta a un repositorio de GitHub
2. Conecta el repo en Netlify → Build Settings: sin comando de build, publish directory: `/`
3. Netlify desplegará automáticamente en cada push

## Notas técnicas

- JavaScript ES5 clásico (compatible con iOS Safari)
- Sin dependencias externas (excepto Google Fonts y Open-Meteo para UVI)
- Catálogo de 42 productos con fotos embebidas en base64
- Funciona offline como PWA
- `config.js` editable desde GitHub sin tocar el código principal

---

© Proyecto Soludable · Hospital Universitario Costa del Sol · Junta de Andalucía  
Desarrollado por DoncelProject · doncel.project@gmail.com
