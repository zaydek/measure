# Measure privacy policy

Last updated: 2026-10-16. This covers Measure, the Chrome extension, version 1.0.0 and later.

## In short

Measure collects nothing, stores nothing and sends nothing anywhere. It has no account, no analytics, no ads and no
server. Everything it does happens in your browser, on the tab where you turn it on, while it is on.

## What it reads

Only on a tab where you turn it on (by clicking its toolbar icon or pressing its shortcut), and only until you turn it
off:

- Which element is under the pointer, and the pointer's position in the window.
- That element's position and size, and those of its direct children (to find a flex or grid gap).
- That element's computed CSS for layout: its margin, border width, padding, display, row and column gap, position and
  top, right, bottom and left offsets, and the position, size and border widths of the element it is positioned against.
- That the page scrolled, resized or was typed into, so it can redraw; it does not read what was typed.
- Whether a key pressed was Escape, so Escape can turn it off; it does not record keys.

It reads no page text, no form values, no cookies, no page storage, no addresses, no history and no other tabs. It draws
its marks in its own layer on top of the page and removes the layer when you turn it off.

The options page reads Measure's own keyboard shortcut from Chrome (`chrome.commands`) and your platform name, so it can
show the key with Mac names on a Mac.

## What it stores

Nothing. It uses no extension storage, no local storage, no cookies and no databases. Turning it off or closing the tab
leaves nothing behind.

## What it sends

Nothing, to anyone. It makes no network requests of any kind. Its only message is internal: the part on the page tells
the extension's own background worker whether Measure is on or off (true or false), so the toolbar icon can show "ON".
That message never leaves your browser. Its content security policy allows only the scripts packaged with it, and it
loads no remote code.

## Permissions

- `activeTab`: access to the one tab you are on, granted by Chrome only when you click the icon or press the shortcut.
- `scripting`: to place Measure's own packaged script into that tab.

It asks for no host permissions and runs no script on any page by itself.

## Changes

A change to this policy is published here, with a new date at the top, before a version that needs it ships.

## Contact

Open an issue at https://github.com/zaydek/measure/issues.
