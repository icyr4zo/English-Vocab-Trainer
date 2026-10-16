# 📚 English Vocab

**A simple and interactive English vocabulary learning web app.**

English Vocab helps you build your vocabulary through flashcards, quizzes, and personalized word lists. Track your learning progress, organize vocabulary by topic, and keep expanding your collection whenever you want.

---

## ✨ Features

- 🃏 **Flashcards** — Learn English words with phonetics, Vietnamese meanings, and example sentences.
- 🧠 **Vocabulary Quiz** — Test your knowledge and reinforce what you have learned.
- 📊 **Learning Statistics** — Keep track of your vocabulary and quiz progress.
- 📝 **Vocabulary Management** — Add, edit, and delete words to create your own collection.
- 🔍 **Search & Filter** — Find words quickly and organize them by topic.
- 📥 **Import Vocabulary** — Import multiple words from a JSON file.
- 📤 **Export Vocabulary** — Export your vocabulary as a JSON file for backup or transfer.
- 🌙 **Dark Mode** — Enjoy a comfortable learning experience with a dark interface.
- 💾 **Local Storage** — Save your vocabulary and progress in your browser without requiring an account.
- 📱 **Responsive Design** — Use the app on desktop and mobile devices.

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript
- Browser Local Storage

## 🚀 Getting Started

### Run Locally

No installation or additional dependencies are required.

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in your web browser.
4. Start learning!

```bash
git clone https://github.com/icyr4zo/English-Vocab-Trainer
```

## 📖 Managing Vocabulary

### Add a Word

1. Open the vocabulary management section.
2. Click **Add Word**.
3. Enter the English word, Vietnamese meaning, and any optional information.
4. Save the word to your collection.

### Import Multiple Words

You can expand your vocabulary without being limited to the default word list.

1. Prepare a `.json` file containing your vocabulary.
2. Open the vocabulary management section.
3. Select **Import JSON** and choose your file.
4. The app will import the words into your collection.

Example JSON format:

```json
[
  {
    "english": "achieve",
    "vietnamese": "đạt được",
    "phonetic": "/əˈtʃiːv/",
    "topic": "General",
    "example": "She worked hard to achieve her goals.",
    "exampleVi": "Cô ấy đã làm việc chăm chỉ để đạt được mục tiêu."
  }
]
```

The `english` and `vietnamese` fields are required. Other fields are optional.

**Note:** Importing a word with an existing matching ID replaces that entry. Export your vocabulary before making major changes if you want to keep a backup.

### Export Vocabulary

Use the export feature to save your current vocabulary as a JSON file. You can keep it as a backup or import it into another browser.

## 💾 Data & Privacy

- Vocabulary and learning progress are stored locally in your browser.
- No account is required to use the app.
- Data is not automatically synchronized between different browsers or devices.
- Export your vocabulary regularly if you want to keep a backup or move your data.

Clearing your browser's local storage may permanently remove locally saved data.

## 🗺️ Roadmap

Potential improvements for future versions:

- [ ] Spaced repetition for better long-term retention.
- [ ] More quiz modes and learning options.
- [ ] Vocabulary learning goals and daily reminders.
- [ ] Cloud synchronization across devices.

## 🤝 Contributing

Suggestions, bug reports, and contributions are welcome. Feel free to open an issue or submit a pull request.

## 📄 License

No license has been specified yet. Add a `LICENSE` file if you want to define how others may use, modify, and distribute this project.

---

**Made with ❤️ for English learners.**
