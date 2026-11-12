# Proyecto Integrador LM 2026 - UD5 · Tablas y Formularios

- **Nombre:** Daniel Odín Carballido Rodríguez
- **Usuario de GitHub:** odincarballido-byte
- **Tema elegido:** Puntuación y valoración de fiestas populares de España.
- **Motivo:** He elegido este tema porque en España tenemos una gran variedad de fiestas que son muy diferentes dependiendo de donde te encuentres; también he tenido la oportunidad de acudir a bastantes de ellas y tienen un impacto cultural enorme. Me parece una buena idea crear un portal donde analizamos y puntuamos según mi experiencia y las de otras personas festividades emblemáticas como la Feria de Abril de Sevilla, Aste Nagusia o San Fermín.

## Mapa del sitio (Estructura del Proyecto)
- `index.html` (Página principal del portal de Fiestas de España, enlazada con contacto y puntuaciones)
- `puntuaciones.html` (Página que contiene la tabla detallada de puntuaciones y valoraciones)
- `contacto.html` (Nueva página con el formulario de inscripción y consultas de la UD5)
- `datos.xml` (Ficha de datos estructurados del proyecto)
- `img/` (Carpeta contenedora de los recursos gráficos del festival)
- `README.md` (Documentación oficial del proyecto integrador)

## UD5 · Tablas y formularios
- **Datos de la tabla:** Se incluye una tabla comparativa con las puntuaciones oficiales, jurado técnico, voto popular y penalizaciones de las principales festividades en la página `puntuaciones.html`.
- **Formulario:** La nueva página `contacto.html` está diseñada para que los visitantes puedan registrarse, apuntarse como jurado o solicitar información sobre las fiestas.

### Prueba del formulario (GET vs POST)
- **Por qué usamos POST frente a GET:** Se utiliza el método `post` porque los datos confidenciales o de formularios extensos (como reservas, consultas y registros de usuarios) viajan de forma oculta y segura en el cuerpo de la petición HTTP, evitando exponer información privada en la barra de direcciones del navegador.
- **URL de la prueba con GET temporal:** `http://127.0.0.1:5500/proyecto/contacto.html?nombre=Odin&email=odin%40email.com&telefono=600123456&festival_interes=fallas&tipo_asistencia=presencial&suscripcion_alertas=eventos&consulta=Duda+sobre+las+entradas&submit=Enviar`

### Validación W3C (0 Errores)
| Archivo | Errores iniciales | Correcciones aplicadas | Errores finales |
| :--- | :--- | :--- | :--- |
| `puntuaciones.html` | 0 | Ninguno (estructura semántica validada correctamente con entidades numéricas) | 0 |
| `contacto.html` | 0 | Ninguno (etiquetas de formulario, fieldsets y atributos validados) | 0 |

## Palabra del día
- [Día]

## Qué he hecho en esta entrega
En esta unidad he integrado una tabla de datos avanzada en `puntuaciones.html` aplicando un diseño semántico estricto con `<thead>`, `<tbody>`, `<tfoot>`, `colgroup`, `caption`, `scope`, `colspan` y `rowspan`. Asimismo, he desarrollado desde cero la página `contacto.html`, implementando un formulario completo con múltiples fieldsets provistos de leyendas, comentarios detallados de bloque y los ocho tipos de control requeridos con validación integrada.