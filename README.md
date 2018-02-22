# Munich311

repository for work on the Munich Codex Graecus 311

## Initial Tasks

1. Generate a codex model for Munich Codex Graecus 311. Example of roughly what it should look like [here](https://github.com/hmteditors/trinity/blob/master/collections/gen44.csv)
  - create a table with the columns (Folio,Sequence,Label,DefaultImage)
  - Folio: urn:cite:hmt:munCG311.X (with X by the folio reference, eg. 1r...)
  - Sequence: starting with 1
  - RV: "recto" or "verso"
  - Label:  Catalogus codicum manuscriptorum Graecorum Bibliothecae Regiae Bavaricae, Bd.: 3, Cod. CCXXXIV - CCCXLVII cont., Monachii, 1806, page X (with X replaced by 1-3 digits for pages 1-739)
  - DefaultImage:  urn:cite2:munich:bsb311imgs.v1:MunCG311_pageX with X replaced by 1-3 digits for pages 1-739

2. Identify line ranges to page references
3. Index lines to image
4. Edit main text.



##  Images

The `views` folder has a markdown page with thumbnails to all images of the MS, linked to the HMT image citation tool.  (Alternatively, it's [visible here](https://github.com/hmteditors/Munich311/blob/master/views/munich311-thumbs.md) in online version of this github repository.)

## Background information

Munich catalog [entry for Codex 311 (CCCXI)](http://daten.digitale-sammlungen.de/~db/bsb00008171/images/index.html?fip=193.174.98.30&seite=266&pdfseitex=)

## URNs

For generating a codex model, this URN refers to the page as an object:

    urn:cite2:munich:bsb311imgs.v1:MunCG311_pageX

with X replaced by 1-3 digits for pages 1-739.

Please note, page numbers are not folio numbers. Page numbers should be sequential.
