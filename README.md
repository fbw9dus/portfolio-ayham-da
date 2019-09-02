# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (0/5)
```diff
- Das ist kein milto-Link
```
- Link für Telefon, der Telefon-Anwendung öffnet (5/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (2/5)
```diff
- Der Link hat keinen Textinhalt, deshalb hat er keine Größe und kann nicht geklickt werden
```
- Links zu Social Media Profilen
  - Haben Icons der Dienste (10/10)
  - Sollen in einem neuen Tab öffnen (5/5)
  
- Foto, das im Kreis dargestellt wird, mit border-radius (5/5)
- Navigation zu den Abschnitten mit Hash-Links (0/10)
```diff
- Es sind nicht die Kapitel verlinkt
```
- Bilder im Portfolio sollen verlinkt sein (10/10)

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
- Padding in den Links der Hauptnavigation (10/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (4/10)
```diff
- Kein Abstand bei h1
- Kein Abstand zum Fensterrand bei Skills
```
- Korrekte html-Grundstruktur (html, head, body) (7/10)
```diff
- Kein title-Tag im head
- Es darf nur eine h1 geben
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**36**/100)
