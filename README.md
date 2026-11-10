# Keys by Touch · Клавиши вслепую

A browser trainer for the Mac keyboard: touch typing on the US layout and
macOS keyboard shortcuts. The interface is in English and Russian.

Браузерный тренажёр клавиатуры Mac: слепая печать в английской раскладке и
сочетания клавиш macOS. Интерфейс на русском и английском, переключатель в
правом верхнем углу.

## Use

Open `index.html` in a browser. There is no build step and no dependencies
besides web fonts. A Mac keyboard is expected.

## Modes

- **Typing**: lessons from the home row outwards, then capitals, punctuation,
  digits, symbols and brackets, then practice on words, sentences, numbers and
  code. An on-screen keyboard highlights the next key and shows which finger
  it belongs to. A "weak keys" drill is built from the keys you miss most.
- **Shortcuts**: macOS shortcuts grouped by topic. A new shortcut is shown
  with its answer, then asked from memory; misses come back.
- **Reference**: every shortcut with search and a learned indicator.

## Notes

- Shortcuts and their wording come from Apple Support: "Mac keyboard
  shortcuts", "Take a screenshot on Mac" and the Mission Control pages of the
  macOS User Guide.
- Shortcuts that macOS or the browser takes before the page can see them
  (Command-Q, Command-Tab, screenshots and others) are entered one key at a
  time instead of as a chord.
- The browser cannot see the fn key; fn-arrow shortcuts are recognised by the
  key event they produce.
- Sounds are synthesized with Web Audio and can be switched off.
- Progress is stored in the browser's `localStorage`.
