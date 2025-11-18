# BRIEF: Landing Page dla 7-dniowego Smoke Testu (UPDATED)

## 🎯 Kontekst
Testujemy usługę automatyzacji procesów dla małych agencji marketingowych (10-25 osób). Landing page ma zbierać zapisy na **bezpłatny 30-minutowy audyt** i weryfikować zainteresowanie rynku.

## 🛠️ Stack Techniczny
- **HTML + Tailwind CSS** (via CDN)
- **Vanilla JavaScript** (prosty, bez frameworków)
- **Deployment:** Netlify lub Vercel (darmowy plan)
- **Formularz:** Tally.so (embed iframe)
- **Domena:** michalpotoczny.com (Michał podłączy później)

## 📋 Struktura Landing Page

### **Header/Navbar**
- **Logo/Brand:** "**Michał Potoczny**" (lewy górny róg)
- **Opcjonalnie podtytuł:** "Automatyzacja dla Agencji" (mniejszym fontem pod imieniem)

### **Sekcja 1: Hero** (Above the fold)
- **Nagłówek:** "Automatyzacja Twojej agencji w 7 dni – bezpłatny audyt"
- **Podnagłówek:** "Przestań tracić czas na ręczne raporty i powtarzalne zadania. Pokażę Ci, jak zaoszczędzić 10+ godzin miesięcznie."
- **CTA Button:** "Umów bezpłatny audyt" (scroll do formularza)
- **Visual:** Opcjonalnie – prosty ilustracja/ikona dashboardu lub automatyzacji

### **Sekcja 2: Problem** (Ból)
**Nagłówek:** "Brzmi znajomo?"
- ✋ Tracisz dni na ręczne tworzenie raportów dla klientów
- 📊 Gubisz się w danych rozproszonych po różnych narzędziach
- 🔄 Każdy nowy klient to chaos w komunikacji i onboardingu
- 😰 Twoi najlepsi ludzie marnują czas na powtarzalne zadania zamiast tworzyć

### **Sekcja 3: Rozwiązanie**
**Nagłówek:** "Jak mogę pomóc?"
Oferuję **bezpłatny 30-minutowy audyt**, w którym:
1. Zmapuję Twoje największe wąskie gardła
2. Pokażę konkretne możliwości automatyzacji
3. Wskażę, ile czasu i pieniędzy możesz zaoszczędzić

**Przykładowe usprawnienia:**
- **Inteligentne raporty z AI:** Nie tylko dane, ale gotowe insights, wykrywanie anomalii i rekomendacje dla każdego klienta
- Dashboard KPI zbierający dane z wszystkich kampanii w czasie rzeczywistym
- Automatyzacja powtarzalnych zadań i standaryzacja procesów

### **Sekcja 4: Dla kogo?**
**Nagłówek:** "To dla Ciebie, jeśli:"
- Prowadzisz agencję marketingową (SEO, Ads, social media)
- Masz 10-25 osób w zespole
- Czujesz, że chaos operacyjny blokuje Wam rozwój
- Chcesz skalować bez zatrudniania kolejnych osób do "gaszenia pożarów"

### **Sekcja 5: Formularz Zapisu**
**Nagłówek:** "Zapisz się na bezpłatny audyt"
**Podnagłówek:** "Tylko 5 miejsc w tym tygodniu"

**Embed Tally Form** (instrukcja integracji poniżej)

### **Sekcja 6: Footer**

**Layout:**
- **Zdjęcie + Tekst** (flexbox: zdjęcie po lewej, tekst po prawej; na mobile: zdjęcie nad tekstem)
- **Zdjęcie:** `Michal Potoczny 1.jpg` (znajduje się w `smoke_test_assets/`)
  - Format: okrągły (circular crop)
  - Rozmiar: ~80-100px
  - Profesjonalne zdjęcie headshot z okularami na neutralnym niebieskim tle

**O mnie:**
*"Cześć! Jestem Michał. Optymalizuję procesy w przemyśle automotive (PLM/Teamcenter) i wiem, jak chaos w systemach zjada czas. Teraz pomagam agencjom automatyzować ich powtarzalne zadania."*

**Email kontaktowy:** [zostaw placeholder - Michał poda]

## 📝 Formularz (Tally)

**Pola do zebrania:**
1. **Imię** (wymagane)
2. **Email** (wymagane)
3. **Nazwa agencji** (wymagane)
4. **Pytanie 1:** "Jaki największy ból odczuwasz w zarządzaniu swoją agencją?" (textarea, wymagane)
5. **Pytanie 2:** "Czy rozważyłbyś inwestycję w automatyczne narzędzia (dashboard, integracje), jeśli zwróciłyby Ci 10+ godzin pracy miesięcznie?" (radio: Tak / Raczej tak / Nie jestem pewien / Raczej nie)

**Po wysłaniu:** Przekierowanie na stronę "Dziękujemy" z komunikatem: "Dziękujemy! Skontaktuję się z Tobą w ciągu 24h z propozycją terminu audytu."

**Instrukcja dla Tally:**
- Stwórz konto na tally.so (darmowe)
- Utwórz formularz z polami powyżej
- Skopiuj kod embed (iframe)
- Wklej do sekcji 5 landing page'a

## 📊 Tracking & Integracje

**POMIŃ NA RAZIE** - Michał doda później Google Analytics 4 i Meta Pixel.

Zostaw tylko komentarze w kodzie gdzie należy wstawić tracking:
```html
<head>
  <!-- TODO: Google Analytics 4 - do dodania później -->

  <!-- TODO: Meta (Facebook) Pixel - do dodania później -->
</head>
```

## 🎨 Design Guidelines
- **Kolory:** Profesjonalne, czyste – np. niebieski (#2563EB) + biały + szary
- **Font:** System fonts (Tailwind default) dla szybkości
- **Mobile-first:** Responsywne na wszystkich urządzeniach
- **Minimalistyczne:** Bez rozpraszaczy, focus na CTA
- **CTA Button:** Wyraźny, kontrastowy, wielokrotnie na stronie (hero + przed formularzem)
- **Personal touch:** Brand "Michał Potoczny" – profesjonalny ale ludzki

## 🚀 Deployment
1. Push kod do GitHub repo
2. Połącz z Netlify (darmowy plan)
3. Domyślnie użyj subdomeny Netlify: `nazwa.netlify.app`
4. Michał później podłączy domenę michalpotoczny.com

## ✅ Deliverables
1. Działający landing page wdrożony na Netlify/Vercel
2. Responsywny design (mobile + desktop)
3. Placeholder dla trackingu (z TODO comments)
4. Integracja z Tally form (Michał utworzy formularz i doda embed)
5. Zdjęcie `Michal Potoczny 1.jpg` zintegrowane w footer (circular crop)
6. Kod źródłowy w GitHub repo
7. Krótka instrukcja jak zmieniać treść i deploy changes

**Uwaga:** Zdjęcie `Michal Potoczny 1.jpg` znajduje się w folderze `smoke_test_assets/` - skopiuj je do projektu landing page'a (np. folder `/assets/` lub `/images/`)

---

**Czas realizacji:** 1-2h

**✅ Gotowe do przekazania asystentowi AI!**
