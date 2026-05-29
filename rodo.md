# Klauzula Informacyjna RODO — Plantdex

**Informacja o przetwarzaniu danych osobowych zgodnie z art. 13 RODO**  
**Wersja 1.0 | Obowiązuje od: 28 maja 2026 r.**

---

## I. Tożsamość i dane kontaktowe Administratora

- **Nazwa:** Babiuchdesign – Babiuch Rafał
- **E-mail:** babiuchdesign@gmail.com
- **Status:** osoba fizyczna (prywatny deweloper)

Administrator nie wyznaczył Inspektora Ochrony Danych (IOD), gdyż nie jest do tego zobligowany na podstawie **art. 37 RODO** — brak przetwarzania danych na dużą skalę ani szczególnych kategorii danych jako działalności głównej. Wszelkie zapytania w sprawach ochrony danych kieruj na adres: babiuchdesign@gmail.com.

---

## II. Cele i podstawy prawne przetwarzania

| Cel przetwarzania | Podstawa prawna |
|---|---|
| Rejestracja i obsługa konta (logowanie SSO) | art. 6 ust. 1 lit. b RODO – niezbędność do wykonania umowy |
| Identyfikacja gatunków roślin przez AI (skanowanie zdjęć) | art. 6 ust. 1 lit. a RODO (zgoda) oraz lit. b (wykonanie umowy) |
| Geolokalizacja – oznaczanie miejsc na mapie | art. 6 ust. 1 lit. a RODO – wyłącznie wyraźna zgoda |
| Powiadomienia lokalne o pielęgnacji roślin | art. 6 ust. 1 lit. a RODO – zgoda na powiadomienia |
| Obsługa płatności i subskrypcji Premium | art. 6 ust. 1 lit. b RODO – wykonanie umowy zakupu |
| Bezpieczeństwo i stabilność techniczna (logi, diagnostyka) | art. 6 ust. 1 lit. f RODO – prawnie uzasadniony interes Administratora |
| Przechowywanie danych po rozwiązaniu umowy w zakresie zakupów | art. 6 ust. 1 lit. f RODO – prawnie uzasadniony interes (obrona przed roszczeniami, art. 118 k.c.) |

---

## III. Kategorie przetwarzanych danych osobowych

- **Dane identyfikacyjne:** adres e-mail, imię (opcjonalnie), unikalny identyfikator konta (UID SSO).
- **Dane lokalizacyjne:** współrzędne GPS (opcjonalnie, za zgodą), dane EXIF zdjęć (opcjonalnie).
- **Zdjęcia roślin:** przesyłane przez Użytkownika do analizy AI.
- **Dane techniczne:** model urządzenia, wersja systemu i Aplikacji, logi błędów.
- **Dane finansowe (pośrednio):** status subskrypcji Premium (aktywna/wygasła/zwrot) — bez danych karty płatniczej.

> **Aplikacja nie przetwarza szczególnych kategorii danych osobowych** w rozumieniu art. 9 RODO (danych dotyczących zdrowia, pochodzenia rasowego, poglądów politycznych, danych biometrycznych itp.).

---

## IV. Odbiorcy danych i podmioty przetwarzające

Na podstawie umów powierzenia przetwarzania danych (DPA) dane przekazywane są następującym podmiotom przetwarzającym:

| Podmiot | Rola | Lokalizacja | Podstawa transferu |
|---|---|---|---|
| **Supabase Inc.** | Infrastruktura chmurowa (baza danych, auth, storage) | West Europe – Londyn, UK | Decyzja o adekwatności KE 2021/1772 |
| **Dostawca usług AI** (Google Cloud Vision / OpenAI) | Analiza gatunkowa zdjęć | USA | SCC (decyzja KE 2021/914) + EU-US DPF (decyzja KE 2023/1795) |
| **Google LLC** | Autoryzacja SSO (Google Sign-In) | USA | EU-US Data Privacy Framework |
| **Apple Inc.** | Autoryzacja SSO (Sign in with Apple) | USA | EU-US Data Privacy Framework |

> Dane osobowe nie są sprzedawane, wynajmowane ani udostępniane innym podmiotom w celach marketingowych.

---

## V. Okresy retencji danych

| Kategoria danych | Okres przechowywania |
|---|---|
| Dane konta, kolekcja roślin, zdjęcia | Przez cały okres aktywności konta. Usunięcie konta = natychmiastowe, nieodwracalne usunięcie z serwerów. |
| Dane techniczne i logi diagnostyczne | 90 dni od daty wygenerowania. |
| Status subskrypcji Premium | Czas aktywności konta; dane dot. zakupów przechowywane przez 5 lat od zakupu (art. 118 k.c. – przedawnienie roszczeń). |

---

## VI. Prawa osoby, której dane dotyczą

