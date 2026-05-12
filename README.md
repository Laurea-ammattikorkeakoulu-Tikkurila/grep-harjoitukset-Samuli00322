[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23895252)
# LinuxCLI-python-grep

Projekti harjoituksia Linux-komentoriviltä käyttäen `grep`.

Uusi hakemistorakenne:

- `src/` - lähdekoodi ja paketti
- `data/` - lähdeaineistot
- `data/tasks/` - tehtävä- ja esimerkkikomennot
- `configs/` - tallennettu tila (esim. `tila.json`)
- `output/` - generoituja tuloksia (esim. `results.json`)
- `tools/` - kehitystyökalut
- `harjoitus.py` - CLI/harjoitusskripti (sijoitettu juureen säilytettäväksi)

## Autograding-repon yhteenvetotaulukko

Aja tämä skripti **autograding-repositoryn juuressa** (siellä missä JSON-tulokset ovat).
Skripti odottaa tiedostonimen muodossa `opiskelija-YYYY-MM-DDTHH-MM-SS.json` ja ottaa
kustakin opiskelijasta uusimman tuloksen mukaan.

```bash
python3 tools/summarize_autograding_results.py --results-dir . --output SUMMARY.md
```

Skripti lukee kentät `score` ja `total` ja tuottaa Markdown-taulukon, jossa näkyy opiskelija,
pistekertymä ja viimeisimmän tuloksen aikaleima.
