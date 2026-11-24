# Porziony Gestionale

Gestionale per ristorazione: prenotazioni inserite a mano in un calendario settimanale, ricettario interno, magazzino e calcolo automatico della spesa settimanale.

## Come funziona
1. **Prenotazioni**: calendario settimanale e lista delle cose da fare.
2. **Ricettario**: ricette con ingredienti per un numero di porzioni di base.
3. **Magazzino**: scorte attuali.
4. **Spesa**: scala le ricette sui coperti, sottrae il magazzino e mostra cosa comprare. Ogni giorno con prenotazioni viene portato ad almeno N coperti (default 8).

## Uso
Apri `index.html` nel browser. I dati sono salvati in `localStorage`, quindi restano solo su quel browser.

## Pubblicazione con GitHub Pages
Settings → Pages → Branch `main` → cartella `/ (root)`.

## Prossimi passi
Salvataggio cloud con Supabase, login, più utenti, versione React e TypeScript.
