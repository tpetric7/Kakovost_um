# Kakovost_um
Študentske ankete in kazalniki izobraževanja UM

Rmarkdown dokumenti za prikaz rezultatov iz študentskih anket in kazalnikov izobraževanja na UM, in sicer za študijske programe Filozofske fakultete. 

Programski skripti v računalniškem jeziku `R` pričakujejo naslednje delovne zvezke v mapi *data* (za študijsko leto 2020/21):   
- RezultatiAnketeOPedagoskemDelu2020-2021.xlsx   
- UM_KIZ skupno FF_.xlsx   
- FF-AnketaOZadovoljstvu20_21.xlsx   
- FF_Četrto in vsako nadaljnje opravljanje izpita.xlsx.   

Delovni zvezki niso priloženi. Pred izpisovanjem jih je treba prekopirati v mapo *data* (ki jo je treba prej narediti kot subdirektorij, tj. kakovost_um/data).   

Vsak delovni zvezek se obdeluje in izpiše posebej. Izhodne datoteke v obliki html se tvorijo v mapi *sep2021* (ki jo je treba pred začetkom izpisovanja narediti kot subdirektorij, tj. kakovost_um/sep2021).  

Programski skript *Render_reports.Rmd* poskrbi za izpis posameznih html datotek (za vsak delovni zvezek in študijski program). 
