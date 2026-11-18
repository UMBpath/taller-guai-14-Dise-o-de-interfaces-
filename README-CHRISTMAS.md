# 🎄 Proyecto de Tarjeta de Navidad

Este proyecto permite crear y enviar tarjetas de Navidad personalizadas por email de forma anónima.

## 📁 Archivos del Proyecto

### Archivos Principales

- **christmas-card.html** - Tarjeta de Navidad interactiva con animaciones CSS
- **christmas-card.png** - Imagen de la tarjeta en alta resolución
- **christmas-sender.html** - Aplicación web para enviar la tarjeta por email
- **index.html** - Página principal del proyecto

### Documentación

- **README.md** - Documentación general del proyecto
- **README-CHRISTMAS.md** - Esta documentación

## 🚀 Cómo Usar

### Opción 1: Ver la Tarjeta

Abre `christmas-card.html` en tu navegador para ver la tarjeta con animaciones.

### Opción 2: Enviar por Email

1. Abre `christmas-sender.html` en tu navegador
2. Obtén una API Key gratuita en https://resend.com/api-keys
3. Pega la API Key en el campo de configuración
4. Escribe el email del destinatario
5. Click en "Enviar Tarjeta"

## ✨ Características

- ✅ **Diseño festivo** con gradientes y animaciones
- ✅ **Alta resolución** (1600x1200 píxeles)
- ✅ **Envío anónimo** usando Resend API
- ✅ **3,000 emails/mes gratis** con Resend
- ✅ **Sin configuración SMTP** compleja
- ✅ **Fácil de usar** - solo escribe el email

## 🎨 Personalización

Puedes personalizar la tarjeta editando `christmas-card.html`:
- Cambiar el mensaje
- Modificar colores
- Agregar tu logo
- Cambiar las decoraciones

## 📧 Servicios de Email

### Resend (Recomendado)
- 3,000 emails/mes gratis
- Muy fácil de configurar
- Totalmente anónimo
- https://resend.com/

### Otros Servicios
El proyecto también soporta:
- Gmail SMTP
- Outlook SMTP
- SendGrid
- Mailgun

## 🔧 Configuración Avanzada

### Usar con Supabase

Para una solución más segura con Supabase Edge Functions:

1. Ve a la carpeta `send-christmas-card/`
2. Sigue las instrucciones en `DEPLOY-GUIDE.md`
3. Despliega la función en Supabase
4. Los emails se envían desde la nube

## 📄 Licencia

Este proyecto es de código abierto y puede ser usado libremente.

## 🎄 ¡Felices Fiestas!

¡Espero que disfrutes enviando tarjetas de Navidad a tus amigos y familiares!
