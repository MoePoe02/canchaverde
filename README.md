# 🏟️ CanchaVerde - Directorio de Canchas Deportivas en CABA

Guía completa y catálogo interactivo de complejos deportivos de alquiler comercial (Fútbol, Pádel y Tenis) en la **Ciudad Autónoma de Buenos Aires (CABA)**.

Permite buscar canchas por barrio, ordenar por cercanía GPS en tiempo real o por calificaciones de Google Maps, consultar turnos directo por WhatsApp y guardar tus canchas favoritas en el dispositivo.

---

## ⚡ Características Principales

* 📍 **Cobertura en los 48 Barrios de CABA**: Filtro ágil por comuna y barrio oficial.
* 🛰️ **Cálculo de Distancia GPS en Vivo**: Ordenamiento por cercanía geográfica desde la ubicación exacta del usuario.
* ⭐ **Puntajes y Reseñas Reales**: Datos sincronizados con Google Maps.
* 💬 **Contacto Directo por WhatsApp**: Mensajes de reserva pre-armados hacia el número oficial del complejo.
* ❤️ **Sección de Canchas Favoritas**: Guardado instantáneo con persistencia local (`localStorage`).
* 🎨 **Diseño Moderno y Responsivo**: Optimizado para teléfonos móviles y computadoras (Tailwind CSS).

---

## 📁 Estructura del Repositorio

```text
canchaverde/
├── index.html        # Aplicación web interactiva (Single Page App)
├── data/
│   └── canchas.json  # Catálogo verificado de canchas de CABA
├── canchas_caba.txt  # Listado de referencia en texto plano
└── README.md
```

---

## 🚀 Despliegue en GitHub Pages

Este proyecto es **100% estático** (HTML, CSS y JavaScript vanilla). No requiere servidores ni bases de datos activas:

1. Ve a **Settings > Pages** en tu repositorio de GitHub.
2. En **Build and deployment > Source**, selecciona `Deploy from a branch`.
3. Elige la rama `main` y la carpeta `/ (root)`.
4. ¡Listo! Tu web estará online en minutos con HTTPS gratuito.
