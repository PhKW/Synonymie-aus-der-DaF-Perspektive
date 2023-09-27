# Synonymie-aus-der-DaF-Perspektive

Im Artikel **Synonymie aus der DaF-Perspektive: eine korpusbasierte Analyse** stützen wir uns auf folgende Korpora: deTenTen18 aus Sketch Engine, “Gesprochene Sprache” aus dem DWDS , W-öffentlich (alle öffentlichen Korpora des Archivs W) aus dem DeReKo (Deutsches Referenzkorpus)  sowie drei interne Themenkorpora aus dem DeReKo (Personalien, Reiseberichte, Themenkorpus). 
Durch ein zusätzliches Recherche-Tool konnten für jedes Adjektiv Listen mit den lemmatisierten Nomina erstellt werden, die Angaben zur absoluten und relativen Frequenz sowie einen Auszug aus dem jeweiligen Verwendungskontext enthalten. Das Recherche-Tool ist ein Python-Skript, das es ermöglicht, Daten aus verschiedenen Korpora einheitlich zu bearbeiten und Frequenzlisten zu erstellen. 
Die input-Dateien und die fertigen Frequenz-Listen (im xlsx-Format) lassen sich im Repository in entsprechenden Ordnern finden:

- Daten aus den Themenkorpora (DeReKo) im Ordner *out_files_dereko_themenkorpora*
- Daten aus dem Archiv W-öffentlich (DeReKo) im Ordner *out_files_dereko_w*
- Daten aus dem Korpus deTenTen18 im Ordner *out_files_sketch_engine*
- Daten aus dem Korpus “Gesprochene Sprache” (DWDS) im Ordner *out_files_dwds* 

In jeder xlsx-Datei finden sich Daten zum Gebrauch vom entsprechenden Adjektiv in attributiver Funktion auf den Sheets, die mit "end_" starten. Auf dem ersten Sheet sind die aus dem Korpus gewonnenen Daten und auf dem zweiten die Frequenzlisten.
