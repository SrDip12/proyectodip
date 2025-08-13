# Generador de Presupuestos de Ventanas 🪟 (Window-Budget-Generator)

**Window-Budget-Generator** es una aplicación web full-stack conceptualizada para transformar la industria de instalación de ventanas. Su objetivo es reemplazar los métodos de cotización manuales, lentos y propensos a errores, por una plataforma digital, instantánea y transparente que gestiona tanto productos a medida como productos en stock.

-----

## 🎯 El Problema a Solucionar

Generar un presupuesto para ventanas es un proceso complejo que involucra múltiples variables: medidas, tipo de vidrio, material del marco y herrajes. Tradicionalmente, esto requiere la visita de un técnico y varios días de espera. Para productos estándar, la consulta de stock es un proceso manual adicional.

**Nuestra solución** centraliza todo en una aplicación intuitiva. Permite la **personalización completa** para proyectos a medida y ofrece un **catálogo de productos estándar** con disponibilidad en tiempo real, entregando un costo final de manera instantánea y transparente.

-----

## 💡 Tipos de Ventanas y Materiales

Una de las claves de la aplicación es educar al usuario sobre el impacto de su elección. Cada material tiene beneficios específicos en aislamiento, seguridad y estética.

### Tipos de Vidrio

  * 🌡️ **Termo-panel (Doble Vidriado Hermético - DVH):** Es el estándar para la eficiencia energética. Consiste en dos láminas de vidrio separadas por una cámara de aire o gas argón, lo que reduce drásticamente la transferencia de temperatura. **Ideal para:** Reducir costos de climatización y un excelente aislamiento acústico.
  
  * 🛡️ **Laminado:** Compuesto por vidrios unidos por una lámina de PVB. En caso de rotura, los fragmentos quedan adheridos, evitando accidentes. **Ideal para:** Seguridad contra impactos, protección contra robos y un excelente filtro de rayos UV (99%).
  
  * 🌫️ **Satinado (o Esmerilado):** Un vidrio tratado para obtener una superficie traslúcida que difumina la luz. **Ideal para:** Baños, oficinas y cualquier espacio donde se requiera privacidad sin sacrificar la entrada de luz.
  
  * 💧 **Normal (Monolítico):** Una sola lámina de vidrio. Es la opción más económica. **Ideal para:** Espacios interiores o donde el aislamiento y la seguridad no son la máxima prioridad.

### Tipos de Marco

  * **PVC (Policloruro de Vinilo):** Es un material no conductor, lo que le confiere un **excelente aislamiento térmico y acústico**. No se oxida, requiere muy bajo mantenimiento y sus esquinas soldadas garantizan una gran hermeticidad.
  
  * **Aluminio (con Ruptura de Puente Térmico - RPT):** Famoso por su **durabilidad, ligereza y resistencia**. Permite perfiles más delgados para vistas más limpias. La RPT inserta un material aislante en el marco para mejorar su eficiencia energética.

-----

## 🚀 Módulos y Funcionalidades Clave

  * 🔐 **Módulo de Autenticación:** Registro y login con roles para **usuarios** (clientes) y **administradores**.
  
  * 🖥️ **Generador de Presupuestos a Medida:** El corazón de la aplicación, con una interfaz visual paso a paso para ventanas personalizadas.
  
  * 🛒 **Catálogo de Ventanas Estándar (En Stock):**
  
      * Ofrece un catálogo de ventanas pre-configuradas con las medidas más comunes del mercado (ej: 1.0m x 1.0m, 1.5m x 1.2m, 2.0m x 1.0m).
      
      * Cada producto en este catálogo está **directamente vinculado al Módulo de Inventario**, mostrando la disponibilidad en tiempo real.
      
  * **Beneficio:** Permite a los clientes comprar productos para entrega inmediata a un costo potencialmente reducido, simplificando drásticamente el proceso de compra.
  
  * 🗂️ **Historial de Presupuestos:** Panel personal donde los usuarios guardan y consultan sus cotizaciones, tanto a medida como de productos estándar.
  
  * ⚙️ **Panel de Administración:** Para gestionar usuarios, precios de materiales, configuraciones globales y el inventario.

-----

## 🗺️ Hoja de Ruta: Próximos Módulos

Para convertir esta herramienta en una solución empresarial completa, se planea el desarrollo de los siguientes módulos:

  * 📦 **Módulo de Gestión de Inventario:**
  
      * Control de stock en tiempo real de **materias primas** (perfiles, planchas de vidrio, herrajes) y de **productos terminados** (las ventanas del catálogo estándar).
      
      * Alertas automáticas para niveles bajos de inventario.
      
      * Asociación de materias primas a los costos de producción de ventanas a medida.
  
  * 📊 **Módulo de Reportes y Analíticas:**
  
      * Dashboard para administradores con métricas clave: ventanas más vendidas (estándar y a medida), ingresos por período, etc.
      
      * Generación de reportes en PDF/Excel sobre ventas y tendencias de inventario.
  
  * 🏗️ **Módulo de Gestión de Proyectos:**
  
      * Permitir a los usuarios agrupar múltiples ventanas (a medida o estándar) en un solo "proyecto" (ej: "Casa Completa", "Oficina Piso 2").
      
      * Asignar estados a los proyectos (Cotizado, Aprobado, En Fabricación, Instalado).
  
  * 🤝 **Módulo de Clientes (CRM Básico):**
  
      * Base de datos de clientes con historial de proyectos y comunicaciones.
      
      * Seguimiento de oportunidades de venta desde la cotización hasta el cierre.

-----

## 🛠️ Tecnologías Propuestas

| Categoría | Tecnologías |
| :--- | :--- |
| **Frontend** | React (con Vite) / Vue 3 / SvelteKit |
| **Backend** | Node.js con Express y TypeScript / Python con FastAPI |
| **Base de Datos**| PostgreSQL / MongoDB |
| **Estilos** | TailwindCSS / Styled-Components |
| **Reportes** | D3.js (para gráficos) / `pdf-lib` (para PDFs) |
| **Despliegue** | Vercel / Netlify / Docker / AWS |

-----

