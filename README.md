# Learn-Armenian-Project

**Flashy** is a simple and interactive desktop application that helps users learn Armenian vocabulary with English translations. The app displays flashcards for Armenian words and allows users to mark words as “known” or “unknown.” Users can also hear the pronunciation of Armenian words using offline Text-to-Speech.

---

## Features

* Displays **Armenian words** with their English translations on flashcards.
* Allows users to **flip cards** automatically after a few seconds.
* Mark words as **known** to remove them from the study list.
* **Offline pronunciation** of Armenian words via `espeak-ng`.
* Progress is saved in `data/words_to_learn.csv`, so you can continue learning where you left off.
* Supports **large word lists** (e.g., 1000+ words).

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/VasilisKokotakis/Learn-Armenian-Project.git
cd Flashy_Armenian-English_Flashcards
```

2. Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install required Python packages:

```bash
pip install pandas
```

4. Install `espeak-ng` for offline Armenian pronunciation:

```bash
sudo apt install espeak-ng
```

---

## Usage

Run the application:

```bash
python3 main.py
```

* Click the **“✅”** button if you know the word.
* Click the **“❌”** button if you don’t know the word.
* Click the **“🔊 Pronounce”** button to hear the Armenian word.

---

## Future Improvements

* **API integration** to fetch new Armenian-English words automatically.
* Improved **voice pronunciation** using online Text-to-Speech services (optional).
* Enhanced UI with animations, keyboard shortcuts, and progress tracking.

---

## File Structure

```
Flashy_Armenian-English_Flashcards/
├─ main.py
├─ data/
│  ├─ armenian_english_1000_words.csv
│  └─ words_to_learn.csv
├─ images/
│  ├─ card_front.png
│  ├─ card_back.png
│  ├─ right.png
│  └─ wrong.png
└─ README.md
```

---

## Screenshots

<img width="895" height="840" alt="image" src="https://github.com/user-attachments/assets/1a50d920-2083-4055-9151-a8feac5d4b6b" />
<img width="895" height="840" alt="image" src="https://github.com/user-attachments/assets/858b6058-4398-4f31-b78f-987f9766fe50" />

## Requirements

* Python 3.8+
* pandas
* espeak-ng (Linux)
* Tkinter (usually included with Python)

