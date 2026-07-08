# LearnApp (MomoLearn) — Android

Android-App der Lernplattform **MomoLearn**, entstanden als Studien-Teamprojekt (IU Internationale Hochschule). Nutzer laden Vorlesungsskripte als PDF hoch; eine KI erzeugt daraus multiple-choice-Karteikarten. Als Gamification wird ein digitales „Pet" durch richtige Antworten mit XP gefüttert.

> Dieses Repository enthält die Android-App (bzw. eine Arbeitsversion davon) aus dem Teamprojekt. Backend und Web-Frontend wurden im Team in separaten Repositories entwickelt.

## Funktionen
- Login und Registrierung, geräteübergreifende Nutzerverwaltung
- Home-Screen mit digitalem Pet und Schnellzugriff-Buttons
- Kursübersicht: Kurse anlegen, ansehen und löschen
- Einzelansicht eines Kurses mit den zugehörigen Lern-Sets und einer Kursbeschreibung
- Profil: persönliche Daten ansehen und ändern, Passwort ändern, Account löschen

## Technischer Stack
- Kotlin, Jetpack Compose, Material 3
- MVVM-Architektur, Navigation Compose
- Retrofit (bzw. OkHttp) für die REST-Anbindung
- JWT-basierte Authentifizierung (Bearer-Token)

## Kontext
Cross-Modul-Studienprojekt (Web- und Android-Entwicklung). Das Backend (Spring Boot, MongoDB/GridFS, KI-Anbindung zur Fragen-Generierung) und ein Web-Frontend entstanden parallel im Team.
