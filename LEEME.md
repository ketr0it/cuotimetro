# Cuotímetro

Calculadora independiente para estimar compras en cuotas. Es una app web instalable (PWA):
se instala en el iPhone desde Safari, abre a pantalla completa y funciona sin internet.

## Publicarla gratis (GitHub Pages)
1. Crea un repositorio público en github.com (por ejemplo `cuotimetro`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. Settings → Pages → Branch: `main`, carpeta `/ (root)` → Save.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/cuotimetro/`.

Alternativas: Cloudflare Pages (subir la carpeta arrastrando) o tu homelab.
Para que funcione sin internet necesita HTTPS.

## Instalarla en el iPhone
Abre el link en Safari → botón Compartir → “Añadir a pantalla de inicio”.

## Actualizarla
Reemplaza los archivos y sube el número en `sw.js` (`cuotimetro-v1` → `cuotimetro-v2`).

## Probarla en la computadora
`python -m http.server 8000` dentro de esta carpeta y abre http://localhost:8000
