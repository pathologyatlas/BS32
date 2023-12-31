







```
r language BS32, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis isospora TR, echo = (language == "TR")
## BS32 - isospora {#sec-BS32 }
```


```
asis isospora EN, echo = (language == "EN")
## BS32 - isospora {#sec-BS32 }
```






```
r BS32 screenshot HE1, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS32-HE1_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS32/HE1.html",
  file = "./screenshots/BS32-HE1_screenshot.png"
)
}
```






```
r BS32 screenshot HE2, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS32-HE2_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS32/HE2.html",
  file = "./screenshots/BS32-HE2_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS32/HE1.html](https://images.patolojiatlasi.com/BS32/HE1.html)





```
asis, echo = (language == "TR")

**isospora**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS32-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS32/HE1.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS32/HE1.html)
```

```
asis, echo = (language == "EN")

**isospora**

[![Click for Full Screen WSI](./screenshots/BS32-HE1_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS32/HE1.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS32/HE1.html)

```









[https://images.patolojiatlasi.com/BS32/HE2.html](https://images.patolojiatlasi.com/BS32/HE2.html)





```
asis, echo = (language == "TR")

**isospora**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS32-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS32/HE2.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS32/HE2.html)
```

```
asis, echo = (language == "EN")

**isospora**

[![Click for Full Screen WSI](./screenshots/BS32-HE2_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS32/HE2.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS32/HE2.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS32/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS32/HE1.html" style="height:600px;width:100%;" data-external="1"></iframe>

```







```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS32/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS32/HE2.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

isospora

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

isospora

:::

```









:::::








