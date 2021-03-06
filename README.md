
<!-- README.md is generated from README.Rmd. Please edit that file -->

# COVID-19 Regional Maps and Code (Italy, Germany, and England)

This repository contains Code and data to connect information on
COVID-19 cases in Italy and Germany on a regional level to geographic
boundaries and population data. For documentation please see the
original data sources and the Code. All required original data is
referenced in the code.

## Data sources

Covid cases Italy

  - Dipartimento della Protezione Civile, Ministero della Salute:
    <https://github.com/pcm-dpc/COVID-19>

Covid cases Germany

  - Robert Koch Institut:
    <https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/dd4580c810204019a7b8eb3e0b329dd6_0>

Covid cases UK

  - Pre-processed data provided by Emma Doughty:
    <https://github.com/emmadoughty/Daily_COVID-19>

Geographies

  - istat Italy: <https://www.istat.it/it/archivio/222527>
  - Robert Koch Institut Germany:
    <https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/917fc37a709542548cc3be077a786c17_0>
  - Bundesamt für Kartographie und Geodäsie Germany:
    <https://gdz.bkg.bund.de/index.php/default/digitale-geodaten/verwaltungsgebiete/verwaltungsgebiete-1-1-000-000-ebenen-stand-01-01-vg1000-ebenen-01-01.html>
  - ONS Open Geography Portal:
    <https://geoportal.statistics.gov.uk/datasets/counties-and-unitary-authorities-december-2019-boundaries-uk-buc/data?page=6>

Demographic data

  - istat Italy: <http://dati.istat.it/Index.aspx?QueryId=18460&lang=en>
  - Regionaldatenbank Deutschland (Zensus 2011 age groups):
    <https://www.regionalstatistik.de/genesis/online/data;sid=FE602C43F3C36B8FA84AAA849E84D6E7.reg2?operation=abruftabelleAbrufen&selectionname=12111-04-01-4&levelindex=0&levelid=1585048532267&index=14>
  - Bundesinstitut für Bau-, Stadt- und Raumforschung INKAR (regional
    statistics 2017): <https://www.inkar.de/>

## Explanations

All steps for data preparation and plotting are in “01\_Script”. Static
data (like shape files or population data) and rocessed data are in
“02\_Data” and Figures in “03\_Output”. Original data on COVID cases
is not included in this repository but read from the links to original
data sources, as specified in script “01\_Read-Data.R”. Thus, the output
(especially the number of available dates) may change depending on
updates of the original data.

Feel free to re-use code and data, but you must consider the data
protection regulations and licenses of the original data, when re-using
or publishing.

Sorry for the scarce documentation, but for now please refer to the
original sources for detailed documenation or see comments in code.

## System and version information

Platform: Windows 10 (x86-64)

Version: R version 3.5.3
