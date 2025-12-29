# Pastelería Mi Perla - Sitio Web

Sitio web oficial de Pastelería Mi Perla - Líder en pastelería fina en Chiclayo.

## 🎯 Características

- ✅ Diseño responsive y moderno
- ✅ Optimizado para SEO
- ✅ 3 sucursales con información completa
- ✅ Galería de productos (Bocaditos, Tortas, Cupcakes)
- ✅ Integración con WhatsApp
- ✅ Mapa de cobertura de delivery
- ✅ Optimización de velocidad y rendimiento

## 📁 Estructura del Proyecto

```
pasteleria-miperla/
├── index.html              # Página principal
├── locales.html           # Página de locales y horarios
├── cobertura.html         # Página de cobertura de delivery
├── productos.html         # Página de productos con galerías
├── css/
│   └── styles.css         # Estilos principales
├── js/
│   ├── main.js           # JavaScript principal
│   └── gallery.js        # JavaScript de galerías
├── images/               # Carpeta de imágenes
│   ├── logo.png
│   ├── hero-bg.jpg
│   ├── about.jpg
│   ├── tortas/
│   ├── bocaditos/
│   └── cupcakes/
├── netlify.toml          # Configuración de Netlify
├── _redirects            # Redirecciones
├── robots.txt            # SEO
└── sitemap.xml           # Mapa del sitio
```

## 🚀 Despliegue en Netlify

### Método 1: Despliegue Automático desde Git

1. Sube el proyecto a GitHub, GitLab o Bitbucket
2. Ve a [Netlify](https://app.netlify.com)
3. Haz clic en "Add new site" > "Import an existing project"
4. Conecta tu repositorio
5. Netlify detectará automáticamente la configuración desde `netlify.toml`
6. Haz clic en "Deploy site"

### Método 2: Despliegue Manual

1. Comprime todos los archivos en un ZIP
2. Ve a [Netlify](https://app.netlify.com)
3. Arrastra y suelta el ZIP en la zona de despliegue
4. Espera a que termine el despliegue

## 🌐 Configurar Dominio Personalizado

### En Netlify:

1. Ve a "Site settings" > "Domain management"
2. Haz clic en "Add custom domain"
3. Ingresa: `pasteleriamiperla.online`
4. Netlify te dará los registros DNS que necesitas configurar

### En tu Proveedor de Dominio:

Agrega estos registros DNS:

**Registro A:**
```
Type: A
Name: @
Value: 75.2.60.5
TTL: 3600
```

**Registro CNAME (para www):**
```
Type: CNAME
Name: www
Value: [tu-sitio].netlify.app
TTL: 3600
```

**Alternativamente, usar Netlify DNS:**
1. En Netlify, ve a "Domain settings"
2. Haz clic en "Netlify DNS"
3. Sigue las instrucciones para cambiar los nameservers en tu proveedor de dominio

Los nameservers de Netlify son:
- dns1.p03.nsone.net
- dns2.p03.nsone.net
- dns3.p03.nsone.net
- dns4.p03.nsone.net

### Habilitar HTTPS

Netlify proporciona certificados SSL gratuitos automáticamente:
1. Ve a "Domain settings" > "HTTPS"
2. Espera a que se provisione el certificado (puede tardar unos minutos)
3. Activa "Force HTTPS" para redirigir todo el tráfico HTTP a HTTPS

## 📸 Imágenes Necesarias

Para que el sitio funcione correctamente, necesitas agregar las siguientes imágenes a la carpeta `images/`:

### Imágenes Principales:
- `logo.png` (200x200px) - Logo de Mi Perla
- `hero-bg.jpg` (1920x1080px) - Imagen de fondo del hero
- `about.jpg` (800x600px) - Imagen para sección "sobre nosotros"
- `pedidos-especiales.jpg` (800x600px)

### Categorías:
- `categoria-bocaditos.jpg` (600x400px)
- `categoria-tortas.jpg` (600x400px)
- `categoria-cupcakes.jpg` (600x400px)

### Productos:
- `tortas.jpg`, `bocaditos.jpg`, `cupcakes.jpg` (400x400px cada una)

### Galería de Productos:
Crea subcarpetas en `images/`:
- `images/tortas/` - 10 imágenes de tortas
- `images/bocaditos/` - 9 imágenes de bocaditos
- `images/cupcakes/` - 10 imágenes de cupcakes

### Imagen Placeholder:
- `placeholder.jpg` (400x400px) - Imagen por defecto si alguna imagen no carga

## 🎨 Colores de Marca

```css
--primary-color: #D4AF37;    /* Dorado */
--secondary-color: #C41E3A;  /* Rojo/Rosado */
--dark-color: #2C1810;       /* Marrón oscuro */
--light-color: #FFF5E6;      /* Crema claro */
```

## 🔧 Optimizaciones Incluidas

- ✅ Lazy loading de imágenes
- ✅ CSS y JS minificados en producción
- ✅ Caché optimizado para recursos estáticos
- ✅ Headers de seguridad configurados
- ✅ Redirecciones automáticas
- ✅ Sitemap.xml para SEO
- ✅ Robots.txt configurado
- ✅ Meta tags Open Graph
- ✅ Diseño mobile-first

## 📱 Contacto

- **WhatsApp Sede Pedro Ruiz:** [985 556 216](https://wa.me/51985556216)
- **WhatsApp Sede San Isidro:** [939 665 548](https://wa.me/51939665548)
- **WhatsApp Sede La Victoria:** [914 906 183](https://wa.me/51914906183)
- **Email:** pasteleriamiperla@gmail.com

## 🔒 Palabras Clave SEO Integradas

El sitio está optimizado para las siguientes palabras clave:
- pasteleria en chiclayo
- tortas personalizadas en chiclayo
- bocaditos en chiclayo
- cupcakes en chiclayo
- pasteleria fina en chiclayo
- bocaditos salados chiclayo
- pasteleria en la victoria chiclayo
- bocaditos para fiestas chiclayo
- venta de bocaditos en chiclayo

## 📈 Analytics (Opcional)

Para agregar Google Analytics:

1. Obtén tu ID de medición de Google Analytics
2. Agrega este código antes del `</head>` en todas las páginas HTML:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU-ID-AQUI"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU-ID-AQUI');
</script>
```

## 🆘 Soporte

Si tienes problemas con el despliegue:

1. Verifica que todos los archivos estén en la raíz del proyecto
2. Asegúrate de que las rutas de las imágenes sean correctas
3. Revisa los logs de despliegue en Netlify
4. Verifica que tu dominio esté correctamente configurado

## 📝 Licencia

© 2024 Pastelería Mi Perla. Todos los derechos reservados.
