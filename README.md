# construccionyasesoria.com

Sitio público de **Construcción, Terracerías y Asesoría Inmobiliaria, S.A. de C.V.** (Río Bravo, Tamaulipas).

Sitio estático (HTML puro, sin build). Se despliega en Vercel; cada `git push` a `main` publica automáticamente.

## Archivos
- `index.html` — landing del negocio (casas, lotes, construcción, créditos, contacto/WhatsApp). Trae botón "Acceso" al panel del equipo.
- `aviso-de-privacidad.html` — Aviso de Privacidad (accesible en `/aviso-de-privacidad.html`).
- `panel.html` — panel de administración del equipo (Alejandro/Laura/Mayra). Login por correo interno + NIP contra Supabase. Accesible en `/panel.html`.

## Desplegar en Vercel
1. Sube esta carpeta a un repo de GitHub.
2. En Vercel: **Add New → Project → Import** el repo. Framework Preset: **Other** (sitio estático). Deploy.
3. En el proyecto: **Settings → Domains → Add** → `construccionyasesoria.com` (y `www`).
4. Cada cambio: `git push` y Vercel republica solo.
