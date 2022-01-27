# Learning [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

## [Live expressions](https://developers.google.com/web/tools/chrome-devtools/console/live-expressions)

Good as variable watch substitute when debugging live.

1. Ctrl+Shift+i
2. Ctrl+Shift+P
3. Search "create live expression"

For example: `document.activeElement` with automatically show the currently-focused element.

## [Print preview](https://developers.google.com/web/tools/chrome-devtools/css/print-preview)

1. Ctrl+Shift+i
2. Ctrl+Shift+P
3. Search "print media type"
4. To undo, search "not emulate CSS media type" (to not emulate CSS media type)

## [Code coverage](https://developers.google.com/web/tools/chrome-devtools/coverage#open)

1. Ctrl+Shift+i
2. Ctrl+Shift+P
3. Search "coverage" (but watch out: it can be slow to open files to show you which lines got (un)used)

## [Access local servers with port forwarding](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/local-server)

Connect a localhost port on your laptop to your cellphone! Laptop Chrome -> mobile Chrome (or Firefox!).

1. Enable developer options on an Android mobile device: <https://developer.android.com/studio/debug/dev-options>
2. Set up remote debugging on an Android mobile device: <https://developers.google.com/web/tools/chrome-devtools/remote-debugging>
3. Set up access to local servers: <https://developers.google.com/web/tools/chrome-devtools/remote-debugging/local-server>

## [Find performance bottlenecks](https://developer.chrome.com/docs/devtools/evaluate-performance/#find_the_bottleneck)

1. Performance tab
2. record and stop
3. look for full CPU levels or dropped frames
4. see Main tab for long rectangles (long = slow. directly above = caused lower rectangles)
5. see Summary tab for link to initiator or source function.
