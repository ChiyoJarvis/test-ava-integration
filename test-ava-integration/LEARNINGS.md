# Hintergrund-Prozesse in PowerShell

1. **Start-Job**: Gut für kurze Aufgaben innerhalb der Session.
2. **Start-Process -WindowStyle Hidden**: Beste Methode, damit kein Fenster aufpoppt.
3. **nssm**: Profi-Lösung für dauerhafte Hintergrund-Dienste.

*Entscheidung:* Für einfache Skripte ist 'Start-Process -WindowStyle Hidden' am stabilsten.