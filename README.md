# Instalar y actualizar CensorMD

CensorMD anonimiza documentos **en tu propio equipo**: los documentos nunca se envían a internet. La única conexión de la app es la búsqueda de actualizaciones, que solo descarga de aquí el número de la última versión y se puede desactivar en «Ajustes».

Las versiones están en [Releases](https://github.com/tocaway/CensorMD-releases/releases). Cada una va firmada: la app comprueba la firma antes de instalar una actualización y rechaza cualquier paquete alterado.

## Mac (Apple Silicon, macOS 13 o posterior)

1. Descarga `CensorMD-X.Y.Z-macOS13-arm64.dmg` de la última versión «CensorMD Mac».
2. Ábrelo y arrastra **CensorMD** a **Aplicaciones**.
3. La primera vez: clic derecho sobre CensorMD → **Abrir** → **Abrir**. Si el Mac dice que no puede comprobarla, ve a **Ajustes del Sistema → Privacidad y seguridad** y pulsa **Abrir igualmente**.

Para actualizar, CensorMD debe estar en **Aplicaciones** (no abierta desde el DMG).

## Windows (10 u 11, x64)

Elige una de las dos:

- **Instalada:** descarga `CensorMD-Setup-vX.Y.Z.exe` de la última versión «CensorMD Windows» y ábrelo.
- **Portable (sin instalar):** descarga `CensorMD-portable-vX.Y.Z.exe` y guárdalo donde quieras (también en un USB). Se abre con doble clic.

Si Windows muestra «Windows protegió su PC», pulsa **Más información → Ejecutar de todas formas**.

## Actualizaciones

Cuando hay una versión nueva, CensorMD avisa al abrirse y muestra los cambios. Pulsa **Actualizar**: la app descarga la versión, comprueba su firma, se cierra y se vuelve a abrir actualizada. Nunca se instala nada sin que lo pulses.

En **Ajustes → Actualizaciones** puedes:

- desactivar la comprobación al abrir;
- buscar una versión nueva en el momento;
- **volver a la versión anterior** si la nueva te da problemas.

En la versión portable, la versión nueva sustituye al `.exe` en su misma carpeta y la anterior se guarda a su lado como `CensorMD-portable.anterior.exe`. Si la carpeta no se puede modificar (por ejemplo, un USB protegido), la app avisa y abre esta página para descargarla a mano.
