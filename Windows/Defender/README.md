# Windows Defender

## Excluded Items

Below are several example directories to be excluded for better performance.

### vcpkg

- `${VCPKG_DIR}` (e.g. `C:/dev/vcpkg`)
- `%LocalAppData%\Temp`
- `%LocalAppData%\Temp\vcpkg`
- `%LocalAppData%\vcpkg`

### JetBrains

IDE Data:

- `%LocalAppData%\JetBrains`

Jetbrains Toolbox:

- `${TOOLBOX_DIR}` (e.g. `E:/Jetbrains/Toolbox`)

### Python

Installed directory:

- `C:\Program Files\Python\Python311`
- `%LocalAppData%\Programs\Python\Python311`

Pip:

- `%LocalAppData%\pip`

### Rust

- `~/.cargo`

### Visual Studio

- `D:\Program Files\Visual Studio`
- `D:\Windows Kits`

### Firefox

- `C:\Program Files\Firefox Nightly`

