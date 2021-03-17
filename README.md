[![DOI](https://zenodo.org/badge/216908574.svg)](https://zenodo.org/badge/latestdoi/216908574)

# Einführung in Datenauswertung mit Jupyter Notebooks

Dieser Workshop hat während der Open Access Week 2019 stattgefunden.

## Übersicht über Jupyter Notebooks

1. [01 Boston Wohnungsgrundstueck-Preise.ipynb](01%20Boston%20Wohnungsgrundstueck-Preise.ipynb)
1. [02 Verkehrsfluss.ipynb](./02%20Verkehrsfluss.ipynb)
1. [03 Repraesentation von Farbbildern.ipynb](./03%20Repraesentation%20von%20Farbbildern.ipynb)
1. [04 Erkennung von Ziffern.ipynb](./04%20Erkennung%20von%20Ziffern.ipynb)
1. [05 Klassifiziere Verkehrsschilder.ipynb](./05%20Klassifiziere%20Verkehrsschilder.ipynb)

## Konzept des Repositories

Die Jupyter Notebooks sind im Zusammenhang mit der [Open Access Week 2019 an der TUHH](https://www.tub.tuhh.de/blog/2019/10/14/oaweek2019-an-der-tuhh-programm/) zusammengestellt worden.
Im Workshop wird erklärt, wie Datenauswertung, d. h. deskriptive Statistiken, Visualisierungen u. ä., mit Jupyter Notebooks erstellt werden können.
Damit lässt sich ein Datensatz besser begreiflich machen.
Die dahinterliegenden Konzepte aus der deskriptiven Statistik und des Maschinellen Lernens können in diesem Umfang von einem Nachmittag nicht abgedeckt werden.
Für den Einstieg ins Maschinelle Lernen ist 
["Praxiseinstieg Machine Learning mit Scikit-Learn und TensorFlow : Konzepte, Tools und Techniken für intelligente Systeme" von Géron Aurelien](https://katalog.tub.tuhh.de/Record/898831717)
ein sehr empfehlenswertes Buch.

## Jupyter Notebooks ausführen

Man kann sich die Jupyter Notebooks auf verschiedenen Wegen anschauen:

#### Online 

Über mybinder wird die aktuelle Version der Jupyter Notebooks im Internet geladen.
Der Dienst lädt die Jupyter Notebooks nur temporär, sie werden nach einer Weile wieder gelöscht.
mybinder installiert bereits alle Bibliotheken automatisch.
[Starte mybinder.](https://mybinder.org/v2/git/https%3A%2F%2Fcollaborating.tuhh.de%2Fcmk3624%2Feinfuehrung-in-datenauswertung.git/master)

#### Lokal

Die Dateien liegen auf dem eigenen Rechner, alle Änderungen werden auf der Festplatte (standardmäßig Heimlaufwerk) gespeichert.

- Man kann sich die aktuelle Version als 
[ZIP-Archiv](https://collaborating.tuhh.de/cmk3624/einfuehrung-in-datenauswertung/-/archive/master/einfuehrung-in-datenauswertung-master.zip)
herunterladen und dieses entpacken.

- Mit [git](https://git-scm.com/) kann man das Repository clonen, die URL lautet hierfür `https://collaborating.tuhh.de/cmk3624/einfuehrung-in-datenauswertung.git`
Somit kann man sich später leicht Updates herunterladen oder Änderungen vorschlagen.

Um die Jupyter Notebooks lokal auszuführen, wird [Anaconda](https://www.anaconda.com/distribution/) empfohlen.
Um alle benötigten Bibliotheken lokal zu installieren, kann man die [environment.yml](./environment.yml)-Datei verwenden.
Dieser Schritt wird 
[hier](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)
erklärt.
Danach sollten alle Jupyter Notebooks ausführbar sein.
Für das Laden der Verkehrsdaten und der Straßenschilder muss der Download von externen Webseiten gesondert angestoßen werden.

## Lizenzrechtliches

Dieses Repository unterliegt zwei Lizenzen, zum einen der MIT-Lizenz (siehe [LICENSE](./LICENSE)) und zum anderen der Creative Commons Lizenz (siehe die jeweiligen Jupyter Notebooks).
