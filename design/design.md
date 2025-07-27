---
tnh_processing:
- model: gpt-4o
  pattern: repair_markdown
  processor: GeneralProcessor
  step: process_text
  template_dict: {}
  timestamp: '2025-07-27T08:43:44.935506'
  tool: null
---

# Suggested Documents to Add to the design/ Folder

Here’s a starting set of documents for project methodology, interaction principles, and evolving norms:

## design/

- `style-guide.md`
- `design-guide.md`
- `ai-human-collaboration-guide.md`
- `testing-and-validation.md`
- `metadata-and-tagging-scheme.md`
- `repo-architecture-notes.md`

---

### style-guide.md

Covers:

- Markdown conventions (headings, emphasis, citation style)
- Tone and voice (reflective, academic, dialogic)
- Inline citations vs. footnotes
- Code comment conventions
- Example code formatting (Python, YAML, JSON)
- Accessibility and clarity guidelines

---

### design-guide.md

Covers:

- Paper architecture (narrative arc, modular structure)
- Layout of appendices and reference artifacts
- Integration of code simulations and text
- Planning future web or interactive outputs

---

### ai-human-collaboration-guide.md

Covers:

- Principles of dialogic co-creation
- Workflow for clarifying misunderstandings
- Human oversight checkpoints
- AI prompt scaffolding and framing strategies
- Reflections on co-authorship and attribution

---

### testing-and-validation.md

Covers:

- If we develop code (e.g., dialog agent models), describe:
- Testing frameworks (pytest, notebook testing)
- Human-in-the-loop validation methods
- Evaluation criteria (accuracy, clarity, ethical plausibility)

---

### metadata-and-tagging-scheme.md

(Optional, if using tagging later)

- Rules for annotating documents
- Tag examples: #dialog, #ethics, #AI-agent, #fallibility, etc.

---

### repo-architecture-notes.md

- Explains file structure philosophy
- Folder purpose, naming conventions
- Commit practices (e.g., message tags: `[draft]`, `[review]`)
