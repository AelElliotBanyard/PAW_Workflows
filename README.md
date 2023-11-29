# PAW_Workflows

Geht auf Github und danach auf Actions dort findet ihr eine bleuen text indem steht "set up a workflow yourself" oder "Richten Sie selbst einen Workflow ein" oder etwas in diese richtung. Drücht darauf!
Geht in dieses Repository und  sucht den richtigen Workflow für euer Projekt. Kopiert den Inhalt dieses Dokumentes und fügt es bei euch ein!
Danach speichern.
Danach auf die Einstellungen des Repo und unter "Secrets und variabeln"("Secrets and variables") -> "Actions" -> "Neues repository secret"("New repository secret")
Erstellt drei Secrets:
1. ftp_server
   Der Wert dieses ist der Host
2. ftp_username
   Den Benutzernamen für den ftp zugriff
3. ftp_password
   Das Passwort für den ftp zugriff

Danach lädt GitHub die Dateien auf den Server sobald ein Push getätigt wird.
