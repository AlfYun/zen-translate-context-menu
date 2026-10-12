# Translate Context Menu

A [Sine](https://github.com/CosmoCreeper/Sine) mod for Zen Browser.

Firefox only offers its full-page translation prompt automatically, once,
when a page loads. Dismiss it and there's no quick way back short of
hunting for the (often hidden) translate icon in the address bar.

This adds **번역하기** to the page's right-click menu. Clicking it calls
the exact same `FullPageTranslationsPanel.open()` the native toolbar
button's click handler uses, so it's the same panel, just reachable any
time.

## Install

1. Install [Sine](https://github.com/CosmoCreeper/Sine).
2. In Zen, go to **Settings → Sine Mods**, open Sine's settings and turn on
   **installing JS from unofficial sources**.
3. Paste `AlfYun/zen-translate-context-menu` into the marketplace box.
4. Restart Zen when Sine asks.
