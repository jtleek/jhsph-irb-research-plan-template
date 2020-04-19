# JHSPH IRB Documents Template

The [Leek group](http://jtleek.com/) is writing IRB submissions to [PHIRST](https://phirst.jhsph.edu/sph/sd/PublicCustomLayouts/SSO/Selection?redirect=https%3A%2F%2Fphirst.jhsph.edu%2Fsph%2Fsd%2FRooms%2FDisplayPages%2FLayoutInitial%3FContainer%3Dcom.webridge.entity.Entity%255BOID%255B0A7646F3B149874E902185897C144551%255D%255D) more frequently. The auto-formatting for the IRB docs
makes them somewhat difficult to write. Here we will be posting R markdown templates for these docs for members of the
Leek group and others to use when submitting IRB forms. There is no guarantee they will continue to match the formatting required by 
the JHSPH IRB. 

## research-plan-template.Rmd

This is the template for new data collection research plans. The document will be rendered as a Word document by default. For the 
purpose of editing it may make more sense to change the document type to `html_document` and to use the [xaringan](https://github.com/yihui/xaringan) 
package for continuous rendering. 

```r 
library(flextable)
library(tibble)
library(xaringan)
xaringan::infinite_moon_reader("research-plan-template.Rmd")
```
