# Vocabulary Booklet

Interactive English vocabulary learning site built with HTML + Web Speech API.

## Structure

```
vocab-booklet/
├── index.html          # Homepage / course directory
├── 3.1/
│   └── U1/
│       ├── week5.html  # Grade 3.1, Unit 1, Week 5
│       └── week6.html  # (coming soon)
└── README.md
```

## Features

- 📇 Flashcards with 3D flip animation + auto-pronunciation
- 🎯 Multiple choice quiz with instant feedback
- 🔗 Word-meaning matching game
- 📖 Grammar notes with collapsible sections
- 🔊 Web Speech API — adjustable speed (0.75x / 1x / 1.25x)

## Deployment

Hosted on GitHub Pages: `https://<username>.github.io/vocab-booklet/`

## Adding a New Week

1. Copy an existing week file (e.g. `week5.html`) as a starting template
2. Update the `cards`, `quizData`, `matchPairs`, and grammar section content
3. Place the file at `3.1/U1/week6.html`
4. Add a new card to `index.html` in the week grid
