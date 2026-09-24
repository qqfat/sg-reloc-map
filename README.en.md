[繁體中文](README.md) | [简体中文](README.zh-CN.md) | **English** | [Tiếng Việt](README.vi.md)

# Relocation Range Preview

Mark the coordinates you want to attack, find the relocation spot that covers the most of them, and preview the 60-tile attack range before you relocate.

The whole tool is a single `index.html`. Everything runs in your browser — it never connects to or controls the game, and your targets are stored only in your own browser.

## How to use

1. **Add target**: click the map, or type `x,y` in the box (you can paste several at once). Click an existing target to remove it.
2. **Suggested relocation** lists the spot that covers the most targets, plus alternatives that cover just as many. If targets are too spread out, a 2nd and 3rd relocation are planned.
3. **Try spot**: move the cursor over the map to see the range if you relocate there.
4. Optionally fill in **Current main city** — targets already in range won't need a relocation.

The language follows your browser. Switch it at the top right, or add `?lang=zh-Hant`, `?lang=zh-Hans`, `?lang=en` or `?lang=vi` to the URL.

## Limitations

- Bandit camps, other players' cities and land ownership are live server state that this page can't see. If the first choice is blocked, use an alternative.
- The exact tile your city lands on is only known in relocation mode, so suggestions keep a 3-tile safety margin.

Unofficial fan-made tool, not affiliated with the game's publisher.
