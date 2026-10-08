---
type: page
title: About Obsidian
aliases:
  - about-obsidian
  - About Obsidian
tags:
  - type/page
layer: 5
authority: personal
scope: universal
created: 2026-09-08
modified: 2026-09-27
description: "The program this library runs in — settings that matter, the templates, the table views, and the two command-line tools."
---

# About Obsidian

This library is a folder of plain text files. That is not a figure of speech: open any note in TextEdit or Notepad and you will see exactly what Obsidian shows you, plus a few lines of settings at the top. Nothing is in a database. Nothing needs a subscription. If Obsidian vanished tomorrow the library would still be readable in 2050.

Obsidian is a reader for that folder. It draws the links, builds the tables, and keeps the links correct when you move things.

**Get it at obsidian.md.** When it asks, choose *Open folder as vault* and point it at this folder.

## The four settings that matter

They are already set correctly here. If you ever copy this library or start a new one, these are the four to check — Settings → Files and links.

| Setting | Here | Why |
|---|---|---|
| **Automatically update internal links** | on | Move a note and every link to it is rewritten. This is the setting the whole library depends on. |
| **New link format** | Shortest possible | Writes `[[name]]`, not `[[folder/name]]`. See [[how-the-links-work]] for why that matters. |
| **Use Wikilinks** | on | Links look like `[[this]]`, not like Markdown. |
| **Default attachment folder** | `99-assets` | Images you paste in land in one place instead of scattering. |

One warning about the second one. *Shortest possible* still writes a folder path when two notes share a name — Obsidian has no other way to tell them apart. So if you ever see a link with a slash in it, that is Obsidian telling you there is a duplicate filename somewhere. Fix the duplicate, not the link.

## The plugins installed here

**Templater** — makes the blank cards in `00-admin/templates` available from the New Note button. See below.


## Templates

Blank cards live in `00-admin/templates`, one for each kind of note this library uses:

| Template | For |
|---|---|
| `template-term` | A glossary entry — one idea |
| `template-figure` | A saint or historical person |
| `template-work` | A book, holding all its editions together |
| `template-feast` | A feast day |
| `template-source-page` | A chapter or section of a source text |
| `template-default` | Anything else — title, type, created, modified, and nothing more |

**They apply themselves.** A new note made inside `05-terms` gets the term card. Inside `06-figures`, `07-works` or `08-feasts`, the matching one. Anywhere else, `template-default` — a plain note with no architecture on it at all. You never have to remember which is which; make the note where it belongs and it arrives dressed.

To reach for one deliberately instead — a source page, say, which has no folder of its own — use the command palette (`Ctrl/Cmd + P`) → *Templater: Open insert template modal*.

The four card templates carry the three architecture fields already filled with the usual answer for that kind of note. Change them if the note is unusual; [[how-the-layers-work]] explains what they mean. The default template carries none: a note you dash off is just a note, and it can be given a layer later if it turns into something.

## The table views

`base.base` at the top of the library is a Base — Obsidian's built-in spreadsheet over your notes. Open it like a note.

Down the side are the views. Each is the same 11,687 notes filtered and sorted differently: everything, by type, by authority, by layer, recently touched, the formation corpus, the indexes, the terms alone, the reference library.

One more Base sits deeper in the library for its own corner: `04-formation/propers/propers-base.base` for the propers.

To add a view of your own, open the Base, click the **+** beside the view tabs, and choose the properties to show. Nothing you do to a Base can damage a note — a Base only reads.

## The two command-line tools

You will probably never need these. They are written down because the day you do need them, the difference between the two is not obvious.

### Obsidian CLI — drives the app you have open

```
obsidian vault=CatholicLibrary help
obsidian vault=CatholicLibrary move file=<name> to=<folder>
```

**`vault=` must come first, always.** And **never run a bare `obsidian` with no arguments** — it opens whatever vault it feels like, which on a machine with several vaults is rarely the one you meant.

It is the only way to move a note from the command line and keep the links correct, because link-rewriting is something the *app* does. `mv` in a terminal moves the file and breaks every link to it silently.

Beyond moving, `obsidian vault=<name> help` lists over a hundred commands. The four worth knowing:

| Command | Answers |
|---|---|
| `unresolved` | every link pointing at nothing — using Obsidian's own resolver, so aliases count |
| `orphans` | notes nothing links to |
| `backlinks file=<name>` | what points at this note |
| `properties` | the frontmatter, without hand-parsing YAML |

That resolver is the same one the `[[` picker uses, which makes it the authority. Any script that re-implements it will get aliases and attachments wrong.

### Obsidian Headless (`ob`) — a different animal

A standalone client that runs with no desktop app. Its entire command list is `login`, `logout`, nine sync commands and seven publish commands. **It cannot move, rename, create, delete, or rewrite a link** — those are app behaviours.

It exists for syncing and publishing without opening the app. For this library, which does neither, it has no use at all.

## If you want to change how it looks

Settings → Appearance. Themes are free and there are hundreds. Nothing you choose changes a single note — the folder is the same either way.

> 📚 [[start-here|Start Here]] · [[how-the-layers-work|How the Layers Work]] · [[how-the-links-work|How the Links Work]]
