# AI Email Triage System

## **Opis projektu**

System wykorzystujący sztuczną inteligencję do analizy wiadomości email, generowania odpowiedzi oraz podejmowania decyzji, czy odpowiedź wymaga weryfikacji człowieka.

Projekt wykorzystuje bazę wiedzy przechowywaną w Google Docs oraz model OpenAI do przygotowania odpowiedzi zgodnych z dostępną dokumentacją.

---

## **Problem biznesowy**

Wiele wiadomości klientów dotyczy prostych i powtarzalnych pytań, jednak część z nich wymaga indywidualnej oceny pracownika.

Projekt automatyzuje analizę wiadomości oraz rozdziela zgłoszenia na:

* możliwe do automatycznej obsługi,
* wymagające weryfikacji człowieka.

---

## **Technologie**

* Make
* OpenAI API
* Gmail
* Google Docs
* JSON

---

## **Architektura rozwiązania**

Klient → Gmail → Google Docs (baza wiedzy) → OpenAI API → JSON (decyzja) → Router

### Ścieżka 1 – Automatyczna odpowiedź

Router → Gmail → Klient

### Ścieżka 2 – Weryfikacja przez człowieka

Router → Gmail (pracownik) → Weryfikacja → Gmail → Klient

---

## **Funkcje**

* analiza treści wiadomości email,
* wykorzystanie bazy wiedzy zapisanej w Google Docs,
* generowanie odpowiedzi przez AI,
* ocena pewności odpowiedzi,
* automatyczne podejmowanie decyzji o eskalacji,
* obsługa modelu Human-in-the-Loop,
* automatyczne wysyłanie odpowiedzi dla prostych spraw.

---

## **Przykładowe screenshoty**

### Workflow w Make

*(Dodaj screenshot scenariusza Make)*

### Baza wiedzy

*(Dodaj screenshot fragmentu Google Docs)*

### Decyzja AI w formacie JSON

*(Dodaj screenshot przykładowego wyniku JSON)*

### Automatyczna odpowiedź

*(Dodaj screenshot wiadomości wysłanej automatycznie)*

### Odpowiedź wymagająca weryfikacji

*(Dodaj screenshot wiadomości przekazanej do pracownika)*

---

## **Czego nauczyłem się podczas realizacji projektu**

* integracji Gmail z Make,
* wykorzystania OpenAI API w procesach biznesowych,
* projektowania workflow Human-in-the-Loop,
* pracy z formatem JSON,
* budowy systemów wspierających obsługę klienta,
* podejmowania decyzji przez AI na podstawie zdefiniowanych kryteriów.

