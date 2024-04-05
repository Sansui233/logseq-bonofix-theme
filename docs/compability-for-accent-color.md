## Compability for accent color (to theme developer)

Color pallete variable structure.

```
Light mode
└ Common style
  └ Accent color specific
  └ Default logseq color specific (also as fallback)
```

And the same as dark mode.

Notice that accent color design system use a fixed color variable from color pallete ahead of all self-defined variables. which makes it hard to overwrite color in accent color mode with good compability.

There are two ways of overwriting:

1. Overwrite dom style. Turn it back to self-defined variable first as old design does. It requires a constant alignment with Logseq's new design and the custom-theme will be in frequent update.
2. Write the full self-defined color pallete. This requires a large amount of code and introduces additional performance overhead, which may not be desirable for a custom-theme.

And, here's the third way:

- Give up adaption of accent color.

