# 🎨 Assets de Marketing

Este directorio contiene todos los recursos visuales y multimedia utilizados en las campañas de marketing de Bella K Super Store y 579 Fashion Store.

## Estructura

```
assets/
├── images/             # Imágenes y fotografías
├── videos/            # Videos y contenido multimedia
└── logos/             # Logotipos y elementos de marca
```

## Organización de Assets

### Por Marca
Todos los assets están organizados por marca:
- **Bella K Super Store** (`bellak/`)
- **579 Fashion Store** (`579/`)
- **Compartidos** (`shared/`)

### Por Tipo
Cada categoría tiene su propia estructura interna según el tipo de contenido.

## Acceso Rápido

### Imágenes
📁 [images/README.md](./images/README.md)
- Fotos de productos
- Lifestyle photography
- Banners y gráficos
- Contenido para redes sociales

### Videos
🎬 [videos/README.md](./videos/README.md)
- TikToks y Reels
- Tutoriales
- Product showcases
- Anuncios

### Logos
🎨 [logos/README.md](./logos/README.md)
- Logos principales
- Variaciones de marca
- Iconos
- Brand guidelines

## Naming Convention General

Todos los assets deben seguir esta convención de nombres:

**Formato**: `[marca]_[categoria]_[descripcion]_[version].[ext]`

**Componentes**:
- `marca`: `bellak`, `579`, o `shared`
- `categoria`: tipo de asset (producto, social, tutorial, etc.)
- `descripcion`: breve descripción del contenido
- `version`: v1, v2, v3, etc.
- `ext`: extensión del archivo

**Ejemplos**:
- `bellak_producto_serum_hero_v1.jpg`
- `579_social_lookbook_primavera_v2.mp4`
- `shared_background_gradient_pink_v1.png`

## Lineamientos de Calidad

### Resolución Mínima
- **Imágenes web/social**: 1080px (lado mínimo)
- **Imágenes impresión**: 300dpi
- **Videos social**: 1080p mínimo
- **Logos**: Vectoriales (SVG/AI) preferidos

### Formato de Archivo

**Imágenes**:
- JPG: Fotografías sin transparencia
- PNG: Gráficos con transparencia
- SVG: Logos y elementos vectoriales
- WebP: Optimización web (cuando sea posible)

**Videos**:
- MP4 (H.264): Estándar para redes sociales
- MOV: Archivos fuente de alta calidad

**Vectores**:
- SVG: Web y digital
- AI/EPS: Archivos fuente para diseñadores
- PDF: Compartir con terceros

### Tamaño de Archivo

**Límites recomendados**:
- Imágenes social media: 1-2MB máximo
- Videos para repo: 50MB máximo
- Logos PNG: 500KB máximo
- Archivos fuente: Sin límite pero documentar ubicación si >100MB

## Gestión de Assets

### Agregar Nuevos Assets

1. **Preparar archivo**:
   - Optimizar tamaño
   - Nombrar correctamente
   - Verificar calidad

2. **Ubicar correctamente**:
   - Carpeta de marca apropiada
   - Subcategoría correcta
   - Mantener organización

3. **Documentar**:
   - Actualizar README si es relevante
   - Agregar metadata si es necesario
   - Incluir información de licencia

4. **Commit**:
   - Usar mensaje descriptivo
   - Referenciar campaña si aplica

### Archivar Assets Antiguos

- Mover a carpeta `archived/` dentro de cada categoría
- Mantener por 6-12 meses antes de eliminar
- Documentar razón de archivo

### Backup de Assets

**Archivos en Repo**:
- Assets finales optimizados
- Versiones listas para publicar
- Tamaños apropiados para Git

**Archivos Fuera de Repo**:
- RAW files / archivos fuente
- Videos sin comprimir
- PSDs/AIs con todas las capas
- Almacenar en Google Drive / Dropbox

## Licencias y Derechos

### Assets Originales
- Mantener registro de creador
- Documentar fecha de creación
- Almacenar releases de modelos (fuera de repo)

