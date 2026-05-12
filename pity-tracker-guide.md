# How to Track Your Pity in Arknights: Endfield

Losing track of pity is one of the most common mistakes new Endfield players make. This guide covers everything you need to know about the pity system — and how to track it without manual spreadsheets.

---

## Why Tracking Matters

Unlike some gacha games, Arknights: Endfield's API **only stores a rolling window of pull history**. If you don't track regularly, older pulls may disappear from the server logs — making your pity count permanently inaccurate.

**The risk:** You might think you're at pull 40 when you're actually at pull 65 — or vice versa. At soft pity (66+), the 6★ rate climbs rapidly. Knowing your exact count helps you decide when to save vs. spend.

---

## The ReEnd Pity Tracker

**[reend.vallov.com/headhunt-tracker](https://reend.vallov.com/headhunt-tracker/)**

The ReEnd tracker imports your full pull history directly from Endfield's servers using your session token. It then stores everything **locally in your browser** — no account required, no data sent to external servers.

**What it tracks:**
- Current pity count per banner (Chartered, Basic, Beginner, Arsenal Exchange)
- Soft pity progress (pull 66+)
- Rate-Up Guarantee progress (out of 120)
- Full pull history with timestamps
- Stats: 6★ rate, average pulls per 6★, lucky vs. unlucky streaks

**Privacy:**
- Token is read once and immediately discarded — never stored
- All data stays in your browser's IndexedDB
- Exporting a JSON backup is recommended

---

## Manual Tracking (Spreadsheet Method)

If you prefer not to use external tools, here's the minimal data to track:

| Column | What to Record |
|--------|---------------|
| Date | Pull date |
| Banner | Chartered / Basic / Arsenal |
| Pull # | Your cumulative pull since last 6★ |
| Result | Operator/weapon name |
| Rarity | 3★ / 4★ / 5★ / 6★ |

**Formulas to know:**
- Pity resets to 0 after any 6★
- Rate-Up Guarantee counter resets when you pull the featured 6★ or the banner ends
- Arsenal Exchange pity resets every new issue (separate from character banner pity)

---

## Banner-Specific Pity Rules

### Chartered (Limited) Banner
- Shares pity with Basic Headhunting
- 50% chance per 6★ to be featured
- Rate-Up Guarantee: 120 paid pulls → next 6★ is guaranteed featured
- Runs for a limited time — check the end date before spending

### Basic Headhunting (Standard)
- Permanent, never goes away
- Shares pity with Chartered
- Good to pull on between limited banners

### Beginner Banner
- Discounted pulls (cost reduction)
- Hard pity at **50 pulls** (not 80)
- Limited to 50 total pulls per account — use them early

### Arsenal Exchange (Weapon)
- Completely separate pity from character banners
- Hard pity at pull 40 (25% featured weapon) and pull 80 (guaranteed featured)
- Pity resets each new issue — don't leave pulls wasted at issue end
- Arms Offering cumulative milestones persist across issues

---

## Frequently Asked Questions

**Q: Does pity carry over when a banner ends?**
A: Character banner pity carries over between Chartered and Basic Headhunting. Arsenal Exchange pity does NOT carry over between issues — it resets.

**Q: If I lose the 50/50, is my next 6★ guaranteed featured?**
A: No. Unlike Genshin Impact, Endfield does NOT have a 50/50 carry-over. Each 6★ is independently 50% featured. The only hard guarantee is the 120-pull Rate-Up Guarantee.

**Q: Can I check my pull history in-game?**
A: Yes, but only a limited window. For full history and pity tracking, use [reend.vallov.com/headhunt-tracker](https://reend.vallov.com/headhunt-tracker/).

**Q: Is using the pity tracker safe?**
A: The token used to import pull history is read-only and not stored anywhere. It cannot be used to make purchases or modify your account.

**Q: What happens if I clear my browser data?**
A: Your local pull records will be deleted. Export a JSON backup regularly from the tracker's settings.

---

*For more Endfield resources, visit [reend.vallov.com](https://reend.vallov.com/)*
