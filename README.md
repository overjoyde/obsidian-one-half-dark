# One Half Dark

An Obsidian theme based on the **One Half Dark** colour scheme from Windows Terminal, with a matching **One Half Light** mode.

![One Half Dark — headings, formatting, lists and tasks](./images/screenshot-full.png)

| Callouts | Code highlighting | Tables and code | Project note |
| --- | --- | --- | --- |
| ![Callouts](./images/callouts.png) | ![Code samples](./images/code-samples.png) | ![Table and code](./images/table-and-code.png) | ![Garden project](./images/garden-project.png) |

## Palette

| Role                 | Dark      | Light     |
| -------------------- | --------- | --------- |
| Background           | `#282C34` | `#FAFAFA` |
| Foreground           | `#DCDFE4` | `#383A42` |
| Faint (bright black) | `#5A6374` | `#A0A1A7` |
| Red                  | `#E06C75` | `#E45649` |
| Yellow               | `#E5C07B` | `#C18301` |
| Green                | `#98C379` | `#50A14F` |
| Cyan                 | `#56B6C2` | `#0997B3` |
| Blue (accent)        | `#61AFEF` | `#0184BC` |
| Purple               | `#C678DD` | `#A626A4` |

## Features

- Headings H1–H6 follow the ANSI order: red → yellow → green → cyan → blue → purple
- **Bold** in yellow and _italic_ in purple
- Code syntax highlighting follows the One Half colours
- Callouts, tables, tags, graph view and checklists use the same palette
- Blue accent line on the active tab, like Windows Terminal
- Monospace font order: Cascadia Code → JetBrains Mono → SF Mono → Menlo, using fonts already on your computer (no remote assets)
- Built only on Obsidian CSS variables with low-specificity selectors and no `!important`, so you can override anything with a snippet

## Customising

Every colour is set once in the palette section at the top of `theme.css` (`--ohd-*` variables). To change a colour, override that variable in a CSS snippet, for example:

```css
.theme-dark {
  --bold-color: var(--ohd-fg);
}
```

## Credits

The palette comes from [One Half](https://github.com/sonph/onehalf) by Son A. Pham (MIT), as shipped in Windows Terminal.

## License

[MIT](./LICENSE)
