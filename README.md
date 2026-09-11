# Bordeaux

🍷 Part of the Vineyard family for Obsidian.

![The Bordeaux color palette](palette.png)

A dark wine red theme for Obsidian. I wanted something I could write in for hours without it getting loud, so everything is flat. No gradients and no glow. The only thing that moves is a quick color fade when you hover over something.

This is what it looks like in a real vault, with [Grape Clusters](https://github.com/creativemindrito/grape-clusters-obsidian) grouping the graph by folder:

![Bordeaux in Obsidian, with the file list on the left and the graph view on the right](screenshot.png)

## Install

1. Download `theme.css` and `manifest.json` from the [latest release](https://github.com/creativemindrito/bordeaux-theme-obsidian/releases/latest).
2. Put them in a folder called `Bordeaux` inside `.obsidian/themes/` in your vault.
3. Pick Bordeaux under *Settings → Appearance*.

## Make it yours

The reds sit at the top of `theme.css`. To change one, copy its line into a CSS snippet (*Settings → Appearance → CSS snippets*) so an update never undoes it:

```css
.theme-dark {
  --bordeaux-bar: #6e1016;
  --bordeaux-fabric: #3a1212;
  --bordeaux-accent: #b3262f;
  --bordeaux-rose: #e0949a;
  --bordeaux-gold: #d4a24c;
}
```

Dark mode only for now. It's plain CSS and it doesn't load anything from the internet.

Made by [creativemindrito](https://github.com/creativemindrito). Free to use under the [MIT license](LICENSE).
