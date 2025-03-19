# CRUD con Google Sheets para Evaluación de Cata de Cervezas

## Descripción del Proyecto
Desarrollo de un sistema CRUD basado en Google Sheets para evaluar una copa de cata de cervezas con más de 150 personas en Santiago, Chile. Se implementaron diversas herramientas de Google para optimizar la recopilación y visualización de datos en tiempo real.

## Tecnologías Utilizadas
- **Google Sheets**: Base de datos principal, con un documento por usuario.
- **Google Scripts**: Backend para la interacción entre el usuario y su hoja de evaluación.
- **Google Colaboratory (Python)**: Generación de las hojas de cálculo para cada usuario y creación de la base de datos consolidada.
- **Vuetify**: Framework de frontend para la visualización de datos en HTML.
- **Códigos QR**: Generados para cada usuario para facilitar el acceso a su evaluación.

## Implementación
1. **Generación de Hojas de Evaluación**
   - Con Python en Google Colaboratory, se crearon 150 Google Sheets (uno por usuario).
   - Se asignó a cada hoja un Google Script que funciona como backend.
   - Cada hoja contenía un enlace para que el usuario visualizara su evaluación en una interfaz HTML basada en Vuetify.

2. **Automatización del Acceso**
   - Se generó un código QR para cada usuario, permitiendo acceso rápido desde la entrada del evento.

3. **Consolidación de Datos**
   - Google Colaboratory recopiló datos de los 150 Google Sheets en una base de datos centralizada.
   - La digitalización permitió optimizar la evaluación en un 100% en comparación con la versión manual escrita.

## Recursos
- **Ejemplo de CRUD en Google Sheets**: [Enlace al documento](https://docs.google.com/spreadsheets/d/1oMeU10zORa8Ey_0cOsw9KaoHGy73x1ECNoMxQLDYLO0/edit?gid=0#gid=0)
- **Generación de Códigos QR**: [Google Colaboratory](https://colab.research.google.com/drive/1XmhOclPAFT6D_oeiUX55Qs02BamLmgqs?usp=sharing)

## Impacto y Beneficios
- Reducción del tiempo de evaluación en un 100%.
- Eliminación de errores manuales en la recopilación de datos.
- Acceso rápido y seguro mediante códigos QR.
- Interfaz amigable basada en Vuetify para una mejor experiencia de usuario.

Este sistema demuestra cómo aprovechar herramientas de Google para desarrollar soluciones escalables y eficientes para la gestión de eventos y evaluaciones.
