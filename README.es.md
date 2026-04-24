# EnvStudio Feedback

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## Acerca de EnvStudio

**EnvStudio** es un gestor moderno de variables de entorno para Windows basado en WinUI 3. Sustituye el anticuado diálogo de «Propiedades del sistema → Variables de entorno» por una experiencia nativa de Windows 11.

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/es/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/es/cover2.png" width="48%" />
</p>

## Descargar

<p align="center">
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## Funciones principales

- **Editor visual intuitivo** — Añada, edite, elimine y reordene variables de entorno con una interfaz WinUI 3 moderna.
- **Gestión de lista PATH** — Reordenación con arrastrar y soltar, detección de duplicados y de enlaces rotos.
- **Detección de conflictos EXE** — Escanea todos los directorios del PATH en busca de ejecutables y muestra cuáles son sobrescritos por entradas anteriores, con un clic para saltar a la entrada en conflicto.
- **Detección de conflictos de ámbito** — Cuando una variable de usuario oculta una variable de sistema con el mismo nombre, muestra un tachado con un icono de advertencia para que siempre sepa qué valor está realmente en vigor.
- **Interruptor no destructivo** — Desactive una variable sin eliminarla. Renombra silenciosamente el valor del registro preservando los datos originales. Reactive en cualquier momento con un clic.
- **Verificaciones de seguridad al eliminar** — Antes de eliminar una variable, escanea todas las demás variables en busca de referencias `%VARNAME%` y advierte sobre posibles roturas.
- **Vista previa de expansión** — Pase el cursor sobre cualquier valor que contenga referencias `%VAR%` para ver la ruta completamente resuelta en un tooltip.
- **Detección de cambios externos** — Monitorea el registro en tiempo real. Si otro programa modifica las variables de entorno mientras EnvStudio está abierto, recibe una notificación inmediata.
- **Sistema de perfiles** — Guarde, cambie y aplique perfiles de variables para diferentes entornos de desarrollo (ej. «Java 8», «Node.js», «AI/ML»).
- **Instantáneas y reversión** — Instantáneas automáticas antes de cada cambio, con vista diff estilo Git y reversión en un clic.
- **Búsqueda y filtrado** — Encuentre rápidamente variables entre los ámbitos de Usuario y Sistema con soporte regex. Las subentradas PATH coincidentes se expanden automáticamente con un badge de conteo.
- **Exportación** — Exporte variables a formatos PowerShell, Batch o archivo .env para compartir con su equipo o restaurar tras una reinstalación.
- **Elevación UAC** — Elevación de administrador fluida para editar variables del sistema.
- **Difusión instantánea** — Los cambios se transmiten inmediatamente al sistema mediante `WM_SETTINGCHANGE`.

## 100% Sin conexión · Completamente gratis

EnvStudio **funciona completamente sin conexión, sin telemetría ni recopilación de datos.** Su configuración permanece estrictamente en su propia máquina.

Todas las funciones son **completamente gratis**, sin anuncios ni muros de pago. En el futuro podría añadirse una opción de donación, pero ninguna función será restringida jamás.

Consulte nuestra [Política de privacidad](https://prunelab.net/es/products/envstudio/privacy) para más detalles.

---

## Comentarios

> **Nota:** Este repositorio **no contiene** el código fuente de EnvStudio. Está dedicado a recopilar comentarios de usuarios y seguimiento de problemas.

| Acción | Enlace |
|------|------|
| Informar de un error | [Crear informe de error](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| Sugerir una función | [Enviar solicitud](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| Ver todos los Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## Antes de informar

Busque primero en los [Issues existentes](https://github.com/PruneLab/EnvStudio-Feedback/issues) para evitar duplicados.

Al informar de un error, incluya:
- **Versión de EnvStudio** (en Configuración → Acerca de)
- **Versión de Windows** (ej. Windows 11 23H2)
- **Pasos para reproducir** el problema
- **Comportamiento esperado** vs **comportamiento real**
- Capturas de pantalla (si aplica)

## Ideas de funciones

¡Nos encanta escuchar sus ideas! Antes de enviar:
- Verifique si alguien ya lo ha sugerido
- Describa el caso de uso — ¿qué problema resolvería?
- Maquetas o referencias son siempre bienvenidas
