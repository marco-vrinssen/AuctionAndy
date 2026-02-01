# FastExchange

A lightweight World of Warcraft addon that streamlines vendor and auction house interactions.

## Features

### 🛒 Vendor Automation
- **Auto-Sell Junk**: Automatically sells all gray items when opening a vendor
- **Auto-Repair**: Automatically repairs all gear when opening a vendor
- **Confirm Dialogs**: Auto-confirms repair cost dialogs

### ⭐ Auction Favorites
- **Cross-Character Sync**: Favorites sync across all characters on your account
- **Crafting Orders**: Also applies to the Professions Customer Orders UI
- **Current Expansion Filter**: Defaults auction search to current expansion items

### ⚡ Quick Auctioning
- **Spacebar Posting**: Press Space to quickly post auctions while in the sell tab

## Installation

1. Download the addon
2. Extract to `World of Warcraft/_retail_/Interface/AddOns/`
3. Restart WoW or `/reload`

## File Structure

```
FastExchange/
├── FastExchange.toc
├── vendor.lua      # Sell & repair automation
├── favorites.lua   # Favorites sync for AH & crafting orders
├── auctioning.lua  # Spacebar posting
└── README.md
```

## License

MIT License
