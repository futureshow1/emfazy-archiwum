# Lech Emfazy Stefański – Indeks źródeł
## Projekt: Film dokumentalny
## Współpraca: dr Zbigniew Łagosz (UJ)
## Ostatnia aktualizacja: 2026-03-27 (wieczór)

---

## 1. Facebook – Fanpage

- **URL:** https://www.facebook.com/profile.php?id=100083371857729
- **Status:** ✅ KOMPLETNE (posty + komentarze)
- **Pliki lokalne:**
  - `Facebook/posty_business_suite.md` – 47 postów z Meta Business Suite (posty 20-47 mają skrócone opisy)
  - `Facebook/posty_fanpage.md` – 47 postów (starsza wersja)
  - `Facebook/komentarze_fanpage.md` – ✅ pełne komentarze ze wszystkich 47 postów (rozwinięte, posortowane "Wszystkie komentarze")
  - `Facebook/images/` – pusty (zdjęcia do pobrania ręcznie)
- **NotebookLM:** TAK (posty_fanpage.md, posty_business_suite.md, komentarze_fanpage.md)
- **TODO:** Pobrać zdjęcia w pełnej rozdzielczości (wymaga Graph API lub ręcznie)

---

## 2. Academia.edu – Artykuły dr. Łagosza (51 prac)

- **Profil:** https://jagiellonian.academia.edu/ZbigniewŁagosz
- **Status:** 🔄 PDFy pobierane przez Chrome (52 linki download z profilu → ~/Downloads)
- **Lista prac:** `Academia/lista_publikacji_lagosz.md`
- **Skrypty:** `Academia/download_all.py`, `Academia/download_v2.py` (wymagają sesji/logowania)

### Artykuły KLUCZOWE (bezpośrednio o Stefańskim):
| # | Tytuł | ID | PDF? | NotebookLM? |
|---|-------|-----|------|-------------|
| 2 | Teatr na Tarczyńskiej – akcja "Zapałki" (2025) | 145551499 | TAK | TAK |
| 6 | Komunistyczny aparat represji – metody (2023) | 98942900 | TAK | TAK |
| 7 | ~~PTP w dokumentach aparatu represji (PR 2022/3)~~ | 91282637 | ❌ NIE ISTNIEJE — brak w spisie treści nr 3/285 | — |
| 8 | ~~Droga lewej ręki Stefańskiego (PR 2021/4)~~ | 82009429 | ❌ NIE ISTNIEJE — brak w spisie treści nr 4/282 | — |
| NEW | Białoszewski, Stefański and the Paranormal (Slavonica 2024) | — | TAK (Bednarczuk, UwB) | do dodania |
| 9 | Ezoterycy na służbie – Stefański i SB (2019) | 51080768 | TAK | TAK |
| 10 | Darker Side – Left-Hand Path | 70898009 | TAK | TAK |
| 26 | Aparat represji vs Robert Walter Memphis | 31730901 | TAK | TAK |
| 27 | Aparat represji vs ezoterycy – zarys | 31613218 | TAK | TAK |

### Uwaga o błędnych ID:
- ID 82009429 → prowadzi do pracy z astronomii (SERMON project), NIE do Łagosza
- ID 29621211 → prowadzi do pracy z medycyny, NIE do Łagosza
- Wymagana weryfikacja z autorem (dr Łagosz)

### PDFy:
- 52 linki do pobrania uruchomione przez Chrome (iframes z profilu)
- PDFy powinny być w ~/Downloads — do przeniesienia do `Academia/PDFs/`
- `Academia/PDFs/` — aktualnie pusty

---

## 3. Artykuły z sieci

| # | Tytuł | Plik | NotebookLM? |
|---|-------|------|-------------|
| 1 | Film dokumentalny – Białczyński.pl | `Artykuly/01_film_dokumentalny_bialczynski.md` | TAK |
| 2 | Podcast Stawiszyńskiego #202 – opis | `Artykuly/02_podcast_magia_psychotronika_lagosz.md` | TAK |
| 3 | Lubimyczytac.pl – autor Stefański | `Artykuly/03_lubimyczytac_autor_stefanski.md` | TAK |
| 4 | FilmPolski – filmografia | `Artykuly/04_filmpolski_filmografia.md` | TAK |
| 5 | Lubimyczytac.pl – "Od magii do psychotroniki" | `Artykuly/05_lubimyczytac_od_magii_do_psychotroniki.md` | TAK |
| 6 | Wikipedia PL – biogram Stefańskiego | `Artykuly/06_wikipedia_pl_stefanski.md` | TAK (nowe) |
| 7 | Culture.pl – biogram | `Artykuly/07_culture_pl_stefanski.md` | TAK (nowe) |
| 8 | Bandcamp – Alicja "Supernauczanie" | `Artykuly/08_bandcamp_alicja_supernauczanie.md` | TAK (nowe) |
| 9 | Scribd – "Od magii do psychotroniki" (info) | `Artykuly/09_scribd_od_magii_do_psychotroniki.md` | TAK (nowe) |
| 10 | Zrzutka.pl – zbiórka na film dokumentalny | `Artykuly/10_zrzutka_pl_zbiorka.md` | TAK (nowe) |

---

## 4. YouTube

