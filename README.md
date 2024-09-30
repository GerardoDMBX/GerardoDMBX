# **Proyecto: Aplicación de Distribución de Alimentos con Despacho a Domicilio**

## **Descripción General**
Este proyecto consiste en el desarrollo de un prototipo no funcional de una aplicación móvil para una empresa de distribución de alimentos que ofrece un servicio de despacho a domicilio. El prototipo permite a los usuarios registrar sus compras, calcular los costos de despacho según reglas de negocio predefinidas y monitorear la temperatura de los productos refrigerados durante la entrega. El administrador de la aplicación podrá recibir alertas si la cadena de frío se ve comprometida.

## **Modelo de Negocio - Canvas**
El modelo de negocio se diseñó utilizando la metodología Canvas para identificar los elementos clave del proyecto, asegurando que la aplicación cumpla con las necesidades de la empresa y de los clientes. El modelo se encuentra disponible en el directorio `/ModeloCanvas` y cubre los siguientes aspectos:

- **Propuesta de valor:** Servicio de despacho eficiente y monitoreo de temperatura para productos refrigerados.
- **Segmento de clientes:** Clientes que compran productos y requieren despacho a domicilio, así como el administrador que supervisa la cadena de frío.
- **Canales:** Aplicación móvil para Android Oreo (clientes) y Android Lollipop (administrador).
- **Relación con los clientes:** Registro mediante cuentas Gmail y notificaciones sobre el estado del pedido.
- **Flujo de ingresos:** Ventas de productos y tarifas de despacho.
- **Recursos clave:** Herramientas de desarrollo, equipo de transporte, infraestructura tecnológica.
- **Actividades clave:** Desarrollo de la aplicación, integración de monitoreo de temperatura.
- **Socios clave:** Proveedores de productos y empresas de transporte.
- **Estructura de costos:** Desarrollo y mantenimiento de la aplicación, infraestructura en la nube.

## **Prototipo No Funcional**
El prototipo fue desarrollado utilizando Pencil, una herramienta de diseño de interfaces. Las pantallas incluyen:

1. **Pantalla de Inicio de Sesión:** Permite a los usuarios registrarse o iniciar sesión utilizando cuentas Gmail.
2. **Pantalla Principal de Productos:** Muestra la lista de productos disponibles y permite agregarlos al carrito.
3. **Pantalla de Cálculo de Valor de Despacho:** Calcula automáticamente el costo de despacho basado en las reglas de negocio.
4. **Pantalla de Estado de Despacho:** Permite al usuario hacer seguimiento de su pedido.
5. **Pantalla de Monitoreo de Temperatura:** Alerta al administrador si la temperatura del congelador excede los límites permitidos.

Las imágenes del prototipo están disponibles en el directorio `/Prototipo`.

## **Reglas de Negocio**
- **Despacho Gratuito:** Para compras superiores a $50,000 dentro de un radio de 20 km.
- **Tarifa de $150 por km:** Para compras entre $25,000 y $49,999.
- **Tarifa de $300 por km:** Para compras inferiores a $25,000.

El cálculo del despacho se realiza automáticamente dentro de la aplicación para cada pedido, según la ubicación y monto total de la compra.

## **Requisitos Funcionales y No Funcionales**
- **Funcionales:**
  - Registro e inicio de sesión mediante Gmail.
  - Cálculo automático del costo de despacho.
  - Monitoreo de temperatura en tiempo real para productos congelados.
  - Visualización del estado de despacho y notificaciones.

- **No Funcionales:**
  - La aplicación debe ser compatible con Android Lollipop (administrador) y Android Oreo (clientes).
  - La aplicación debe ser intuitiva y fácil de usar.

## **Tecnologías Utilizadas**
- **Diseño del Modelo de Negocio:** Canvas
- **Prototipo No Funcional:** Pencil

## **Estructura del Repositorio**
- **README.md:** Documentación del proyecto.
- **/Prototipo:** Contiene las imágenes del prototipo de la aplicación.
- **/ModeloCanvas:** Incluye el modelo de negocio Canvas.
- **/Documentación:** Documentos adicionales sobre el desarrollo del proyecto.

<!---
GerardoDMBX/GerardoDMBX is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
