mapsBR
======

Mapas das regiões brasileiras

Para instalação do pacote **```mapsBR```  ** use a função **```install_github()```** do pacote **```devtools```**.

```{r}
install.package('devtools') #instala pacote devtools
require(devtools) #carrega pacote devtools
install_github('lgsilvaesilva/mapsBR') #instala pacote mapsBR
require(mapsBR)
data(regMun) #carrega mapa com os municípios brasileiros
```
