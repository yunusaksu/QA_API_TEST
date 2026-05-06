📌 API Testdokumentation – Fake Store API

Dieses Projekt enthält eine strukturierte Qualitätssicherungs-Dokumentation für eine REST-API.
Die Tests wurden auf der Fake Store API durchgeführt.

🔗 Base API

👉 https://fakestoreapi.com

Alle Testfälle und Bug Reports basieren auf dieser REST-API.

README.md
🧪 Testfälle (Sheet: „Testfälle“)

Das erste Excel-Sheet enthält alle funktionalen Testfälle der API.

Abgedeckte Bereiche:
📦 Produkte (/products)
🔐 Authentifizierung (/auth/login)
🛒 Warenkörbe (/carts)
👤 Benutzer (/users)
Ziel:

Validierung der API-Funktionalität durch:

Positive Testfälle
Negative Testfälle
Status Code Überprüfung
Datenvalidierung (CRUD Operationen)
🐞 Fehlerberichte (Sheet: „FehlerBerichte“)

Das zweite Excel-Sheet dokumentiert gefundene Fehler während der API-Tests.

Gefundene Probleme:
❌ Negative Preise werden akzeptiert
❌ Ungültige Datentypen (z. B. String statt Number)
❌ Null-Werte werden nicht validiert
❌ Leere Request Bodies werden akzeptiert
Auswirkungen:

Diese Probleme zeigen eine unzureichende serverseitige Validierung der API.

🎯 Projektziel

Dieses Projekt dient der:

🧪 Qualitätssicherung (QA)
🔍 API-Validierung
🐛 Bug Tracking
📊 Dokumentation von Testfällen
🛠️ Verwendete Tools
Microsoft Excel (Testdokumentation)
Postman / API Testing Tools
Manuelle Testausführung
Git & GitHub
👤 Zusammenfassung

Dieses Projekt demonstriert manuelle API-Testmethoden, inklusive strukturierter Testfälle und Fehleranalyse auf Basis einer realen REST-API.

