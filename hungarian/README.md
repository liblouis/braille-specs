# Hungarian braille specifications, latest 2019 determined standard
The official hungarian grade 1 and grade 2 braille standard is deterbined with The Hungarian Braille Committee official in 2012, and latest modification date is 2019. This subpage always containing latest official accepted hungarian braille standards for Liblouis braille developer community.
The hungarian braille tables affected with this standard is following:
* tables/hu-hu-comp8.ctb: the official accepted 8-dots computer braille table. In hungary we using only eight dot mode with computer braille format, other variations is six dot type (the full braille and the grade 2 tables). This is the official standard mode.
* tables/hu-hu-g1.ctb: the official accepted grade 1 braille (six dot mode), this is the full braille mode table.
* tables/hu-hu-g2.ctb: this table containing the hungarian grade 2 braille rules, with official uses hungari in literary books, hungarian braille news papers, etc. Hungarian grade 2 braille have two variations, small, fever abbreviations containing rule set (this variation containing only 45 abbreviation rules), and larger variations, with need using literary books, braille printing documents.
In 2017, the larger variation is implemented.

Official table maintainer from Liblouis community in Hungary: Attila Hammer from [IT Foundation for the Visually Impaired - Hungary](http://www.infoalap.hu).
Attila is subscribed in Liblouis list. If anybody have question the hungarian braille tables related, feel free ask a quastion in developer community.
Please ask beginner table maintainers:
If would like doing bigger changes in hungarian braille tables related, please not commit the changes official the source [Liblouis repository](https://github.com/liblouis/liblouis) until all testcases are not passed, because hungarian language is a very complex language.
If a maintenance change related have a question, have possibility to write e-mail a question the table maintainer with following addresses:
* Full official work time used e-mail address, with awailable the hungarian braille tables: hammer.attila at infoalap dot hu
* Private e-mail address, with Attila subscribed into Liblouis mailing list: hammera at pickup dot hu

## Hungarian language awailable downloadable documents
The Hungarian Braille Committee official subpage is following:
[The Hungarian Braille Committee official subpage](https://www.mvgyosz.hu/tudjon-meg-tobbet-hu/braille-iras/)
Following two documents are standard braille embossers USA braille character set compatible, windows CRLF line terminator wrapped documents, with containing the hungarian braille alphabet. Without changes, this documents are free usable:
* [Braille Alphabet Book (first part, USA BRF document, formatted with Windows line wrap)](https://www.mvgyosz.hu/wp-content/uploads/2020/04/braille-%C3%A1b%C3%A9c%C3%A9sk%C3%B6nyv01.brf)
* [Braille Alphabet Book (second part, USA BRF document, formatted with Windows line wrap)](https://www.mvgyosz.hu/wp-content/uploads/2020/04/braille-%C3%A1b%C3%A9c%C3%A9sk%C3%B6nyv02.brf)
* [Hungarian language used braille dots (an EXCEL table, with containing in 12 worksheet the various braille rules)](https://www.mvgyosz.hu/wp-content/uploads/2020/04/magyar-braille-%C3%ADr%C3%A1s-jelei.xls)
* [Summary collection of decisions concerning Braille adopted by the presidency of the Hungarian National Association of the Blind and Visually Impaired](https://www.mvgyosz.hu/wp-content/uploads/2020/04/braille-%C3%ADr%C3%A1s-eln%C3%B6ks%C3%A9gi-hat%C3%A1rozatok.docx)
* [The medicine boxes braille standards collection documents (dot sizes, line length, etc.)](https://www.mvgyosz.hu/wp-content/uploads/2020/04/braille-gy%C3%B3gyszercsomagol%C3%A1sokon.doc)
## Marburg Medium standard in Hungary
The Marburg Medium standard specifies the following parameters for the size of Braille dots and their spacing:
* Diameter of a point: 1.6 mm
* The distance between the centers of two points inside a letter (horizontally): 2.5 mm
* Distance between the centers of two points within a letter (vertically): 2.5 mm
* The distance between the same point of two letters within a word: 6 mm
* Distance between the same point of two letters if there is a space between the two letters: 12 mm
* Line spacing (between the same point of two letters): 10 mm

## [the hungarian braille dots table awailable informations](https://www.mvgyosz.hu/wp-content/uploads/2020/04/magyar-braille-%C3%ADr%C3%A1s-jelei.xls)
The linked table 12 worksheet described the hungarian language used braille rules, but not all rule types need implementing (yet).
Worksheets list, to easyest other maintainers think when need searching a dot combination a table related:
1. worksheet: this worksheet containing only table of contents.
2. worksheet: hungarian full braille writing braille dots.
3. worksheet: the 10 special computer characters dots combination with changed since 2019, this changes are implemented the 3.21 release. Why need Hungarian Braille Commission determining this change? For example, before 2019, official the \ character and é letters are marked equals with 16 dot combination, and impossible to detecting a reader person the difference both forward and backward translation. The change was fortunately approved by the Hungarian Braille Commission, and the Excel table are described this rules.
4. worksheet: The grade 2 braille rules (the simplest rule definition book). The hungarian braille grade 2 are have two variations: the simplest variation (little grade 2, with described the EXCEL table), this type rule set only containing minimal number of grades, and large grade 2, with more complex, and usual using with braille books and publications. The Hungarian Braille Commission asked me and colleagues to implement in 2017 the large grade2 set.
Larger grade 2 rules is described hungarian language in [this document](hungarian_large_grade2_rules.doc).
5. worksheet: Hungarian mathematics braille rules (not need yet implementing, not requested the implementation with the Braille Commission). With screen readers uses the basic full braille writing mathematical dots with forward translation, and if screen reader supports this, math ML content presents with nemeth braille specification (For example in JAWS For Windows copyed from LiblouisUTDML source repository the nemeth.ctb file).
6. worksheet: In music usable hungarian notation braille dot combinations (482 dot combinations). Not need implementing yet, the Hungarian Braille Commissee not requested the implementation.
7. worksheet: hungarian unicode braille dot combinations (I think 587 dot combinations), not need checking this sheet, because this is a very large worksheet.
8. worksheet:     Euro unicode braille worksheet with I think oldest time used with JAWS 12.0 mixed USA unicode braille. Not need doing this sheet anything.
9. worksheet: similar with the prewious sheet, this seet I think containing only with european unicode braille characters. Very large worksheet. Not need doing this sheet anything.
10. worksheet: Similar with the previous two pages, I think this is only the eight dots USA unicode computer braille, with oldest time used with JAWS 12.0. This is a very large worksheet. Not need doing anything this sheet related.
11. worksheet: Hungarian braille dots with need using in chess game (25 dot combinations). I don't no why have this sheet in this Excel table, Hungarian Braille Commission not requested yet the implementation.
12. worksheet: Hungarian braille dots with need using in hungarian Braille cards (33 dot combinations). I don't no why have this sheet in this Excel table, Hungarian Braille Commission not requested yet the implementation.


