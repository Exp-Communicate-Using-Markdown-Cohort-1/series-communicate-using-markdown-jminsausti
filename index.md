# PRIMERA CABERCERA
## SEGUNDA CABECERA
![Image of KATUA](https://octodex.github.com/images/yaktocat.png)
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
````
