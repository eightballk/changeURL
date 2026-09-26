# Change URL Extension

This browser extension changes the URL of Reddit and X (Twitter) to bypass login requirements, allowing you to browse these platforms anonymously without having to create an account. It modifies URLs as follows:

- **Reddit**: `www.reddit.com` to `redlib.catsarch.com`
- **X (Twitter)**: `x.com` to `nitter.cf`

> [!Note]
> Your browsing history is not saved by this extension. This extension simply changes URL to bypass login. No other additional features are added in this extension at this time.

## Acknowledgments

Big thanks to the developers of Nitter and RedLib for allowing to bypass twitter's and reddit's login.

- **[Nitter](https://github.com/zedeus/nitter)**
- **[RedLib](https://github.com/redlib-org/redlib-instances)**

## Features

- **Bypass Login**: Access Reddit and X (Twitter) without needing to log in or create an account.
- **Simple URL Change**: Automatically redirects to the specified alternative URLs.

## Installation

1. Click [this](https://github.com/eightballk/changeURL/releases/tag/v1.0.1) link and download the extension file (Change-URL.zip).
2. Extract the zip file.
3. Open your browser and go the extension page.
4. Enable developer mode and click on "Load unpacked" button.
5. Select the extension's folder (Change-URL) and confirm the installation.

> [!WARNING]
> Note that this extension may not work properly on Mozilla Firefox.

## Usage

Once the extension is installed, you can manually select the option to change URL of either websites.

## Build

This project uses plain TypeScript (no bundler). Source files live in `src/` and compile to `public/dist/`.

```bash
npm install
npm run build
```

Use `npm run watch` instead during development to automatically recompile on save.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push to the branch.
5. Open a pull request.
