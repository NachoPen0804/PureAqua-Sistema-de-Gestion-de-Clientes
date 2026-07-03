# PureAqua — Sistema de gestión de clientes
 
Una aplicación web de gestión de clientes desarrollada para **PureAqua**, una empresa de tratamiento de aguas con sede en Picassent, Valencia, España.

## Descripción general

PureAqua gestiona contratos de mantenimiento recurrentes con clientes residenciales y comerciales. Esta aplicación sustituye su anterior flujo de trabajo en Excel por una interfaz web en tiempo real a la que se puede acceder desde cualquier dispositivo.

## Características

### Vista de oficina (`oficina.html`)
- Base de datos de clientes organizada por año y mes
- Búsqueda y filtrado por tipo de equipo, estado de pago y frecuencia
- Estadísticas de ingresos: total facturado, cobrado y nuevas ventas
- Añadir, editar y eliminar clientes
- Importación/exportación a Excel (mismo formato que las hojas de cálculo originales)
- Asignación de tareas diarias al técnico sobre el campo

### Vista del técnico (`tecnico.html`)
- Lista de tareas optimizada para móviles asignada por la oficina
- Confirmación con un solo toque mediante un cuadro de diálogo de confirmación
- Enlace directo a Google Maps para la dirección de cada cliente
- Búsqueda completa de clientes en todos los registros

## Pila tecnológica

- **Frontend:** HTML puro, CSS, JavaScript — sin marcos de trabajo, sin pasos de compilación
- **Backend:** Supabase (PostgreSQL + Realtime)
- **Alojamiento:** Netlify
- **Iconos:** Tabler Icons

## Capturas de pantalla
 
Abre `oficina.html` o `tecnico.html` en un navegador para ver la demostración en vivo con datos de ejemplo.
 
---
 
*Esta es una demostración de portafolio. Todos los datos de clientes que se muestran son ficticios.*
