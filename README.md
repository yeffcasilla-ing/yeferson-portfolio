# Portafolio Profesional — Yeferson Casilla

Sitio web profesional y portafolio personal de **Yeferson Abdiel Casilla Pérez**, enfocado en **Ingeniería de Sistemas, Desarrollo de Software e Infraestructura Tecnológica**.

- **Dominio personalizado**: [https://yeffcasillard.quest](https://yeffcasillard.quest)
- **Subdominio de hosting**: [http://yeffcasillard.kesug.com](http://yeffcasillard.kesug.com)
- **GitHub**: [https://github.com/Deseex](https://github.com/Deseex)
- **Contacto**: [yeffcasilla@gmail.com](mailto:yeffcasilla@gmail.com)

---

## 🚀 Tecnologías y Arquitectura

- **Front-End**: HTML5 semántico, CSS3 moderno con variables y soporte responsive (Mobile First), JavaScript (ES6+) sin dependencias de compilación pesadas.
- **Tipografías**: Google Fonts (*Plus Jakarta Sans* y *JetBrains Mono*).
- **Diseño**: Tema oscuro premium (*Dark Minimalist UI*), transiciones fluidas con curvas `cubic-bezier`, badges de estado, menú móvil tipo drawer y soporte para `prefers-reduced-motion`.
- **Compatibilidad**: Diseñado para funcionar eficientemente en servidores Apache, hosting compartido gratuito (InfinityFree) y GitHub Pages.

---

## 📁 Estructura del Proyecto

```
yeferson-portfolio/
│
├── index.html                 # Página principal del portafolio
├── 404.html                   # Página de error 404 personalizada
├── .htaccess                  # Configuración Apache (HTTPS, 404, caché y cabeceras de seguridad)
├── robots.txt                 # Instrucciones para motores de búsqueda
├── sitemap.xml                # Mapa del sitio para indexación SEO
├── README.md                  # Documentación del proyecto
└── assets/
    ├── css/
    │   └── styles.css         # Hoja de estilos con variables de color y diseño responsive
    ├── js/
    │   └── main.js            # Lógica de navegación, menú móvil, touch en proyectos y copiado de email
    └── images/
        └── profile.jpg        # Fotografía profesional de perfil
```

---

## 🛠️ Instrucciones de Despliegue y Mantenimiento

### 1. Despliegue en InfinityFree
1. Accede al administrador de archivos en el panel de InfinityFree:
   `https://dash.infinityfree.com/accounts/if0_43316012/filemanager`
2. Navega a la carpeta pública del dominio:
   - Para el dominio principal/alias: `htdocs/`
   - O la carpeta asignada al dominio personalizado: `yeffcasillard.quest/htdocs/`
3. Sube todos los archivos respetando la estructura (`index.html`, `404.html`, `.htaccess`, carpeta `assets/`).
4. Comprueba en el navegador que el sitio cargue con HTTPS y sin errores 403 o 404.

### 2. Configuración de Dominio en Porkbun
Para vincular el dominio `yeffcasillard.quest` con InfinityFree:
1. Accede a tu panel en [Porkbun Domains](https://porkbun.com/account/domainsSpeedy).
2. En la opción **Editar Servidores de Nombres (Nameservers)** de `yeffcasillard.quest`, configura los servidores autorizados de InfinityFree:
   ```
   ns1.infinityfree.com
   ns2.infinityfree.com
   ```
   *(o alternativamente `ns1.byet.org` y `ns2.byet.org`)*.
3. En el panel de InfinityFree, añade el dominio personalizado en la sección **Agregar dominio**.
4. Una vez propagado el DNS, activa el certificado SSL gratuito desde la sección **Certificados SSL** de InfinityFree.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el código y adáptalo a tus necesidades.
