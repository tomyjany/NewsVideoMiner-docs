# NewsVideoMiner-docs
Systém pro vizuální protěžbu videonahrávek televizních pořadů 
# 📺 Systém pro zpracování videí z televizních pořadů

Tento projekt slouží k **automatickému zpracování televizních pořadů**. Obsahuje moduly pro **vizuální segmentaci scén, OCR textu a detekci/identifikaci osob**.

## 📥 Instalace (Délka: ~50 slov)
Popis instalace prostředí
- docker-compose instrukce
- lokální instalace 
- Stažení ML modulů
- Instalace závislostí (pip)
- Nastavení prostředí (`.env`, konfigurace)

Tady odkaz na instalace.md

## 🚀 Showcase: Jak použít REST API
Příklad spuštění celého pipeline na testovacím videu:
- Příprava vstupního videa
- spuštění systému
- Výstupní JSON soubory a jejich struktura

tady odkaz na api.md

## ⚙️ Konfigurace (Délka: ~100–500 slov)
Jaké **parametry** lze nastavit v každém modulu pro následnou inferenci:
- **Segmentace scén**: nastavení detekční metody, thresholdy?
- **OCR model**: výběr modelu (PaddleOCR, Tesseract), jazyk modelu
- **Detektor televezních log**: výběr modelu (malý, větší, největší)

tady odkaz na konfigurace.md

## 👤 GUI Správa databáze osob (Délka: ~200 –500 slov + screenshoty)
Jak přidat nové osoby do databáze:
- Jak přidat nový obličej pomocí GUI
- Struktura databáze (vysvětlení adresáře)
tady odkaz na people.md

## 🖼 GUI pro anotaci segmentů (Délka: ~100–600 slov + screenshoty)
Detailní popis ovládání GUI pro manuální anotaci:
- Jak **označit scénu** jako střih
- Ukládání anotací do JSON

tady odkaz na anotace.md





