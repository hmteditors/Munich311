# Munich311
repository for work on the Munich Codex Graecus 311

## Initial Tasks:
1. Generate a codex model for Munich Codex Graecus 311. Example of roughly what it should look like [here](https://github.com/hmteditors/trinity/blob/master/collections/gen44.csv)
  - create a table with the columns (Page,Sequence,Label,DefaultImage)
  - Page: urn:cite2:munich:bsb311imgs.v1:MunCG311_pageX with X replaced by 1-3 digits for pages 1-739
  - Sequence: starting with 1
  - Label:  Catalogus codicum manuscriptorum Graecorum Bibliothecae Regiae Bavaricae, Bd.: 3, Cod. CCXXXIV - CCCXLVII cont., Monachii, 1806, page X (with X replaced by 1-3 digits for pages 1-739)
  - DefaultImage: the urn for the image as provided by the HMT image service on BETA (see below)
  
2. Identify line ranges to page references
3. Index lines to image
4. Edit main text. 

## Links:
[BETA](http://beta.hpcc.uh.edu/tomcat/hmt-digital/) 

http://daten.digitale-sammlungen.de/~db/bsb00008171/images/index.html?fip=193.174.98.30&seite=266&pdfseitex=

## URNs:
### For generating a codex model, this URN refers to the page as an object
urn:cite2:munich:bsb311imgs.v1:MunCG311_pageX with X replaced by 1-3 digits for pages 1-739.

Please note, page numbers are not folio numbers. Page numbers should be sequential. 
