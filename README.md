# Frontend Testing Setup

Dieses Repository enthält ein grundlegendes Testing-Setup für ein JavaScript-Frontend-Projekt. Es nutzt **Jest** für Unit-Tests, **Cypress** für End-to-End-Tests und **Mocha + Chai** für weitere Testmöglichkeiten.

## 📌 Installation

Um das Projekt lokal einzurichten, folge diesen Schritten:

```sh
# Repository klonen
git clone https://github.com/dein-user/frontend-testing-setup.git
cd frontend-testing-setup

# Abhängigkeiten installieren
npm install
```

## 🧪 Testing-Frameworks
Das Projekt enthält folgende Testing-Frameworks:
- **Jest**: Für Unit-Tests
- **Mocha + Chai**: Alternative für Unit- oder Integrationstests
- **Cypress**: Für End-to-End-Tests

## 🔍 Struktur
```
frontend-testing-setup/
│── sum.js               # Beispiel-Funktion
│── sum.test.js          # Unit-Test mit Jest
│── package.json         # Skript-Konfiguration
│── cypress/
│   └── integration/
│       └── sample.spec.js  # Beispiel E2E-Test mit Cypress
└── README.md            # Diese Datei
```

## 🚀 Tests ausführen

### 🔹 Unit-Tests mit Jest
```sh
npm test
```

### 🔹 End-to-End-Tests mit Cypress
```sh
npm run e2e
```


