# hissumaformulario

Este repositorio contiene el formulario HTML de Hissuma que apunta a un Webhook en n8n.

## Archivos

- `index.html` – El formulario completo.
- `README.md` – Estas instrucciones.

## Despliegue en GitHub Pages

1. **Crear el repositorio**  
   - En GitHub, haz click en **New Repository**, ponle nombre (ej. `formulario-hissuma`) y crea el repo.

2. **Subir los archivos**  
   - Desde tu terminal:
     ```bash
     git clone https://github.com/<tu-usuario>/formulario-hissuma.git
     cd formulario-hissuma
     # Copia aquí index.html y README.md
     git add .
     git commit -m "Añadir formulario Hissuma"
     git push origin main
     ```

3. **Habilitar GitHub Pages**  
   - En tu repo en GitHub:  
     `Settings` → `Pages` →  
     - Branch: `main`  
     - Folder: `/ (root)`  
     → Click en **Save**.

4. **Acceder al formulario**  
   - Espera un par de minutos y luego visita:  
     `https://<tu-usuario>.github.io/formulario-hissuma/`

¡Listo! Tu formulario enviará datos directamente a tu Webhook de n8n en `https://nico0508.app.n8n.cloud/webhook-test/formulario-hissuma`. 

---

Cuando ya esté publicado, podemos continuar con los nodos en n8n para enviar el email y guardar en Sheets. ​:contentReference[oaicite:0]{index=0}​
