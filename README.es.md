# Repositorio de proyecto GEPIA

**GEPIA — Grupo Estudiantil de Proyectos de Ingeniería Aplicada.**

Este repositorio fue creado a partir de la plantilla de proyectos GEPIA. Usa GitHub Issues y Pull Requests como fuente de verdad:

- **Requerimientos** = issue
- **Criterio de aceptación** = sub-issue del requerimiento
- **Tarea** = pull request
- **Evidencia** = commits, salida de pruebas, capturas y enlaces dentro del PR

Los archivos Markdown describen el proyecto; no reemplazan el estado de los issues/PRs.

English version: [README.md](README.md)

## 1. Crear el repositorio

1. Abra la plantilla:  <https://github.com/gepia-mgmt/gepia-repo-template>
2. Haga clic en **Use this template → Create a new repository**.
3. Elija **su cuenta personal de GitHub** como propietario. **No transfiera la propiedad a la organización.**
4. Use un nombre claro, relacionado a la temática del proyecto.
5. Elija visibilidad pública o privada según las instrucciones del PM.

## 2. Dar acceso

- Si el repositorio es **privado**, agregue al PM/docente como colaborador con permiso de **Read**.
- Si es público, el PM puede agregarlo al Project sin acceso adicional.

## 3. Verificar las etiquetas

La plantilla incluye `.github/workflows/setup-labels.yml`.

1. Abra **Actions → GEPIA — setup labels**.
2. Debe ejecutarse en el primer push. Si no ocurrió, haga clic en **Run workflow**.
3. Verifique que existan etiquetas como `type:requirement`, `type:acceptance`, `type:task`, `priority:must` y `area:software` en **Issues → Labels**.

## 4. Verificar los formularios de issues

Abra **Issues → New issue**. Debe ver:

- **Requirement**
- **Acceptance criterion**

Los issues en blanco deben estar deshabilitados.

## 5. Crear los primeros elementos de trabajo

El primer issue será el de la definición de la descripción del proyecto. Asegúrese de hacer esta tarea inicial antes de continuar con el siguiente paso.

1. Abra un issue de tipo **Requirement**.
2. Cree un issue de tipo **Acceptance criterion** que diga "Inclusion to GEPIA org" y agréguelo como **sub-issue** del requerimiento.
3. Abra un **Pull Request** como primera tarea.
   - Enlace el requisito y el criterio de aceptación.
   - Use `Closes #<issue AC>` solo si el PR completa ese criterio.
   - Asegúrese de ajustar el README.md para este primer requerimiento.
   - Incluya commits, logs de prueba y evidencia en el PR.

## 6. Reportar el repositorio al PM

Este es el paso final de configuración. Una vez tenga su primer requerimiento en estado "Closed", reporte su proyecto al PM, para así poder añadirlo al Project de GEPIA.

Abra un issue aquí:

<https://github.com/gepia-mgmt/gepia-management/issues/new>

Título:

```text
[REPO] owner/nombre-del-repositorio
```

Incluya:

- URL del repositorio;
- su usuario de GitHub;
- integrantes del equipo;
- visibilidad pública/privada;
- si el PM tiene acceso de lectura (obligatorio para repositorios privados);
- confirmación de que el workflow de etiquetas se ejecutó;
- confirmación de que los formularios de issues funcionan;
- enlaces al primer requisito, criterio de aceptación y PR.

No asuma que el repositorio queda registrado automáticamente solo por existir.

## 7. Idioma de trabajo

Se recomienda usar **inglés** para los artefactos de desarrollo del proyecto. Esto aplica especialmente a:

- nombre y descripción del repositorio;
- títulos y descripciones de issues;
- títulos y descripciones de PRs;
- código, identificadores y mensajes de commit;
- README y documentación técnica;
- diagramas, nombres de pruebas y pies de evidencia.

Se puede usar español en el proyecto, pero mantener el registro técnico en inglés facilita la revisión, reutilización, publicación y colaboración internacional.

## 8. Documentación del proyecto

Use Markdown para:

- objetivos y justificación;
- arquitectura y decisiones de diseño;
- documentación de usuario;
- informes.

Mantenga el estado vivo en issues, PRs y el Project de GitHub. No duplique el estado en Markdown.
