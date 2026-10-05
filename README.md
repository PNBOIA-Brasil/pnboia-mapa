# pnboia-mapa

Mapa público das estações oceanográficas (boias fundeadas) do PNBOIA e da REMObs,
incorporado na página <https://www.marinha.mil.br/chm/dados-do-goos-brasil/pnboia-mapa>.

- Mapa: <https://pnboia-brasil.github.io/pnboia-mapa/>
- Variante com marcadores circulares: <https://pnboia-brasil.github.io/pnboia-mapa/circulos.html>

As estações vêm ao vivo da API REMObs (`https://api-boias.remobs.com.br/public/moored/stations`)
a cada abertura da página. Cada arquivo traz também uma cópia da lista, usada se a API não responder.
Com `?diag` no fim do endereço, o rodapé da legenda mostra de onde vieram os dados.

## Incorporar numa página

```html
<iframe src="https://pnboia-brasil.github.io/pnboia-mapa/" title="Mapa das estações PNBOIA e REMObs"
        style="width:100%;height:600px;border:0" loading="lazy"></iframe>
```

Os arquivos deste repositório são gerados; não edite à mão. Equipe REMObs / CHM.
