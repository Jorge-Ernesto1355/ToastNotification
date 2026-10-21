# 🍞 Toast Notifications (Notify.js)

Un sistema de notificaciones flotantes (`Toasts`) ligero, moderno, accesible y sin dependencias externas, escrito en **JavaScript Vanilla**. Cuenta con soporte para gestos táctiles/arrastre (swipe-to-dismiss), barras de progreso temporizadas, accesibilidad (ARIA) y múltiples posiciones en pantalla.

---

## ✨ Características

* **Sin dependencias:** Cero frameworks o librerías pesadas (puro JavaScript y CSS).
* **Tipos predefinidos:** `success`, `error`, `warning` e `info`.
* **Interactividad táctil/mouse:** Permite arrastrar la notificación hacia los lados para descartarla.
* **Accesible:** Atributos ARIA integrados (`role="status"`, `role="alert"`, `aria-live`) y soporte para cerrar con la tecla **Escape**.
* **Acciones personalizadas:** Añade botones interactivos dentro de la notificación (ej. "Deshacer", "Ver detalles").
* **Control de apilamiento:** Límite máximo configurable para evitar saturar la pantalla.
* **Temporizador visual:** Barra de progreso automática que indica el tiempo restante.

---

## 🚀 Guía de Uso

### 1. Métodos Directos (Atajos)
La forma más rápida de lanzar una notificación es usando los métodos específicos por tipo:

```javascript
Notify.success("¡Éxito!", "Los cambios se guardaron correctamente.");
Notify.error("Error", "No se pudo conectar con el servidor.");
Notify.warning("Cuidado", "Tu sesión está a punto de expirar.");
Notify.info("Información", "Hay una nueva actualización disponible.");
