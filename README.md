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
- [example](https://github.com/hmteditors/trinity/blob/master/collections/LineRangestoFolio.csv)

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


## Editing Main Text ##

1. **Hard Copy Edit** Before you edit the main text in the XML, you should do a hardcopy edit. This means printing out an edition of the Iliad to be our base text and marking the differences as need.
2. **XML Edit** after you've done your pass at hardcopy editing, you may update the xml file. You should follow [these instructions](http://hcmid.github.io/tech/software/) for downloading the software you'll need to edit in XML
3. **XML Mark Up** There is a limited about of mark up we use in XML editing of the main text. Review the [editor's manual](http://homermultitext.github.io/hmt-editors-guide/guide/) here for more information. 

**Other Helpful Links**
1. [Typing Greek etc.](http://homermultitext.github.io/hmt-docs/tips/)
2. [Other Useful References](http://homermultitext.github.io/hmt-docs/references/) 
