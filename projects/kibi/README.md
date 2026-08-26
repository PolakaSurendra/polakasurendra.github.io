# Kibi — Assistive Virtual Assistant

Files for the Kibi project card on the portfolio site.

- `code/` — source files (`.py`, `.c`, `.ino`, `.zip`, ...)
- `docs/` — documents (`.pdf`, `.docx`, `.md`, ...)

## How to publish a file here

1. Drop the file into `code/` or `docs/`.
2. Open `index.html`, find the Kibi entry in the `projects` array
   (search for `Kibi — Assistive Virtual Assistant`).
3. Add a line to its `files: [ ... ]` array:

       { name: "Dialog manager", path: "projects/kibi/code/dialog_manager.py" },

4. Commit and push. The link shows up under the project card.

Avoid spaces in file names — use `dialog-manager.py`, not `dialog manager.py`.
