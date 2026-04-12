
# EfikCoin Eternal – Official Website

**Live:** [https://efikcoinofficialecosystem.com](https://efikcoinofficialecosystem.com)  
**Contract:** `0x9F8C29E496ECB6C39c221458f211234DfCB233E0`

EfikCoin Eternal (ECE) is a decentralized finance ecosystem on Binance Smart Chain. This repository hosts the official project website – a modern landing page introducing staking (up to 750% APR), airdrops, loans, multi‑network wallet, and the immutable smart contract.

The website displays live price, market cap, volume, and total supply (fetched from DexScreener and the blockchain). It includes tokenomics, roadmap, founder message, and social links.

**Live wallet:** [https://efikcoineternal.github.io/ECE-Wallet/](https://efikcoineternal.github.io/ECE-Wallet/)

Built with HTML5, Tailwind CSS, vanilla JS. Deployed via GitHub Pages.

Coin is life. Life is for everyone.
# Rename Guide – EfikCoin Eternal Ecosystem

To keep your project balanced and branded correctly, use this guide to rename the following components when needed.

---

## 1. Telegram Bot (`ecewalletbot`)

### Current name:
- Bot username: `@ecewalletbot`
- Bot display name: `EfikCoin Eternal Assistant`

### To rename:
1. Open Telegram → `@BotFather`
2. Send `/setname` → select your bot → enter new display name.
3. Send `/setusername` → select your bot → enter a new unique username (must end with `bot`).
4. Update the Mini App URL in `BotFather` (`/setdomain`) if your domain changes.

### Recommended new name pattern:
- Display: `EfikCoin Eternal [Feature]` (e.g., `EfikCoin Eternal Game Hub`)
- Username: `efikcoin_[feature]_bot` (e.g., `efikcoin_game_bot`)

---

## 2. Token Symbol & Name

| Current | Can be changed to |
|---------|-------------------|
| Token name: `EfikCoin Eternal` | `EfikCoin` or `ECE Token` |
| Symbol: `ECE` | Keep `ECE` for consistency (or change to `EFK`) |

### How to change (if you deploy a new contract):
- Create a new token contract with updated `name` and `symbol` in the constructor.
- Update the `TOKEN_ADDRESS` and `TOKEN_ABI` in the HTML/JavaScript files.
- Update the token address in all smart contracts (staking, loan, etc.).

---

## 3. Web App (Mini App / World Hub)

### File name:
`index.html` (current). You can rename it to any `.html` file, but GitHub Pages expects `index.html` as the default.

### Title and metadata (appears in browser tab and link previews):
Edit these lines in the `<head>` of `index.html`:

```html
<title>EfikCoin Eternal – Mine, Battle, Bet, Earn</title>
<meta property="og:title" content="EfikCoin Eternal Mini App" />
<meta property="og:description" content="Play the live sports game, mine ECE/BTC/USDT, fight dragons, and earn crypto rewards!" />
