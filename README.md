# Cursor Rules & Configurations

Este repositorio está dedicado a almacenar y gestionar un conjunto de "Cursor Rules" y otras configuraciones para mejorar la interacción con la inteligencia artificial de Cursor. El objetivo es centralizar las directrices y patrones que la IA debe seguir para generar código de alta calidad, consistente y alineado con las mejores prácticas de desarrollo.
La idea es ir añadiendo poco a poco diferentes tipos de Cursor Rules, añadir también MCPs cuando estén mas avanzados y funcionales, etc. (Por ejemplo uno de BD o de QGIS)

## Propósito

El propósito principal de este repositorio es:

-   **Centralizar Reglas:** Mantener un conjunto de reglas personalizadas para Cursor en un único lugar.
-   **Consistencia:** Asegurar que la IA genere código que siga siempre los mismos estándares.
-   **Eficiencia:** Facilitar el uso de la IA al tener directrices predefinidas para diferentes contextos (frontend, backend, etc.).
-   **Colaboración:** Compartir y versionar las reglas para poder colaborar con otros desarrolladores.

## ¿Cómo utilizar estas reglas?

Para utilizar las reglas de este repositorio en Cursor, puedes hacer referencia a ellas usando la sintaxis `@` seguida del nombre del archivo de la regla (por ejemplo, `@full-stack.mdc`).

Cuando menciones una regla en un prompt, Cursor leerá el contenido del archivo correspondiente y lo usará como contexto para generar su respuesta.

**Ejemplo:**

```
@full-stack.mdc por favor, crea un componente en React...
```

## Contenido del Repositorio

Este repositorio contendrá dos tipos principales de artefactos para trabajar con Cursor:

### 1. Cursor Rules (`.mdc`)

Son archivos de Markdown que contienen directrices y principios que la IA debe seguir. Permiten guiar a Cursor para que genere código con un estilo y una arquitectura específicos.

### 2. Model-in-the-Loop Code (MCPs)

Los MCPs son configuraciones más avanzadas que permiten a la IA interactuar con herramientas y flujos de trabajo locales. A medida que se desarrollen, se añadirán a este repositorio para casos de uso como:

-   Interacción con bases de datos.
-   Automatización de tareas con herramientas como QGIS.
-   Flujos de trabajo de desarrollo personalizados.

## Reglas Disponibles

A continuación se listan las reglas que se planea añadir a este repositorio:

*   `@full-stack.mdc`: Reglas generales para un desarrollo full-stack, aplicando principios como SOLID, KISS, y buenas prácticas tanto en frontend como en backend.
*   `@frontend.mdc`: Directrices específicas para el desarrollo de frontend.
*   `@backend.mdc`: Directrices específicas para el desarrollo de backend.
*   `@general.mdc`: Reglas generales de estilo y formato de código.
*   `@custom.mdc`: Reglas personalizadas para proyectos específicos.
*   `@definitive.mdc`: Una regla "definitiva" que combina varias de las otras para un contexto de desarrollo completo.

---

Creado con la ayuda de Cursor.
