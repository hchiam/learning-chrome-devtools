# Learning [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

## [Live expressions](https://developers.google.com/web/tools/chrome-devtools/console/live-expressions)

Good as variable watch substitute when debugging live.

- Ctrl+Shift+i
- Ctrl+Shift+P
- Search "create live expression"

For example: `document.activeElement` with automatically show the currently-focused element.

## [Print preview](https://developers.google.com/web/tools/chrome-devtools/css/print-preview)

- Ctrl+Shift+i
- Ctrl+Shift+P
- Search "print media type"
- To undo, search "not emulate CSS media type" (to not emulate CSS media type)

## [Code coverage](https://developers.google.com/web/tools/chrome-devtools/coverage#open)

- Ctrl+Shift+i
- Ctrl+Shift+P
- Search "coverage" (but watch out: it can be slow to open files to show you which lines got (un)used)

## [Access local servers with port forwarding](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/local-server)

Connect a localhost port on your laptop to your cellphone! Laptop Chrome -> mobile Chrome (or Firefox!).

- Enable developer options on an Android mobile device: <https://developer.android.com/studio/debug/dev-options>
- Set up remote debugging on an Android mobile device: <https://developers.google.com/web/tools/chrome-devtools/remote-debugging>
- Set up access to local servers: <https://developers.google.com/web/tools/chrome-devtools/remote-debugging/local-server>

## [Find performance bottlenecks](https://developer.chrome.com/docs/devtools/evaluate-performance/#find_the_bottleneck)

Performance tab -> record and stop -> look for full CPU levels or dropped frames -> see Main tab for long rectangles (long = slow. directly above = caused lower rectangles) -> see Summary tab for link to initiator or source function.
