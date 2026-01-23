# Git Basics

## Aufgabe 1 – GitHub Repository erstellen

Ich habe auf GitHub ein neues Repository mit dem Namen  
`IN250_HungerbuehlerOliver_Docs` erstellt.

Dabei bin ich wie folgt vorgegangen:
- Auf GitHub eingeloggt
- Neues Repository erstellt
- Repository als Public angelegt
- README.md beim Erstellen hinzufügen lassen
- Diese Datei (`git_basics.md`) zur Dokumentation erstellt

Damit ist das Repository bereit für die nächsten Aufgaben.


## Aufgabe 2 – Repository klonen

Ich habe das zuvor erstellte Repository
mit Git Bash auf meinen Computer geklont.

Dabei bin ich wie folgt vorgegangen:
- Git Bash geöffnet
- In den Zielordner gewechselt
- Repository-URL von GitHub kopiert
- Repository mit `git clone` geklont


## Aufgabe 3 – Commit erstellen

Ich habe mein Markdown-Cheatsheet in das
lokale Repository kopiert und einen Commit erstellt.

Dabei bin ich wie folgt vorgegangen:
- Status mit `git status` geprüft
- Dateien mit `git add` zum Commit hinzugefügt
- Commit mit der Nachricht „Initial commit“ erstellt


## Aufgabe 4 – Gitignore erstellen

Ich habe eine `.gitignore` Datei erstellt,
um bestimmte Dateien vom Repository auszuschliessen.

Dabei habe ich folgende Einträge hinzugefügt:
- *.log
- GeheimeBankInformationen.txt


## Aufgabe 5 – Repository mit git init erstellen

Ich habe einen neuen lokalen Ordner erstellt
und darin ein Git-Repository mit `git init` initialisiert.

Anschliessend habe ich das Repository mit dem
bereits bestehenden GitHub-Repository verbunden
und die Daten mit `git pull` synchronisiert.

Dabei bin ich wie folgt vorgegangen:
- Neuen Ordner erstellt
- Repository mit `git init` initialisiert
- Remote Repository mit `git remote add` hinzugefügt
- Branch von `master` auf `main` umgestellt
- Inhalte mit `git pull origin main` übernommen


## Aufgabe 6 – Warum Git?

### Warum nutzt man Git in der Softwareentwicklung?
Git hilft dabei, Änderungen am Code sauber nachzuverfolgen. Man kann jederzeit sehen,
was geändert wurde und von wem. Ausserdem kann man auf ältere Versionen zurückgehen,
falls etwas kaputtgeht. In Teams ist Git praktisch, weil mehrere Personen gleichzeitig
arbeiten können, ohne sich ständig Dateien hin- und herzuschicken.

### Warum bei einem Feuer zuerst `git commit` und dann `git push`?
`git commit` speichert den aktuellen Stand lokal. Damit geht die Arbeit auf dem Laptop
nicht verloren, auch wenn danach etwas passiert. Mit `git push` wird alles zusätzlich
auf GitHub gesichert. Falls der Computer kaputtgeht oder man ihn liegen lassen muss,
ist der Stand trotzdem online vorhanden. Darum: erst sichern (commit + push), dann raus.


Dokumentation abgeschlossen.
