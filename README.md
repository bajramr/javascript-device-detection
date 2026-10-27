# Basic JavaScript Device Detection

A beginner exercise by Bajram Ramadan, based on the original user-agent example.

## Start

1. Open index.html in a browser.
2. Edit it in a text editor, save and reload.
3. No installation, dependencies or server are needed.

All code is in one HTML file. There is no dashboard or framework. Comments explain each part. The matching tutorial is included as javascript-device-detection-tutorial.md; follow its publishing instructions to add a Blog post and optional Playground entry.

## What the code does

Read navigator.userAgent, convert it to lowercase, check /iphone/, /android/ and /ipad/, add tablet and desktop clues, then display a message using if / else if and textContent. Android without mobile is treated as a possible tablet; desktop OS strings exclude the recognised mobile platforms. Desktop and laptop cannot be distinguished.

This matches text, not verified device hardware. A missing match does not mean desktop. For actual responsive layouts use CSS; for optional browser functionality use feature detection.

## Practice

Temporarily replace the userAgent line with `const userAgent = "iphone";` and try android, ipad and example too. Restore the original browser-based line afterwards.

## Hosting

Upload index.html to a static folder on your hosting. Attach the ZIP to your Playground download field. Do not install it as a WordPress plugin or theme. Add the actual deployed and download URLs to the article before publishing.

## Checks

The five message branches and case normalization were checked using sample strings. The complete code in the tutorial was compared with index.html. Visual browser verification was not run in this environment.

## License

MIT; see LICENSE. This license covers the supplied code, not the original reference graphic (which is not bundled).
