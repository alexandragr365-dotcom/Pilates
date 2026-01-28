# Pilates Evolve - Práctica 1: Geolocalización y Redes Sociales

Sitio web profesional con sistema de geolocalización interactivo para mostrar lugares de interés y atracciones en Nezahualcóyotl, con integración a redes sociales.

## Características Principales

- Diseño limpio y profesional con colores modernos
- Sistema de geolocalización con mapa interactivo
- 5 lugares de interés en Nezahualcóyotl
- Enlaces a sitios web de cada ubicación
- Integración con Instagram
- Diseño responsivo (móvil, tablet y escritorio)

## Funcionalidades

### Lugares de Interés
El sitio incluye 5 atracciones y lugares importantes:
1. Starbucks Neza (predeterminado)
2. Plaza Centro Neza
3. Parque del Pueblo
4. Cinépolis Neza
5. Walmart Neza

### Información Mostrada
Al seleccionar cualquier ubicación, se muestra:
- Coordenadas GPS exactas
- Dirección completa
- Sitio web oficial
- Marcador en el mapa interactivo
- Enlace directo a Google Maps
- Popup con información detallada

## Archivos Incluidos

- `index.html` - Archivo principal del sitio web
- `README.md` - Documentación del proyecto

## Cómo Subir a GitHub

### Opción 1: Interfaz Web de GitHub

1. Inicia sesión en [GitHub](https://github.com)
2. Clic en "+" → "New repository"
3. Nombra el repositorio (ejemplo: `pilates-evolve-practica1`)
4. Selecciona "Public"
5. NO marques "Add a README file"
6. Clic en "Create repository"
7. En la página del repositorio, clic en "uploading an existing file"
8. Arrastra los archivos `index.html` y `README.md`
9. Clic en "Commit changes"

### Opción 2: Línea de Comandos

```bash
# Inicializar repositorio local
git init

# Agregar archivos al staging
git add index.html README.md

# Crear primer commit
git commit -m "Agregar sitio web de Pilates Evolve con geolocalización"

# Conectar con repositorio remoto (reemplaza con tu usuario y repositorio)
git remote add origin https://github.com/TU_USUARIO/pilates-evolve-practica1.git

# Subir archivos
git branch -M main
git push -u origin main
```

## Cómo Subir a InfinityFree

### Paso 1: Registrarse

1. Visita [InfinityFree](https://dash.infinityfree.com/accounts/create/free)
2. Completa el formulario de registro
3. Confirma tu correo electrónico

### Paso 2: Crear Cuenta de Hosting

1. Accede a tu panel de InfinityFree
2. Haz clic en "Create Account"
3. Selecciona un subdominio gratuito o usa tu dominio propio
4. Finaliza la configuración

### Paso 3: Subir Archivos

1. En el panel de control, busca "File Manager"
2. Navega a la carpeta `htdocs` (o `public_html`)
3. Sube el archivo `index.html`
4. Asegúrate de que el nombre sea exactamente `index.html` (minúsculas)

**Importante:** Si el archivo tiene otro nombre, deberás acceder con `tudominio.com/nombre.html`

### Paso 4: Verificar

1. Espera 5-10 minutos para la propagación
2. Visita tu dominio en el navegador
3. El sitio debe estar funcionando correctamente

## Tecnologías Utilizadas

### Mapa Interactivo
El sitio utiliza **OpenStreetMap** con la librería **Leaflet.js**

**Ventajas:**
- No requiere API keys
- Completamente gratuito
- Funciona inmediatamente
- Mapa interactivo completo (zoom, arrastrar, etc.)
- Marcadores personalizados
- Popups informativos

### Características del Mapa
- Carga automática de la ubicación predeterminada
- Marcador personalizado con colores corporativos
- Animaciones suaves al cambiar ubicaciones
- Popups con información detallada
- Zoom automático al seleccionar ubicación

## Cómo Funciona

### Cambio de Ubicaciones
1. Haz clic en cualquier tarjeta de ubicación
2. El mapa se actualiza automáticamente
3. Se muestran las coordenadas GPS
4. Se actualiza la dirección
5. Se muestra el sitio web correspondiente
6. Aparece un popup con toda la información

### Diseño Responsivo
- **Escritorio (>968px):** Diseño de tres columnas
- **Tablet/Móvil (<968px):** Diseño apilado en una columna

## Redes Sociales

- Instagram: [@pilates_evolve](https://www.instagram.com/pilates_evolve?igsh=bTg1cnYyMmhkNTQy)

### Tarjeta de Instagram
Incluye una sección completa con:
- Avatar del perfil
- Nombre y handle del usuario
- Biografía del negocio
- Ubicación
- Botón para seguir en Instagram

## Ubicación Principal

**Coordenadas GPS:** 19.4003, -99.0115  
**Dirección:** Av. Bordo de Xochiaca, Plaza Jardín  
**Lugar:** Starbucks Neza

## Personalización

Para modificar los colores principales, edita estas propiedades CSS:

```css
/* Colores principales */
.header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Color de botones y enlaces */
.btn-maps {
    background: #667eea;
}
```

## Estructura de Archivos

```
proyecto/
├── index.html          # Página principal
└── README.md          # Documentación
```

## Navegadores Soportados

- Chrome (última versión)
- Firefox (última versión)
- Safari (última versión)
- Edge (última versión)

## Recursos Externos

- Leaflet.js: https://leafletjs.com/
- OpenStreetMap: https://www.openstreetmap.org/

## Licencia

Este proyecto es de uso educativo para la asignatura de desarrollo web.

## Soporte

Para problemas con:
- **GitHub:** Consulta la [documentación oficial](https://docs.github.com/)
- **InfinityFree:** Visita el [foro de soporte](https://forum.infinityfree.com/)
- **Leaflet:** Revisa la [documentación de Leaflet](https://leafletjs.com/reference.html)

---

Desarrollado para Pilates Evolve - Práctica 1 de Geolocalización
