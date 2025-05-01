# Konkow Language Lexicon Toolkit

A modern, web-based toolkit for exploring, preserving, and expanding the **Konkow Maidu language** using a structured database of words, affixes, example sentences, and grammar rules. Built with **Flask**, **SQLite**, and designed to support both educational use and long-term language revitalization.

![Konkow Language Tool](https://via.placeholder.com/800x400?text=Konkow+Language+Toolkit)

## Features

- **Morphological Analysis & Word Building** - Break down and construct Konkow words with intelligent component detection
- **Searchable Konkow Dictionary** with English glosses
- **Phonological Rule Implementation** for accurate morphological generation
- **Sentence Simulator** with grammar features practice and progression-based learning
- **Example Sentence Database** with authentic usage examples
- **Web Scraper** for collecting Konkow language information from online sources
- **Progressive Web App (PWA)** with offline capabilities
- **Compatible with Replit** for easy deployment and sharing

## Quick Start

### On Replit

1. Click the "Run" button in the Replit interface
2. Visit the homepage at the generated URL
3. Import authentic Konkow lexicon by clicking the "Import Konkow Lexicon" button
4. Start exploring the language using the various tools

### Local Development

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```
4. Open your browser to `http://localhost:5000`

## Key Components

### Word Builder

Allows users to construct Konkow words by combining roots and affixes following language rules. Visualize morphological processes with:

- Root word selection
- Affix ordering validation
- Phonological rule application
- Resulting morpheme breakdown

### Translation Engine

Translate between Konkow and English with:

- Word component analysis
- Grammar validation
- Morpheme-by-morpheme breakdown
- Contextual hints

### Sentence Simulator

Practice with automatically generated Konkow sentences with varying complexity:

- Random sentence generation
- Feature-focused practice (plural, tense, case)
- Sentence transformations (questions, negatives, imperatives)
- Progressive learning sequences

### Dictionary Browser

Browse a comprehensive dictionary of Konkow linguistic components:

- Roots and base words
- Prefixes and suffixes
- Usage examples and grammatical notes
- Enhanced with authentic Konkow lexicon data

## Technical Details

- **Backend**: Flask web framework
- **Database**: SQLite with SQLAlchemy ORM
- **Frontend**: HTML, CSS with Bootstrap
- **Offline Support**: PWA with service worker and IndexedDB
- **Word Processing**: Custom morphological analysis engine

## Development

The codebase is organized into modular components:

- `main.py`: Application entry point
- `app.py`: Flask application configuration
- `models.py`: Database models (Root, Affix, etc.)
- `routes.py`: HTTP route definitions
- `language_processor.py`: Core language processing logic
- `morphology.py`: Morphological analysis and generation
- `grammar.py`: Grammar validation rules
- `sentence_simulator.py`: Sentence generation and practice
- `import_konkow_data.py`: Data import for authentic lexicon

## License

MIT License © 2024

## Acknowledgments

- **Konkow.org** — for primary word lists and lesson materials
- **Academic Sources** — foundational grammar of the Konkow Maidu language
- **Replit** — for making web-based development and language revitalization accessible

---

*This toolkit is a digital resource for the Konkow indigenous language, enabling linguistic analysis, language learning, and preservation efforts.*