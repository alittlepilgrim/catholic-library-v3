---
type: page
title: How the Links Work
aliases:
  - how-the-links-work
  - How the Links Work
tags:
  - type/page
layer: 5
authority: personal
scope: universal
created: 2026-09-08
modified: 2026-09-08
description: "Double brackets, the reference line at the foot of every card, and the one rule that keeps 230,000 links from breaking."
---

# How the Links Work

There are about 230,000 links in this library and every one of them lands on something. This page explains how they are written, so that when you add your own they land too.

## Double brackets

Type two square brackets and a name:

```
[[teresa-of-avila-saint]]
```

That is a link. Click it and the note opens. If you start typing inside the brackets, a list appears and you can pick from it — you almost never type a whole name by hand.

Three variations do almost everything:

| Written | Does |
|---|---|
| `[[devil-demon]]` | A plain link |
| `[[devil-demon\|the devil]]` | Same link, but the page shows *the devil* |
| `[[devil-demon#Etymology]]` | Jumps straight to that heading |

The vertical bar means "show these words instead." Use it constantly — it is how a link disappears into a sentence instead of interrupting it.

## The one rule: the name is the address

**A link is always the bare name of the note. Never a folder path.**

```
[[teresa-of-avila-saint]]          ✅
[[06-figures/teresa-of-avila-saint]]  ❌
```

Both work today. Only the first one survives.

The reason is that this library has no hidden ID numbers. A note's filename *is* its identity. So a link written as a bare name keeps working no matter where the file is moved to — drag it into another folder and every link to it still lands. A link written with a folder in it breaks the moment anything moves.

Which means:

- **Moving a note is safe.** Do it freely. Obsidian rewrites what it needs to.
- **Renaming a note is the operation to be careful with.** Rename it *inside Obsidian* — right-click, Rename — and Obsidian will find and fix every link pointing at it. Rename it in Finder and nothing gets fixed; you have just broken every link silently.

That is the whole rule. Move freely, rename inside the program, never write a folder into a link.

## Aliases — one note, several names

Look at the top of a figure card and you will see something like:

```
aliases:
  - zelie-martin-saint
  - Zélie Martin
  - Marie-Azélie Guérin
  - Saint Zélie Martin
```

Every one of those names finds that card, in search and in the link picker. You do not have to remember which spelling the file uses. If you find yourself searching for a name that does not work, add it to the aliases list.

## Embeds — one line, changed everywhere

Put an exclamation mark in front of a link and the content appears *inside* the current note instead of being linked to:

```
![[reference-footer#^ref-footer]]
```

The `^ref-footer` part points at one specific line inside `00-admin/reference-footer.md`. Change that one line and the bottom of 1,398 cards changes with it.

**There are two footers in this library**

**The reference cards** — every term, figure, work and feast, 1,398 of them — end with that one shared line, pointing at the bibliography and the abbreviations. They are apparatus: they need a way back to the reference shelf, and it is the same way back for all of them.

**The source pages** — 6,260 of them — end with a *different* embed, and each one names the exact edition that page was transcribed from:

```
![[bibliography#^biblio-nabre]]      a Scripture page, NAB-RE
![[bibliography#^biblio-ccc]]        a Catechism paragraph
![[bibliography#^biblio-jc-cw-ics-3e]]   the ICS third edition of John of the Cross
```

There are 126 of these in use, one per edition, and every one of them lives in the single `00-admin/bibliography.md` note — which defines 162, holding a few in reserve. So the edition statement under a chapter of the *Ascent* is not typed into that chapter — it is one line in the bibliography, embedded 300 times. Correct the citation once and 300 pages are corrected.

That is why you can always tell what edition you are standing in, and why no page can drift out of agreement with the bibliography: the page has no copy of its own to drift.

About 113 notes carry neither — our own lists, tables of contents, and cover pages, which cite no single source.

**Some anchors in the bibliography are not used by anything yet, and that is on purpose.** The sixteen Vatican II documents each have their own entry and their own anchor, while the council pages presently cite the collected volume. The individual entries are stocked ahead of need: when you are writing and want to quote *Lumen Gentium* precisely, the anchor is already there. Having to stop and build one, mid-thought, is exactly the interruption this design exists to prevent. An unused anchor is stock on the shelf, not a gap in the shelf.

This is also the technique to reach for whenever you want something to be true in one place only.

## Seeing what points back

Open any note and look for **Backlinks** — every note that links *to* this one. It is the most useful panel in the program and the one most people never open.

It is how the library is meant to be read. Open `05-terms/prayer.md`, look at the backlinks, and you are looking at every passage in Scripture, the Catechism, Teresa and John that this library has connected to prayer. No search built that list; the links did, one at a time.

The **Graph** view draws the same thing as a picture. It is beautiful and almost never useful. Look at it once.

## Wandering

The intended way to read this library is not to search. It is:

1. Open a term card — say `05-terms/dark-night.md`.
2. Follow it up to the text it cites, in `03-spiritual-theology`.
3. From that chapter, follow a link sideways to a figure card.
4. From the figure, to the feast, or to the work card that holds every edition of the book.
5. From the work card, into a different edition of the same passage.

Every card points you back to the bibliography, and every source page names the edition it was transcribed from, so you always know what you are standing in.

## When a link does not work

An unresolved link shows in a different color and clicking it offers to create the note. If you meant to point at something that exists, one of three things is true: the name is spelled differently, the note has a different filename than its title, or it is genuinely not in this library — some notes were deliberately left out of this copy, and links to them were rewritten as plain words rather than left dangling.

Obsidian has no one button that lists them all. The graph view can show unresolved links as their own dots if you turn that on in its settings, and a community plugin will make a proper list. 

> 📚 [[bibliography|Bibliography]] · [[how-the-layers-work|How the Layers Work]] · [[start-here|Start Here]]
