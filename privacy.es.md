# Política de Privacidad

**Vigente desde: 27 de junio de 2026**

Purr es una aplicación de notas para macOS desarrollada por KatLabs (en adelante "nosotros"). Esta Política de Privacidad explica qué datos maneja Purr y de qué manera.

## Versión corta

Purr no recolecta, transmite ni vende tus datos personales. Tus notas permanecen en tu dispositivo y, opcionalmente, en tu propia cuenta de iCloud. No tenemos servidores, ni analítica, ni rastreo, ni publicidad.

## Datos que NO recolectamos

No recolectamos:

- Tus notas, etiquetas, tareas, adjuntos ni ningún contenido que crees en Purr.
- Identificadores personales (nombre, correo, dirección IP, ID de dispositivo, identificador publicitario).
- Métricas de uso, telemetría ni grabaciones de sesión.
- Reportes de fallos (a menos que tú decidas enviarlos voluntariamente vía el sistema de reportes de macOS — esos van a Apple, no a nosotros).
- Datos de marketing o publicidad.

No usamos SDKs de analítica de terceros, redes publicitarias, fingerprinting ni servicios de rastreo.

## Datos almacenados en tu dispositivo

Purr guarda tus notas, etiquetas, tareas, adjuntos, ajustes y preferencias localmente en tu Mac, dentro del sandbox de aplicaciones de macOS. Estos datos nunca salen de tu dispositivo, salvo que tú actives explícitamente alguna de las integraciones descritas más abajo.

## Sincronización opcional con iCloud

Si tienes sesión iniciada en iCloud en tu Mac y tienes iCloud Drive habilitado para Purr, tus notas se sincronizan a tu propia cuenta de iCloud usando el framework CloudKit de Apple.

- Estos datos viven en tu base de datos privada de iCloud.
- Nosotros no tenemos acceso a ellos. Se rigen por los términos de iCloud de Apple.
- Puedes desactivar la sincronización en cualquier momento desde Configuración del sistema → ID de Apple → iCloud → Apps que usan iCloud.

## Integraciones opcionales con otras apps

Purr ofrece integraciones que se ejecutan únicamente cuando tú las habilitas explícitamente:

- **Obsidian.** Purr lee y escribe archivos Markdown en una carpeta a la que tú le otorgas acceso vía un security-scoped bookmark de macOS. Los archivos permanecen en tu sistema de archivos; nada se envía a nosotros ni a los servidores de Obsidian.
- **Apple Notes.** Purr lee y escribe notas de tu app Apple Notes mediante scripting de macOS (AppleScript). Todo el intercambio de datos ocurre localmente entre dos apps de tu propio Mac.

La sincronización corre solamente en la cadencia que tú elijas (manual, diaria o semanal). Purr nunca consulta nuestros servidores — no tenemos.

## Funciones de IA en el dispositivo

Algunas funciones (búsqueda semántica, sugerencias inteligentes, embeddings) usan modelos de machine learning que corren íntegramente en tu Mac. No se envía contenido a OpenAI, Anthropic, Google ni a ningún otro proveedor externo de IA.

Si decides configurar opcionalmente una instancia local de Ollama, las consultas viajan únicamente a tu `localhost` — nunca a nosotros ni a terceros.

## Conexión de clientes de IA externos (MCP)

Purr incluye un servidor MCP (Model Context Protocol) opcional que puedes habilitar para permitir que clientes de IA que tú elijas —como Claude Code o Codex— lean y escriban tus notas. Se ejecuta localmente y solo cuando tú lo inicias.

Si conectas uno de estos clientes, las notas y el contenido que compartas con él se envían y son procesados por ese cliente y su proveedor de IA (por ejemplo, Anthropic u OpenAI) bajo sus propias políticas de privacidad, no la nuestra. No participamos en ese intercambio ni tenemos acceso a él. Las funciones de IA en el dispositivo descritas arriba nunca envían tu contenido a terceros.

## Compras

Las compras integradas y suscripciones son procesadas por Apple a través de StoreKit. Nunca vemos tu información de pago; Apple sí. La validación de recibos y el estado de la suscripción ocurren en el dispositivo contra los servidores de Apple, bajo la política de privacidad de Apple.

## Respaldos locales

Purr puede crear archivos de respaldo locales (`.zip`) en la ubicación que elijas. Estos archivos nunca salen de tu dispositivo a menos que tú los muevas.

## Búsqueda Spotlight

Purr registra los títulos y previsualizaciones de tus notas con el Spotlight de macOS para habilitar la búsqueda a nivel de sistema. El índice de Spotlight es administrado por macOS y nunca sale de tu dispositivo.

## Privacidad de menores

Purr no está dirigida a menores de 13 años y no recolecta datos a sabiendas — de nadie, incluidos menores.

## Tus derechos

Como no recolectamos ningún dato personal, no hay nada que podamos consultar, exportar, corregir ni eliminar de nuestro lado. Para borrar tus datos locales, desinstala Purr. Para borrar tus datos en iCloud, inicia sesión en iCloud.com con tu Apple ID y elimina los datos de Purr, o contacta al soporte de Apple.

## Cambios a esta política

Si actualizamos esta política, modificaremos la fecha "Vigente desde" arriba y publicaremos la nueva versión en la misma URL. Los cambios materiales serán anunciados dentro de la app o en las notas de actualización del App Store.

## Contacto

Consultas sobre esta política: purr.katlabs@gmail.com
