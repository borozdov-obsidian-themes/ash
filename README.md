# Borozdov Ash

A theme from the Borozdov collection. Two faces — light **Bleach**, graphite ink on warm
paper, and dark **Smudge**, the same ink smudged across a graphite page. Hairline-edged
cards, three tiers of grey, and inversion as the only accent.

![Borozdov Ash in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/ash/main/screenshots/light.png)

![Borozdov Ash in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/ash/main/screenshots/dark.png)

## Principles

- **No hue at all.** Every surface, border and label is grey. State is never carried by
  colour — only by weight, a hairline and the one place the theme inverts.
- **Three tiers of grey.** Ink for running text, muted for secondary, faint for
  tertiary — the same three steps the interface leans on everywhere, from headings down to
  a table's footnote row.
- **A hairline builds every card.** Callouts, code panes, tables and popovers are the same
  card: a mist fill and a 1px hairline rim at 10px corners, never a shadow.
- **One inversion.** True black on Bleach, true white on Smudge, reserved for the filled
  button, the checked box and the caret — the single moment the whole page flips.
- **Developer-native type.** The platform's own sans at 400 for text and 600 for headings;
  no embedded font, no load, no flash of unstyled text.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts, code blocks, tables and popovers drawn as the same hairline-rimmed card
- Tags and property pills as flat, square badges that invert under the pointer
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- A toggle thumb tuned per face so it never disappears against its own track
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays around 12 KB
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Ash** under Style Settings → Borozdov Ember → Variant. The variant brings this theme's
palette, type and corners; its own layout, and its embedded font if it has one, come with
the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/ash/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Ash/`, then choose Borozdov Ash under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Bleach» — графитовые чернила
на тёплой бумаге, и тёмный «Smudge» — тот же штрих, размазанный по графитовой странице.
Карточки на тонкой линии, три ступени серого и инверсия как единственный акцент. Шрифты не
встроены. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Ash в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
