# Git Auto-Commit & Push Rule

- **Trigger**: Nach jeder erfolgreichen Modifikation oder Neuerstellung einer Datei im Workspace.
- **Aktion**: Schlage dem Benutzer unmittelbar danach einen Terminal-Befehl über `run_command` vor, der diese Änderungen committet und pusht.
- **Befehls-Format**: `git add <dateipfad> && git commit -m "<Kurze, präzise deutsche Beschreibung der Änderung>" && git push`
- **Ziel**: Der Benutzer kann die Änderungen direkt durch Klicken auf "Zulassen" (Approve) in sein GitHub-Repository hochladen.
