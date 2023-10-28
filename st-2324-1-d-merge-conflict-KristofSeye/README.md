# Cursusvoorbeeld branches: merge conflict

Deze repository bevat drie HTML bestanden:

- `index.html`
- `contact.html`
- `info.html`

In de startsituatie is er 1 enkele branch `main`.

### Doorloop deze stappen

1. Maak een branch `dev` en check deze meteen uit (met een enkel commando).
2. Maak vanaf `dev` twee nieuwe branches: `update-index` en `update-info`.
3. Controleer met het gepaste commando of alle branches correct zijn aangemaakt.
4. Ga naar de branch `update-info` en maak een kleine aanpassing aan de inhoud van `info.html` (wat je precies verandert is niet belangrijk).
5. Stage en commit de wijziging (op de actieve branch `update-info`).
6. Wissel naar de branch `update-index`.
7. Doe een wijziging aan de inhoud van `index.html`.
8. Stage en commit de wijziging (op de actieve branch `update-index`).
9. Doe ook nog een wijziging aan de inhoud van `info.html`. Wijzig dezelfde lijn(en) die je eerder wijzigde op de branch `update-info`, maar maak deze keer op die lijn(en) een **andere** wijziging.
10. Stage en commit de wijziging aan `info.html` (op de actieve branch `update-index`).
11. Keer terug naar de `dev` branch.
12. Merge de branch `update-info` in `dev`.
13. Merge ook de branch `update-index` in `dev`.
14. Los het merge conflict op (bv. in Visual Studio Code).
15. Stage het bestand `info.html` om aan te geven dat je het conflict opgelost hebt.
16. Commit de wijzigingen om de merge af te ronden.
