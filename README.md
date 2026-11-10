# WalletGuard

One simple place for everyday Solana users to ask: **is this thing safe?**
A wallet address, a link, or a program — paste it, get a plain-language answer.

- Built on **Solana**. Wallet: Phantom (injected provider, no login, no tracking).
- 100% client-side, zero dependencies, single page.
- Risk scoring slots are wired for the **DD.xyz (Webacy)** Risk Engine:
  - `Threat Risks API` — address checks
  - `URL Risk API` — link checks
  - `Contract Risk API` — program checks
- Until API credentials are issued (grant onboarding), slots render honest
  wait states — no fake scores are ever shown.

## Run
Open `index.html` in any browser, or serve statically:

```
python -m http.server 8080
```

## Status
Interface + integration contract complete. Live scoring connects at onboarding.
