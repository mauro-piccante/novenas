# Novenas

Web para rezar novenas día a día, en español e italiano.
https://mauro-piccante.github.io/novenas/

| Oración | Carpeta |
|---|---|
| Novena a María Desatanudos | `desatanudos/` |
| Treintena a San José | `san-jose/` |
| Novena a San Rafael Arcángel | `san-rafael/` |
| Novena de las Rosas a Santa Teresita | `santa-teresita/` |

Cada carpeta es un solo `index.html`, sin dependencias ni build. Idioma con `?lang=es` o `?lang=it`
(se recuerda en `localStorage`, clave `novenas-lang`). El progreso se guarda solo en el navegador.

Las antiguas direcciones (`novena-desatanudos`, `novena-san-raffaele`, `trentena-san-giuseppe`,
`novena-santa-teresita`) redirigen aquí.
