# ¡Atrapa ese asteroide con poliastro!

Charla "¡Atrapa ese asteroide con poliastro!" en la PyConES 2017.

http://nbviewer.jupyter.org/format/slides/github/poliastro/pycones2017-talk/blob/master/%C2%A1Atrapa%20ese%20asteroide%20con%20poliastro%21.ipynb#/6

## Instalación

```
$ pip install -r requirements.txt
```

Para regenerar las diapositivas [compatibles con ausencia de conexión a Internet](https://github.com/jupyter/nbconvert/issues/91#issuecomment-283736634):

```
$ jupyter nbconvert ¡Atrapa\ ese\ asteroide\ con\ poliastro\!.ipynb --to slides --reveal-prefix "https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.1.0"
$ python -m http.server
```
