Una herramienta poderoso que nos permite adaptar nuestra pagina web a diferents resoluciones.

Poniendo q cada resolucion poniendo un estilo diferente, si cumple cada paso o orden.


--- ESTRUCTURA DE LAS MEDIA QUERIES:
@media not|only mediatype and (expressions){
    CSS-code
}

1. @media : Es la regla que inicia la media querie
2. not|only: Operadores opcionales. Not excluye a los dispositivos que cumplen con la consulta. Only es para navegadores antiguos que no soportan media queries para que pueden utilizar los estilos definidos en la consulta.
3. mediatype: El tipo de medidor para la consulta. 
4. and: opcional. para combinar varias expressiones en una consulta.
5. (expressions):  Avaluan caracteristicas especificas.