# Web ejemplo con Hugo

Ejemplo de web con Hugo para clase de DAW

## Clonar con submódulos
```bash
$ git clone --recurse-submodules https://github.com/lmorillas/ejemplo-hugo.git
```

## Para usar en codespaces

```bash
git submodule update --init --recursive
hugo server -D -b / --appendPort=false
```


## Uso de Gallery

```md
{{< gallery match="images/*" sortOrder="desc" rowHeight="150" margins="5" thumbnailResizeOptions="600

```