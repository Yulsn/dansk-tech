# 🇩🇰 Den danske tech stack

En oversigt over danske tech-systemer som alternativer til store internationale spillere. Få inspiration til din tech stack med danske SaaS-løsninger til betalinger, analytics, monitoring og mere.

🌐 **Live på:** [dansktechstack.dk](https://dansktechstack.dk)

---

## 📖 Om projektet

I en tid hvor der ofte tales om Danmarks afhængighed af udenlandsk software, vil vi fremhæve danske systemer, vi selv har tillid til - med hovedkontor i Danmark eller med danske stiftere eller medstiftere.

Danmark har nemlig en stolt tradition inden for softwareudvikling. Teknologier som Ruby on Rails, TypeScript, C# og PHP har danske rødder, og på dette site har vi samlet en liste over stærke danske alternativer til software, der ellers typisk købes i udlandet.

### Formål

Projektet har til formål at:
- ✅ Sætte fokus på danske tech-produkter til software-virksomheder
- ✅ Give inspiration til danske alternativer i tech stacks
- ✅ Fremme synligheden af dansk tech-innovation
- ✅ Støtte danske iværksættere og software-virksomheder

---

## 👥 Hvem står bag?

Initiativet er startet af en gruppe danske iværksættere, chefer og investorer, der gerne vil bidrage til at fremme dansk tech. Se listen på [dansktechstack.dk/#iværksættere](https://dansktechstack.dk/#iværksættere).

---

## 🤝 Hvordan bidrager du?

Vi er glade for bidrag! 

**Vigtigt:** Som ekstern bidragyder skal du kun tilføje produkter til listen **"Software fra eksterne bidragydere"**, som vises på siden. Dette gøres ved at redigere filen `community-products.json`.

Du skal **ikke** redigere `index.php` eller tilføje billeder - det håndteres internt af projektet.

### Tilføj et produkt til listen

Følg disse trin for at tilføje et dansk tech-produkt:

1. **Fork dette repository** (klik på "Fork" øverst til højre på GitHub)

2. **Clone din fork** til din computer:
   ```bash
   git clone https://github.com/DIT-BRUGERNAVN/dansk-tech.git
   cd dansk-tech
   ```

3. **Opret en ny branch**:
   ```bash
   git checkout -b tilfoej-produkt-navn
   ```

4. **Rediger `community-products.json`**:
   - Åbn filen i din editor
   - Tilføj dit produkt til arrayet (efter de eksisterende produkter)
   - Følg denne struktur:
   ```json
   {
     "name": "DitProdukt.dk",
     "url": "https://ditprodukt.dk",
     "description": "Kort beskrivelse af hvad produktet gør",
     "alternatives": ["Internationalt Produkt 1", "Internationalt Produkt 2", "Internationalt Produkt 3"]
   }
   ```
   - **Vigtigt:** `alternatives` skal være en array (med firkantede parenteser) med op til 3 internationale produkter
   - Sørg for at JSON filen er gyldig (brug en JSON validator hvis du er i tvivl)
   - Husk komma efter hvert produkt (undtagen det sidste)

5. **Commit og push**:
   ```bash
   git add community-products.json
   git commit -m "Tilføj [Produktnavn]"
   git push origin tilfoej-produkt-navn
   ```

6. **Opret en Pull Request** på GitHub:
   - Gå til dit forked repository på GitHub
   - Klik på "Compare & pull request"
   - Udfyld beskrivelsen med information om produktet
   - Submit pull request

**Eksempel på et reelt produkt i JSON filen:**
```json
{
  "name": "Ubivox.dk",
  "url": "https://ubivox.dk/",
  "description": "Send nyhedsbreve nemt og sikkert",
  "alternatives": ["MailChimp", "Campaign Monitor", "Klaviyo"]
}
```

**Vigtigt:** Produkter tilføjet via `community-products.json` vises automatisk i sektionen "Software fra eksterne bidragydere" på siden.

---

## 📋 Retningslinjer for bidrag

### Kriterier for produkter

For at et produkt kan inkluderes, skal det opfylde følgende:

**Danske kriterier** (mindst ét af følgende):
- ✅ Hovedkontor i Danmark
- ✅ Dansk stifter eller medstifter
- ✅ Primært dansk ejerskab

**Tech stack kriterier**:
- ✅ Produktet skal kunne anvendes i en tech-stack for software-virksomheder
- ✅ Produktet skal være relevant for SaaS-firmaer, e-commerce-firmaer eller lignende tech/web-firmaer

### Produktinformation

Når du tilføjer et produkt til `community-products.json`, skal du inkludere:

- **name**: Produktets fulde navn (inkl. domæne, f.eks. "Alunta.com")
- **url**: URL til produktets hjemmeside
- **description**: Kort beskrivelse af hvad produktet gør (1-2 sætninger)
- **alternatives**: Array med op til 3 internationale produkter, som det danske produkt er alternativ til

---

## 📝 Filstruktur for bidragydere

Som bidragyder skal du kun redigere én fil:

- **`community-products.json`** - Tilføj dit produkt her. Produkter i denne fil vises automatisk i sektionen "Software fra eksterne bidragydere" på siden.

---

## 📝 Licens

Dette projekt er open source og tilgængeligt under [MIT License](LICENSE) (eller den licens du vælger).

---

## 📧 Kontakt

Har du spørgsmål eller forslag? Kontakt os på:

- 📧 Email: [kontakt@langsom.com](mailto:kontakt@langsom.com)
- 🌐 Website: [dansktechstack.dk](https://dansktechstack.dk)

---

## 🙏 Tak

Tak til alle der bidrager til at fremme dansk tech! Hver tilføjelse, forbedring eller deling hjælper med at gøre danske tech-systemer mere synlige.

---

**Bygget i København af folkene fra langsom.com + venner fra branchen.** 🇩🇰
