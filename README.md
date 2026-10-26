# CloudStream repo — SaPrevodom

Repozitorij za CloudStream s pluginom **SaPrevodom** (filmovi i serije sa prevodom).

## Datoteke
- `repo.json`    – manifest repozitorija (ovaj link upisuješ u CloudStream)
- `plugins.json` – popis dodataka
- `SaPrevodomProvider.cs3` – sam plugin

## Link za CloudStream
```
https://raw.githubusercontent.com/gabac198-cmd/saprevodom-repo/main/repo.json
```

## Kako ubaciti datoteke na GitHub
1. Otvori repozitorij `saprevodom-repo`.
2. Klikni **Add file** → **Upload files**.
3. Povuci `repo.json`, `plugins.json` i `SaPrevodomProvider.cs3`.
4. Klikni **Commit changes**.

## Kako dodati u CloudStream
1. Otvori CloudStream.
2. **Settings** → **Extensions** (Dodaci).
3. **Add repository** (Dodaj repozitorij).
4. Zalijepi link iznad i potvrdi.

## Napomena
Plugin je veličine 41212 bajtova, a SHA-256 hash mora odgovarati vrijednosti
upisanoj u `plugins.json`, inače CloudStream odbije instalaciju.

Ovaj repozitorij koristi **verziju 3**.
