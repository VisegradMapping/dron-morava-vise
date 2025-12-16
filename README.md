# dron-morava
 
## zpracování dat

* snímky z dronu (cca 160), JPEG se souřadnicemi v EXIF
* Agisoft Metashape na učebně
    * *Workflow: Add photos; Align Photos; Build DEM; Build Photomosaic*
    * ořez polygonem (*outer boundary*)
    * *Export Photomosaic*
        * typ *Google Map Tiles* (PNG v ZIP)
* exportované dlaždice komprimovány `optipng`
    * cca 360 MiB → 310 MiB