- **Plik:** `YouTube/wyniki_youtube.md` — 29 unikalnych filmów (4 zapytania)
- **Transkrypcje (auto-generated PL):**
  - `YouTube/transkrypcja_podcast_202.md` — ✅ Podcast #202: Magia, psychotronika i służby specjalne (45k znaków)
  - `YouTube/transkrypcja_podcast_076.md` — ✅ Podcast #76: Masoni, jasnowidze, magowie i SB w PRL (52k znaków)
  - `YouTube/transkrypcja_podcast_077.md` — ✅ Podcast #77: Magia, psychotronika, okultyzm w PRL cz. 2 (44k znaków)
- **Pliki VTT (surowe napisy):**
  - `YouTube/podcast_202.pl.vtt`
  - `YouTube/podcast_076.pl.vtt`
  - `YouTube/podcast_077.pl.vtt`
- **NotebookLM:** TAK (wyniki_youtube.md, 3 transkrypcje, 2 filmy YT jako linki)

---

## 5. NotebookLM

### Istniejący notebook (z wcześniejszych prac):
- **ID:** `45416ba6-ff75-4abf-ab1a-c7dcbb2624d3`
- **Tytuł:** "Lech Emfazy Stefanski"
- **Źródła:** 16 (PDFy, 2× YouTube, 1× Markdown)

### Nowy notebook (zbieranie materiałów):
- **ID:** `a920123b-a2b0-44d5-a025-a2b2c1094dd1`
- **Tytuł:** "Lech Emfazy Stefański – Materiały (zbieranie)"
- **Źródła dodane:** ~30
  - Wikipedia PL (Stefański)
  - 9 artykułów z Artykuly/
  - Wyniki YouTube + 2 filmy jako linki
  - 3 transkrypcje podcastów
  - Posty z FB fanpage (2 pliki)
  - Komentarze z FB fanpage
  - 8 artykułów Łagosza z academia.edu (URL)
- **Źródła z błędami:** 2 (zły ID academia, 1 error)

---

## 6. Google Drive / Google Docs

- **Status:** ✅ Pobrane (15 dokumentów + 3 duże do pobrania)
- **Folder lokalny:** `GoogleDrive/`
- **NotebookLM:** TAK (wszystkie 15 dodane)

| # | Tytuł | Plik | Rozmiar |
|---|-------|------|---------|
| 01 | LES spis twórczości teatralnej | `01_LES_spis_tworczosci_teatralnej.md` | 27k |
| 02 | EMFAZY - SHOOTING SCRIPT 2024 | `02_EMFAZY_shooting_script_2024.md` | 22k |
| 03 | EMFAZY - Struktura NON-LINEAR 90min | `03_EMFAZY_struktura_nonlinear_90min.md` | 48k |
| 04 | EMFAZY TRAILER + notki | `04_EMFAZY_trailer_notki.md` | 2.5k |
| 05 | HOOK-CONFLICT struktura dramaturgiczna | `05_HOOK_CONFLICT_struktura.md` | 16k |
| 06 | Emfazy - opis filmu (JLP) | `06_Emfazy_opis_filmu_JLP.md` | 5k |
| 07 | LES w Polskim Radio - notatki JAN | `07_LES_w_Polskim_Radio_JAN.md` | 15k |
| 08 | LES scenario notes (linki + notatki) | `08_les_scenario_notes.md` | 6k |
| 10 | LES lista do treatmentu (chronologia) | `10_LES_lista_do_treatmentu.md` | 2k |
| 11 | LES DOK v.1 treatment | `11_LES_DOK_v1_treatment.md` | 15k |
| 12 | TREATMENT1 (rozbudowany) | `12_TREATMENT1.md` | 47k |
| 13 | LES PRZEKRÓJ (artykuł/wywiad) | `13_LES_PRZEKROJ.md` | 22k |
| 14 | LES scenariusz filmu dok (wczesny) | `14_LES_scenariusz_filmu_dok.md` | 4k |
| 15 | SCRIPTMENT - EMFAZY (JLP) | `15_SCRIPTMENT_EMFAZY_JLP.md` | 50k |
| 16 | EMFAZY (JLP) scriptment v2 | `16_EMFAZY_JLP_scriptment_v2.md` | 55k |

### Duże pliki na Drive (do pobrania ręcznie):
- **TREATMENT_v.3 visuals - EMFAZY (JLP)** (~14 MB, za duży na API)
- **LES-claude1** (~219 KB, za duży na API)
- **Psychotronics pismo pol.** (~204 KB, za duży na API)

---

## 7. Do zrobienia (TODO)

### Pilne:
- [ ] Sprawdzić ~/Downloads — przenieść pobrane PDFy z academia.edu do `Academia/PDFs/`
- [ ] Zweryfikować poprawność pobranych PDFów (czy to faktycznie PDFy, nie HTML)
- [ ] Poprawić błędne ID academia.edu (82009429, 29621211) — skontaktować z dr. Łagoszem
- [ ] Dodać pobrane PDFy do NotebookLM

### Facebook:
- [ ] Pobrać zdjęcia w pełnej rozdzielczości (wymaga Graph API lub ręcznie)
- [ ] Uzupełnić pełne teksty postów 20-47 w posty_business_suite.md

### Inne:
- [ ] Pobrać materiały z Google Drive użytkownika
- [ ] Pobrać materiały z Dokumentów Google użytkownika
- [ ] IPN – dokumenty archiwalne (jeśli dostępne online)
- [ ] Dodać pozostałe PDFy do NotebookLM (po weryfikacji)
