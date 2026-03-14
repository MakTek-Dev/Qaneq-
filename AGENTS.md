# AGENTS.md

## Project

**Qaneq / Qanyuuli Language System**

Purpose:
Build an AI system that translates, teaches, and preserves **Kuskokwim Yup’ik** language and culture.

Primary components may include:

* QanyuuliGPT (AI translation and explanation engine)
* Mumiggcisuun App (translator interface)
* language datasets and morphology rules
* cultural and linguistic explanations

The system must respect Yup’ik linguistic structure and community knowledge.

---

# Core Principles

1. **Dialect First**

   * Default dialect is **Kuskokwim Yup’ik**.
   * Do NOT substitute Central Yup’ik or other dialects unless explicitly specified.
   * If dialect is uncertain, mark the result as **uncertain** rather than guessing.

2. **Preserve Meaning**

   * Yup’ik is a **polysynthetic language**.
   * Avoid simple word-for-word translation.
   * Prefer morphological analysis:

     * root
     * suffix chain
     * contextual meaning.

3. **Teach, Not Just Translate**

   * When possible, generate explanations including:

     * root meaning
     * suffix meanings
     * grammatical role
     * cultural context.

4. **Cultural Respect**

   * Language entries may include worldview concepts such as:

     * respect for land
     * respect for animals and plants
     * cultural traditions.
   * Never remove cultural explanations without instruction.

5. **Do Not Invent Language**

   * If a translation is uncertain:

     * mark it as `UNCERTAIN`
     * request review
     * leave a comment explaining why.

---

# Repository Behavior Rules

Codex should follow these operational rules:

## Branching

* Never commit directly to `main`.
* Create feature branches for all changes.

Example:

feature/translator-engine
feature/morphology-parser
feature/ui-improvements

## Pull Requests

Open a pull request for:

* new language rules
* translation logic changes
* dataset changes
* application features
* structural refactors

Small documentation updates may commit directly to feature branches.

---

# Protected Data

Never automatically delete or overwrite:

* language datasets
* root word dictionaries
* suffix tables
* cultural notes
* linguistic explanations

If changes are needed, propose edits via Pull Request.

---

# Translation Engine Guidelines

Translation system should attempt the following order:

1. identify root word
2. detect suffix sequence
3. determine grammatical structure
4. infer contextual meaning
5. generate translation
6. generate explanation

Example output structure:

Word: qanellruuq

Root
qan – speech / say

Suffix
-llruuq – narrative past

Meaning
"He said (as part of a story)."

---

# Code Style

Preferred priorities:

1. clarity
2. modular design
3. maintainability
4. readable naming
5. strong documentation

Avoid overly complex abstractions.

---

# File Organization (Recommended)

language/
roots.json
suffixes.json
dialect_rules.json

translator/
morphology_engine.py
translation_engine.py

app/
api/
web_interface/

docs/
cultural_notes.md
linguistic_explanations.md

---

# Testing

Every translation change should include:

* test examples
* expected translation output
* morphology explanation validation.

---

# Automation

Codex may:

* propose code improvements
* generate tests
* review pull requests
* refactor code safely

Codex must NOT:

* change dialect rules without review
* fabricate Yup’ik words
* remove cultural documentation.

---

# Mission Reminder

Qaneq is not only a translator.

It is a **language preservation and teaching system** designed to help future generations learn and understand Yup’ik language and worldview.

