# Publicación de Ruedita

Sitio estático de soporte y privacidad; no contiene la aplicación móvil.

## Activación inicial

1. Settings > Pages > Build and deployment > Source: Deploy from a branch.
2. Branch: main; carpeta: /(root); Save.
3. Custom domain: ruedita.invertorc.com; Save antes de crear el DNS.
4. Cloudflare > invertorc.com > DNS > Records: crear CNAME con nombre ruedita, destino ator89.github.io, Proxy status DNS only y TTL Auto. Conservar los registros de correo.
5. Volver a GitHub Pages y activar Enforce HTTPS cuando el certificado esté disponible.
6. Verificar sin iniciar sesión la página principal, /soporte/ y /privacidad/, los enlaces y ambos idiomas.

El correo configurado es soporte@invertorc.com. La publicación y el certificado aún requieren verificación; la presencia de CNAME no prueba que Pages esté activado.

## Mantenimiento

Las páginas son HTML y CSS, sin dependencias, JavaScript, anuncios ni analítica propia. Editar y guardar en main actualiza el sitio una vez activado Pages.

La política describe Ruedita 1.0 y separa el procesamiento de la aplicación del correo de soporte y las visitas web. Revisar conjuntamente la política de la app y las declaraciones de las tiendas cuando cambie el tratamiento de datos.
