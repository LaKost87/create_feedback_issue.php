# create_feedback_issue.php
Passe $token, $owner, $repo und den Pfad zu deinen Assets an. führe das skript aus  --  php create_feedback_issue.php  --   __  


  -- 
 -- 
   --

--

 macOS-Feedback-Automatisierung
Dieses Repository enthält ein PHP-Skript, das automatisiert ein GitHub-Issue erstellt, um macOS-Feedback direkt im Repository zu dokumentieren und mit Screenshots sowie Videos zu verknüpfen.


--

  --
    Voraussetzungen
- PHP 7.4 oder neuer
- cURL-Erweiterung für PHP
- Ein GitHub Personal Access Token mit repo-Rechten
- GitHub-Repository, in dem das Issue erstellt werden soll

  --


__
Installationsschritte
- Repository klonen oder lokal anlegen
- PHP-Abhängigkeiten prüfen (cURL-Erweiterung)
- .github/assets/ anlegen und folgende Dateien ablegen:
- Screenshots.zip
- Fehlervideo.mov
__


--
 Konfiguration
Öffne create_feedback_issue.php und passe folgende Variablen an:
$token = 'YOUR_GITHUB_TOKEN';           // Dein GitHub Personal Access Token
$owner = 'dein-benutzername-oder-org'; // GitHub-Account oder Organisation
$repo  = 'dein-repo-name';             // Name des Ziel-Repositories





--

--
$token = 'YOUR_GITHUB_TOKEN';           // Dein GitHub Personal Access Token
$owner = 'dein-benutzername-oder-org'; // GitHub-Account oder Organisation
$repo  = 'dein-repo-name';             // Name des Ziel-Repositories
--


---

Nutzung
- Terminal öffnen
- In das Projektverzeichnis wechseln
- Skript ausführen:
php create_feedback_issue.php
- Prüfen, ob im GitHub-Repo ein neues Issue angelegt wurde

---

--  
Automatisierung
Um regelmäßig neues Feedback einzureichen, kannst du das Skript per Cronjob ausführen:
0 * * * * /usr/bin/php /pfad/zum/repo/create_feedback_issue.php >> /var/log/feedback.log 2>&1



--  
Automatisierung
Um regelmäßig neues Feedback einzureichen, kannst du das Skript per Cronjob ausführen:
0 * * * * /usr/bin/php /pfad/zum/repo/create_feedback_issue.php >> /var/log/feedback.log 2>&1






-- 


--
__
Creating README content
The user wants a suitable README content for their GitHub repository, specifically for a PHP script called create_feedback_issue.php, which posts feedback about macOS Feedback Assistant bugs. They need the README to explain the repository's usage, script, configuration, and prerequisites. Since the request is in German, I'll write the content in German, using proper Markdown format. Hmm, I’ll consider making the README bilingual, as that might be helpful. Let me think about how best to structure it!

__
