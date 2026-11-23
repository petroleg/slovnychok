# SlovnychOK

SlovnychOK is an English-Ukrainian dictionary with flashcards for iPhone and iPad.

This repository holds:

- the app's [privacy policy](https://petroleg.github.io/slovnychok/privacy.html) and [support page](https://petroleg.github.io/slovnychok/support.html) (`docs/`, served by GitHub Pages);
- the dictionary data shipped in the app, published under CC BY-SA 4.0 on the [releases page](https://github.com/petroleg/slovnychok/releases);
- [issues](https://github.com/petroleg/slovnychok/issues) for support questions and corrections.

The app's source code is not part of this repository.

## Dictionary data

Each release contains:

| File | Content |
|---|---|
| `dictionary.sqlite` | The English-Ukrainian dictionary (SQLite): entries, phrases, senses, examples, levels, relations and learning content |
| `decks.json` | Word decks by topic and level |
| `ngsl-deck.json` | NGSL 1.2 word deck |
| `audio.tar.gz` | Pronunciation recordings from Wikimedia Commons (`audio` table gives author and license per file) |

### License

The dictionary data (`dictionary.sqlite`, `decks.json`, `ngsl-deck.json`) is an adaptation of the sources below
and is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) (full text in `LICENSE`).
The adaptation combines the sources, adds Ukrainian translations, edits senses and examples, and assigns CEFR levels.
The recordings in `audio.tar.gz` keep their own licenses (public domain, CC0 or CC BY), listed per file.

### Sources and attribution

- **Wiktionary** (senses, translations, examples, relations, categories, etymology), via [kaikki.org](https://kaikki.org), CC BY-SA 4.0 / GFDL. Page histories: [en.wiktionary.org](https://en.wiktionary.org).
- **Open English WordNet 2025**, Princeton WordNet and the Open English Wordnet team, CC BY 4.0.
- **Tatoeba** example sentences, [tatoeba.org](https://tatoeba.org), CC BY 2.0 FR; authors per sentence in `example_extra.author`.
- **wordfreq** by Robyn Speer, CC BY-SA 4.0 (frequency ranks; its data includes Google Books Ngram, SUBTLEX and OpenSubtitles).
- **CEFR-J Wordlist Version 1.5**, Tono Laboratory, Tokyo University of Foreign Studies (levels A1-B2), free for research and commercial use with citation.
- **Octanove Vocabulary Profile C1/C2 1.0**, CC BY-SA 4.0 (levels C1-C2), via openlanguageprofiles/olp-en-cefrj.
- **New General Service List 1.2**, Browne, C., Culligan, B., Phillips, J. (2013), [newgeneralservicelist.com](https://www.newgeneralservicelist.com), CC BY-SA 4.0.
- **CMUdict** (US pronunciations), Carnegie Mellon University, BSD-2-Clause.
- **Britfone** (UK pronunciations), Jose Llarena, MIT.
- **English Wikipedia** (collocation statistics), CC BY-SA 4.0.
- **Wikimedia Commons** pronunciation recordings, public domain, CC0 or CC BY; author, license and file page per recording in the `audio` table. The recordings were converted to compressed mono audio.
