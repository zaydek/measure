# Measure

<p align="center">
  <img src="media/apple.gif" width="960" alt="A cursor glides across Apple's home page hero; Measure draws each button's border, padding and size, and the gap between the two buttons, as it moves">
</p>

**Hover any element on any page to see its margin, border, padding and size, a flex or grid gap, and where it sits.**

A Chrome extension. Each side's value sits on its band, a gap is hatched with its value, a positioned element shows its
offsets, and the size sits just above it. [See the site](https://zaydek.github.io/measure/).

## See it on

<table>
  <tr>
    <td width="50%"><img src="media/google.gif" alt="A cursor moves from Google's search box to its two buttons; Measure shows each one's padding, margin and size"><br><sub><b>google.com</b>: the search box's padding, then each button's margin, border and size</sub></td>
    <td width="50%"><img src="media/stripe.gif" alt="A cursor moves across Stripe's hero; Measure hatches the grid's row gaps, then the gap in a button group"><br><sub><b>stripe.com</b>: a hero grid's 40 px row gaps, then the gap between two buttons</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/google.png" alt="Measure on Google's search button: margin, border, padding and size"><br><sub><b>google.com</b>: a button's margin, border and padding</sub></td>
    <td width="50%"><img src="media/github.png" alt="Measure on a GitHub repo's button group: the 8 px flex gap between buttons"><br><sub><b>github.com</b>: the flex gap in a repo's button group</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/stripe.png" alt="Measure on Stripe's hero: the grid's 40 px row gap, hatched"><br><sub><b>stripe.com</b>: a grid's row gap, hatched</sub></td>
    <td width="50%"><img src="media/tailwind.png" alt="Measure on Tailwind CSS's hero: the 16 px flex gap between two buttons"><br><sub><b>tailwindcss.com</b>: the gap between two buttons</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="media/apple.png" alt="Measure on Apple's hero button: border, padding, content and size"><br><sub><b>apple.com</b>: a button's border, padding and size</sub></td>
    <td width="50%"></td>
  </tr>
</table>

## Install

**[Add to Chrome](https://chromewebstore.google.com/detail/measure/dgikeobpapokgcfcamabaoojiejphnfk)**: free, from the Chrome Web Store.

## Use

- Toggle: **Option+Shift+M** (Alt+Shift+M on Windows and Linux), or click the toolbar icon. The icon reads "ON" on a tab
  where it is lit.
- Hover any element. A scroll under a still pointer measures what is under it now.
- **Escape** turns it off, and nothing of it stays on the page.
- Change the key at `chrome://extensions/shortcuts`. The options page (right-click the icon, then Options) shows the
  current key.

It runs only on the tab where you turn it on. Chrome keeps every extension out of `chrome://` pages and the Web Store.

## Privacy

Measure stores nothing and sends nothing anywhere. [PRIVACY.md](PRIVACY.md) says exactly what it reads.

## License

Free to install and use; all rights reserved. See [LICENSE](LICENSE).

The sites shown are their owners' trademarks, pictured only to show Measure working on them; none of them endorses or is
affiliated with Measure.