Możesz skorzystać z poniższych praw kontaktując się pod adresem **babiuchdesign@gmail.com** lub bezpośrednio przez ustawienia Aplikacji. Administrator odpowie bez zbędnej zwłoki, **nie później niż w ciągu 30 dni** (art. 12 ust. 3 RODO). W przypadku złożonych wniosków termin może zostać przedłużony o kolejne 60 dni, o czym Administrator poinformuje w terminie pierwszych 30 dni.

### Prawo dostępu (art. 15 RODO)
Prawo do uzyskania informacji o przetwarzanych danych oraz otrzymania ich kopii.

### Prawo do sprostowania (art. 16 RODO)
Prawo żądania poprawienia błędnych lub uzupełnienia niekompletnych danych. Dane profilowe możesz edytować bezpośrednio w Aplikacji.

### Prawo do usunięcia — „prawo do bycia zapomnianym" (art. 17 RODO)
Możesz natychmiastowo usunąć konto w **Ustawieniach → Profil → Usuń konto**. Skutek jest natychmiastowy i nieodwracalny.

### Prawo do ograniczenia przetwarzania (art. 18 RODO)
Prawo żądania ograniczenia przetwarzania do czasu rozpatrzenia wniosku (np. gdy kwestionujesz prawidłowość danych).

### Prawo do przenoszenia danych (art. 20 RODO)
Prawo do otrzymania danych w formacie **JSON/CSV** i przesłania ich do innego administratora. Realizowane na wniosek mailowy.

### Prawo do sprzeciwu (art. 21 RODO)
Prawo wniesienia sprzeciwu wobec przetwarzania opartego na prawnie uzasadnionym interesie Administratora (art. 6 ust. 1 lit. f RODO), w tym profilowania.

### Prawo do cofnięcia zgody (art. 7 ust. 3 RODO)

Cofnięcie zgody nie wpływa na zgodność z prawem przetwarzania sprzed jej cofnięcia. Jak cofnąć:

- **Kamera/galeria:** Ustawienia → Aplikacje → Plantdex → Uprawnienia.
- **Lokalizacja GPS:** Ustawienia → Prywatność → Lokalizacja.
- **Powiadomienia:** Ustawienia → Powiadomienia → Plantdex.

---

## VII. Prawo wniesienia skargi do organu nadzorczego

Masz prawo wniesienia skargi do organu nadzorczego właściwego dla miejsca Twojego zamieszkania, miejsca pracy lub miejsca domniemanego naruszenia. W Polsce organem nadzorczym jest:

**Prezes Urzędu Ochrony Danych Osobowych (PUODO)**
- Adres: ul. Stawki 2, 00-193 Warszawa
- Telefon: +48 22 531 03 00
- Strona: [www.uodo.gov.pl](https://www.uodo.gov.pl)
- E-mail: kancelaria@uodo.gov.pl

---

## VIII. Zautomatyzowane podejmowanie decyzji i profilowanie

Identyfikacja rośliny przez silnik AI stanowi zautomatyzowaną analizę przesłanego zdjęcia. Informujemy zgodnie z **art. 22 RODO**, że:

- Wynik identyfikacji ma charakter **wyłącznie pomocniczy i informacyjny** — nie wywołuje skutków prawnych ani podobnie istotnych skutków dla Użytkownika.
- Użytkownik zachowuje pełną kontrolę — może odrzucić lub ręcznie poprawić wynik przed zapisaniem rośliny.
- Aplikacja **nie prowadzi profilowania** Użytkowników w celach marketingowych, scoringu ani żadnych innych form oceny, o których mowa w art. 22 ust. 1 RODO.

---

## IX. Źródło danych

Wszystkie dane osobowe zbierane przez Aplikację pochodzą **bezpośrednio od Użytkownika** — są przekazywane podczas rejestracji, korzystania z funkcji skanera, oznaczania lokalizacji roślin lub w wyniku logowania przez serwisy Google / Apple. Administrator nie pozyskuje danych osobowych z innych zewnętrznych źródeł.

---

## X. Dobrowolność podania danych

| Dane | Dobrowolność |
|---|---|
| Adres e-mail, UID SSO | **Wymagane** — warunek konieczny do założenia konta. |
| Lokalizacja GPS, dane EXIF | **Opcjonalne** — brak zgody nie uniemożliwia korzystania z skanera ani innych funkcji. |
| Zgoda na powiadomienia | **Opcjonalna** — brak zgody oznacza jedynie brak przypomnień o pielęgnacji roślin. |

---

## XI. Zmiany klauzuli informacyjnej

Niniejsza klauzula może być aktualizowana w przypadku zmian w przepisach prawa lub sposobie przetwarzania danych. O istotnych zmianach Użytkownik zostanie poinformowany za pośrednictwem komunikatu w Aplikacji z co najmniej **14-dniowym wyprzedzeniem**.

---

*Plantdex – Babiuchdesign / Babiuch Rafał · babiuchdesign@gmail.com · Ostatnia aktualizacja: 28 maja 2026 r.*
