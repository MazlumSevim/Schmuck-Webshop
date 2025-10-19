# 💎 Schmuck-Webshop 4.0

Ein moderner, responsiver Prototyp eines Schmuck-Onlineshops, entwickelt von **Team Fian** als **Teamprojekt im Rahmen einer Umschulung zur Fachinformatiker:in Anwendungsentwicklung**.  
Das Projekt entstand zur **Vorbereitung auf die IHK-Abschlussprüfung** und diente als praxisnahes Lernprojekt zur Anwendung und Vertiefung von Webtechnologien, Projektmanagement und Softwareentwicklung.

---

## 🚀 Projektüberblick

Der **Schmuck-Webshop 4.0** ist ein vollständig clientseitiger Web-Prototyp, der typische E-Commerce-Funktionen wie Produktsuche, Warenkorb und Registrierung abbildet.  
Das Projekt wurde gemeinsam als **Teamarbeit während der schulischen Umschulung** umgesetzt, um den kompletten Entwicklungsprozess — von der Anforderungsanalyse bis zur Abnahme — praxisnah zu trainieren.

**Projektzeitraum:** 9. – 20. Oktober 2025  
**Team:** 8 Teilnehmer:innen (Team Fian)  
**Art des Projekts:** Schulisches Lern- und Prüfungsprojekt (Umschulung, IHK Berlin)  
**Auftraggeber:** Fiktiver Kunde (Dozent des Umschulungsträgers)  

---

## 🎯 Ziele (SMART)

Bis zum 20. Oktober 2025 wurde ein funktionsfähiger Prototyp mit folgenden Kernfunktionen umgesetzt:

1. **Produktkatalog:** Schmuckartikel durchsuchen und filtern  
2. **Warenkorb & Dummy-Checkout:** Artikel hinzufügen, summieren und Testbestellung durchführen  
3. **Produktverwaltung:** CRUD-Funktionen für Administrator:innen  
4. **Registrierung:** Benutzer:innen können sich registrieren (Passwörter werden gehasht gespeichert)  
5. **Dokumentation:** Vollständige Projekt-, Benutzer- und Entwicklerdokumentation  

---

## 🧠 Technischer Überblick

| Kategorie | Technologie / Tool |
|------------|--------------------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Layout** | Flexbox, CSS-Grid, responsives Design |
| **Datenhaltung** | LocalStorage, JSON-Dateien |
| **Tools** | Git, ESLint, Prettier, W3C-Validator |
| **Server (optional)** | `http-server` über npm |
| **Prototyping** | Mockups, Use-Case-Diagramme, Gantt-Plan |

---

## 🧩 Architektur & Module

```
/assets
  ├── css/
  ├── data/products.json
  └── img/
app.js
ui.js
products.js
auth.js
admin.html
index.html
```

- **`app.js`** – zentrale Steuerung und Event-Handling  
- **`ui.js`** – Rendering-Logik für Produktlisten und Modals  
- **`products.js`** – Produktdatenmanagement  
- **`auth.js`** – Registrierung, Passwort-Hashing, LocalStorage-Persistenz  

---

## ⚙️ Installation & Start

### 1️⃣ Lokaler Start (empfohlen)
```bash
npm install -g http-server
npx http-server
```
Öffne die angezeigte URL, z. B. [http://127.0.0.1:8080](http://127.0.0.1:8080)

### 2️⃣ Direkt im Browser
Doppelklick auf `index.html`  
> ⚠️ Hinweis: Manche Browser blockieren lokale JSON-Ladevorgänge.

---

## 🖥️ Nutzung

### Besucher:innen
- Schmuck im Katalog durchsuchen, filtern und sortieren  
- Produkte in den Warenkorb legen und Dummy-Checkout durchführen  
- Responsive Darstellung auf Desktop & Smartphone  

### Administrator:innen
- CRUD-Funktionen über `admin.html`  
- Produkte anlegen, bearbeiten und löschen  

### Registrierung
- Formular mit Validierung  
- Passwort-Hashing via Web-Crypto-API (SHA-256)  
- Speicherung im LocalStorage  

---

## ✅ Qualitätssicherung

- **Agiles Vorgehen** (2-tägige Sprints, Daily-Standups, DoD/DoR)  
- **Teamarbeit:** gemeinsame Planung, Pair-Programming, Code-Reviews  
- **Issue-Tracking** mit Kanban-Board (Trello)  
- **Automatische Formatierung** mit ESLint & Prettier  
- **Testfälle (TC01–TC07)** erfolgreich bestanden  
- **Performance:** Startseite < 2 Sekunden bei 50 Produkten  

---

## 📈 Ergebnisse

| Bereich | Ergebnis |
|----------|-----------|
| **Katalog & Suche** | ✅ vollständig |
| **Warenkorb & Checkout** | ✅ vollständig |
| **Produktverwaltung** | 🟡 Basisfunktionen |
| **Registrierung** | ✅ mit Passwort-Hashing |
| **Backend** | ❌ bewusst ausgelassen |
| **Dokumentation** | ✅ vollständig |

---

## 🔮 Nächste Schritte

1. Backend-Integration (Flask / Django / Express + REST-API)  
2. Login-System & Benutzerverwaltung  
3. Zahlungsabwicklung (z. B. Stripe)  
4. Automatisierte Tests (Jest / Cypress)  
5. Rechtliche Inhalte (AGB, Impressum, Datenschutz)  

---

## 🧾 Hinweis & Lizenz

📘 **Hinweis:**  
Dieses Projekt wurde im Rahmen einer **Umschulung als Teamarbeit** zur **Vorbereitung auf die IHK-Abschlussprüfung Fachinformatiker:in Anwendungsentwicklung** durchgeführt.  
Es dient ausschließlich **zu Lern-, Übungs- und Demonstrationszwecken**.

© 2025 Team Fian – alle Rechte vorbehalten.
