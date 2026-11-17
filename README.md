# Rueda Libre 🚲

Sitio web de **Rueda Libre**, un negocio de alquiler de bicicletas y recorridos guiados en Medellín. Desde aquí se puede ver la flota, consultar tarifas y rutas, y reservar una bicicleta con un formulario que valida los datos antes de enviarlos.

Versión actual: **v2.0-beta**, el sitio completo migrado a Bootstrap.

## Qué hay en el sitio

| Página | Qué muestra |
| --- | --- |
| **Inicio** | Portada, carrusel de promociones, rutas guiadas, servicios, flota de 7 modelos, beneficios y cómo alquilar |
| **Tarifas y Rutas** | Tablas de tarifas de alquiler y de recorridos, con información adicional al lado |
| **Reservas** | Formulario de reserva, alerta de recordatorio y ventana con las políticas de alquiler |
| **Pruebas** | Catálogo de la flota hecho solo con la grilla de Bootstrap |

## Promociones del carrusel

- Martes 2x1 en bicicletas urbanas
- 20 % de descuento en eléctricas de lunes a jueves
- Si cumples años, el recorrido guiado es gratis

## Formulario de reservas

Cada campo obligatorio muestra su propio mensaje si se envía mal. Las reglas son:

- Nombre de mínimo 3 caracteres
- Documento de 6 a 10 dígitos
- Celular de 10 dígitos que empiece por 3
- Correo con formato válido
- Fecha entre el 1 de noviembre y el 31 de diciembre de 2026
- Entre 1 y 6 bicicletas
- Tipo de bicicleta, plan y recorrido elegidos
- Políticas aceptadas

## Tecnologías

- HTML5 y CSS3
- Bootstrap 5.3 por CDN (grilla, utilidades y componentes)
- Bootstrap Icons 1.11.3
- Google Fonts: Montserrat y Open Sans

## Componentes de Bootstrap usados

- Navbar colapsable (menú hamburguesa por debajo de 992 px)
- Cards con la misma altura en cada fila
- Carrusel con controles y avance automático
- Botones con variantes (`btn-success`, `btn-outline-dark`) y tamaños (`btn-lg`, `btn-sm`)
- Formulario con validación visual
- Alerta que se puede cerrar
- Modal de políticas de alquiler

## Responsive

Revisado a 360 px, 768 px y 1280 px.

| Ancho | Columnas de la flota |
| --- | --- |
| Celular | 1 |
| `sm` (576 px) | 2 |
| `lg` (992 px) | 3 |
| `xl` (1200 px) | 4 |

## Estructura del proyecto

```
rueda-libre/
├── index.html
├── bitacora.txt
├── css/
│   └── style.css
├── img/
├── paginas/
│   ├── tarifas.html
│   └── reservas.html
└── pruebas/
    └── catalogo-boostrap.html
```

`style.css` solo guarda la identidad visual de la marca (colores, tipografía, tablas y botón de WhatsApp); la distribución y los componentes los resuelve Bootstrap.

## Cómo verlo en tu computador

1. Clona el repositorio:
   ```
   git clone https://github.com/Deivilegend/rueda-libre.git
   ```
2. Abre `rueda-libre/index.html` en el navegador, o sírvelo con la extensión Live Server de VS Code.
3. Necesitas internet para cargar Bootstrap, los iconos y las fuentes.

## Sitio publicado

https://deivilegend.github.io/rueda-libre/rueda-libre/

## Autor

**Deivi García**: [Deivilegend](https://github.com/Deivilegend)