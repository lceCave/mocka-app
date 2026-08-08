# Screenshots for the public README

Drop PNGs here with these exact names (gallery order):

| File | Screen |
|------|--------|
| `flashcards.png` | Flashcard review |
| `notes.png` | Rich notes |
| `board.png` | Drawing board |
| `library.png` | Library / subjects |
| `performance.png` | Performance (Rendimiento) |
| `study-board.png` | Study board (Tablero) |
| `theme-midnight.png` | Midnight theme preview |
| `theme-quasar.png` | Quasar theme preview |
| `theme-forest.png` | Forest theme preview |
| `theme-synthwave.png` | Synthwave theme preview |

Then in `~/Desktop/mocka-public`:

```bash
cp -R "/Users/carlos/Proyecto Mocka/MockaCombined/public-landing/screenshots/"*.png screenshots/
git add screenshots README.md
git commit -m "Add app screenshots"
git push
```
