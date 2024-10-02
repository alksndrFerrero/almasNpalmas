<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo-darkmode.svg">
  <source media="(prefers-color-scheme: light)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo.svg">
  <img alt="Prism Launcher" src="/program_info/org.prismlauncher.PrismLauncher.logo.svg" width="40%">
</picture>
</p>

<p align="center">
  Este <b>fork</b> de Prism Launcher reemplaza las cuentas heredadas de Mojang por cuentas de Ely.by<br />
  <br />Esto <b>no</b> está respaldado por Prism Launcher o Ely.by.
</p>

## Instalación

- Todas las descargas se pueden encontrar [aquí](https://github.com/Octol1ttle/PrismLauncher-elyby/releases/latest).
- El estado de la última compilación se puede encontrar en las [GitHub Actions](https://github.com/Octol1ttle/PrismLauncher-elyby/actions).

## Comunidad y Soporte

No dudes en crear un issue en GitHub si encuentras un error o quieres sugerir una nueva función. Tenemos un servidor de Discord donde otros miembros de la comunidad pueden ayudarte:

[![Servidor de Discord de Prism Launcher](https://discordapp.com/api/guilds/1201522867901313045/widget.png?style=banner3)](https://discord.gg/5kcBCvnbTp)

## Compilación

Si deseas compilar Prism Launcher tú mismo, consulta las [Instrucciones de Compilación](https://prismlauncher.org/wiki/development/build-instructions/).

## Patrocinadores y Socios

Gracias a JetBrains por proporcionarnos algunas licencias para todos sus productos, como parte de su [programa de Código Abierto](https://www.jetbrains.com/opensource/).

[![JetBrains](https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.svg)](https://www.jetbrains.com/opensource/)

## Política de Forking/Redistribución/Compilaciones personalizadas

Eres libre de hacer un fork, redistribuir y proporcionar compilaciones personalizadas siempre que sigas los términos de la [licencia](LICENSE) (esto es una responsabilidad legal), y si realizaste cambios en el código en lugar de solo empaquetar una compilación personalizada, por favor haz lo siguiente como una cortesía básica:

- Deja claro que tu fork no es Prism Launcher y no está respaldado ni afiliado al proyecto Prism Launcher (<https://prismlauncher.org>).
- Revisa [CMakeLists.txt](CMakeLists.txt) y cambia las claves API de Prism Launcher por las tuyas o configúralas como cadenas vacías (`""`) para desactivarlas (de esta manera, el programa seguirá compilándose, pero la funcionalidad que requiere esas claves estará desactivada).

Si tienes alguna pregunta o deseas alguna aclaración sobre las condiciones anteriores, por favor crea un issue y pregúntanos.

Si solo estás compilando Prism Launcher para tu distribución, asegúrate de configurar `Launcher_BUILD_PLATFORM` a un identificador que represente tu distribución. Ejemplos son `archlinux`, `fedora` y `nixpkgs`.

Ten en cuenta que si compilas este software sin eliminar las claves API proporcionadas en [CMakeLists.txt](CMakeLists.txt), aceptas los siguientes términos y condiciones:

- [Términos de Uso de Microsoft Identity Platform](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
- [Términos y Condiciones de la API de Terceros de CurseForge](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

Si no estás de acuerdo con estos términos y condiciones, entonces elimina las claves API asociadas del archivo [CMakeLists.txt](CMakeLists.txt) configurándolas como cadenas vacías (`""`).

## Licencia [![https://github.com/Octol1ttle/ElyPrismLauncher/blob/develop/LICENSE](https://img.shields.io/github/license/Octol1ttle/ElyPrismLauncher?label=License&logo=gnu&color=C4282D)](LICENSE)

Todo el código del lanzador está disponible bajo la licencia GPL-3.0-only.
