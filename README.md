# Daisy GT - Hardened Precision Telemetry HUD

High-contrast, zero-glare dashboard environment built explicitly for integration as a Telegram Mini App (TMA). Tailored for track environments, diagnostic logging, and digital asset distribution.

## Tech Stack Overview
- **Frontend Framework:** Pure Vanilla HTML5 / CSS3 / JavaScript (Zero heavy dependencies)
- **Design Tokens:** Strictly dark mode (`#0D0D0E`), featuring high-visibility **Racing Red** and **Electric Cyan** accents.
- **Typography:** `Rajdhani` (Headers/HUD metrics) & `JetBrains Mono` (Tabular real-time data rows).
- **Integrations:** Native `telegram-web-app.js` software development kit.

## Architecture Guidelines
- All text strings modifying data streams must be mapped to tabular monospace text layouts to prevent viewport layout shifts during high-speed sensor refreshes.
- Monetization engine utilizes the secure Telegram Stars infrastructure linked via `@BotFather`.
