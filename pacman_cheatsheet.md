# Pacman Cheatsheet

Search for already installed packages

```bash
pacman -Qs string
```

List all packages no longer required as dependencies (orphans)

```bash
pacman -Qdt
```

List all packages explicitly installed and not required as dependendies.

```bash
pacman -Qet
```

View information about a package

```bash
pacman -Si package
```

Remove a package and its dependencies which are not required by any other package

```bash
pacman -Rs package
```

Clean up local cache files

```bash
pacman -Scc
```

Remove dependencies that are no longer needed (orphans)

```bash
pacman -Rs $(pacman -Qtdq)
```
