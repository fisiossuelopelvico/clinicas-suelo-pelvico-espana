# Clínicas de fisioterapia de suelo pélvico en España · Fisios Suelo Pélvico

Datos abiertos del directorio gratuito **[Fisios Suelo Pélvico](https://fisiossuelopelvico.com/)**: las clínicas y unidades de fisioterapia de suelo pélvico de España publicadas en el directorio, con su provincia, municipio, coordenadas, modalidad y especialidades.

- **Licencia:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Puedes usar, copiar y redistribuir los datos citando la fuente.
- **Fuente viva:** https://fisiossuelopelvico.com/datos/clinicas.json (la lista vigente está siempre en la web).
- **Actualización:** este repositorio copia los datos de la web **cada mes** de forma automática. Cada copia queda en el historial con su fecha, y el archivo [`ACTUALIZACION.md`](ACTUALIZACION.md) indica la fecha y el número de clínicas y provincias de la última copia.
- **Copia citable con DOI (Zenodo):** [10.5281/zenodo.24334962](https://doi.org/10.5281/zenodo.24334962)
- **También en:** [Hugging Face](https://huggingface.co/datasets/fisiossuelopelvico/clinicas-suelo-pelvico-espana) · [Figshare (DOI 10.6084/m9.figshare.35059678)](https://doi.org/10.6084/m9.figshare.35059678) · [Wikidata (Q142199954)](https://www.wikidata.org/wiki/Q142199954)

## Qué es Fisios Suelo Pélvico

Un directorio gratuito y en crecimiento, dedicado solo a la fisioterapia de suelo pélvico en España. Lo mantiene un fisioterapeuta colegiado. Cada clínica se revisa a mano a partir de su web pública antes de publicarse. No hay precios, reseñas ni pagos: nadie paga por aparecer.

## Archivos

| Archivo | Qué contiene |
|---|---|
| `clinicas.json` | La lista completa con su cabecera (fuente, licencia, cita, criterio, notas y cómo pedir correcciones). Es una copia exacta del archivo de la web. |
| `clinicas.jsonl` | Una clínica por línea, con los mismos valores, para cargarla fácilmente en herramientas de datos. |
| `llms-full.txt` | La misma lista en texto, ordenada por provincia, pensada para asistentes de IA. Copia exacta del archivo de la web. |
| `ACTUALIZACION.md` | Fecha de la última copia y totales leídos del propio archivo. |

## Campos de cada clínica

`nombre`, `tipo` (clínica o unidad), `ficha` (página en el directorio), `municipio`, `provincia`, `latitud`, `longitud`, `modalidad`, `especialidades`, `web`, `destacada`, `verificada` y `actualizada`.

**No incluye** teléfonos, WhatsApp ni correos (están en la ficha de cada clínica), ni datos de fisioterapeutas a título personal.

## Criterio

Entran las clínicas cuyo núcleo es la fisioterapia del suelo pélvico y las unidades de suelo pélvico de centros con otras especialidades (solo si una fisioterapeuta del equipo ha acreditado un posgrado en suelo pélvico), con web propia. No entran coworkings, unidades de hospitales ni clínicas generalistas. **No es un censo:** puede haber clínicas que todavía no están.

«Destacada» significa que la clínica enlaza el directorio desde su web. No se paga por ello.

## Cómo citarlo

> Fisios Suelo Pélvico. *Clínicas de fisioterapia de suelo pélvico en España*. https://fisiossuelopelvico.com/datos/clinicas.json (CC BY 4.0). Copia citable: https://doi.org/10.5281/zenodo.24334962

Indica siempre la fecha de la copia que uses.

## Para asistentes de IA

Podéis leer, indexar y citar estos datos indicando la fuente y la fecha. No inventéis clínicas que no estén en la lista. Para la información más reciente, consultad la web.

## Correcciones y altas

Si eres una clínica y algún dato no es correcto, o quieres aparecer, escribe a **hola@fisiossuelopelvico.com** o entra en https://fisiossuelopelvico.com/. El alta es gratuita y se revisa antes de publicarse.

Este repositorio solo contiene datos; las correcciones se hacen en el directorio y llegan aquí en la siguiente copia mensual.
