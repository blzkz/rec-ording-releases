# rec·ording · descargas

Graba tu móvil Android y conviértelo en un vídeo promocional con marco, fondo y zooms suaves.

Aquí se publican las versiones de la app. La app comprueba este repositorio al abrirse, avisa cuando hay una nueva y la instala sola.

## Instalar

Descarga el archivo de tu sistema en la [última versión](https://github.com/blzkz/rec-ording-releases/releases/latest):

| Sistema | Archivo | Cómo se instala |
| --- | --- | --- |
| Arch, CachyOS, Manjaro | `rec-ording-<versión>-1-x86_64.pkg.tar.zst` | `sudo pacman -U <archivo>` |
| Debian, Ubuntu, Linux Mint, Pop!_OS | `rec-ording_<versión>-1_amd64.deb` | `sudo apt install ./<archivo>` |
| Fedora | `rec-ording-<versión>-1.x86_64.rpm` | `sudo dnf install ./<archivo>` |
| openSUSE | `rec-ording-<versión>-1.x86_64.rpm` | `sudo zypper install <archivo>` |
| Otra distribución | `rec-ording-<versión>-x86_64.AppImage` | `chmod +x <archivo>` y ábrelo |
| Windows | `rec-ording-<versión>-windows-x64.zip` | Descomprímelo y abre `rec-ording.exe` (lee `LEEME.txt`) |

En Linux hace falta glibc 2.35 o más reciente (Ubuntu 22.04, Debian 12, Fedora 36 o posteriores). Para grabar el móvil se usan adb y scrcpy; con el AppImage instala aparte ffmpeg, adb y scrcpy.

Los archivos «Source code» que GitHub añade a cada versión solo contienen este README.

## Créditos

El modelo 3D incluido, «Samsung S26 Ultra», es de [Sagar Modi](https://sketchfab.com/modis1761) ([Sketchfab](https://sketchfab.com/3d-models/samsung-s26-ultra-7ff228963ea446f39f46a5541f71e352)), con licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
