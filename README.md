# NewsVideoMiner-docs
Systém pro vizuální protěžbu videonahrávek televizních pořadů 
# 📺 Systém pro zpracování videí z televizních pořadů

Tento projekt slouží k **automatickému zpracování televizních pořadů**. Obsahuje moduly pro **vizuální segmentaci scén, OCR textu a detekci/identifikaci osob**.

## 📥 Instalace (Délka: ~100–200 slov)
Popis instalace prostředí pomocí Dockeru nebo jiných metod.
- Požadavky na prostředí (Python verze, knihovny, Docker)
- Klonování repozitáře
- Instalace závislostí
- Nastavení prostředí (`.env`, konfigurace)

## ⚙️ Konfigurace (Délka: ~300–500 slov)
Jaké **parametry** lze nastavit v každém modulu:
- **Segmentace scén**: nastavení detekční metody, thresholdy, FPS analýzy
- **OCR model**: výběr modelu (PaddleOCR, Tesseract), jazyk modelu
- **Detekce obličejů**: nastavení přesnosti modelu, databáze identit

📌 **Odkaz na README každého modulu:**
- [`segmentace-scén/README.md`](segmentace-scén/README.md)
- [`ocr/README.md`](ocr/README.md)
- [`detekce-obličejů/README.md`](detekce-obličejů/README.md)

## 🖼 GUI pro anotaci segmentů (Délka: ~400–600 slov)
Detailní popis ovládání GUI pro manuální anotaci:
- Jak **načíst video** do GUI
- Jak **označit scénu** jako střih
- Ukládání anotací do JSON

📌 **Odkaz:** [`anotacni-gui/README.md`](anotacni-gui/README.md)

## 👤 Správa databáze osob (Délka: ~300–500 slov)
Jak přidat nové osoby do databáze:
- Struktura databáze
- Jak přidat nový obličej (ručně vs. automaticky)
- Jak aktualizovat databázi

📌 **Odkaz:** [`databaze-osob/README.md`](databaze-osob/README.md)

## 🚀 Showcase: Jak program spustit (Délka: ~200–400 slov)
Příklad spuštění celého pipeline na testovacím videu:
- Příprava vstupního videa
- Spuštění segmentace
- Spuštění OCR a detekce obličejů
- Výstupní JSON soubory a jejich struktura

📌 **Ukázkové příkazy pro běh v Dockeru nebo lokálně.**

---

## 🔗 Další reference
- 📜 **Seznam modelů, které projekt používá**
- 📊 **Výsledky testování jednotlivých modelů**
- 📚 **Odkazy na použité knihovny a API**

