## Praxisübungen des codecentric.AI Bootcamps

In diesem Repository findest Du die Praxisübungen des [codecentric.AI Bootcamps](https://bootcamp.codecentric.ai).

Um den Code der Praxisübungen auf deinem Rechner ausführen zu können, musst du zuerst eine Entwicklungsumgebung (JupyterLab) einrichten. Hierfür durchlaufe einfach Schritt für Schritt die Anleitung hier unten.

Falls du Hilfe benötigen solltest, chatte einfach mit uns in unserer [Slack Community](https://join.slack.com/t/cc-ai-bootcamp/shared_invite/enQtNTQyMTk0MzM2OTMxLTNkODg2YzIwYjdhZGI4YmU3YWNhMDc4NmIwZmFmMmJiN2JiODM1M2EyYTQxZGNhZjQwOGIwMTRlMDlhYzg1YTI). Wir freuen uns auch über Feedback zu deinen Erfahrungen.

Voraussetzungen:

- **Git** [installieren](https://git-scm.com/book/de/v1/Los-geht%E2%80%99s-Git-installieren)

- **Docker** [installieren](https://docs.docker.com/install/)

### Entwicklungsumgebung einrichten (lokal)

```bash
# Klone den Code mit Übungsaufgaben auf deinen Rechner
git clone https://github.com/codecentric/codecentric.AI-bootcamp

# Wechsele in den Ordner des Repositories
cd codecentric.AI-bootcamp

# Lade nun das Docker-Image herunter
docker pull codecentric/codecentric.ai-docker
```

Die Entwicklungsumgebung ist jetzt eingerichtet. Du kannst sie nun jederzeit wie folgt starten und aufrufen:

### Entwicklungsumgebung starten

Der folgende Befehl muss aus dem Ordner *codecentric.AI-bootcamp* heraus gestartet werden.

  - Unter Mac / Linux:

```bash
# Starte Entwicklungsumgebung
sh run.sh
```
  - Unter Windows:

```bash
# Starte Entwicklungsumgebung 
run
```

Los geht's! Rufe [http://localhost:8888/](http://localhost:8888/) in deinem Browser auf.

---

#### Problembehebung
* *Ich sehe keine Übungsaufgaben, wenn ich die Entwicklungsumgebung starte*

   Vermutlich wurde nicht der richtige Pfad der Übungsaufgaben zum Container hinzugefügt. Achte darauf, dass du dich im    Terminal (bzw. in der Shell) zuerst zum Ordner des Bootcamps wechselst, bevor du die Befehle ausführst.

---

### Entwicklungsumgebung einrichten (Cloud)

Für manche Übungsaufgaben empfiehlt es sich, geeignete Grafikkarte zu verwenden, um ein Training in überschaubarer Zeit abzuschließen. Falls die Grafikkarte deines Rechners dafür nicht ausreicht, kannst du die Übungsaufgaben in der Cloud ausführen. Wir verwenden hierfür Amazon Web Services (AWS). Im Kurs zeigen wir Dir, wie du einen AWS EC2 Instanz einrichten kannst, um dort unser Docker-Image einrichten zu können.
