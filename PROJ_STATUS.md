# Context de reluare

## Proiect

Schelet Python pentru demonstratii de dezvoltare controlata cu agenti AI. Nu exista inca implementare, teste sau documentatie: `src/`, `tests/` si `docs/` sunt directoare locale goale, deci nu sunt urmarite de Git.

## Conventii si configurare

- Citeste `AGENTS.md` inainte de editari. Nu instala pachete, nu sterge/redenumeste fisiere, nu modifica asteptari de test si nu face `git push` fara acord.
- Foloseste mediul virtual `.venv`; VS Code este configurat sa il activeze in PowerShell.
- Dependinta de dezvoltare este `pytest==9.1.1` in `requirements.txt`.
- Comanda de validare: `.\.venv\Scripts\python.exe -m pytest` (sau `python -m pytest` dupa activarea mediului).
- Task-ul de test din VS Code foloseste inca `unittest`, desi conventia proiectului cere `pytest`; aliniaza-l cand modificarea este aprobata.

## Ultima validare

`pytest 9.1.1` ruleaza cu succes si colecteaza 0 teste, deoarece `tests/` este gol. Poate aparea un avertisment neblocant de permisiune pentru cache-ul `.pytest_cache`; nu a fost suprimat sau investigat.

## Urmatorul pas

Defineste prima functionalitate, implementeaz-o in `src/`, adauga teste `pytest` in `tests/` si completeaza `README.md` cu scopul si instructiunile proiectului.

Inainte de lucru, ruleaza `git status --short --branch`: raportul nu inlocuieste starea curenta a arborelui de lucru.
