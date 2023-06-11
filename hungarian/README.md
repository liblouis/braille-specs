# Hungarian braille specifications, latest 2019 determined standard

The official Hungarian grade 1 and grade 2 braille standard is
determined with the Hungarian Braille Committee official in 2012, and
latest modification date is 2019. This sub page always contains the
latest official accepted Hungarian braille standards for the liblouis
braille developer community.

## Hungarian language awailable downloadable documents

The Hungarian Braille Committee official sub page is following:

[The Hungarian Braille Committee official sub page](https://www.mvgyosz.hu/tudjon-meg-tobbet-hu/braille-iras/)

Following two documents are standard braille embossers USA braille
character set compatible, windows CRLF line terminator wrapped
documents, with containing the Hungarian braille alphabet. Without changes, this documents are free usable.
Publisher: MVGYOSZ
Documents created by: Braille Committee of the Hungarian National Association of the Blind and Visually Impaired
Release date: 2018
ISBN number: 978-615-5919-01-5

* [Braille ábécés könyv (első rész, USA BRF formátumú dokumentum, Windows sortöréssel formázva)](braille-ábécéskönyv01.brf)
* [Braille ábécés könyv (második rész, USA BRF dokumentum, Windowsos sortöréssel formázva)](braille-ábécéskönyv02.brf)
* [Magyar Braille írásjelek táblázata](magyar-braille-írás-jelei.xls)
This document contains Hungarian language used braille dots an EXCEL table, with containing in 12 worksheet the various braille rules.
* [Magyar nagy rövid írás szabálykönyv](hungarian_large_grade2_rules.doc)
This document contains hungarian Grade 2 rules documentation book document.
* [Braille-írás elnökségi határozatai](braille_iras_elnoksegi_hatarozatok.docx)
This document contains a summary collection of decisions concerning Braille adopted by the presidency of the Hungarian National Association of the Blind and Visually Impaired (latest modification date: 2019-03-14)
* [Braille-írás elnökségi határozatai (online verzió)](https://www.mvgyosz.hu/wp-content/uploads/2020/04/braille-%C3%ADr%C3%A1s-eln%C3%B6ks%C3%A9gi-hat%C3%A1rozatok.docx)

## [The Hungarian braille dots table available information](magyar-braille-írás-jelei.xls)

The linked table 12 worksheet describes the Hungarian language used
braille rules, but not all rule types need implementing (yet).

Worksheets list, to easyest other maintainers think when need
searching a dot combination a table related:

1. worksheet: this worksheet containing only table of contents.
2. worksheet: Hungarian full braille writing braille dots.
3. worksheet: the 10 special computer characters dots combination with
   changed since 2019, this changes are implemented the 3.21 release.
   Why need Hungarian Braille Commission determining this change? For
   example, before 2019, official the \ character and é letters are
   marked equals with 16 dot combination, and impossible to detecting
   a reader person the difference both forward and backward
   translation. The change was fortunately approved by the Hungarian
   Braille Commission, and the Excel table are described this rules.
4. worksheet: The grade 2 braille rules (the simplest rule definition
   book). The Hungarian braille grade 2 are have two variations: the
   simplest variation (little grade 2, with described the EXCEL
   table), this type rule set only containing minimal number of
   grades, and large grade 2, with more complex, and usual using with
   braille books and publications. The Hungarian Braille Commission
   asked me and colleagues to implement in 2017 the large grade2 set.
   Larger grade 2 rules is described Hungarian language in [this
   document](hungarian_large_grade2_rules.doc).
5. worksheet: Hungarian mathematics braille rules (not need yet
   implementing, not requested the implementation with the Braille
   Commission). With screen readers uses the basic full braille
   writing mathematical dots with forward translation, and if screen
   reader supports this, math ML content presents with nemeth braille
   specification (For example in JAWS For Windows copied from
   LiblouisUTDML source repository the nemeth.ctb file).
6. worksheet: In music usable Hungarian notation braille dot
   combinations (482 dot combinations). Not need implementing yet, the
   Hungarian Braille Committee not requested the implementation.
7. worksheet: Hungarian Unicode braille dot combinations (I think 587
   dot combinations), not need checking this sheet, because this is a
   very large worksheet.
8. worksheet: Euro Unicode braille worksheet with I think oldest time
   used with JAWS 12.0 mixed USA Unicode braille. Not need doing this
   sheet anything.
9. worksheet: similar with the precious sheet, this sheet I think
   containing only with European Unicode braille characters. Very
   large worksheet. Not need doing this sheet anything.
10. worksheet: Similar with the previous two pages, I think this is
    only the eight dots USA Unicode computer braille, with oldest time
    used with JAWS 12.0. This is a very large worksheet. Not need
    doing anything this sheet related.
11. worksheet: Hungarian braille dots with need using in chess game
    (25 dot combinations). I don't no why have this sheet in this
    Excel table, Hungarian Braille Commission not requested yet the
    implementation.
12. worksheet: Hungarian braille dots with need using in Hungarian
    Braille cards (33 dot combinations). I don't no why have this
    sheet in this Excel table, Hungarian Braille Commission not
    requested yet the implementation.


