# Printing Press Cream

A light VS Code theme that feels like a small print press: solid warm ink on
flat cream paper, with the **same cream colour on every panel** — editor,
sidebar, tabs, terminal, status bar, title bar. No patchwork of slightly
different beiges, no washed-out grey-blue text.

Text contrast is the point: the main ink (`#332E27`) measures roughly
**12:1** against the paper (`#FCF4E3`), where classic Solarized Light's
slate foreground manages only about 4:1.

## Palette

| Role | Colour |
| --- | --- |
| Paper (all surfaces) | `#FCF4E3` |
| Raised surface / hover | `#F0E5C8` |
| Selection | `#E9DCB9` |
| Ink (main text) | `#332E27` |
| Soft ink (secondary text) | `#6D675F` |
| Comments | `#6F6E69` (italic) |
| Strings | `#66800B` |
| Keywords | `#5E409D` |
| Functions | `#205EA6` |
| Types & headings | `#AD8301` |
| Numbers & constants | `#BC5215` |
| Tags & errors | `#AF3029` |

Accent colours are the light 600-step inks from
[Flexoki](https://stephango.com/flexoki) by Steph Ango (MIT), chosen because
they stay legible on warm paper. The integrated terminal uses the same
palette for its ANSI colours, so CLI output doesn't clash with the editor.

## Install

**From the Marketplace:** search for **Printing Press Cream**, install, then
`Cmd+K Cmd+T` (macOS) / `Ctrl+K Ctrl+T` and pick **Printing Press Cream**.

**From a .vsix file:**

```sh
code --install-extension printing-press-cream-0.1.0.vsix
```

then select the theme the same way.

## Good pairings

- Any clean mono font works. Iosevka or JetBrains Mono at 13–14px keeps the
  print feel.
- Set `"workbench.iconTheme"` to whatever you like — the theme deliberately
  ships no opinions about icons.

## Credits

- Accent palette: Flexoki by Steph Ango, MIT License —
  https://github.com/kepano/flexoki
- Everything else: original, MIT licensed (see `LICENSE`).
