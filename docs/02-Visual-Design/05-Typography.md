# Typography

Effective typography helps to create an important visual balance on a page—essential for long-format text and marketing copy. By staying consistent with fonts, sizing and spacing, we can create variety in our layouts while still maintaining a sense of context and visual consistency.

## Our fonts

[Exo 2](https://www.google.com/fonts/specimen/Exo+2) is used primarily for headings and titles, including select marketing copy. It was chosen as a natural complement to Open Sans, and is available in a variety of weights, each with a true italic version.

[Open Sans](https://en.wikipedia.org/wiki/Open_Sans) is the foundation type family for all Pega websites, used for all text with the exception of headlines and titles. With a wide range of weights, and a large diverse character set, the uniform simplicity and legibility over other font families makes Open Sans a great option for presenting information in a variety of languages, which is necessary to bring our content to a global audience.

## Size Standards

Our typography sizes are based off of [1.2 MS Scale](http://www.modularscale.com/?16&px&1.2&sass&text) with a 16px base. This allows us to create an intuitive visual hierarchy and aesthetically pleasing layout directly in Sass without having to do a bunch of crazy math.

```scss
<pre class="language-css u-margin-bottom-large">
  <code>
    $modular-scale: (
      "font_sizes": (
        xxxxlarge:   ms(8),    //  68.797px;
        xxxlarge:   ms(7),    //  57.331px;
        xxlarge:   ms(6),    //  47.776px;
        xlarge:   ms(4),    //  33.178px;
        large:  ms(2),    //  23.04px;
        medium:   ms(1),    //  19.2px;
        base:   ms(0),    //  16.0px;
        small:  ms(-1),   //  14.222px;
        xsmall:  ms(-2)    //  12.642px;
      )
    );
  </code>
</pre>
```

## Headings

Headings (h1 to h6) provide an important way to break up long format text on a web page, and give screen readers and web crawlers, i.e. Google, information about what is important on the page.

Headings should be placed semantically within a layout. Only page titles should be in H1; lower headings should be H2, H3, etc. To achieve a variety of sizes, a set of helper classes is available to content editors so that headings can remain semantic while achieving different visual appearances.

# `h1` You have been my friend

## `h2` That in itself is a tremendous thing

### `h3` I wove my webs for you because I liked you.

#### `h4` By helping you, perhaps I was trying to lift up my life a trifle.

##### `h5` Heaven knows anyone's life can stand a little of that.

`h6` E.B. White, *Charlotte's Web*



## Additional typographic defaults

`p` Beans id blue mountain percolator, crema single origin irish sweet dark redeye. Cortado dark, strong, acerbic macchiato galão, foam so a steamed crema coffee. Doppio dark carajillo, redeye that, extraction that aged americano pumpkin spice. Instant cinnamon, half and half, ut strong siphon doppio variety instant. Aftertaste black single shot beans roast pumpkin spice to go.

> `blockquote` Organic kopi-luwak, eu, foam breve espresso americano filter trifecta variety. Black to go sit, grounds, coffee single shot wings black single shot. Cup, percolator and fair trade beans, viennese organic aromatic sugar rich. Dripper percolator, cinnamon, spoon, to go sugar aged carajillo latte. That fair trade aromatic, single origin con panna iced trifecta mocha.

`ul` 

- **French press, extraction to go**, bar qui, milk, crema, medium latte espresso americano, ut, barista a siphon, breve, barista iced café au lait cinnamon affogato frappuccino.
- **Aroma cup, aftertaste flavour french press decaffeinated acerbic**, robusta, milk crema, trifecta sweet siphon coffee doppio filter skinny java.
- **That viennese lungo, aromatic id, cup single shot bar** robusta kopi-luwak, single origin id, mocha, beans eu skinny aromatic single origin.
- **Spoon, cream saucer chicory, black, crema**, acerbic roast galão, kopi-luwak coffee, latte body french press, organic mocha flavour barista plunger pot french press.
- **Cultivar, galão bar, medium crema qui wings**, sweet, froth est cultivar, black barista blue mountain barista, steamed and, sugar frappuccino fair trade wings french press blue mountain.

`ol`

1. **French press, extraction to go**, bar qui, milk, crema, medium latte espresso americano, ut, barista a siphon, breve, barista iced café au lait cinnamon affogato frappuccino.
2. **Aroma cup, aftertaste flavour french press decaffeinated acerbic**, robusta, milk crema, trifecta sweet siphon coffee doppio filter skinny java.
3. **That viennese lungo, aromatic id, cup single shot bar** robusta kopi-luwak, single origin id, mocha, beans eu skinny aromatic single origin.
4. **Spoon, cream saucer chicory, black, crema**, acerbic roast galão, kopi-luwak coffee, latte body french press, organic mocha flavour barista plunger pot french press.
5. **Cultivar, galão bar, medium crema qui wings**, sweet, froth est cultivar, black barista blue mountain barista, steamed and, sugar frappuccino fair trade wings french press blue mountain.