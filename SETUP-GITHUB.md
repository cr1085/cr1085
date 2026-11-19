# Implementación del rediseño en GitHub

## 1. Reemplazar el README del perfil

El repositorio especial de perfil es `cr1085/cr1085`.

1. Abre https://github.com/cr1085/cr1085
2. Pulsa **Add file → Upload files**.
3. Sube el `README.md` de este paquete para reemplazar el actual.
4. Crea la carpeta `assets` si no existe y sube `assets/github-cyber-banner.png`.
5. Sube también `README.es.md` para ofrecer la versión en español.
6. Confirma los cambios con un mensaje como `Redesign profile README with cyber brand identity`.

Es importante mantener la ruta exacta `assets/github-cyber-banner.png`, porque el README la usa como imagen principal.

## 2. Bio recomendada

Senior Software Engineer | AI Developer | Backend Architect | Founder @ 3CB Soluciones | Building intelligent software & digital products.

## 3. Configuración del perfil

- **Location:** Cartagena, Colombia
- **Website:** https://cr1085.github.io/
- **Social account:** LinkedIn
- **Availability:** activa Open to Work solo si deseas recibir oportunidades laborales ahora mismo.

## 4. Orden recomendado para los seis repositorios fijados

Fijar los repositorios desde **Customize your pins** en el perfil. Orden recomendado:

1. `rag-notes` — demuestra búsqueda semántica y RAG.
2. `ai-edge-agents` — demuestra experimentación con agentes y automatización.
3. `salesmind_version_3.0.0` — conecta IA con un caso de uso comercial.
4. `asistente-freelance` — presenta una aplicación de gestión con integración de IA.
5. `foto-sym` — muestra desarrollo de software de negocio con Laravel.
6. `EdaRepository` — respalda la faceta de análisis de datos y docencia.

`JavaClassRepository` y `3cb-ai-boilerplate` pueden permanecer enlazados en el README, pero primero conviene mejorar sus instrucciones de instalación.

## 5. Mejoras prioritarias antes de promover los repositorios

- `asistente-freelance`: sustituir el badge de Discord de ejemplo, corregir el comando `git clone` para que use `cr1085/asistente-freelance` y aclarar que nunca deben exponerse claves privadas de proveedores de IA en código ejecutado en el navegador.
- `rag-notes`: corregir el nombre de carpeta del comando `cd` para que coincida con el repositorio y añadir capturas de pantalla o un GIF de uso.
- `ai-edge-agents`: documentar permisos y límites de cada herramienta del agente, añadir advertencias para acciones externas y pruebas de seguridad.
- `salesmind_version_3.0.0`: actualizar dependencias y referencias de modelos si ya no coinciden con los proveedores vigentes; agregar `.env.example` sin secretos reales y mejorar el comando de clonación.
- `3cb-ai-boilerplate`: completar el comando `git clone` y validar el flujo de instalación desde cero.
- Todos: añadir screenshots, estado real del proyecto, requisitos, licencia verificada, pruebas y pasos reproducibles.

## 6. Nota de seguridad

Antes de mostrar repositorios públicamente, revisar que no contengan `.env`, tokens, claves API, credenciales, datos personales ni archivos de configuración sensibles. Rotar cualquier credencial que haya sido publicada accidentalmente.
