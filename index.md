# PRIMERA CABERCERA
## SEGUNDA CABECERA

#### Añadimos una imagen
![Image of Yaktocat](https://fptxurdinaga.eus/wp-content/uploads/2023/06/Logo_Home3.png)

#### Añadimos código

```javascript
function cambiaBordeDiv3(div3){
                //no muestra nada porque el estilo se aplica desde etiqueta style o fichero externo
                //alert(eldiv.style.borderColor)
                if (!div3.style.borderColor)
                    bColor=null
                div3.innerHTML="Color del Borde sin getComputedStyle: " + bColor +"  "
                //muestra los estilos aplicados finales
                //alert(getComputedStyle(eldiv).getPropertyValue("border-color"))
                div3.innerHTML += "<br> Color del Borde con getComputedStyle: "+getComputedStyle(div3).getPropertyValue("border-color")
                div3.style.border="green 3px solid";
            }
```

#### Añadimos una lista
- [X] Elemento 1
- [ ] Elemento 2
- [ ] Elemento 3

