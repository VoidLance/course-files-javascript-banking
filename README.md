# Scopt Banking

Scopt Banking is a small, browser-based banking application example built with JavaScript. It demonstrates account selection, balance checks, deposits, withdrawals, and a transaction history using sample accounts.

This is an educational demo, not a real banking service. Its account data exists only in the browser and resets when the page is reloaded.

## Why use it

- Explore a simple JavaScript `bankAccount` class with methods for deposits, withdrawals, and balance checks.
- Select from five preloaded sample accounts, including accounts with zero and negative balances.
- See the selected account's details and a transaction history in the page.
- Run it without installing dependencies or setting up a build system.

## Get started

### Requirements

- A modern web browser
- Python 3, or another local static web server

### Run locally

From the repository root, start a local server:

```sh
python3 -m http.server 8000
```

Then open [http://localhost:8000/html/](http://localhost:8000/html/) in your browser. Serving the files over HTTP allows the browser to load the JavaScript modules correctly.

### Use the app

Choose an account from the dropdown, then select **Check Balance**, **Deposit**, or **Withdraw**. Deposit and withdrawal amounts are entered in the browser prompt. Transactions appear in the history below the account controls.

The app starts with sample accounts for John Doe, Jane Smith, Empty Account, Negative Balance, and Richie Rich. Changes are temporary and are not saved between page loads.

## Project structure

- [`html/index.html`](html/index.html) — application page and controls
- [`js/index.js`](js/index.js) — sample accounts and browser interactions
- [`js/bankAccount.js`](js/bankAccount.js) — account class and balance operations

There is no package manifest, build process, or automated test suite in this repository.

## Help

For questions or bug reports, [open an issue](https://github.com/VoidLance/course-files-javascript-banking/issues). You can also review the [source files](js/index.js) and [application page](html/index.html).

## Maintainers and contributions

The project is maintained in the [VoidLance/course-files-javascript-banking repository](https://github.com/VoidLance/course-files-javascript-banking). Contributions are welcome: open an issue to discuss a proposed change, then submit a pull request with a clear description of what changed and how it was checked.

No `CONTRIBUTING.md` or `LICENSE` file is currently included; please open an issue to discuss contribution questions or licensing before reusing the project.
