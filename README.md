# scoop-lyra

A [Scoop](https://scoop.sh) bucket for [Lyra Viewer](https://github.com/lyra-viewer/Lyra) —
a high-performance, minimalist native image viewer for Windows.

## Install

```powershell
scoop bucket add lyra https://github.com/lyra-viewer/scoop-lyra
scoop install lyra-viewer
```

Launch it from the Start Menu (**Lyra Viewer**) or from a terminal - the bucket
also installs a `lyra` shim, so you can open a file directly:

```powershell
lyra path\to\image.png
```

## Update

```powershell
scoop update lyra-viewer
```

## Uninstall

```powershell
scoop uninstall lyra-viewer
```

## Notes

- Windows builds are **64-bit (x86-64)** only.
- The distribution is self-contained: `LyraViewer.exe` plus the native codec
  libraries under `lib\Windows\`. No .NET runtime install is required.

---

Manifests live in [`bucket/`](bucket). The app itself is developed at
[lyra-viewer/Lyra](https://github.com/lyra-viewer/Lyra).
