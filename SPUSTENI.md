# 🚀 Rychlé spuštění webové stránky

## 📱 Lokální spuštění

### 1. Otevření v prohlížeči
- Dvojklik na `index.html` - otevře se v výchozím prohlížeči
- Nebo přetáhněte `index.html` do prohlížeče

### 2. Přes lokální server (doporučeno)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (pokud máte nainstalované)
npx serve .

# PHP (pokud máte nainstalované)
php -S localhost:8000
```

Poté otevřete: `http://localhost:8000`

## 🌐 Nahrání na GitHub Pages

### Rychlý postup:
1. **Vytvořte repozitář** na GitHub: `titanic-website`
2. **Nahrajte soubory** přes "Upload files"
3. **Aktivujte Pages** v Settings → Pages
4. **Počkejte** na nasazení (5-10 minut)

### Detailní postup v README.md

## 📁 Struktura souborů

```
titanic-website/
├── index.html          # 🏠 Hlavní stránka
├── styles.css          # 🎨 Styly a design
├── script.js           # ⚡ Interaktivita
├── README.md           # 📖 Návod na GitHub
├── SPUSTENI.md         # 🚀 Tento soubor
├── .gitignore          # 🚫 Git ignoruje
└── images/             # 🖼️ Složka pro obrázky
    └── README.md       # 📸 Návod na obrázky
```

## 🔧 Testování

### ✅ Co zkontrolovat:
- [ ] Stránka se načte bez chyb
- [ ] Navigace funguje
- [ ] Responzivita na mobilech
- [ ] Animace běží
- [ ] Formulář funguje
- [ ] Všechny odkazy vedou správně

### 📱 Testování responzivity:
- **F12** → Device Toolbar
- Testujte různé velikosti obrazovek
- **Mobile**: 375px, **Tablet**: 768px, **Desktop**: 1024px+

## 🚨 Řešení problémů

### Problém: Stránka se nenačte
- Zkontrolujte, že všechny soubory jsou ve stejné složce
- Otevřete Developer Tools (F12) a podívejte se na chyby

### Problém: Styly se nenačítají
- Zkontrolujte cestu k `styles.css`
- Ujistěte se, že soubor existuje

### Problém: JavaScript nefunguje
- Zkontrolujte cestu k `script.js`
- Podívejte se na chyby v Console (F12)

## 🎯 Další kroky

1. **Přidejte obrázky** do složky `images/`
2. **Upravte obsah** v `index.html`
3. **Přizpůsobte styly** v `styles.css`
4. **Nahrajte na GitHub** podle README.md

## 📞 Potřebujete pomoc?

- 📖 Přečtěte si `README.md`
- 🔍 Podívejte se na chyby v Developer Tools
- 🌐 Vyhledejte řešení na Stack Overflow

---

**Webová stránka je připravena k použití! 🎉**

*Otevřete `index.html` a začněte objevovat tajemství Titaniku!*
