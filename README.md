# CloudStream repo — SaPrevodom

Flat repo s pluginom **SaPrevodom**.

## Datoteke (flat repo)
- `repo.json`    – manifest repozitorija (ovaj link se upisuje u CloudStream)
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
- Verzija: **1**
- Veličina: **37371 bajtova**
- SHA-256 mora odgovarati vrijednosti u `plugins.json`, inače CloudStream odbije instalaciju.
