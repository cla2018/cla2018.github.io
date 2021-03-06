# Computerlinguistische Anwendungen
### Anwendung maschineller Lernverfahren in Python
### Sommersemester 2018
### Centrum für Informations- und Sprachverarbeitung, LMU München

[Ergebnisse der Nachklausur](nachklausur_ergebnisse) vom 20.10.2018 (für Studierende, die der Veröffentlichung zugestimmt haben - alle anderen müssen warten, bis die Noten an das Prüfungsamt übermittelt sind).

Klausureinsicht: 29.10.2018, 9:00, Raum C105
 
Sie erreichen den Dozenten und die Tutoren unter:

cla2018 [at] cis [dot] uni [minus] muenchen [dot] de

Anmeldung zur Vorlesung:
 - Studenten mit Computerlinguistik als Hauptfach, und nicht-Informatiker melden sich bitte über das LSF zur Vorlesung an.
 - Studenten mit Informatik als Hauptfach benutzen bitte das Webformular
 
 Für die Übungen benötigen Sie einen GitLab Account des IFI:  [Mehr Informationen](https://www.rz.ifi.lmu.de/infos/gitlab_de.html){:target="_blank"}

Übungen werden in Teams aus 2 oder 3 Teilnehmern gebildet. Sie können ein Team hier anmelden: Webformular

 - Zeit/Vorlesung: Mi 14:00-17-00 (c.t.)
 - Ort/Vorlesung: Hörsaal L 155, Oettingenstr. 67
 - Zeit/Übung: <span style="color:red">**Do 14:00 s.t. - 16:00 s.t. (s.t. = pünktlich)**</span>
 - Ort/Übung: CIP Pool (Sibirien/Gobi)

 - Dozenten: Benjamin Roth
 - Tutoren: Daniel Weber, Felip Guimerà Cuevas, Ziad Elsayes 




| Date | slides | homework | materials |
|-----------------------------|:--------------------------------:|:------:|:-------------------------------------------------------------------|
| - |  |  | [PyCharm Intro (optional, jedoch vorteilhaft zur Übungsbearbeitung)](pycharm.pdf){:target="_blank"} |
| - |  |  | [**Tips (Coding Basics)**](tipps.pdf){:target="_blank"} |
| 11.4. | [Course Overview](01_overview.pdf){:target="_blank"}; [Machine Learning Basics](01_machine_learning.pdf){:target="_blank"}; [Perzeptron](01_perceptron_short.pdf){:target="_blank"} |  | Literatur: Hal Daume [(pdf)](http://www.ciml.info/dl/v0_99/ciml-v0_99-ch04.pdf){:target="_blank"} |
| 12.4. |  | [Homework 1](hw01_perceptron.pdf){:target="_blank"} **Updated Ex.9**| [enron.tgz](http://www.cis.uni-muenchen.de/~beroth/cla/enron.tgz){:target="_blank"} |
| 18.4. | [Naive Bayes; Multiclass Classification](02_naive_bayes.pdf){:target="_blank"} |  | Literatur: Jurafsky&Martin [(pdf)](https://web.stanford.edu/%7Ejurafsky/slp3/6.pdf){:target="_blank"} |
| 19.4. |  | [Homework 2](hw02_naive_bayes.pdf){:target="_blank"} |  |
| 25.4. | [Praraphrases; Numpy; Scikit-Learn](paraphrases_scikit_numpy.pdf){:target="_blank"} |  |  |
| 26.4. |  | [Homework 3](hw03_paraphrases.pdf){:target="_blank"} | [paraphrases.tgz](http://www.cis.uni-muenchen.de/~beroth/cla/paraphrases.tgz){:target="_blank"} |
| 2.5. | [MaxEnt Klassifikator](scikit_classification.pdf){:target="_blank"}; [SVM](thang_vu_svm.pdf){:target="_blank"} |  |  |
| 3.5. |  | [Homework 4](hw04_sklearn_paraphrases.pdf){:target="_blank"} **Updated Ex.3**| |
| 9.5. | [Wort-Repräsentationen 1](wordspace.pdf){:target="_blank"} |  | [Wikipedia word space](http://www.cis.uni-muenchen.de/schuetze/intro/tmp/){:target="_blank"}; [Tensorflow Projector](http://projector.tensorflow.org/){:target="_blank"} |
| 9.5. | Wg. Feiertag: Vorlesung bis 16:30, Übung: 17:00 (s.t.)-18:30 | [Homework 5](cooccurrences.pdf){:target="_blank"} |  |
| 16.5. | [Word-Embeddings durch Matrix-Faktorisierung](embedmatrix.pdf){:target="_blank"}; [Implementierung](word_similarity.pdf){:target="_blank"} |  |  |
| 17.5. |  | [Homework 6](hw06_word_similarity.pdf){:target="_blank"} | [Solution Code Snippet](cooc_func.nopy){:target="_blank"} |
| 23.5. | [Skipgram (Word2Vec)](embedgd.pdf){:target="_blank"}; [Implementierung](word2vec.pdf){:target="_blank"} |  |  |
| 24.5. |  | [Homework 7](hw07_skipgram.pdf){:target="_blank"} |  |
| 30.5. | [Anwendung von Wortvektoren](word_vectors_applications.pdf){:target="_blank"} |  |  |
| 30.5. | Wg. Feiertag: Vorlesung bis 16:30, Übung: 17:00 (s.t.)-18:30 | [Homework 8](hw08_entity_types.pdf){:target="_blank"} | [entities_types.tgz](http://www.cis.uni-muenchen.de/~beroth/cla/entities_types.tgz){:target="_blank"} |
| 6.6. | [RNNs; Keras](neural_networks.pdf){:target="_blank"}; CNNs for images [(.pptx)](cnn.pptx){:target="_blank"} [(.pdf)](cnn.pdf){:target="_blank"}; [CNNs for Text](convolution_pooling.pdf){:target="_blank"} |  |  |
| 7.6. |  | [Homework 9](hw09_neural_networks.pdf){:target="_blank"} |  |
| 13.6. | [Relation Prediction Challenge](hw10_relation_prediction_challenge.pdf){:target="_blank"} ([leaderboard](leaderboard){:target="_blank"})|  | [relations.tgz](relations.tgz){:target="_blank"}  |
| 20.6. | [Deep Learning for NLP](dl4nlp_roth.pdf){:target="_blank"}; Firmenvortrag MunichRe |  |  |
| 27.6. | Kurzvorträge Projekt: <span style="color:red">**1 Folie Pro Team-Mitglied, jedes Mitglied soll z.B. einen Ansatz beschreiben, den Sie versucht haben, und was der Effekt davon war. Senden Sie die Folien (mit Namen) bitte bis 12:00 an cla2018@...**</span>|  | [Probeklausur](probe_klausur.pdf){:target="_blank"} **Aufg. 7 (2) korrigiert (5.7.2018)**|
| 28.6. | Fragestunde mit den Tutoren (CIP-Pool Sibirien/Gobi) |  |  |
| 4.7. | Besprechung der Probeklausur <span style="color:red">**Wichtig: Bitte beabeiten Sie die Probeklausur zuhause, und bringen Sie Ihre Lösungen mit, damit wir diese zusammen besprechen können.**</span> |  |  |
| 5.7. | Fragestunde **Raum: L155** |  |  |
| 11.7. | Klausur |  |  |



Zur Korrektur verwendete Unit-Tests:

[hw01](hw01_perceptron.tar.gz){:target="_blank"},[hw02](hw02_naive_bayes_solution.7z){:target="_blank"},[hw03](hw03_paraphrases.7z){:target="_blank"},[hw04](hw04_sklearn_paraphrases.7z){:target="_blank"},[hw05](hw05_cooccurrence.7z){:target="_blank"},[hw06](hw06_word_similarity.7z){:target="_blank"},[hw07](hw07_skipgram_solution.7z){:target="_blank"},[hw08](hw08_entity_types.7z){:target="_blank"},[hw09](hw09_neural_networks.7z){:target="_blank"}
