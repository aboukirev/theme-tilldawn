# Till Dawn theme

## Why
Initially I used my custom tmTheme from SublimeText with VSCode.  The latest version of VSCode now uses JSON format for native themes.
This is an attempt to port my tmTheme to JSON.  

## Status
Refer to `/src/vs/editor/browser/standalone/media/standalone-tokens.css` in VSCode source tree on GitHub for built-in scopes (CSS classes after `.token`).
Researching it lead me to using empty scope to define default foreground and background.  It works now but may change in the future as JSON format and global
scopes are undocumented.

I am still tinkering with actual colors and will continue to adjust them.  I aim to reduce the number of distinct colors and use as few scopes as possible.