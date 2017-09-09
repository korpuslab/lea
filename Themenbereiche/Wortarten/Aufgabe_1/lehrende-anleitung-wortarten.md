---
id: wortarten-01
layout: exercise_teacher
---

{% include assign_exercise.md %}

## Auswahl und Inhalt der Aufgaben

Das Aufgabenpaket enthält eine Liste an Token, die nach ihrer Wortart bestimmt werden sollen. 
Die Auswahl der zu bestimmenden Wortarten orientiert sich an den folgenden Lehrbüchern:

- Karin Pittner & Judith Berman (2015): _Deutsche Syntax. Ein Arbeitsbuch._ 6. Auflage. Tübingen: narr-Verlag.
- Musan, Renate (2009): _Satzgliedanalyse._ 2., aktualisierte Aufl. Heidelberg: Winter.

Welche Kategorien unterschieden werden, sieht man an der vereinfachten und leicht abgeänderten Version von STTS, s. [STTS_gekuerzt.pdf](STTS_gekuerzt.pdf), die den Studierenden zur Bearbeitung der Aufgabe zur Verfügung gestellt wird. Die nachfolgende Übersicht veranschaulicht die Abweichungen von STTS. 

- Die Spalte **Tagset für die Aufgabe** dokumentiert, inwiefern das ursprüngliche Tagset verändert wurde. Sie enthält also die Kategorien, die von den Studierenden für die Aufgabe bereitstehen. In den meisten Fällen wurden Kategorien zusammengefasst, z.B. Adverb und Pronominaladverb zu ADV. Nur an einer Stelle wurde eine Kateogorie gesplittet und zwar beim definiten und indefiniten Artikel: ART unterteilt sichin ARTDEF und ARTINDEF. Ein "/" zeigt an, dass die Kategorie entfernt wurde und daher auch nicht in der Aufgabe vorkommt.  

- Die Spalte **abgefragt?** dokumentiert, ob die jeweilige Kategorie in der Aufgabe abgefragt wird (+ = wird abgefragt, - = wird nicht abgefragt) 

