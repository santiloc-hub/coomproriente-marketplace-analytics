# Encuestas Coomproriente - Centro de Abastos

## Descripción del Proyecto

Este repositorio contiene datos simulados de tres encuestas realizadas a diferentes perfiles involucrados en el ecosistema del Centro de Abastos y la plataforma web de Coomproriente:

1. **Consumidores**: Personas que compran productos agrícolas en el Centro de Abastos.
2. **Transportistas**: Profesionales que transportan mercancía desde y hacia el Centro de Abastos.
3. **Comerciantes**: Vendedores y comerciantes que operan en el Centro de Abastos.

El objetivo de estas encuestas es evaluar el conocimiento, uso y necesidades de mejora de la plataforma web actual de Coomproriente, que publica reportes de precios agrícolas, así como identificar oportunidades para desarrollar nuevas funcionalidades, incluyendo un posible e-commerce.

## Estructura de los Archivos

Este repositorio contiene los siguientes archivos CSV con datos simulados:

- `respuestas_consumidores.csv`: 50 respuestas de consumidores
- `respuestas_transportistas.csv`: 50 respuestas de transportistas
- `respuestas_comerciantes.csv`: 50 respuestas de comerciantes

## Cuestionarios y Guía de Interpretación

A continuación se detallan las preguntas de cada cuestionario y cómo interpretar las respuestas:

---

## I. Perfil: Consumidor

| Código | Tipo | Pregunta | Respuestas / Escala |
|--------|------|----------|---------------------|
| C1 | Demográfica | ¿Con qué frecuencia compras productos agrícolas directamente al Centro de Abastos? | 1=Nunca, 2=Rara vez, 3=Ocasionalmente, 4=Frecuentemente, 5=Siempre |
| C2 | Cerrada | ¿Conoces la página de Coomproriente donde solo se publican los precios agrícolas? | 1=Sí, 2=No |
| C3 | Cerrada | Si respondiste "Sí" en C2: ¿Con qué frecuencia consultas esos reportes de precio? | 1=Nunca, 2=Una vez al año, 3=Varias veces al año, 4=Una vez al mes, 5=Semanal |
| C4 | Likert | ¿Qué tan fácil te resulta encontrar los precios que buscas en esos reportes? | 1=Muy difícil → 5=Muy fácil |
| C5 | Likert | ¿Qué tan completa encuentras la información de cantidades y unidades (Kg, bulto, caja)? | 1=Muy incompleta → 5=Muy completa |
| C6 | Likert | ¿Qué tan claro está el formato de presentación de los datos (tabla, fecha, origen)? | 1=Muy confuso → 5=Muy claro |
| C7 | Likert | ¿Qué tan satisfecho(a) estás con la actualización y puntualidad de los precios publicados? | 1=Muy insatisfecho → 5=Muy satisfecho |
| C8 | Cerrada | En tu opinión, ¿sería útil poder **pedir y pagar** productos directamente desde la web? | 1=Nada útil, 2=Poco útil, 3=Medianamente útil, 4=Útil, 5=Muy útil |
| C9 | Likert | ¿Qué tan cómodo te sentirías usando un carrito de compras y métodos de pago en línea? | 1=Muy incómodo → 5=Muy cómodo |
| C10 | Abierta | ¿Qué funcionalidades añadirías para que la web te facilite la compra (p.ej. filtro de productos, chat, seguimiento de pedido)? | Respuesta libre |

### Notas para interpretación - Consumidores:

- **C1**: Indica la frecuencia con que el consumidor visita el Centro de Abastos. Valores más altos (4-5) indican usuarios frecuentes.
- **C2**: Determina si el consumidor conoce la plataforma web actual. Respuestas "1" (Sí) significan que conocen la plataforma.
- **C3-C7**: Estas preguntas solo aplican si el consumidor conoció "Sí" en C2. Si no conoce la página, estos campos contienen "-" (guion).
- **C8-C9**: Evalúan el interés en una nueva funcionalidad de e-commerce. Valores más altos indican mayor interés.
- **C10**: Proporciona ideas específicas para mejorar la plataforma desde la perspectiva del consumidor.

---

## II. Perfil: Transportista

