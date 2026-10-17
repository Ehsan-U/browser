# Browser

Browser distributions for macOS ARM64, Linux x86_64, and Linux ARM64.

Download the archives from [Releases](https://github.com/Ehsan-U/browser/releases/latest). Each release includes SHA256 checksums and platform details.

Extract the complete archive and retain its bundled resources. Use the extracted executable with Playwright through `executable_path` / `executablePath`, or set `CLOAKBROWSER_BINARY_PATH` for compatible launchers.

- macOS ARM64: `Chromium.app/Contents/MacOS/Chromium`
- Linux x86_64 and ARM64: `chrome`

Use separate user-data directories for independent browser processes. Linux requires Chromium runtime dependencies appropriate to the distribution.
