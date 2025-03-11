# NewsVideoMiner-docs
Systém pro vizuální protěžbu videonahrávek televizních pořadů 
# 📺 Systém pro zpracování videí z televizních pořadů

Tento projekt slouží k **automatickému zpracování televizních pořadů**. Obsahuje moduly pro **vizuální segmentaci scén, OCR textu a detekci/identifikaci osob**.

## 📥 Instalace (Délka: ~50 slov)
Popis instalace prostředí pomocí Dockeru nebo jiných metod.
- Požadavky na prostředí (Python verze, knihovny)
- Klonování repozitáře
- Stažení ML modulů
- Instalace závislostí (pip)
- Nastavení prostředí (`.env`, konfigurace)

## ⚙️ Konfigurace (Délka: ~100–500 slov)
Jaké **parametry** lze nastavit v každém modulu pro následnou inferenci:
- **Segmentace scén**: nastavení detekční metody, thresholdy?
- **OCR model**: výběr modelu (PaddleOCR, Tesseract), jazyk modelu

📌 **Odkaz na README každého modulu:**
- [`segmentace-scén/README.md`](segmentace-scén/README.md)
- [`ocr/README.md`](ocr/README.md)

## 🖼 GUI pro anotaci segmentů (Délka: ~100–600 slov + screenshoty)
Detailní popis ovládání GUI pro manuální anotaci:
- Jak **načíst video** do GUI
- Jak **označit scénu** jako střih
- Ukládání anotací do JSON

📌 **Odkaz:** [`anotacni-gui/README.md`](anotacni-gui/README.md)

## 👤 GUI Správa databáze osob (Délka: ~200 –500 slov + screenshoty)
Jak přidat nové osoby do databáze:
- Struktura databáze (vysvětlení adresáře)
- Jak přidat nový obličej pomocí GUI

📌 **Odkaz:** [`databaze-osob/README.md`](databaze-osob/README.md)

## 🚀 Showcase: Jak program spustit (Délka: ~200–400 slov + console example)
Příklad spuštění celého pipeline na testovacím videu:
- Příprava vstupního videa
- spuštění systému
- Výstupní JSON soubory a jejich struktura

