### git tag nombre_etiqueta
Lista las etiquetas en orden alfabetico.

### git tag -a nombre_etiqueta -m "mensaje_etiqueta"
Etiqueta anotada. Se guarda en la base de datos de Git como objeto entero. Tienen un checksum; contienen el nombre del etiquetador, correo electronico y fecha; y tienen un mensaje asociado.

```
git tag -l "v1.*"
```

Lista de etiquetas que coincidan con el patron especifico.