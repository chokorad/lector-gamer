# Lector Gamer — Yosi Robux 📖🎮

App familiar: leer páginas gana puntos y minutos de pantalla, canjeables por tiempo extra o tarjetas de Robux.

## Deploy (igual que WakeUp Cards)

1. Crea un repo nuevo en GitHub (ej. `lector-gamer`), sube TODOS estos archivos:
   `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
2. Settings → Pages → Deploy from branch → main → / (root)
3. Abre `https://chokorad.github.io/lector-gamer/`

## Seguridad de Firestore (IMPORTANTE, antes de 30 días)

El modo test expira. En Firebase Console → Firestore → Rules, pega el contenido
de `firestore-rules.txt` y publica. Los datos quedan solo en la ruta secreta de la familia.

## Instalación en los teléfonos

- iPhone de Yosi: Safari → abrir URL → Compartir → "Agregar a inicio"
- Tu Android: Chrome → abrir URL → menú → "Agregar a pantalla principal"

## Primer uso

1. Ábrela tú primero, entra como papá con PIN `1234` y CÁMBIALO en Ajustes.
2. En el iPhone de Yosi, elegir "Soy Yosi".
3. Él registra su primer libro → te llega a tu Bandeja → apruebas el premio → a leer.

## Reglas del sistema (resumen)

- 1 pág ES = 1 pt · 1 pág EN = 2 pts · 2 págs = 1 min (EN doble)
- Releer = mitad · Libros escolares no cuentan (no los apruebes)
- Racha: 10+ págs/día · +25 pts cada 7 días · metas 30/60/100 días
- Congeladas: máx 2/semana, con tu aprobación
- Robux: 10 min = 5 MXN, mínimo $40, siempre con tu aprobación
- El banco de minutos nunca se reinicia; tú apruebas cada retiro
