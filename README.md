# SendKeys

VB6 Setup Citrix helper (`SetupCitrix.exe`) that launches the Citrix ICA Client and drives its UI with Bryan Wolf's `VbSendKeys` keyboard injection (DOS/Windows-capable SendKeys alternative in `modMain`). Open `SetupCitrix.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SetupCitrix` (`SetupCitrix.vbp`) | VB6 | WinForms exe | Automate Citrix ICA Client setup via SendKeys |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `SetupCitrix.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Citrix ICA Client installed at the path expected by the form (historical)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/SendKeys`.
Company names in `.vbp` files: Freelance.
`VbSendKeys` author credit in source: Bryan Wolf, 1999.

## License

MIT © 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
