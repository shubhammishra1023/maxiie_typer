# maxiie_typer — Loksewa Typing Practice

A comprehensive, browser-based typing practice tool designed specifically for Loksewa (Public Service Commission) Computer Operator (4th & 5th level) practical exam preparation. 

## 🚀 Features

*   **Bilingual Support**: Practice in both Nepali (Romanized Unicode) and English (US).
*   **Exam Mode**: Simulates the real Loksewa exam hall environment by disabling live highlights and real-time statistics to test your actual focus.
*   **Customizable Tests**: 
    *   Choose time limits (1, 2, 3, 5, 6, or 10 minutes).
    *   Select passage lengths (Short ~150 words, Standard ~350 words).
    *   Paste your own custom text for targeted practice (works for both English and Devanagari).
*   **Real-time Analytics**: Tracks Net WPM, Gross WPM, Accuracy, and Error counts dynamically as you type.
*   **Post-Test Analysis**: Highlights difficult and mistyped words so you can identify your weak spots.
*   **Progress Tracking**: Saves your practice history and personal best scores locally in your browser.
*   **Accessible UI/UX**: Dark and light mode toggle, visually appealing typography, and an optional sound-on-mistake feature.

## 📋 Usage Instructions

1.  **Launch the App**: Since this is a client-side application, simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
2.  **System Setup**: Switch to romanized unicode layout in your pc using win + space for nepali typing [cite: 1].
3.  **Configure your Test**: 
    *   Select your target language under **1 · भाषा छनोट (Language)**.
    *   Choose your text source under **2 · पाठ स्रोत (Text source)**.
    *   Set the passage length and time limit.
4.  **Start Typing**: Click the "Start typing test →" button. The countdown timer starts automatically on your very first keystroke. 
5.  **Tips for Success**: Keep your eyes on the printed text or the passage, not the keyboard. Type straight through — the timer keeps running even on mistakes, exactly like the real exam hall.
6.  **Review Results**: After the time is up (or you finish typing the passage), review your Net WPM, accuracy, and practice history on the results screen.

## 🇳🇵 Nepali Romanized Typing Guide

The app features a built-in best-effort phonetic engine for Nepali. Type Nepali the way it sounds using English letters, and the tool will convert it to Unicode Devanagari live, letter by letter:

### Vowels
*   **Long vowels**: Double the letter or capitalize it. 
    *   `aa` or `A` = आ / ा
    *   `ee` or `I` = ई / ी
    *   `oo` or `U` = ऊ / ू
*   **Other vowels**: `a`=अ, `i`=इ/ि, `u`=उ/ु, `e`=ए/े, `o`=ओ/ो, `ai`=ऐ/ै, `au`=औ/ौ

### Consonants
*   **Retroflex (Capital) vs Dental (Lowercase)**: 
    *   `T / Th / D / Dh / N` = ट / ठ / ड / ढ / ण
    *   `t / th / d / dh / n` = त / थ / द / ध / न
*   **Aspirates**: `kh`=ख, `gh`=घ, `chh`=छ, `jh`=झ, `ph`=फ, `bh`=भ
*   **Sibilants**: `sh`=श, `S`=ष, `s`=स
*   **Conjuncts**: `ksh`=क्ष, `gya`=ज्ञ, `tra`=त्र, `shr`=श्र

### Special Characters
*   `M` = ं (Anusvar)
*   `~` = ँ (Chandrabindu)
*   `.` = । (Full stop / Danda)

*Note: This spelling mapping helps build intuitive typing patterns, though official layouts may vary slightly on specific complex conjuncts.*

## 🏆 Loksewa Scoring Reference

The tool calculates WPM using the standard 5-characters-per-word convention. For reference, here are the official PSC practical exam score bands (Devanagari text ≈200 words / English text ≈225 words):

| Nepali CWPM | Marks | English CWPM | Marks |
| :--- | :--- | :--- | :--- |
| < 3.5 | 0 | < 4 | 0 |
| 3.5 – 6.9 | 1.0 | 4 – 7.9 | 0.5 |
| 7 – 10.4 | 2.0 | 8 – 11.9 | 1.0 |
| 10.5 – 13.9 | 3.0 | 12 – 15.9 | 1.5 |
| 14 – 17.4 | 4.0 | 16 – 19.9 | 2.0 |
| 17.5 – 20.9 | 5.0 | 20 – 23.9 | 2.5 |
| 21 – 24.4 | 6.0 | 24 – 27.9 | 3.0 |
| 24.5 – 27.9 | 7.0 | 28 – 31.9 | 3.5 |
| 28 – 31.4 | 8.0 | 32 – 35.9 | 4.0 |
| 31.5 – 34.9 | 9.0 | 36 – 39.9 | 4.5 |
| ≥ 35 | 10.0 | ≥ 40 | 5.0 |

## 💻 Technical Details & Local Deployment

This project is highly lightweight and built entirely using:
*   **HTML5**
*   **CSS3** (with CSS Variables for theming)
*   **Vanilla JavaScript** (No dependencies, frameworks, or external libraries)

No build tools, package managers, or local servers are required to run this project. Simply clone the repository and open the HTML file:

```bash
git clone https://github.com/your-username/maxiie_typer.git
cd maxiie_typer
# Open index.html in your preferred browser
```
