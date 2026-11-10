# Vault Guide

## Find things

- [[Example Project]] shows how to give an agent context about a feature in a separate Git checkout.
- [[Clippings/README|Clippings]] holds articles saved with Obsidian Web Clipper.
- [[Wiki/README|Wiki]] holds free-form notes.
- [[Daily/README|Daily]] is a place for daily notes, with an optional [[Templates/Daily|template]].
- [[Drawings/README|Drawings]] holds editable Excalidraw files.

## Write here

Use short Markdown headings, descriptive filenames, and [[Example Project|wikilinks]] for notes in the vault. Use ordinary Markdown links for repositories and other websites. Use the user's conventions when editing existing notes. A clipped article is reference material. The user chooses which notes and drawings the agent can edit.

## Give an agent context

Replace the example path with the vault's absolute path on the machine where your agent runs. Point the agent to the project note for the current task.

> My Obsidian vault is at `/absolute/path/to/vault`. Read `Vault Guide.md` and `Example Project.md` there for context. Keep code in the separate Git checkout. Edit the vault files I ask you to change. If this vault is synced, your edits can appear on my other devices.

For drawings, use the format in [[Drawings/Example.excalidraw|the editable example]]. A new headless drawing uses the same frontmatter and Markdown sections, matching text block IDs to editable scene elements in the Drawing JSON block. Save it to an unused path and link it from the relevant note.
