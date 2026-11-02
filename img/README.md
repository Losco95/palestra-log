# Immagini esercizi

Copia locale delle immagini del database aperto **free-exercise-db**:
https://github.com/yuhonas/free-exercise-db (licenza Unlicense, pubblico dominio; vedi `LICENSE-free-exercise-db.md`).

Ogni cartella `img/<ExerciseId>/` contiene `0.jpg` (posizione iniziale) e `1.jpg` (posizione finale). `<ExerciseId>` è l'`id` dell'esercizio nel database ed è salvato nella colonna M (`ExerciseId`) di `Piano_Dati`.

## Aggiungere un esercizio
1. Cercare l'`id` in https://raw.githubusercontent.com/yuhonas/free-exercise-db/main/dist/exercises.json (o nel sito https://yuhonas.github.io/free-exercise-db).
2. Copiare `exercises/<id>/0.jpg` e `1.jpg` da quella repo in `img/<id>/`.
3. Scrivere l'`id` nella colonna M di `Piano_Dati`.

Altri campi utili dello stesso database (non copiati qui): `primaryMuscles`, `secondaryMuscles`, `equipment`, `level`, `instructions`.
