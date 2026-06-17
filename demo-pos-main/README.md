# CoffeePOS Premium Pro

Sistema web front-end para restaurante, pensado como proyecto de portafolio estudiantil y base de aprendizaje profesional.  
Incluye inicio de sesión, panel del negocio, mesas, toma de pedidos, flujo hacia cocina, compras, ventas y análisis simple de compraventa.

---

## ¿Qué hace este sistema?

Este proyecto simula la operación básica de un restaurante:

- iniciar sesión;
- visualizar un panel administrativo;
- ver el estado de las mesas;
- tomar pedidos desde mesa;
- enviar pedidos a cocina;
- cambiar estados de cocina;
- cerrar cuentas y registrar ventas;
- registrar compras e insumos;
- revisar un resumen simple del negocio.

Todo funciona en el navegador usando **HTML, CSS, JavaScript y LocalStorage**.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript Vanilla
- LocalStorage

---

## Estructura del proyecto

```bash
demo-pos/
├── index.html
├── README.md
└── assets
    ├── css
    │   └── styles.css
    └── js
        ├── data.js
        └── app.js
```

---

## Cómo ejecutar el proyecto

### Opción 1. Muy fácil
1. Descomprime el archivo ZIP.
2. Abre la carpeta en **Visual Studio Code**.
3. Abre el archivo `index.html` con **Live Server**.

### Opción 2. Directo en navegador
1. Descomprime el archivo ZIP.
2. Haz doble clic en `index.html`.

> Recomendación: usar **Live Server** para trabajar más cómodo y ver cambios en tiempo real.

---

## Usuario de prueba

**Correo:** `admin@demo.com`  
**Contraseña:** `admin123`

También puedes probar:

**Correo:** `mesera@demo.com`  
**Contraseña:** `mesera123`

---

## Módulos incluidos

### 1. Inicio de sesión
Permite ingresar al sistema con credenciales demo.

### 2. Resumen del negocio
Muestra:
- ventas del día;
- compras registradas;
- mesas activas;
- pedidos en cocina;
- actividad reciente;
- indicadores rápidos.

### 3. Gestión de mesas
Permite:
- ver mesas libres y ocupadas;
- abrir pedido por mesa;
- agregar productos;
- guardar borrador;
- enviar a cocina;
- cerrar la cuenta.

### 4. Cocina
Permite:
- ver pedidos enviados;
- revisar productos solicitados;
- cambiar estado a “listo”.

### 5. Compras
Permite:
- registrar compras;
- guardar proveedor;
- cargar cantidad y valor;
- revisar historial.

### 6. Ventas
Permite:
- revisar pedidos pagados;
- ver total vendido;
- estimar balance simple entre compras y ventas.

### 7. Catálogo
Muestra el menú base del restaurante.

---

## Cómo está organizado el código

### `index.html`
Contiene toda la estructura visual del sistema:
- sidebar;
- topbar;
- vistas;
- formularios;
- modales.

### `assets/css/styles.css`
Contiene:
- paleta de colores;
- diseño responsive;
- tarjetas;
- tablas;
- modales;
- botones;
- estados visuales.

### `assets/js/data.js`
Contiene la data semilla del sistema:
- usuarios;
- menú;
- mesas;
- pedidos;
- compras;
- actividad.

### `assets/js/app.js`
Contiene toda la lógica:
- login;
- navegación;
- renderizado;
- gestión de mesas;
- pedidos;
- cocina;
- compras;
- ventas;
- LocalStorage.

---

## Mejoras recomendadas para llevarlo a otro nivel

Estas son mejoras reales que los estudiantes pueden implementar para fortalecer el proyecto y hacerlo aún más profesional.

### Nivel 1. Mejora visual
- cambiar paleta de colores;
- agregar logo real del restaurante;
- mejorar iconografía;
- agregar fotos de platos;
- usar tipografías institucionales.

### Nivel 2. Mejora funcional
- separar vistas en varios archivos;
- añadir búsqueda de pedidos;
- filtrar mesas por estado;
- permitir eliminar compras;
- imprimir factura simple;
- agregar método de pago.

### Nivel 3. Mejora técnica
- usar `modules` de JavaScript;
- dividir el código en componentes;
- crear utilidades aparte;
- mejorar validaciones;
- controlar errores con mayor detalle.

### Nivel 4. Mejora profesional
- migrar a backend con Node.js + Express;
- conectar base de datos MySQL o PostgreSQL;
- crear autenticación real;
- guardar pedidos por usuario;
- generar reportes por fecha;
- desplegar en Render, Vercel o Netlify.

---

## Ideas de evolución del proyecto

Este sistema puede evolucionar hacia:

- POS real para restaurante;
- sistema multiusuario;
- panel para domicilios;
- control de caja;
- inventario completo;
- impresión de comandas;
- módulo de facturación;
- módulo de clientes frecuentes.

---

## Qué puede practicar un estudiante con este proyecto

- lectura de código existente;
- modificación y personalización de páginas;
- ajuste de scripts y estilos;
- manejo del DOM;
- eventos en JavaScript;
- diseño responsive;
- organización de carpetas;
- creación de proyectos para GitHub.

---

## Recomendación docente o de portafolio

Para que el repositorio se vea más fuerte, se recomienda que el estudiante agregue:

- capturas del sistema;
- GIF o video corto;
- explicación de cambios realizados;
- nuevas funciones creadas por él;
- problemas encontrados y cómo los resolvió.

---

## Créditos de uso

Proyecto base creado como material de aprendizaje y mejora progresiva para estudiantes de desarrollo de software.

Puedes modificarlo, personalizarlo y usarlo como base para prácticas, talleres y portafolio.