<table border>
<thead><tr>
<th>Wortart</th><th>Bezeichnung STTS</th><th>Beispiel</th><th>STTS</th><th>Tagset für die Aufgabe</th><th>abgefragt?</th>
</tr></thead>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Adjektiv</td></tr>
<tr><td></td><td>attributives Adjektiv</td><td>[das] große [Haus]</td><td>ADJA</td><td>ADJA</td><td>+</td></tr>
<tr><td></td><td>adverbiales oder prädikatives Adjektiv</td><td>[er fährt] schnell, [er ist] schnell</td><td>ADJD</td><td>ADJD</td><td>+</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Adverb</td></tr>
<tr><td></td><td>Adverb</td><td>schon, bald, doch</td><td>ADV</td><td rowspan="2">ADV</td><td>+</td></tr>
<tr><td></td><td>Pronominaladverb</td><td>dafür, dabei, deswegen, trotzdem</td><td>PAV</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Präposition</td></tr>
<tr><td></td><td>Präposition</td><td>in [der Stadt]</td><td>APPR</td><td rowspan="2">AP</td><td>+</td></tr>
<tr><td></td><td>Postposition</td><td>[ihm] zufolge, [der Sache] wegen</td><td>APPO</td><td>+</td></tr>
<tr><td></td><td>Präposition mit Artikel</td><td>im [Haus], zur [Sache]</td><td>APPRART</td><td>/</td><td>-</td></tr>
<tr><td></td><td>Zirkumposition rechts</td><td>[von jetzt] an</td><td>APZR</td><td>/</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Artikel</td></tr>
<tr><td></td><td>definiter Artikel</td><td>der, die, das</td><td rowspan="2">ART</td><td>ARTDEF</td><td>+</td></tr>
<tr><td></td><td>indefiniter Artikel</td><td>ein, eine</td><td>ARTIND</td><td>+</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Konjunktion</td></tr>
<tr><td></td><td>unterordnende (subordinierende) Konjunktion mit Satz</td><td>weil, dass, damit, wenn, ob</td><td>KOUS</td><td>KOUS</td><td>+</td></tr>
<tr><td></td><td>nebenordnende (koordinierende) Konjunktion</td><td>und, oder, aber</td><td>KON</td><td>KON</td><td>+</td></tr>
<tr><td></td><td>unterordnende Konjunktion mit &bdquo;zu&ldquo; und Infinitiv</td><td>um [zu leben], anstatt [zu fragen]</td><td>KOUI</td><td>/</td><td>-</td></tr>
<tr><td></td><td>Vergleichskonjunktion</td><td>als, wie</td><td>KOKOM</td><td>/</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Nomen</td></tr>
<tr><td></td><td>normales Nomen</td><td>Tisch, Herr, [das] Reisen</td><td>NN</td><td>NN</td><td>+</td></tr>
<tr><td></td><td>Eigennamen</td><td>Hans, Hamburg, HSV</td><td>NE</td><td>NE</td><td>+</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Pronomen</td></tr>
<tr><td></td><td>Demonstrativpronomen</td><td>dieser, jener</td><td>PDS</td><td rowspan="2">PD</td><td>-</td></tr>
<tr><td></td><td>attribuierendes Demonstrativpronomen (=Demonstativartikel)</td><td>jener [Mensch], dieser [Fall]</td><td>PDAT</td><td>+</td></tr>
<tr><td></td><td>Indefinitpronomen</td><td>keiner, viele, man, niemand</td><td>PIS</td><td rowspan="3">PI</td><td>-</td></tr>
<tr><td></td><td>attribuierendes Indefinitpronomen</td><td>kein [Mensch], irgendein [Glas]</td><td>PIAT</td><td>+</td></tr>
<tr><td></td><td>attribuierendes Indefinitpronomen mit Determiner</td><td>[ein] wenig [Wasser], [die] beiden [Brüder]</td><td>PIDAT</td><td>-</td></tr>
<tr><td></td><td>Personalpronomen</td><td>ich, er, ihm, mich, dir</td><td>PPER</td><td>PPER</td><td>+</td></tr>
<tr><td></td><td>Possessivpronomen</td><td>meins, deiner</td><td>PPOSS</td><td rowspan="2">PPOS</td><td>-</td></tr>
<tr><td></td><td>attribuierendes Possessivpronomen (=Possessivartikel)</td><td>mein [Buch], deine [Mutter]</td><td>PPOSAT</td><td>+</td></tr>
<tr><td></td><td>Relativpronomen</td><td>[der Hund ,] der</td><td>PRELS</td><td rowspan="2">PREL</td><td>+</td></tr>
<tr><td></td><td>attribuierendes Relativpronomen</td><td>[der Mann ,] dessen [Hund]</td><td>PRELAT</td><td>-</td></tr>
<tr><td></td><td>reflexives Personalpronomen</td><td>sich, einander, dich, mir</td><td>PRF</td><td>PRF</td><td>-</td></tr>
<tr><td></td><td>Interrogativpronomen</td><td>wer, was</td><td>PWS</td><td rowspan="2">PW</td><td>+</td></tr>
<tr><td></td><td>attribuierendes Interrogativpronomen (=Interrogativartikel)</td><td>welche[Farbe], wessen [Hut]</td><td>PWAT</td><td>-</td></tr>
<tr><td></td><td>adverbiales Interrogativ- oder Relativpronomen</td><td>warum, wo, wann, worüber, wobei</td><td>PWAV</td><td>/</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Partikel</td></tr>
<tr><td></td><td>&bdquo;zu&ldquo; vor Infinitiv</td><td>zu [gehen]</td><td>PTKZU</td><td rowspan="5">PTK</td><td>-</td></tr>
<tr><td></td><td>Negationspartikel</td><td>nicht</td><td>PTKNEG</td><td>+</td></tr>
<tr><td></td><td>abgetrennter Verbzusatz</td><td>[er kommt] an, [er fährt] rad</td><td>PTKVZ</td><td>-</td></tr>
<tr><td></td><td>Antwortpartikel</td><td>ja, nein, danke, bitte</td><td>PTKANT</td><td>-</td></tr>
<tr><td></td><td>Partikel bei Adjektiv oder Adverb</td><td>am [schönsten], zu [schnell]</td><td>PTKA</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Verben</td></tr>
<tr><td></td><td>finites Vollverb</td><td>[du] gehst, [wir] kommen [an]</td><td>VVFIN</td><td>VVFIN</td><td>+</td></tr>
<tr><td></td><td>Imperativ vom Vollverb</td><td>komm [!]</td><td>VVIMP</td><td>VVIMP</td><td>-</td></tr>
<tr><td></td><td>Infinitiv vom Vollverb</td><td>gehen, ankommen</td><td>VVINF</td><td>VVINF</td><td>+</td></tr>
<tr><td></td><td>Infinitiv mit &bdquo;zu&ldquo; vom Vollverb</td><td>anzukommen, loszulassen</td><td>VVIZU</td><td>VVIZU</td><td>-</td></tr>
<tr><td></td><td>finites Hilfsverb</td><td>[du] bist, [wir] werden</td><td>VAFIN</td><td>VAFIN</td><td>+</td></tr>
<tr><td></td><td>Imperativ vom Hilfsverb</td><td>sei [ruhig !]</td><td>VAIMP</td><td>VAIMP</td><td>-</td></tr>
<tr><td></td><td>Infinitiv vom Hilfsverb</td><td>werden, sein</td><td>VAINF</td><td>VAINF</td><td>-</td></tr>
<tr><td></td><td>finites Modalverb</td><td>[ich] will, [er] durfte</td><td>VMFIN</td><td>VMFIN</td><td>+</td></tr>
<tr><td></td><td>Infinitiv vom Modalverb</td><td>wollen dürfen, können müssen, sollen, mögen, möchten</td><td>VMINF</td><td>VMINF</td><td>-</td></tr>
<tr><td></td><td>Partizip Perfekt vom Modalverb</td><td>gekonnt, [er hat gehen] können</td><td>VMPP</td><td>VMPP</td><td>-</td></tr>
<tr><td></td><td>Partizip Perfekt vom Vollverb</td><td>gegangen, angekommen</td><td>VVPP</td><td>VVPP</td><td>+</td></tr>
<tr><td></td><td>Partizip Perfekt vom Hilfsverb</td><td>gewesen</td><td>VAPP</td><td>VAPP</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Kardinalzahlen</td></tr>
<tr><td></td><td>Kardinalzahl</td><td>zwei [Männer], [im Jahre] 1994</td><td>CARD</td><td>/</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Interjektion</td></tr>
<tr><td></td><td>Interjektion</td><td>mhm, ach, tja</td><td>ITJ</td><td>ITJ</td><td>+</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Interpunktion</td></tr>
<tr><td></td><td>Komma</td><td>,</td><td>\$,</td><td>\$,</td><td>+</td></tr>
<tr><td></td><td>Satzbeendende Interpunktion</td><td>. ? ! ; :</td><td>\$.</td><td>\$.</td><td>+</td></tr>
<tr><td></td><td>sonstige Satzzeichen; satzintern</td><td>\- () []</td><td>$(</td><td>/</td><td>-</td></tr>
<tr style="background-color:#DDDDDD;"><td style="text-align:left;" colspan="6">Sonstiges</td></tr>
<tr><td></td><td>Fremdsprachliches Material</td><td></td><td>FM</td><td>/</td><td>-</td></tr>
<tr><td></td><td>Kompositions-Erstglied</td><td>An- [und Abreise]</td><td>TRUNC</td><td>/</td><td>-</td></tr>
<tr><td></td><td>Nichtwort, Sonderzeichen enthaltend</td><td>3:7, H2O, D2XW3</td><td>XY</td><td>/</td><td>-</td></tr>
</table>

> Hinweis: Kopulaverben und Hilfsverben werden in STTS nicht unterschieden; sie erhalten also gleichermaßen die Auszeichnungen VAFIN, VAIMP oder VAINF. 

## Nächste Schritte

- Um sich mit dem Aufgabenformat vertraut zu machen, empfehlen wir als nächsten Schritt die [Anleitung für die Studierenden]({{exercise.student_page}}) zu lesen
- Danach können Sie sich die Aufgabendateien
  ([Aufgabendatei]({{exercise.exercise_file}}) und
  [Musterlösung]({{exercise.solution_file}})) ansehen.

> Wenn Sie inhaltliche Änderungen an der Aufgabe an der Aufgabe vornehmen wollen, finden Sie hierzu eine Anleitung im zweiten Teil der [Technikanleitung für Lehrende](../../../Annotationsprogramm/Tabellenkalkulation/lehrende-anleitung-csv.html).

- Anschließend können Sie den Studierenden die Aufgabe zur Verfügung stellen. Wenn Sie keine inhaltlichen Änderungen durchgeführt haben, sind alle für die Studierenden notwendigen Dateien in der zip-Datei <a href="#" onClick="getZip(); return false">aufgabe.zip</a> zusammengestellt. Falls Sie Änderungen durchgeführt haben, muss das Paket entsprechend angepasst werden. 
- Nachdem Sie die Lösungen der Studierenden erhalten haben, kann es mit der Auswertung losgehen. Alle notwendigen Informationen hierzu finden sich in der [Technikanleitung für Lehrende](../../../Annotationsprogramm/Tabellenkalkulation/lehrende-anleitung-csv.html).