| Código | Tipo | Pregunta | Respuestas / Escala |
|--------|------|----------|---------------------|
| T1 | Demográfica | ¿Qué tipo de vehículo usas para transportar la mercancía? | a) Camión pequeño b) Camión mediano c) Camión grande |
| T2 | Cerrada | ¿Conoces el portal de precios de Coomproriente? | 1=Sí, 2=No |
| T3 | Cerrada | Si respondiste "Sí" en T2: ¿Lo consultas para planificar tus rutas o costos? | 1=Nunca, 2=Rara vez, 3=Ocasionalmente, 4=Frecuentemente, 5=Siempre |
| T4 | Likert | ¿Qué tan clara y suficiente encuentras la info de precios para tus cotizaciones? | 1=Muy insuficiente → 5=Muy suficiente |
| T5 | Cerrada | ¿Sueles requerir datos adicionales (peso, volumen, tiempos) que no aparecen en el reporte de precios? | 1=Sí, 2=No |
| T6 | Likert | ¿Qué tan importante sería para ti un módulo donde los comerciantes hagan pedidos y asignen rutas? | 1=Nada importante → 5=Muy importante |
| T7 | Cerrada | ¿Crees que un sistema en línea que integre pedidos y rutas te ahorraría llamadas o desplazamientos? | 1=Sí, 2=No |
| T8 | Abierta | ¿Qué datos adicionales o herramientas en la web te ayudarían a optimizar tu trabajo? | Respuesta libre |

### Notas para interpretación - Transportistas:

- **T1**: Clasifica al transportista según el tamaño de su vehículo, lo que permite segmentar por capacidad de carga.
- **T2**: Determina si el transportista conoce la plataforma actual. Respuestas "1" (Sí) significan que conocen la plataforma.
- **T3-T4**: Estas preguntas solo aplican si el transportista respondió "Sí" en T2. Si no conoce el portal, estos campos contienen "-" (guion).
- **T5**: Identifica si la información actual es suficiente. Respuestas "1" (Sí) indican necesidad de datos adicionales.
- **T6-T7**: Evalúan el interés en un sistema de gestión logística integrado. Valores más altos en T6 y respuestas "1" en T7 indican mayor interés.
- **T8**: Proporciona ideas específicas para mejorar la plataforma desde la perspectiva del transportista.

---

## III. Perfil: Comerciante

| Código | Tipo | Pregunta | Respuestas / Escala |
|--------|------|----------|---------------------|
| M1 | Demográfica | ¿Cuánto tiempo llevas operando en el Centro de Abastos? | 1=<1 año, 2=1–3 años, 3=3–5 años, 4=>5 años |
| M2 | Cerrada | ¿Conoces la página de Coomproriente con los reportes de precios? | 1=Sí, 2=No |
| M3 | Cerrada | Si "Sí" en M2: ¿Con qué fin principal la usas? | a) Ver precios b) Comparar proveedores c) Historial |
| M4 | Likert | ¿Qué tan actualizada está la información de precios y stock en ese reporte? | 1=Muy desactualizada → 5=Muy actualizada |
| M5 | Cerrada | ¿Has tenido que contactar por otro medio para confirmar o corregir precios? | 1=Sí, frecuentemente 2=Sí, ocasionalmente 3=No |
| M6 | Likert | Para tu negocio, ¿qué tan relevante sería un sistema de pedidos y facturación integrado en la web? | 1=Muy irrelevante → 5=Muy relevante |
| M7 | Cerrada | ¿Estarías dispuesto(a) a pagar una suscripción o comisión por usar un e-commerce que te ahorre tiempo? | 1=Sí, 2=No |
| M8 | Abierta | ¿Qué otros servicios (alertas de variación de precio, reportes descargables, facturación automática) te gustaría tener? | Respuesta libre |

### Notas para interpretación - Comerciantes:

- **M1**: Indica la experiencia del comerciante en el Centro de Abastos. Valores más altos indican mayor experiencia.
- **M2**: Determina si el comerciante conoce la plataforma actual. Respuestas "1" (Sí) significan que conocen la plataforma.
- **M3-M4**: Estas preguntas solo aplican si el comerciante respondió "Sí" en M2. Si no conoce la página, estos campos contienen "-" (guion).
- **M3**: Identifica el propósito principal para usar la plataforma. Las respuestas pueden ser a) Ver precios, b) Comparar proveedores o c) Historial.
- **M5**: Evalúa si la información en la plataforma es confiable. Valores "1" indican que frecuentemente necesitan confirmar precios por otros medios.
- **M6-M7**: Evalúan el interés y disposición a pagar por un sistema integrado de pedidos y facturación. Valores más altos en M6 y respuestas "1" en M7 indican mayor interés y disponibilidad.
- **M8**: Proporciona ideas específicas para mejorar la plataforma desde la perspectiva del comerciante.

---


