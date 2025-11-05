# SEO Dokončení

## ✅ Co je hotové:
- sitemap.xml vytvořen
- robots.txt vytvořen
- Meta tagy optimalizovány (title, description)
- Meta keywords odstraněn (deprecated)
- JSON-LD upgraded na LocalBusiness
- Breadcrumbs schema přidáno
- Vnitřní linky s keyword anchor text
- og-image.svg vytvořen

## 🔧 Co je třeba dokončit:

### 1. Převést og-image.svg na og-image.png

**Použijte online nástroj:**
- https://cloudconvert.com/svg-to-png
- Nebo https://convertio.co/cs/svg-png/

**Nastavení:**
- Width: 1200px
- Height: 630px
- Quality: High

**Postup:**
1. Nahrajte `og-image.svg`
2. Konvertujte na PNG (1200x630)
3. Uložte jako `og-image.png` do root složky

**Alternativa (Inkscape):**
```bash
inkscape og-image.svg --export-type=png --export-width=1200 --export-height=630 --export-filename=og-image.png
```

---

### 2. Registrace na Firmy.cz (✅ Hotovo)
- URL aktualizovat v JSON-LD na správnou: https://firmy.cz/detail/[vaše-ID]

---

### 3. Google Search Console
1. Přidejte web: https://search.google.com/search-console
2. Ověřte vlastnictví (meta tag nebo DNS)
3. Odešlete sitemap: https://msplus.cz/sitemap.xml

---

### 4. Seznam.cz Webmaster Tools
1. Registrujte se: https://search.seznam.cz/
2. Přidejte web msplus.cz
3. Ověřte vlastnictví
4. Odešlete sitemap

---

### 5. Firmy.cz profil
- Vyplňte kompletní informace
- Přidejte fotky (logo, kancelář)
- Získejte první recenze od klientů

---

## 📊 SEO Kontrola

**Google PageSpeed Insights:**
https://pagespeed.web.dev/

**Seznam.cz SEO Check:**
https://napoveda.seznam.cz/cz/fulltext-hledani-v-internetu/pro-webmastery/

**Schema Markup Validator:**
https://validator.schema.org/

**Testujte mobile-friendly:**
https://search.google.com/test/mobile-friendly