### Stock Assets
- Solo usar con licencia apropiada
- Documentar fuente y tipo de licencia
- Guardar comprobante de compra (fuera de repo)

### User-Generated Content
- Obtener permiso escrito antes de usar
- Documentar consentimiento
- Dar crédito apropiado

## Optimización de Assets

### Imágenes
- Comprimir sin pérdida visible de calidad
- Usar formato apropiado (JPG vs PNG)
- Redimensionar a tamaño de uso final
- Considerar WebP para web

**Herramientas**:
- TinyPNG / TinyJPG
- ImageOptim
- Squoosh
- Photoshop "Save for Web"

### Videos
- Comprimir a bitrate apropiado
- H.264 codec para compatibilidad
- Resolución adecuada a plataforma
- Eliminar metadata innecesaria

**Herramientas**:
- HandBrake
- Adobe Media Encoder
- FFmpeg
- CloudConvert

## Workflow de Producción

### 1. Planificación
- Definir necesidades de assets
- Crear lista de shots necesarios
- Planificar sesión de fotos/video

### 2. Producción
- Capturar material según plan
- Múltiples variaciones
- Alta calidad

### 3. Selección
- Revisar todo el material
- Seleccionar mejores opciones
- Descartar material no útil

### 4. Edición
- Editar según brand guidelines
- Mantener consistencia
- Preparar variaciones necesarias

### 5. Optimización
- Comprimir apropiadamente
- Exportar en formatos necesarios
- Nombrar correctamente

### 6. Organización
- Ubicar en carpetas correctas
- Actualizar documentación
- Hacer commit con mensaje claro

### 7. Backup
- Copiar archivos fuente a storage externo
- Verificar integridad
- Documentar ubicación

## Búsqueda de Assets

### Por Naming Convention
Los nombres descriptivos facilitan encontrar assets:
```bash
# Buscar todos los productos de Bella K
grep -r "bellak_producto_" assets/

# Buscar todos los videos para TikTok
find assets/ -name "*tiktok*"
```

### Por Campaña
Los assets específicos de campaña están también referenciados en:
`campaigns/[nombre-campana]/`

### Por Fecha
Los commits de Git mantienen historial de cuándo se agregó cada asset.

## Checklist de Assets

Antes de agregar un asset al repositorio:

- [ ] Archivo optimizado (tamaño apropiado)
- [ ] Naming convention correcta
- [ ] Calidad verificada
- [ ] Ubicado en carpeta correcta
- [ ] Licencia/derechos verificados
- [ ] Metadata relevante documentada
- [ ] README actualizado si es necesario
- [ ] Archivos fuente respaldados fuera de repo

## Assets por Plataforma

### TikTok
- Videos verticales (9:16)
- 1080x1920px
- MP4, 15-60 segundos
- Subtítulos incluidos

### Instagram Feed
- Cuadrados (1:1) o verticales (4:5)
- 1080x1080px o 1080x1350px
- JPG/PNG para imágenes
- MP4 para videos

### Instagram Stories
- Verticales (9:16)
- 1080x1920px
- JPG/PNG/MP4
- Elementos interactivos considerados

### Instagram Reels
- Verticales (9:16)
- 1080x1920px
- MP4, 15-90 segundos
- Optimizado para mobile

## Mantenimiento

### Revisión Periódica
- **Mensual**: Revisar assets recientes, optimizar si es necesario
- **Trimestral**: Archivar assets obsoletos
- **Anual**: Limpieza profunda, eliminar archivos muy antiguos

### Actualización de Documentación
- Mantener READMEs actualizados
- Documentar cambios en organización
- Actualizar ejemplos cuando sea relevante

## Recursos Adicionales

- [Templates](../templates/): Plantillas para usar estos assets
- [Campaigns](../campaigns/): Ejemplos de uso en campañas
- [MARKETING_CONTEXT.md](../MARKETING_CONTEXT.md): Lineamientos de marca

---

*Para preguntas sobre assets o para solicitar nuevos materiales, contacta al equipo de producción*
