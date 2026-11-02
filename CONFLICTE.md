# Com reproduir el conflicte

La línia 1 del `README.md` és diferent a `main` i a `exemple`.

1. `git switch main`
2. Edita la línia 1 del `README.md` (per exemple: `# Zero to GitHub, versió main`) i fes commit.
3. `git merge exemple`
4. Git avisa: `CONFLICT (content): Merge conflict in README.md`.
5. Obre el fitxer, tria quina versió vols (Accept Current / Incoming / Both) i desa.
6. `git add README.md` i `git commit` per tancar la fusió.

Per desfer-ho abans de resoldre: `git merge --abort`.
