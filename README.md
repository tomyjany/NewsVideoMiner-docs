# 📺 NewsVideoMiner

Systém pro **automatické zpracování videonahrávek televizních pořadů**.  
Cílem je extrahovat záznamy o televizních střizích, rozpoznaný text, televizní loga a identifikovat osoby.

Projekt kombinuje několik modulů:
- **Segmentace scén** (detekce střihů mezi záběry)
- **OCR** (optické rozpoznávání textu)
- **Detekce a identifikace osob**
- **Detekce televizních log**
- REST API a vizuální rozhraní

---

## 📥 Instalace

Instrukce pro spuštění systému:
- instalace pomocí `docker-compose` nebo lokálně přes `venv`
- stažení předtrénovaných modelů
- konfigurace prostředí a proměnných

📄 [Dokumentace k instalaci](docs/instalace.md)

---

## 🚀 REST API – Showcase

Ukázka, jak spustit zpracování videa přes REST API:
- jak API volat (curl, Python)
- struktura vstupu a výstupních JSON souborů
- přehled parametrů

📄 [Dokumentace k REST API](docs/api.md)

---

## ⚙️ Konfigurace

Všechny komponenty lze přizpůsobit pomocí konfiguračního souboru `config.yml`:
- volba metody segmentace scén (TransNet, SceneDetect, Autoshot…)
- výběr OCR (Tesseract, EasyOCR, PaddleOCR)
- konfigurace cest k modelům a databázi osob

📄 [Dokumentace ke konfiguraci](docs/konfigurace.md)

---

## 👤 Správa databáze osob

GUI aplikace pro:
- přidávání nových osob do databáze
- vyhledávání obličejů přes Bing API
- výběr a uložení embeddingů pro pozdější rozpoznání

📄 [Dokumentace k databázi osob](docs/people_gui.md)

---

## 🖼 Anotační nástroj na střihy

Grafický nástroj pro manuální anotaci střihů:
- procházení po snímcích
- označení začátku a konce střihu
- uložení a načtení anotací ve formátu JSON

📄 [Dokumentace k anotacím](docs/anotace.md)

---
