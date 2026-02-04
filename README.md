# Curriculum Vitæ

## Installazione

    python -m venv .venv    
    source .venv/bin/activate
    pip install rendercv[full]

## Uso

    source .venv/bin/activate

Modifica i file .yaml, e ricompila i file con

    rendercv render --watch Carmone_EN.yaml

I file prodotti sono disponibili dentro `rendercv_output/` 

    xdg-open rendercv_output/Francesco_P.Carmone_CV.pdf

> Puoi abilitare `intellisense` impostando `RenderCV` come JSON schema

## Colori

Rimpiazza la variabile

    name: &accent rgb(128,128,128)

Con il colore di accento preferito. Alcune scelte:

```
Teal:                       rgb(0, 128, 128)
Dark Forest Green:          rgb(34, 69, 34)
Dark Forest Green:          rgb(38, 94, 38)
Charcoal Black:             rgb(36, 36, 36)
Graphite:                   rgb(65, 74, 76)
Dark Teal:                  rgb(0, 77, 77)
Espresso Brown:             rgb(59, 47, 47)
Bourgogne:                    rgb(113, 62, 68)
```