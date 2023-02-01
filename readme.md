# Chrome Extension - Redirector

This is a simple chrome extension that redirects you to a specific URL if you open certain websites.

## Installation

1. Clone or download this repository.
2. Open Google Chrome and go to `chrome://extensions/`.
3. Enable `Developer mode` on the top right corner of the page.
4. Click on `Load unpacked` button and select the downloaded folder.

## Usage

1. Open `manifest.json` file in the downloaded folder.
2. Edit the `matches` and `redirectTo` fields according to your needs.
3. Save the changes in the `manifest.json` file.
4. Open a new tab in Google Chrome and try opening a website that matches the `matches` field. It should redirect you to the specified `redirectTo` URL.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
