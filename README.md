---

# Qaneq

**Qaneq** is a Yup’ik-centered language system designed to translate, teach, and preserve **Kuskokwim Yup’ik**.

The word *Qaneq* means **“mouth”** — the place where language lives.

Words can hurt.
Words can heal.
That is the power of Qaneq.

---

## Purpose

Qaneq exists to build tools that help people:

* Translate between English and Yup’ik
* Learn Yup’ik structure, not just vocabulary
* Understand cultural meaning behind words
* Preserve Yup’ik knowledge for future generations

---

## Project Philosophy

Yup’ik is not simply a collection of words—it is a **knowledge system**.

Qaneq follows these principles:

* Respect all Yup’ik dialects
* Avoid flattening Yup’ik into direct English equivalents
* Teach structure, not just definitions
* Preserve cultural and relational context
* Treat language as living knowledge

---

## Project Status

🚧 Early Development — v0.1.0

Core functionality is in progress.
This project is actively being built and expanded.

---

## Quick Start

Clone the repository:

```bash
git clone https://github.com/MakTek-Dev/Qaneq.git
cd Qaneq
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the translator:

```bash
python -m qaneq.translator
```

---

## CLI Usage

Translate a word:

```bash
python -m qaneq.translator qaneq
```

Example output:

```
mouth
```

Future flags (planned):

```bash
--explain
--morphology
--examples
--context
```

---

## Project Structure

```
qaneq/
├── translator.py
├── core/
├── morphology/
data/
dictionary/
```

---

## Core Components

### Elitnaurista Qanyuuli

**Teaching + Translation Engine**

Responsible for:

* Word translation
* Morphological analysis
* Grammar explanation
* Cultural interpretation

---

### Dictionary System

Qaneq uses structured dictionary data.

Example:

```
dictionary/
Yupik_dictionary.json
```

Each entry may include:

* Yup’ik word
* English meaning(s)
* Root analysis
* Postbase and suffix breakdown
* Cultural/context notes

---

## Technology Stack

* **Python** — core logic and CLI
* **JSON / YAML** — dictionary structure
* **AI models** — teaching and explanation layer

---

# 🗺️ Development Roadmap

This roadmap reflects both **technical progression** and **cultural integrity goals**.

---

## Phase 1 — Foundation

* [ ] Create CLI translator (`qaneq/translator.py`)
* [ ] Add `data/` folder for wordlists
* [ ] Add `core/` module structure
* [ ] Finalize README
* [ ] Add installation + usage instructions
* [ ] Add LICENSE
* [ ] Add `.gitignore`

---

## Phase 2 — Core Language Engine

* [ ] Yup’ik → English lookup
* [ ] English → Yup’ik lookup
* [ ] Support multiple meanings per word
* [ ] Add cultural/context notes
* [ ] Structured dictionary format (JSON/YAML)
* [ ] CLI error handling with helpful messages

---

## Phase 3 — Morphology & Structure

* [ ] Create `morphology/` module
* [ ] Root extraction
* [ ] Postbase parsing
* [ ] Suffix parsing
* [ ] Vowel harmony and assimilation rules
* [ ] Add tests and examples

---

## Phase 4 — Teaching Tools

* [ ] Word breakdown feature
* [ ] Structure explanation mode
* [ ] Example sentences with explanations
* [ ] Cultural notes tied to grammar

---

## Phase 5 — CLI Enhancements

* [ ] Add flags:

  * `--explain`
  * `--morphology`
  * `--examples`
  * `--context`
* [ ] Colorized terminal output
* [ ] Interactive mode (`qaneq --interactive`)

---

## Phase 6 — Data Expansion

* [ ] Add 100 core Yup’ik words
* [ ] Add 100 verbs with postbases
* [ ] Add kinship terms with relational context
* [ ] Add place-based vocabulary
* [ ] Add ceremonial and worldview vocabulary

---

## Phase 7 — Architecture for Growth

* [ ] Document module structure
* [ ] Add `CONTRIBUTING.md`
* [ ] Add `ROADMAP.md`
* [ ] Implement versioning (v0.1.0 → v1.0.0)
* [ ] Prepare for local model integration

---

## Phase 8 — Long-Term Vision

* [ ] Morphology-aware parser
* [ ] Yup’ik-first translation engine
* [ ] Local model trained on Kuskokwim Yup’ik
* [ ] Teaching interface for youth
* [ ] Full Yup’ik language environment

---

## Goals

* Build reliable Yup’ik ↔ English translation tools
* Teach grammar and linguistic structure clearly
* Preserve cultural knowledge and meaning
* Operate on **low-power devices and mobile systems**
* Expand into a full learning ecosystem

---

## Cultural Respect

Qaneq recognizes that Yup’ik language belongs to the Yup’ik people.

This project exists for:

* Preservation
* Education
* Respectful use

---

## Future Development

Potential expansions include:

* Cup’ik dialect support
* Cup’ig dialect support
* Siberian Yup’ik support
* AI-assisted teaching tools
* Mobile applications

---

## License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

## Name Meaning

**Qaneq**
→ *“mouth”*

Speech carries knowledge.
Knowledge carries culture.

Qaneq exists to keep that knowledge alive.

---

## Final Note

Qaneq is not just software.

It is an effort to protect, teach, and continue a living language.

---
