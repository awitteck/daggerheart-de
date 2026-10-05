## Daggerheart - Deutsch
Modul zur Übersetzung von Daggerheart für Foundry VTT.

Anleitung
- installiere das Daggerheart-System von Foundryborne
- installiere die deutsche Übersetzung des Foundry-Core [core-translation-de-foundryVTT](https://foundryvtt.com/packages/core-translation-de-foundryVTT)
- installiere dieses Modul
- aktiviere die Module im Kontrollbereich
- stelle die Sprache im Kontrollbereich auf Deutsch um

## Installation und Updates

Füge in Foundry unter **Module installieren → Manifest-URL** diese Adresse ein:

```text
https://github.com/awitteck/daggerheart-de/releases/latest/download/module.json
```

Foundry lädt darüber die aktuelle Version herunter und kann spätere Updates über
dieselbe Manifest-URL finden. GitHub-Adressen mit `blob/` sind HTML-Seiten und
keine installierbaren JSON-Manifeste.

## Neue Version veröffentlichen

Erhöhe `version` in `module.json` und passe `download` an die neue Versionsnummer
an. Die Manifest-URL bleibt unverändert. Erstelle einen GitHub-Release mit dem
Tag `v<VERSION>` und hänge `module.json` sowie `daggerheart-de-<VERSION>.zip` an.
Das ZIP muss die Moduldateien direkt auf oberster Ebene enthalten, ohne `.git`.
Markiere den Release als neuesten Release, damit Foundry ihn für Updates findet.

## Inhalt, Credits und Lizenz:

- Diese Übersetzung wird mit dem von Foundryborne entwickelten Daggerheart-System verwendet (https://foundryvtt.com/packages/daggerheart)
- Diese Übersetzung und die Makros basieren auf der französischen Version von sasmira (https://foundryvtt.com/packages/daggerheart-fr-foundryborne)

Für Probleme und Meldungen erreichst du mich auf Discord: arcadio21
