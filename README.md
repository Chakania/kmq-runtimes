# kmq-runtimes

Los runtimes de **DEVIA Terminal**, firmados, para que la app (variante `direct`) los instale desde el teléfono.

Aquí solo hay **releases**: el código que los construye y los firma vive en otro repositorio. Cada release trae
`manifest.json`, su firma `manifest.sig` y el árbol en un `.tar.gz`; la app verifica la firma y el `sha256` de todo
antes de instalar nada. El catálogo de lo publicado está en la release `catalog` (`catalog.json` y `catalog.sig`),
firmado con la misma clave.

Cada runtime lleva sus licencias y su procedencia en el propio manifiesto.
