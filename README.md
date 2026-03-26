# 🎫 Sistema de Gestión de Rifas - Vibras Positivas

Una aplicación web ligera, rápida y personalizada para la gestión de rifas de 100 números (00-99). Diseñada para funcionar directamente desde el navegador, permitiendo el control total de ventas, cobros y personalización de premios.

## 🚀 Características principales

- **Panel de Configuración en Vivo:** Cambia el título, premio, precio, lotería y fecha del sorteo en tiempo real.
- **Control de Ventas Automático:** Registra el nombre del comprador haciendo clic sobre el número.
- **Semáforo de Pagos:**
  - 🟢 **Verde:** Cuando el registro incluye la palabra **"pago"**.
  - 🔴 **Rojo:** Cuando el registro incluye la palabra **"debe"**.
  - ⚪ **Blanco:** Números disponibles.
- **Sistema de Backup:** Descarga y restaura copias de seguridad para no perder tu información si cambias de dispositivo.
- **Diseño Responsivo:** Optimizado para celulares y tablets.

## 🛠️ Cómo utilizar

1. **Configuración:** En la parte superior, completa los datos de tu rifa. Estos se guardarán automáticamente.
2. **Vender un número:** Toca cualquier número en la cuadrícula. Se abrirá una ventana para ingresar el nombre del cliente.
3. **Marcar estados:**
   - Si el cliente ya pagó, escribe: `Nombre Apellido PAGO`.
   - Si el cliente aún no paga, escribe: `Nombre Apellido DEBE`.
4. **Seguridad:** Utiliza el botón **📥 Backup** periódicamente para descargar tu base de datos en formato JSON. Si necesitas abrir la app en otro teléfono, usa **📤 Restaurar** con ese mismo archivo.

## 📋 Tecnologías utilizadas

- HTML5
- CSS3 (Flexbox & Grid)
- JavaScript (Vanilla)
- LocalStorage (Persistencia de datos local)

## ⚖️ Derechos de Autor

App desarrollada por **Vibras Positivas**. 
Derechos de Autor reservados (3117700431).

---
*Optimizado para ser alojado en GitHub Pages.*
