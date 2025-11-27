# 🎰 Sistema de Rifas - Gestión Completa de Rifas y Sorteos

<div align="center">

![PHP](https://img.shields.io/badge/PHP-7.4+-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-5.7+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Sistema profesional de gestión de rifas y sorteos con arquitectura escalable y seguridad empresarial**

[Características](#-características-y-módulos) • [Stack Tecnológico](#-stack-tecnológico) • [Contacto](#-contacto--demo)

</div>

---

## 📋 Descripción General

Sistema web profesional para la **gestión integral de rifas y sorteos**, desarrollado con **PHP + MySQL**. Solución completa con frontend público para clientes y panel de administración avanzado, ideal para empresas, organizaciones y emprendedores que buscan profesionalizar sus rifas con una plataforma robusta, segura y escalable.

---

## 🚀 Características y Módulos

### 🌐 Frontend Público

#### 🏠 Página Principal

- Hero section personalizable con gradientes y banners
- Carrusel de rifas destacadas y finalizadas con ganadores
- Diseño responsive para todos los dispositivos

#### 🎰 Catálogo de Rifas

- Listado completo con filtros por categoría y estado
- Búsqueda inteligente
- Cards informativas con datos clave en tiempo real

#### 🎯 Compra de Tickets

- Galería de imágenes de alta calidad
- Selector interactivo de números con disponibilidad en tiempo real
- Múltiples métodos de pago configurables
- Carga y verificación de comprobantes
- Confirmación con URL segura (hash único) para compartir

---

### 🔐 Panel de Administración

#### � Dashboard

- Estadísticas y métricas en tiempo real
- Resumen de rifas por estado (activas, cerradas, finalizadas)
- Gráficos de actividad y ventas
- Alertas de tickets pendientes de verificación

#### 🎪 Gestión de Rifas

- Creación con configuración completa (números, precios, imágenes, fechas)
- Edición con validaciones de seguridad
- Control de estados y categorías
- Galería de hasta 5 imágenes por rifa

#### 🎫 Gestión de Tickets

- Listado con filtros avanzados por estado
- Visualización y verificación de comprobantes
- Sistema de alertas para tickets expirados
- Estadísticas de pagos (pendientes, verificados, denegados)

#### � Sistema de Sorteos

- Modalidades flexibles:
  - Entre todos los números del rango
  - Solo números vendidos y verificados
  - Exclusión de números en verificación
- Sorteos múltiples (hasta 10 ganadores)
- Animación de ruleta en vivo
- Vista de streaming para audiencia pública
- Registro automático de ganadores

#### ⚙️ Configuración del Sistema

Acceso exclusivo para administradores:

- **General**: Nombre del sitio, contacto, textos personalizables
- **Apariencia**: Logo, banner, colores, gradientes, modo oscuro/claro
- **Sistema**: Límites de upload, días de verificación, rate limiting
- **Base de Datos**: Exportación, importación, backups y restauración
- **Email (SMTP)**: Configuración de servidor y pruebas de envío
- **Métodos de Pago**: Creación, edición y activación de métodos

---

### 👤 Sistema de Roles

**🔑 Administrador**: Acceso total (usuarios, configuración, rifas, tickets, sorteos, auditoría)  
**👔 Operador**: Gestión de rifas, tickets y sorteos (sin acceso a configuración del sistema ni usuarios)

---

### 🔒 Seguridad y Optimización

**Seguridad Empresarial:**

- Protección CSRF, SQL Injection y XSS
- Rate limiting por IP y sesión
- Hashing Bcrypt y regeneración de IDs de sesión
- Validación avanzada de archivos subidos

**Performance:**

- Caché multinivel (APCu + archivos) con TTL configurable
- Lazy loading y compresión automática de imágenes
- Batch processing e índices optimizados en BD
- Prepared statements en todas las consultas

---

## 📸 Screenshots

<div align="center">

### Frontend Público

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://imgur.com/q6pblih.png" alt="Página Principal" width="100%" />
      <b>🏠 Página Principal</b>
      <p><em>Hero section y rifas destacadas</em></p>
    </td>
    <td align="center" width="33%">
      <img src="https://imgur.com/qOOG0rK.png" alt="Catálogo de Rifas" width="100%" />
      <b>🎰 Catálogo de Rifas</b>
      <p><em>Filtros y búsqueda inteligente</em></p>
    </td>
    <td align="center" width="33%">
      <img src="https://imgur.com/EiJKLS5.png" alt="Detalle de Rifa" width="100%" />
      <b>🎯 Detalle de Rifa</b>
      <p><em>Selector de números y compra</em></p>
    </td>
  </tr>
</table>

### Panel de Administración

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://imgur.com/UhfDEt5.png" alt="Dashboard Admin" width="100%" />
      <b>📊 Dashboard</b>
      <p><em>Estadísticas en tiempo real</em></p>
    </td>
    <td align="center" width="33%">
      <img src="https://imgur.com/ssQ24CB.png" alt="Gestión de Rifas" width="100%" />
      <b>🎪 Gestión de Rifas</b>
      <p><em>Creación y edición</em></p>
    </td>
    <td align="center" width="33%">
      <img src="https://imgur.com/aFa5lTc.png" alt="Gestión de Tickets" width="100%" />
      <b>🎫 Gestión de Tickets</b>
      <p><em>Verificación de pagos</em></p>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <img src="https://imgur.com/XTKk7fE.png" alt="Sistema de Sorteos" width="100%" />
      <b>🎲 Sistema de Sorteos</b>
      <p><em>Animación de sorteos</em></p>
    </td>
    <td align="center" width="33%">
      <img src="https://imgur.com/gSWQVpr.png" alt="Configuración" width="100%" />
      <b>⚙️ Configuración</b>
      <p><em>Panel de configuración</em></p>
    </td>
    <td align="center" width="33%">
      <img src="https://imgur.com/BgHG3Yh.png" alt="Sorteo en Vivo" width="100%" />
      <b>📺 Sorteo en Vivo</b>
      <p><em>Vista de streaming público</em></p>
    </td>
  </tr>
</table>

</div>

> **Nota**: Screenshots del sistema completo disponibles bajo solicitud. Contacta para acceso a demo en vivo.

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

## 🎯 Enfoque y Casos de Uso

Solución **empresarial lista para producción** con arquitectura escalable, código limpio, seguridad de nivel empresarial y sistema de auditoría completo.

**Ideal para:**

- 🏢 Empresas y organizaciones corporativas
- 🎪 ONGs para recaudación de fondos
- 💼 Emprendedores del sector de rifas
- 🏆 Eventos y promociones comerciales
- 📱 Creadores de contenido y comunidades

---

## 📄 Licencia

Este proyecto es de uso privado. **Todos los derechos reservados**.

---

## 💬 Contacto & Demo

Este repositorio es **solo demostrativo** para fines de portafolio. El código fuente completo y soporte están disponibles mediante **compra o licencia**.

**Servicios disponibles:**

- ✅ Compra del sistema completo con código fuente
- 💻 Demo en vivo personalizada
- 🛠️ Instalación y configuración profesional
- 🎨 Personalización y desarrollo a medida

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

<img src="https://imgur.com/SBaKBq4.png">

</div>


