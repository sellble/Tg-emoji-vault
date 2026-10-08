# Note : i will add 1000+ more emojis If i get more stars
# 🗃️ TG Emoji Vault

A ready-made catalog of **500+ Telegram custom emoji IDs**, each one described by how it actually looks, so AI can pick the right emoji for your bot without any guesswork.

---

## 🤔 The Problem

When you want your Telegram bot to use premium/custom emojis, you normally have to:

- Extract emoji IDs manually, one by one
- Paste a long list of IDs into your AI prompt
- Hope the AI guesses which ID is which (it can't, since an ID like `5368324170671202286` tells it nothing)

## ✅ The Solution

**TG Emoji Vault** lists every emoji ID together with a **plain-text description of how it looks**.

So the AI can read something like *"golden crown with small jewels"*, understand it, and pick the correct ID by itself.

- ❌ No manual ID extraction
- ❌ No giant ID lists in your prompt
- ❌ No guessing
- ✅ Just search, pick, and use

---

## ✨ Features

| Feature | Description |
|---|---|
| 📦 **500+ emojis** | Telegram custom emoji IDs, organized in packs |
| 👁️ **Visual descriptions** | Every emoji says how it looks, written for AI |
| 🔌 **REST API** | Fetch, search, and browse packs from your code |
| 🌐 **Web app** | Browse the vault visually in your browser |

---

## 🔗 Links

- 🌐 **Web App:** https://emojivault.bypixel.site/
- 📚 **API Docs:** https://emojivault.bypixel.site/api

---

## 🚀 API Quick Start

Base URL: `https://emojivault.bypixel.site`

### Get all emojis
```http
GET https://emojivault.bypixel.site/emoji
```

### Search by keyword
```http
GET https://emojivault.bypixel.site/emoji/search?q=crown
```

### Get a specific pack
```http
GET https://emojivault.bypixel.site/packs/white-premium
```

### Example with `curl`
```bash
curl "https://emojivault.bypixel.site/emoji/search?q=crown"
```

---

## 🤖 How to Use It With an AI Bot

1. Your bot (or AI) needs an emoji, for example a crown for a "VIP" message.
2. It calls `/emoji/search?q=crown`.
3. The API returns matching emojis with their **IDs and descriptions**.
4. The AI picks the best match and uses the ID in the Telegram message.

No hardcoded lists. The AI finds what it needs on demand.

---

## 💖 Support the Project

If this saves you time, consider donating:

👉 https://sellble.rork.app/

---

Made with ❤️ for bot developers.
