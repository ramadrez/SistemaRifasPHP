# 🎰 Sistema de Rifas - Gestión Completa de Rifas y Sorteos

<div align="center">

![PHP](https://img.shields.io/badge/PHP-7.4+-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-5.7+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Sistema completo de gestión de rifas y sorteos desarrollado en PHP con MySQL**

[Características](#-características-principales) • [Módulos](#-módulos-funcionales) • [Stack Tecnológico](#-stack-tecnológico) • [Contacto](#-contacto--demo)

</div>

---

## 📋 Descripción General

Sistema web profesional para la **gestión integral de rifas y sorteos**, desarrollado con **PHP + MySQL** y diseñado para uso en producción. Ofrece una solución completa que incluye frontend público para clientes y panel de administración avanzado para gestión total del negocio.

Ideal para empresas, organizaciones y emprendedores que buscan profesionalizar sus rifas y sorteos con una plataforma robusta, segura y escalable.

---

## 🚀 Características Principales

### ✨ Gestión Integral de Rifas

- ✅ Creación, edición y administración completa de rifas
- ✅ Sistema de categorías personalizables
- ✅ Galería de hasta 5 imágenes por rifa
- ✅ Control de estados: activa, cerrada, pausada, finalizada
- ✅ Configuración de rangos de números y precios

### 💳 Sistema de Ventas

- ✅ Compra de tickets con selección interactiva de números
- ✅ Validación de disponibilidad en tiempo real
- ✅ Múltiples métodos de pago configurables
- ✅ Carga y verificación de comprobantes de pago
- ✅ URLs seguras con hash único para cada ticket

### 🎯 Sistema de Sorteos

- ✅ Modalidades flexibles de sorteo:
  - Entre todos los números del rango
  - Solo números vendidos y verificados
  - Exclusión de números en verificación
- ✅ Sorteos múltiples (hasta 10 ganadores)
- ✅ Animación de ruleta para sorteos en vivo
- ✅ Vista de streaming para sorteos públicos

### 📊 Panel de Administración

- ✅ Dashboard con estadísticas en tiempo real
- ✅ Gestión completa de tickets y pagos
- ✅ Sistema de roles (Administrador y Operador)
- ✅ Auditoría completa de acciones administrativas
- ✅ Gestión de métodos de pago
- ✅ Configuración visual y funcional del sistema

### 🎨 Experiencia de Usuario

- ✅ Diseño moderno y responsive (móvil, tablet, desktop)
- ✅ Modo oscuro y claro con persistencia
- ✅ Transiciones suaves y animaciones
- ✅ Contraste WCAG AA para accesibilidad
- ✅ Lazy loading para optimización de carga

### 🔒 Seguridad Empresarial

- ✅ Protección CSRF en todos los formularios
- ✅ Prevención de SQL Injection
- ✅ Protección XSS con sanitización de inputs
- ✅ Rate limiting por IP y sesión
- ✅ Validación avanzada de archivos subidos
- ✅ Hashing seguro de contraseñas (Bcrypt)
- ✅ Regeneración de IDs de sesión

---

## 📸 Screenshots

<table>
  <tr>
    <td align="center" width="33%">
      <h3>🏠 Página Principal</h3>
      <img src="https://imgur.com/q6pblih.png" alt="Página Principal" width="100%" />
      <p><em>Hero section, rifas destacadas y diseño responsive</em></p>
    </td>
    <td align="center" width="33%">
      <h3>🎰 Catálogo de Rifas</h3>
      <img src="https://imgur.com/qOOG0rK.png" alt="Catálogo de Rifas" width="100%" />
      <p><em>Listado completo con filtros y búsqueda</em></p>
    </td>
    <td align="center" width="33%">
      <h3>🎯 Detalle de Rifa</h3>
      <img src="https://imgur.com/EiJKLS5.png" alt="Detalle de Rifa" width="100%" />
      <p><em>Selector de números y formulario de compra</em></p>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <h3>📊 Dashboard Admin</h3>
      <img src="https://imgur.com/UhfDEt5.png" alt="Dashboard Administrativo" width="100%" />
      <p><em>Estadísticas en tiempo real y métricas</em></p>
    </td>
    <td align="center" width="33%">
      <h3>🎪 Gestión de Rifas</h3>
      <img src="https://imgur.com/ssQ24CB.png" alt="Gestión de Rifas" width="100%" />
      <p><em>Creación, edición y control de rifas</em></p>
    </td>
    <td align="center" width="33%">
      <h3>🎫 Gestión de Tickets</h3>
      <img src="https://imgur.com/aFa5lTc.png" alt="Gestión de Tickets" width="100%" />
      <p><em>Verificación de pagos y comprobantes</em></p>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <h3>🎲 Sistema de Sorteos</h3>
      <img src="https://imgur.com/XTKk7fE.png" alt="Sistema de Sorteos" width="100%" />
      <p><em>Configuración y animación de sorteos</em></p>
    </td>
    <td align="center" width="33%">
      <h3>⚙️ Configuración</h3>
      <img src="https://imgur.com/gSWQVpr.png" alt="Configuración del Sistema" width="100%" />
      <p><em>Panel de configuración completo</em></p>
    </td>
    <td align="center" width="33%">
      <h3>📺 Sorteo en Vivo</h3>
      <img src="https://imgur.com/BgHG3Yh.png" alt="Vista de Streaming" width="100%" />
      <p><em>Vista pública para sorteos en tiempo real</em></p>
    </td>
  </tr>
</table>

> **Nota**: Las capturas de pantalla del sistema completo están disponibles bajo solicitud. Contacta para obtener acceso a una demo en vivo.

---

## 🏗️ Módulos Funcionales

### 🌐 Frontend Público

#### Página Principal

- Hero section personalizable con gradientes y banners
- Carrusel de rifas destacadas
- Sección de rifas finalizadas con ganadores
- Diseño adaptativo para todos los dispositivos

#### Catálogo de Rifas

- Listado completo de rifas disponibles
- Filtros por categoría y estado
- Búsqueda inteligente
- Cards informativas con datos clave

#### Detalle de Rifa

- Galería de imágenes de alta calidad
- Selector interactivo de números
- Visualización de números vendidos/disponibles
- Panel de compra con resumen en tiempo real
- Formulario de datos del cliente
- Sistema de carga de comprobantes

#### Confirmación de Compra

- Resumen completo del ticket
- Información del cliente y números comprados
- Estado del pago
- Instrucciones de seguimiento
- URL segura para compartir ticket

---

### 🔐 Panel de Administración

#### Dashboard

- Estadísticas en tiempo real
- Resumen de rifas activas, cerradas y finalizadas
- Métricas de ventas e ingresos
- Gráficos de actividad
- Tickets pendientes de verificación
- Accesos rápidos a módulos

#### Gestión de Rifas

- **Listado**: Vista completa de todas las rifas con filtros y búsqueda
- **Creación**: Formulario completo con configuración de números, precios, imágenes y fechas
- **Edición**: Actualización de rifas con validaciones de seguridad
- **Control de estados**: Activación, cierre y finalización de rifas

#### Gestión de Tickets

- Listado completo con filtros por estado
- Estadísticas de tickets (pendientes, verificados, denegados)
- Visualización de comprobantes de pago
- Verificación o denegación de tickets
- Sistema de alertas para tickets expirados
- Información detallada de clientes

#### Sistema de Sorteos

- Selección de rifa a sortear
- Configuración de modalidad de sorteo
- Definición de cantidad de ganadores
- Visualización de números elegibles
- Animación de ruleta en vivo
- Vista de streaming para audiencia
- Registro automático de ganadores

#### Gestión de Estados

- Vista general de todas las rifas
- Estadísticas globales
- Cambio masivo de estados
- Visualización de disponibilidad

#### Configuración del Sistema

Acceso exclusivo para administradores con pestañas:

- **General**: Nombre del sitio, contacto, textos personalizables
- **Apariencia**: Logo, banner, colores, gradientes, transparencias
- **Sistema**: Límites de upload, días de verificación, notificaciones
- **Base de Datos**: Exportación, importación, backups y restauración
- **Email (SMTP)**: Configuración de servidor, credenciales, pruebas de envío

#### Métodos de Pago

- Creación y edición de métodos de pago
- Activación/desactivación de métodos
- Configuración de instrucciones de pago

---

## 👤 Sistema de Roles

### 🔑 Administrador

- Acceso completo al sistema
- Gestión de usuarios y roles
- Configuración total del sistema
- Gestión de rifas, tickets y sorteos
- Acceso a logs de auditoría
- Control de métodos de pago

### 👔 Operador

- Gestión de rifas
- Administración de tickets
- Realización de sorteos
- Sin acceso a configuración del sistema
- Sin acceso a gestión de usuarios

---

## ⚙️ Optimización y Performance

- **Sistema de caché** multinivel (memoria APCu + archivos)
- **Lazy loading** de imágenes para carga rápida
- **Compresión automática** de imágenes subidas
- **Batch processing** para cálculos masivos
- **Índices optimizados** en base de datos
- **Consultas eficientes** con JOINs optimizados
- **Prepared statements** en todas las consultas
- **TTL configurable** para caché

---

## 🧩 Stack Tecnológico

### Backend

- **PHP 7.4+** con orientación a objetos
- **MySQL 5.7+** / **MariaDB 10.2+**
- **PDO** para conexiones seguras

### Frontend

- **HTML5** semántico
- **CSS3** con diseño moderno
- **JavaScript ES6+**
- **Bootstrap 5** para responsividad
- **Font Awesome** para iconografía

### Funcionalidades Avanzadas

- **Variables de entorno** (.env) para configuración
- **Sistema de triggers** en base de datos
- **Vistas optimizadas** para estadísticas
- **Índices FULLTEXT** para búsquedas
- **API RESTful** (disponible)

---

## 🎯 Casos de Uso Ideales

Este sistema es perfecto para:

- 🏢 **Empresas** que organizan rifas corporativas
- 🎪 **Organizaciones sin fines de lucro** para recaudación de fondos
- 💼 **Emprendedores** que gestionan rifas como negocio
- 🏆 **Eventos** que requieren sorteos profesionales
- 🎁 **Comercios** que realizan promociones con rifas
- 📱 **Influencers** que organizan sorteos para su comunidad

---

## 💼 Enfoque Profesional

Este proyecto está diseñado como una **solución empresarial lista para producción**:

- ✅ Arquitectura escalable y mantenible
- ✅ Separación clara de responsabilidades
- ✅ Código limpio y documentado
- ✅ Seguridad de nivel empresarial
- ✅ Optimizado para alto rendimiento
- ✅ Interfaz intuitiva y moderna
- ✅ Sistema de auditoría completo
- ✅ Soporte multi-dispositivo

---

## 📄 Licencia

Este proyecto es de uso privado. **Todos los derechos reservados**.

---

## 💬 Contacto & Demo

### 🎯 ¿Interesado en este sistema?

Este repositorio es **solo demostrativo** para fines de portafolio. El código fuente completo, documentación técnica, instalación y soporte están disponibles mediante **compra o licencia**.

### 📩 ¿Cómo obtener el sistema completo?

Si deseas:

- ✅ **Comprar el sistema completo** con código fuente
- 💻 **Solicitar una demo en vivo** del sistema
- 🛠️ **Contratar instalación y configuración** personalizada
- 🎨 **Solicitar personalización** o desarrollo a medida
- 📞 **Obtener más información** sobre funcionalidades y pricing

### 📧 Contáctame:

> **Envíame un mensaje** para obtener más información, solicitar una demo personalizada o discutir los detalles de compra.
>
> Los interesados recibirán acceso a:
>
> - ✨ Demo en vivo totalmente funcional
> - 📚 Documentación técnica completa
> - 💾 Código fuente completo
> - 🛠️ Guía de instalación detallada
> - 🎯 Soporte técnico durante la instalación
> - 🔄 Actualizaciones y mejoras futuras

---

<div align="center">

### 🌟 Sistema Profesional • Seguro • Escalable • Listo para Producción 🌟

</div>
