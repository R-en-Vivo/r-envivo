# Convenciones

Notar que en @_quarto.yml uso `execute-dir: project` entonces nunca hay que usar el paquete de R `here::here()` o trucos similares. Simplemente hacer referencia a cualquier directorio relativo a la raíz del repositorio en código, por ejemplo `datos/misdatos.csv`

En prosa, nunca usar la construcción: "no es X, sino es Y". 

Tampoco usar em-dash (guiones) como separadores de oraciones compuestas. Siempre preferir construcciones declarativas con puntos y comas, comas o empezar una nueva oración para no embeber una idea en otra.

En el código de R y `tidyverse`, e incluso en prosa que hable sobre este tema, siempre preferiremos utilizar el nuevo pipe `|>` y no el antiguo `%>%`, excepto en donde la operación se vea comprometida si no se utiliza el pipe antiguo.