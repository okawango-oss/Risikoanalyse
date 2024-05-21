# Risikoanalyse 
Software-FMEA, Hardware-FMEA und Prozess-FMEA

## Risikoanalyse elementarer Gefährdungen

Der BSI Grundschutz formuliert  die elementaren Gefährdungen und strukturiert die Elemente nach den Kriterien des BSI-Standard 200-3:

https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Grundschutz/BSI_Standards/standard_200_3.pdf?__blob=publicationFile&v=2 

Zusätzlich sind Gefährdungen des attack.mitre.org Frameworks hilfreich, Gefährdungen in der Risikoanalyse zu ergänzen.:
Beispiele von Taktiken und Mitigations der mitre Matrix:
TA 0001 - initial access 
TA 0008 - lateral movements 
M 1031 - network intrusion prevention
M 1037 - filter network traffic
M 1050 - exploit protection
M 1053 - data backup (immutable)

Die Risikoeinschätzung nach dem BSI Grundschutz ist methodisch eingegrenzt und wird im Kapitel 5.2 des BSI Standard 200-3 beschrieben. Für die dynamischen Schwachstellen wird international der Schweregrad gemäß dem CVSS score in einem Punktesystem von 0-10 definiert. https://nvd.nist.gov/vuln-metrics/cvss

Um die gesamte Gefährdungslage zu beurteilen ist die sogenannte FMEA-Analyse Methode weit verbreitet und wird durch eine Risikoprioritätszahl RPZ (https://de.wikipedia.org/wiki/FMEA) bzw. der Aufgabenpriorität AP (https://vda-qmc.de/wp-content/uploads/2024/03/VDA-QMC-White-Paper-FMEA-24.pdf) dargestellt. Es gibt verschiedene Anwendungskategorien der FMEA: Software-FMEA, Hardware-FMEA, Prozess-FMEA, Design-FMEA (D-FMEA), System-FMEA (S-FMEA).

