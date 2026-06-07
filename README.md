# Ejemplos Cisco Packet Tracer

Colección de prácticas y topologías de red creadas con **Cisco Packet Tracer**. El repositorio contiene 8 archivos de ejemplo (`.pkt`) listos para abrir y estudiar.

## Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `Ejemplo1.pkt` | Topología de ejemplo 1 |
| `Ejemplo2.pkt` | Topología de ejemplo 2 |
| `Ejemplo3.pkt` | Topología de ejemplo 3 |
| `Ejemplo4.pkt` | Topología de ejemplo 4 |
| `Ejemplo5.pkt` | Topología de ejemplo 5 |
| `Ejemplo6.pkt` | Topología de ejemplo 6 |
| `Ejemplo7.pkt` | Topología de ejemplo 7 |
| `Ejemplo8.pkt` | Topología de ejemplo 8 |
| `LICENSE` | Licencia MIT del proyecto |

> Los archivos `.pkt` son archivos binarios propios de Cisco Packet Tracer. **No** se pueden visualizar en un editor de texto; deben abrirse con la aplicación Packet Tracer.

## Requisitos previos

- **Git** instalado. Descárgalo desde [git-scm.com](https://git-scm.com/downloads).
- **Cisco Packet Tracer** (versión recomendada 8.x o superior). Disponible de forma gratuita a través de la [Cisco Networking Academy](https://www.netacad.com/courses/packet-tracer).

Verifica que Git esté instalado:

```bash
git --version
```

## Cómo clonar el repositorio

1. Abre una terminal (PowerShell, CMD, Git Bash o tu terminal preferida).
2. Sitúate en la carpeta donde quieras descargar el proyecto, por ejemplo:

   ```bash
   cd C:\Users\TuUsuario\Downloads
   ```

3. Clona el repositorio:

   ```bash
   git clone https://github.com/Nico1091/Ejemplos_ciscoPackettarcer.git
   ```

4. Entra en la carpeta del proyecto:

   ```bash
   cd Ejemplos_ciscoPackettarcer
   ```

> **Nota:** la rama principal de este repositorio se llama `principal` (no `main`). Al clonar, Git la selecciona automáticamente.

### Clonar una rama específica (opcional)

```bash
git clone -b principal https://github.com/Nico1091/Ejemplos_ciscoPackettarcer.git
```

## Cómo abrir los ejemplos

1. Abre **Cisco Packet Tracer**.
2. Ve a `File > Open` (Archivo > Abrir).
3. Navega hasta la carpeta clonada y selecciona el archivo `.pkt` que quieras revisar (por ejemplo, `Ejemplo1.pkt`).

También puedes hacer doble clic sobre el archivo `.pkt` si Packet Tracer está asociado a esa extensión en tu sistema.

## Mantener tu copia actualizada

Si el repositorio recibe cambios y ya lo tienes clonado, actualízalo con:

```bash
git pull origin principal
```

## Cómo contribuir

1. Haz un *fork* del repositorio.
2. Crea una rama para tus cambios:

   ```bash
   git checkout -b mi-aporte
   ```

3. Añade tus archivos y confirma los cambios:

   ```bash
   git add .
   git commit -m "Descripción de mi aporte"
   ```

4. Sube tu rama y abre un *Pull Request*:

   ```bash
   git push origin mi-aporte
   ```

## Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo [`LICENSE`](./LICENSE) para más detalles.
