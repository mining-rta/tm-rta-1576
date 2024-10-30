# A First Test of Topic Modeling the Data of the Imperial Diet of 1576 in Comparison with the Editorial Subject Terms for 1556/57 and 1576

The repository contains data of a **mini project** created as a test for using **Topic Modeling on the Imperial Diet records** and funded by the **Commission for Modern Austrian History** (*Geschichtswissenschaftliches Edieren in der digitalen Transformation: Eine Annäherung am Beispiel einer Themengeschichte der Reichstage der zweiten Hälfte des 16. Jahrhunderts*). 

The data was also used for a presentation at DiPaDA2024.

## Abstract from the German-Language Application

Die Reichstage (= RTe) sind Ereignisse, in denen im Zusammenspiel von kaiserlichem Reichsoberhaupt und den hochadeligen wie städtischen Reichsständen über die Geschicke Mitteleuropas beraten und beschlossen wurde. Die Beratungsgegenstände sind vielgestaltig und berühren so unterschiedliche wie zentrale Bereiche gesellschaftlichen Miteinanders, wie, in moderner Diktion, Fragen gemeinsamer Gefahrenabwehr, der inneren Sicherheit, der Ausgestaltung gesellschaftlichen Miteinanders im Vorzeichen religiöser Pluralität, um nur die wichtigsten zu nennen. Dennoch ist eine Themengeschichte der RTe des 16. Jahrhunderts bis heute nicht geschrieben. Sie kann nun aber, sich des methodischen Instrumentariums der Digital Humanities bedienend, mit ganz neuen, vielversprechenden Möglichkeiten in Angriff genommen werden. Die Ergebnisse sind für die RTsgeschichte von Interesse, aber auch für die Möglichkeiten, die sich aus der digitalen Transformation für editorische Langzeitvorhaben generell ergeben. 

## The Edited Minutes of the Imperial Diet of 1576

- Edited Texts: https://gams.uni-graz.at/context:rta1576.ed
- Protokoll des kaiserlichen Geheimen Rates zum Regensburger Reichstag: https://gams.uni-graz.at/o:rta1576.edd1e7w15223
- Kurfürstenratsprotokoll Mainz: https://gams.uni-graz.at/o:rta1576.edd1e11W110511
- Kurfürstenratsprotokoll Sachsen: https://gams.uni-graz.at/o:rta1576.edd1e10d24421
- Fürstenratsprotokoll Österreich: https://gams.uni-graz.at/o:rta1576.edd1e7w152270
- Auszug aus dem Fürstenratsprotokoll Hessen-Kassel: https://gams.uni-graz.at/o:rta1576.edd1e7w15fr02
- Auszug aus dem Fürstenratsprotokoll Augsburg: https://gams.uni-graz.at/o:rta1576.edd1e7w15fr04
- Auszug aus dem Fürstenratsprotokoll der Wetterauer Grafen: https://gams.uni-graz.at/o:rta1576.edd1e7w15fr03
- Städteratsprotokoll Ulm: https://gams.uni-graz.at/o:rta1576.edd1e10u1591
- Protokoll der Verhandlungen im Supplikationsausschuss: https://gams.uni-graz.at/o:rta1576.edd1e7W1109116
- Protokoll für die Religionsverhandlungen der CA-Stände (Kurpfalz): https://gams.uni-graz.at/o:rta1576.edd1e11m515221
- Protokoll der Beratungen der katholischen Stände (Kurpfälzer Überlieferung): https://gams.uni-graz.at/o:rta1576.edd1e10m5152274
- Auszug aus dem Fürstenratsprotokoll Eichstätt: https://gams.uni-graz.at/o:rta1576.edd1e8m515511
- Auszug aus dem Fürstenratsprotokoll Straßburg: https://gams.uni-graz.at/o:rta1576.edd1e10k119111
- Auszug aus dem Fürstenratsprotokoll Würzburg: https://gams.uni-graz.at/o:rta1576.edd1e8w99141
- Auszug aus dem Fürstenratsprotokoll Österreich-Tirol: https://gams.uni-graz.at/o:rta1576.edd1e8m531431
- Auszug aus dem Städteratsprotokoll Köln: https://gams.uni-graz.at/o:rta1576.edd1e7k36101

## The DiPaDA2024 Presentation and Abstract on Zenodo

Bleier, Roman, & Zeilinger, Florian (2024, Mai 28). "Matrikelmoderation", what else? Topic Modeling of the Holy Roman Empire's Imperial Diet Records of 1576. Digital Humanities in the Nordic and Baltic Countries Conference (DHNB 2024) (DiPaDA 2024), Reykjavík. Zenodo. https://doi.org/10.5281/zenodo.11371812.

## Content of the Repository

- **cross-edition index:** first attempt to merge subject indices from the general indices of the respective Imperial Diet records editions on 1556/57 and 1576 into a cross-edition index, enables the comparison of editorial indexing of subject terms and Topic Modeling
- **metadata:** contains metadata on the full-text transcribed and edited minutes of the Imperial Diet of 1576, split into daily sections, such as minute title, filename, date and editorially assigned subject terms at a daily level
- **output_gensim:** Resultats of Topic Modeling with Gensim
- **output_mallet:** Resultats of Topic Modeling with Mallet
- **stopwords:** contains a self-created list of stop words to be deleted in the specific preprocessing of Early New High German Imperial Diet records from the second half of the 16th century
- **txt:** contains the full-text transcribed and edited minutes of the edition of the Imperial Diet records of 1576, which are split into daily sections
